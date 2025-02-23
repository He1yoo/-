# -
メンスト公式ch監修。ミッド攻略サイト

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ミッドタイマン攻略サイト</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- ヘッダー -->
  <header>
    <div class="container">
      <h1>ミッドタイマン完全攻略</h1>
      <nav>
        <ul>
          <li><a href="#">ホーム</a></li>
          <li><a href="#">記事</a></li>
          <li><a href="#">動画</a></li>
          <li><a href="#">戦術ガイド</a></li>
          <li><a href="#">武器ガイド</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- メインコンテンツ -->
  <main>
    <section class="intro">
      <div class="container">
        <h2>ミッドタイマンの攻略法</h2>
        <p>ここでは、荒野行動のミッドタイマンにおける戦術やテクニックを徹底解説します。</p>
      </div>
    </section>

    <!-- 最新の攻略記事と動画 -->
    <section class="latest-content">
      <div class="container">
        <div class="content-item">
          <h3>最新記事</h3>
          <p>ここに最新の攻略記事の内容が表示されます。<a href="#">続きを読む</a></p>
        </div>
        <div class="content-item">
          <h3>最新動画</h3>
          <div class="video">
            <iframe src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- フッター -->
  <footer>
    <div class="container">
      <p>&copy; 2025 ミッドタイマン攻略サイト | All Rights Reserved</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

/* ベーススタイル */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background-color: #f4f4f4;
  color: #333;
}

.container {
  width: 90%;
  margin: 0 auto;
}

/* ヘッダー */
header {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
}

header h1 {
  text-align: center;
  font-size: 2em;
}

header nav ul {
  list-style: none;
  text-align: center;
}

header nav ul li {
  display: inline;
  margin: 0 15px;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
  font-size: 1.2em;
}

/* メインコンテンツ */
main {
  padding: 40px 0;
}

.intro {
  text-align: center;
  margin-bottom: 40px;
}

.latest-content {
  display: flex;
  justify-content: space-between;
  gap: 20px;
}

.content-item {
  background-color: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  width: 48%;
}

.content-item h3 {
  font-size: 1.5em;
  margin-bottom: 15px;
}

.content-item p {
  font-size: 1.2em;
}

.video iframe {
  width: 100%;
  height: 300px;
  border-radius: 8px;
}

/* フッター */
footer {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}
