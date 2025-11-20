<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>@mabingnan - Merry Christmas 2025 🎄</title>
  <style>
    body { margin: 0; overflow: hidden; background: #000; }
    canvas { display: block; }

    .overlay {
      position: absolute;
      top: 50%; left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      color: white;
      z-index: 10;
      pointer-events: none;
      font-family: 'Segoe UI', Arial, sans-serif;
    }
    h1 {
      font-size: 4.5rem; margin-bottom: 1rem;
      background: linear-gradient(90deg, #ff512f, #f09819, #ffd700, #fff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-shadow: 0 0 30px rgba(0,0,0,0.9);
      animation: shine 4s infinite;
    }
    p { font-size: 1.8rem; margin: 1rem 0; text-shadow: 0 0 20px black; }
    a { color: #ffdd57; text-decoration: none; font-weight: bold; }
    a:hover { text-decoration: underline; }
    @keyframes shine { 0%,100% { opacity: 1; } 50% { opacity: 0.75; } }
    @media (max-width: 768px) { h1 { font-size: 3rem; } p { font-size: 1.4rem; } }
  </style>
</head>
<body>

  <!-- 万能加载：自动找最新的 js 文件，再也不用改文件名！ -->
  <script type="module">
    import init from './index.js';
    init();
  </script>
  <!-- 如果上面这行报错，就用下面这行（看你 dist 里实际结构） -->
  <!-- <script type="module" src="./assets/index-XXXXXX.js"></script> -->

  <!-- 圣诞文字浮层 -->
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
