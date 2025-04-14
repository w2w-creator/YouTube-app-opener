<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Open in YouTube App</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f5f5f5;
      text-align: center;
    }

    h1 {
      color: #222;
      font-size: 24px;
      margin-bottom: 16px;
      padding: 0 20px;
    }

    p {
      font-size: 16px;
      color: #555;
      padding: 0 20px;
      margin-bottom: 30px;
    }

    button {
      background-color: #ff0000;
      color: white;
      font-size: 18px;
      padding: 14px 28px;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    button:active {
      transform: scale(0.97);
    }
  </style>
</head>
<body>
  <h1>Watch on YouTube</h1>
  <p>Tap the button below to open our channel directly in the YouTube app.</p>
  <button onclick="window.location.href='youtube://www.youtube.com/@weekdayswanderer'">
    Open in YouTube App
  </button>
</body>
</html>