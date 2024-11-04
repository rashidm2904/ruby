<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Love Message for Aliza</title>
  <style>
    body {
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Arial', sans-serif;
      overflow: hidden;
    }

    .heart {
      position: relative;
      width: 300px;
      height: 300px;
      background: #ff4e50;
      transform: rotate(-45deg);
      animation: heartBeat 1.5s ease-in-out infinite;
      box-shadow: 0px 0px 20px rgba(255, 78, 80, 0.7);
    }

    .heart::before,
    .heart::after {
      content: "";
      position: absolute;
      width: 300px;
      height: 300px;
      background: #ff4e50;
      border-radius: 50%;
    }

    .heart::before {
      top: -150px;
      left: 0;
    }

    .heart::after {
      left: 150px;
      top: 0;
    }

    /* Text Container */
    .container {
      position: absolute;
      text-align: center;
      color: white;
      font-size: 3em;
      transform: rotate(45deg); /* Rotates text back to align normally */
      color: #fff5f5;
    }

    h1 {
      font-size: 3em;
      margin: 0;
      text-shadow: 0px 0px 10px rgba(255, 255, 255, 0.7);
      animation: glow 2s infinite alternate;
    }

    /* Animations */
    @keyframes glow {
      from {
        text-shadow: 0px 0px 10px rgba(255, 255, 255, 0.7);
      }
      to {
        text-shadow: 0px 0px 20px rgba(255, 255, 255, 1);
      }
    }

    @keyframes heartBeat {
      0%, 100% {
        transform: scale(1) rotate(-45deg);
      }
      50% {
        transform: scale(1.1) rotate(-45deg);
      }
    }
  </style>
</head>
<body>
  <div class="heart"></div>
  <div class="container">
    <h1>I love you, Aliza</h1>
  </div>
</body>
</html>
# ruby
Ruby
