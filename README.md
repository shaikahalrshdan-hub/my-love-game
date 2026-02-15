# my-love-game
<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>يوم من الأيام</title>
  <link rel="stylesheet" href="start.css" />
</head>
<body>

  <div id="start" class="screen">
    <div class="center">
      <h1>يوم من الأيام</h1>
      <p id="hint">اضغط أي مكان للمتابعة</p>
    </div>
  </div>

  <div id="story" class="screen hidden">
    <div class="story-box">
      <p id="storyText"></p>
      <p class="hint">اضغط للمتابعة</p>
    </div>
  </div>

  <div id="ready" class="screen hidden">
    <div class="center">
      <h2>15 يوليو 2025</h2>
      <button id="startGameBtn">ابدأ اللعبة</button>
    </div>
  </div>

  <script src="start.js"></script>
</body>
</html>
