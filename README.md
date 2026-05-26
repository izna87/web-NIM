<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Web Server Mahasiswa</title>

  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: linear-gradient(135deg, #ffd6e8, #d6f0ff);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .card {
      background: white;
      padding: 40px;
      border-radius: 25px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
      text-align: center;
      width: 350px;
      animation: float 3s ease-in-out infinite;
    }

    h1 {
      color: #ff69b4;
      margin-bottom: 20px;
      font-size: 32px;
    }

    p {
      font-size: 20px;
      color: #555;
      margin: 10px 0;
    }

    .nim {
      color: #4da6ff;
      font-weight: bold;
    }

    .emoji {
      font-size: 40px;
      margin-bottom: 15px;
    }

    @keyframes float {
      0% {
        transform: translateY(0px);
      }
      50% {
        transform: translateY(-10px);
      }
      100% {
        transform: translateY(0px);
      }
    }

    .footer {
      margin-top: 20px;
      font-size: 14px;
      color: gray;
    }
  </style>
</head>

<body>

  <div class="card">
    <div class="emoji">🌸💻✨</div>

    <h1>Data Mahasiswa</h1>

    <p><b>Nama :</b><br>
    Isnaini Khoirun Nisa</p>

    <p class="nim">
      NIM : 048813065
    </p>

    <div class="footer">
    </div>
  </div>

</body>
</html>
