<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>MTN Promo</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: white;
      background: linear-gradient(135deg, #ffcc00, #000000);
      height: 100vh;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      animation: gradientMove 10s infinite alternate;
    }

    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }

    .mtn-text {
      font-size: 64px;
      font-weight: bold;
      color: #ffcc00;
      text-shadow: 2px 2px 4px black;
      animation: pulse 1.5s infinite;
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }

    .promo-message {
      margin-top: 20px;
      font-size: 20px;
      text-align: center;
      max-width: 90%;
    }

    .logo {
      width: 120px;
      margin-top: 30px;
      animation: float 3s ease-in-out infinite;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    .button {
      margin-top: 30px;
      background-color: #ffcc00;
      color: black;
      padding: 12px 24px;
      border: none;
      font-size: 18px;
      cursor: pointer;
      text-decoration: none;
      border-radius: 8px;
      box-shadow: 2px 2px 6px rgba(0, 0, 0, 0.5);
      transition: transform 0.3s ease;
    }

    .button:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <div class="mtn-text">MTN</div>
  <div class="promo-message">
    Congratulations! MTN is rewarding selected users with exclusive data bundles, airtime, and bonuses.<br><br>
    Click the button below to check if you're eligible and claim your reward!
  </div>
  <a href="https://academicagent.net/M3M4ZzAwNnEzQTFpNks=" class="button">Check Now</a>
  <img class="logo" src="https://upload.wikimedia.org/wikipedia/commons/2/24/MTN_Logo.svg" alt="MTN Logo">
</body>
</html>
