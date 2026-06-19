---
layout: default
title: My First Web App
---

<style>
  body {
    background: linear-gradient(135deg, #e0f7fa, #f8f9ff);
    color: #222;
    font-family: "Arial", "Hiragino Sans", "Meiryo", sans-serif;
  }

  .page {
    max-width: 850px;
    margin: 40px auto;
    padding: 35px;
    background: white;
    border-radius: 18px;
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.12);
  }

  h1 {
    color: #006064;
    text-align: center;
    border-bottom: 3px solid #00acc1;
    padding-bottom: 12px;
  }

  h2 {
    color: #00838f;
    margin-top: 35px;
    border-left: 6px solid #00acc1;
    padding-left: 12px;
  }

  p {
    color: #444;
    line-height: 1.8;
    background: #f1fcff;
    border: 1px solid #b2ebf2;
    border-radius: 10px;
    padding: 14px;
  }

  .video {
    text-align: center;
    margin-top: 20px;
  }

  iframe {
    max-width: 100%;
    border-radius: 14px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.18);
  }

  img {
    display: block;
    max-width: 100%;
    margin: 20px auto;
    border-radius: 16px;
    border: 4px solid #e0f7fa;
    box-shadow: 0 6px 18px rgba(0, 0, 0, 0.2);
  }

  .caption {
    text-align: center;
    color: #666;
    font-size: 14px;
    background: none;
    border: none;
    padding: 0;
  }
</style>

<div class="page">

# My First Web App

こんにちは。これはMarkdownとCSSを使って作成した、オリジナルのホームページです。

## YouTube Video

好きな動画をページ内に埋め込みました。HTMLのiframeタグを使うことで、YouTube動画をホームページ上で再生できるようになります。

<div class="video">
<iframe width="560" height="315"
src="https://www.youtube.com/embed/3jIMk43CECY?si=B4QOX81KUW1nT6u0"
title="YouTube video player"
frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
referrerpolicy="strict-origin-when-cross-origin"
allowfullscreen>
</iframe>
</div>

## Hachioji Station

八王子駅周辺の画像を表示しました。画像を入れることで、文字だけのページよりも見やすく、印象に残りやすいページになります。

<img src="images (1).jpg" alt="Hachioji station" width="500">

<p class="caption">Hachioji Station Image</p>

## Comment

今回の発展問題では、Markdownで作成したページにCSSを直接書き込み、背景色、文字色、余白、影、角丸などを設定しました。  
CSSを使うことで、同じ内容のページでも見た目の印象を大きく変えられることが分かりました。

</div>
