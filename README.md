# contact-page
Let’s Get in Touch
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Contact Me</title>
  <style>
    body {
      font-family: 'Inter', 'Segoe UI', sans-serif;
      background-color: #ffffff;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      color: #111;
    }

    h1 {
      font-size: 1.8rem;
      margin-bottom: 40px;
      font-weight: 600;
      letter-spacing: -0.5px;
    }

    .button {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 250px;
      padding: 14px 0;
      margin: 8px 0;
      border-radius: 12px;
      font-size: 16px;
      font-weight: 600;
      text-decoration: none;
      color: white;
      transition: transform 0.15s ease, opacity 0.2s ease;
    }

    .button:hover {
      transform: translateY(-2px);
      opacity: 0.9;
    }

    .kakao { background-color: #FEE500; color: #3C1E1E; }
    .line { background-color: #00B900; }
    .whatsapp { background-color: #25D366; }
    .instagram { background: linear-gradient(45deg, #feda75, #fa7e1e, #d62976, #962fbf, #4f5bd5); }
    .email { background-color: #333; }

    .icon {
      margin-right: 8px;
      font-size: 1.2rem;
    }

    footer {
      position: fixed;
      bottom: 25px;
      font-size: 13px;
      color: #999;
    }
  </style>
</head>
<body>
  <h1>Let’s Connect 🤍</h1>

  <a class="button kakao" href="https://open.kakao.com/o/smhlRkih" target="_blank">
    💛 Chat on KakaoTalk
  </a>

  <a class="button line" href="https://line.me/ti/p/T9-h9V2uUB" target="_blank">
    💚 Message on LINE
  </a>

  <a class="button whatsapp" href="https://wa.link/t2xwgj" target="_blank">
    💬 Talk on WhatsApp
  </a>

  <a class="button instagram" href="https://www.instagram.com/diver_lala?igsh=a3Y4NTkxcDB0enAx&utm_source=qr" target="_blank">
    📸 Connect on Instagram
  </a>

  <a class="button email" href="yeonyang08@gmail.com" target="_blank">
    ✉️ Send an Email
  </a>

  <footer>© 2025 LALA KIM</footer>
</body>
</html>
