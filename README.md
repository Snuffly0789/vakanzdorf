<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mensaje Binario</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      background-color: black;
      color: lime;
      font-family: 'Courier New', monospace;
      height: 100%;
      overflow: hidden;
    }

    .scroll-container {
      position: absolute;
      bottom: -100%;
      width: 100%;
      height: 200%;
      animation: scrollUp 10s linear forwards;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }

    .binary {
      white-space: pre-wrap;
      font-size: 2vw;
      line-height: 1.2;
      text-align: center;
      padding: 20px;
    }

    @keyframes scrollUp {
      0% {
        transform: translateY(100%);
      }
      100% {
        transform: translateY(-100%);
      }
    }
  </style>
</head>
<body>
  <div class="scroll-container">
    <div class="binary">
01001110 01101111 01110011 01101111 01110100 01110010 01101111 01110011 00100000<br>
01100110 01110101 01101001 01101101 01101111 01110011 00100000 01101100 01101111<br>
01110011 00100000 01110010 01100101 01110011 01110000 01101111 01101110 01110011<br>
01100001 01100010 01101100 01100101 01110011 00100000 01110000 01100001 01110010<br>
01100001 00100000 01110100 01110010 01100001 01100101 01110010 01101100 01101111<br>
00100000 01100100 01100101 00100000 01110110 01110101 01100101 01101100 01110100<br>
01100001
    </div>
  </div>
</body>
</html>
