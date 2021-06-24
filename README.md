<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">

  <!-- Bootstrap 4 CDN -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">

  <title>Hangman</title>
</head>
<body>
<div class="container">
  <h1 class="text-center">Hangman</h1>
  <div class="float-right">Wrong Guesses: <span id='mistakes'>0</span> of <span id='maxWrong'></span></div>
  <div class="text-center">
    <img id='hangmanPic' src="./images/0.jpg" alt="">
    <p>Guess The Movie:</p>
    <p id="wordSpotlight"></p>
    <div id="keyboard"></div>
    <button class="btn btn-info" onClick="reset()">Reset</button>
  </div> 
</div>

<script src='./js/hangman.js'></script>
</body>
</html>
