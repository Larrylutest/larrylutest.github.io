<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8">
  <title>GA 測試頁面</title>
  <!-- Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-S6TSJNX4M4"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'G-S6TSJNX4M4');
  </script>
</head>
<body>
  <h1>這是我的 GA 測試頁面</h1>

  <!-- 按鈕 -->
  <button onclick="gtag('event', 'click', {
    'event_category': 'button',
    'event_label': 'test_button',
    'value': 1
  })">點我測試事件</button>

</body>
</html>

