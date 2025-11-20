<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8">
  <title>@mabingnan - Merry Christmas 2025 🎄</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body { margin: 0; overflow: hidden; background: #000; }
    canvas { display: block; }

    /* 居中浮层文字 - 超美圣诞风格 */
    .overlay {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      color: white;
      z-index: 10;
      pointer-events: none; /* 让鼠标可以穿透去拖动3D场景 */
      font-family: 'Segoe UI', Arial, sans-serif;
    }
    h1 {
      font-size: 4.5rem;
      margin-bottom: 1rem;
      text-shadow: 0 0 30px rgba(0,0,0,0.9);
      background: linear-gradient(90deg, #ff512f, #f09819, #ffd700, #fff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: shine 3s infinite;
    }
    p {
      font-size: 1.8rem;
      margin: 1rem 0;
      text-shadow: 0 0 20px rgba(0,0,0,0.8);
    }
    a {
      color: #ffdd57;
      text-decoration: none;
      font-weight: bold;
    }
    a:hover { text-decoration: underline; }

    @keyframes shine {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.8; }
    }

    /* 手机适配 */
    @media (max-width: 768px) {
      h1 { font-size: 3rem; }
      p { font-size: 1.4rem; }
    }
  </style>
</head>
<body>
  <!-- 这里放你原来的 3D 脚本，会自动加载 -->
  <script type="module" src="./index-BZRdRA-q.js"></script>
  <!-- 如果文件名每次打包都不一样，改成你的实际文件名就行 -->

  <!-- 浮层文字 -->
  <div class="overlay">
    <h1>Merry Christmas 2025 🎄</h1>
    <p>Hi，我是 @mabingnan</p>
    <p>
      <a href="https://github.com/mabingnan" target="_blank">GitHub</a> • 
      <a href="https://twitter.com/mabingnan_V" target="_blank">X / Twitter</a>
    </p>
    <p>Wish you a warm & snowy Christmas ❄️✨</p>
  </div>
</body>
</html>
