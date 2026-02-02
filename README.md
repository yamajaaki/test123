<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AIコーデ提案</title>
  <style>
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Hiragino Kaku Gothic ProN", "Noto Sans JP", sans-serif;
      background: #0e0f13;
      color: #eaeaf0;
    }

    header {
      padding: 16px;
      text-align: center;
      border-bottom: 1px solid #2a2d3a;
    }

    header h1 {
      margin: 0;
      font-size: 18px;
    }

    header p {
      margin: 6px 0 0;
      font-size: 12px;
      color: #a0a4b8;
    }

    main {
      max-width: 1000px;
      margin: 0 auto;
      padding: 16px;
    }

    .layout {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 16px;
    }

    @media (max-width: 900px) {
      .layout {
        grid-template-columns: 1fr;
      }
    }

    .card {
      background: #151824;
      border: 1px solid #2a2d3a;
      border-radius: 12px;
      overflow: hidden;
    }

    .card h2 {
      margin: 0;
      padding: 10px 12px;
      font-size: 14px;
      border-bottom: 1px solid #2a2d3a;
    }

    .image-box {
      aspect-ratio: 4 / 3;
      background: #0b0c10;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .image-box img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .model .image-box {
      aspect-ratio: 3 / 4;
    }

    .points {
      margin-top: 16px;
      padding: 14px;
      background: #151824;
      border: 1px solid #2a2d3a;
      border-radius: 12px;
    }

    .points h3 {
      margin-top: 0;
      font-size: 14px;
    }

    .points ul {
      padding-left: 18px;
      margin: 10px 0 0;
      line-height: 1.7;
    }

    footer {
      margin-top: 24px;
      text-align: center;
      font-size: 12px;
      color: #8a8fa8;
    }
  </style>
</head>
<body>

<header>
  <h1>AIコーデ提案</h1>
  <p>ズボン基準｜左：靴・上着｜右：AIモデル</p>
</header>

<main>
  <section class="layout">
    <!-- 左：靴・上着 -->
    <div>
      <div class="card">
        <h2>靴</h2>
        <div class="image-box">
          <img src="shoes.jpg" alt="靴">
        </div>
      </div>

      <div class="card" style="margin-top:16px;">
        <h2>上着</h2>
        <div class="image-box">
          <img src="outer.jpg" alt="上着">
        </div>
      </div>
    </div>

    <!-- 右：AIモデル -->
    <div class="card model">
      <h2>AIモデル着用イメージ</h2>
      <div class="image-box">
        <img src="model.png" alt="AIモデル">
      </div>
    </div>
  </section>

  <!-- 下：ポイント -->
  <section class="points">
    <h3>コーデポイント</h3>
    <ul>
      <li>ズボンはシルエット重視のため、上半身はシンプルにまとめる</li>
      <li>靴はブラウン系で全体のトーンを安定させる</li>
      <li>上着は丈感を抑えてバランスを取る</li>
      <li>画像はAI生成によるイメージです</li>
    </ul>
  </section>
</main>

<footer>
  © AI Styling Demo
</footer>

</body>
</html>
