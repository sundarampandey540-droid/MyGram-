<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MyGram Video</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fafafa;
      margin: 0;
      padding: 0;
    }
    header {
      background: #fff;
      padding: 10px;
      text-align: center;
      font-weight: bold;
      font-size: 20px;
      border-bottom: 1px solid #ddd;
    }
    .feed {
      max-width: 600px;
      margin: 20px auto;
    }
    .post {
      background: #fff;
      border: 1px solid #ddd;
      margin-bottom: 20px;
      border-radius: 10px;
      overflow: hidden;
    }
    .post img, .post video {
      width: 100%;
      display: block;
    }
    .caption {
      padding: 10px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>📸 MyGram</header>

  <div class="feed">

    <div class="post">
      <video controls autoplay muted loop>
        <source src="https://sample-videos.com/video123/mp4/720/big_buck_bunny_720p_1mb.mp4" type="video/mp4">
      </video>
      <div class="caption">🔥 Sample Video - MyGram Demo</div>
    </div>

    <div class="post">
      <img src="https://picsum.photos/600/400" alt="Sample Image">
      <div class="caption">✨ Sample Photo Post</div>
    </div>

  </div>

</body>
</html>
