<!DOCTYPE html>
<html>
<head>
  <title>Slider Gambar</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="slider-container">
    <div class="slide fade">
      <img src="gambar1.jpg" alt="Gambar 1">
    </div>
    <div class="slide fade">
      <img src="gambar2.jpg" alt="Gambar 2">
    </div>
    <div class="slide fade">
      <img src="gambar3.jpg" alt="Gambar 3">
    </div>

    <a class="prev" onclick="changeSlide(-1)">❮</a>
    <a class="next" onclick="changeSlide(1)">❯</a>
  </div>

  <script src="script.js"></script>
</body>
</html>
