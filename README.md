<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hi there! 👋 I'm Mochammad Cholilur Rokhman</title>
  <style>
    body {
      background-color: #111;
      font-family: Arial, sans-serif;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      text-align: center;
    }
    .circle {
      width: 100px;
      height: 100px;
      background-color: #ff6347;
      border-radius: 50%;
      animation: rotate 3s linear infinite, bounce 1s ease-in-out infinite;
    }
    @keyframes rotate {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }
    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-50px);
      }
    }
    h1 {
      font-size: 2.5em;
      margin: 20px 0;
    }
    p {
      font-size: 1.2em;
      margin: 10px 0;
    }
    .links {
      margin-top: 20px;
    }
    .links a {
      margin: 0 10px;
      text-decoration: none;
      color: #fff;
    }
  </style>
</head>
<body>
  <div class="circle"></div>
  <h1>Hi there! 👋 I'm Mochammad Cholilur Rokhman</h1>
  <p>💻 I am a student at Politeknik Negeri Malang</p>
  <p>📫 How to reach me: <a href="mailto:ilulsrut69@gmail.com">ilulsrut69@gmail.com</a></p>

  <h3>🌐 My Most Used Languages:</h3>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mochammadcholilurrokhman&layout=compact&langs_count=10&theme=radical" alt="Top Langs">

  <div class="links">
    <h3>🌐 Let's Connect!</h3>
    <a href="https://linkedin.com/in/moch-cholilur-22674b25a" target="_blank">LinkedIn</a>
    <a href="https://instagram.com/cholilur_rokhman" target="_blank">Instagram</a>
    <a href="https://github.com/mochammadcholilurrokhman" target="_blank">GitHub</a>
  </div>
</body>
</html>
