
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="style.css">
  <title>Сложние</title>
  
</head>
<body>

  <audio id="right.mp3" src="right.mp3" type="audio/mpeg"></audio>
  <audio id="wrong.mp3" src="wrong.mp3" type="audio/mpeg"></audio>

  <header>
    <div class="container">
      <div class="nav">
        <h2><span><i class="fa fa-trophy" aria-hidden="true"></i></span> MATH FOR KIDS</h2>
        <nav>
          <ul>
            <li class="current"><a href="index1.html">Сложение</a></li>
            <li><a href="minus.html">Вычитание</a></li>
            <li><a href="umnozhenie.html">Умножение</a></li>
            <li><a href="delenie.html">Деление</a></li>
          </ul> 
        </nav>
      </div>
    </div>
  </header>
  
  <div class="wrapper">
      <div class="equation">
        <h1  id="num1" style="color:#87CEFA"></h1>
        <h1 style="color: #FF69B4;">+</h1>
        <h1  id="num2" style="color: #98FB98">1</h1>
        <h1  style="color: #EE82EE">=</h1>
        <h1  style="color: #DC143C">?</h1>
      </div>
      <div class="answer-options">
        <div class="options" style="background-color: #87CEFA;">
          <h1 id="option1">1</h1>
        </div>
        <div class="options" style="background-color: #FF69B4;">
          <h1 id="option2">2</h1>
        </div>
        <div class="options" style="background-color: #98FB98;">
          <h1 id="option3">3</h1>
        </div>
      </div>
  </div>

  <script src="plus.js"></script>
  
</body>
</html>
