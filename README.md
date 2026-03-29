# Soundboard-memes-
<!DOCTYPE html>
<html>
<head>
  <title>Meme Soundboard 😂</title>
  <style>
    body {
      font-family: Arial;
      text-align: center;
      background: #111;
      color: white;
    }
    button {
      padding: 15px 25px;
      margin: 10px;
      font-size: 18px;
      border-radius: 10px;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>

<h1>🔥 Meme Soundboard 🔥</h1>

<button onclick="playSound('bruh')">BRUH 😂</button>
<button onclick="playSound('wow')">WOW 😲</button>
<button onclick="playSound('laugh')">EVIL LAUGH 😈</button>

<audio id="bruh" src="sounds/bruh.mp3"></audio>
<audio id="wow" src="sounds/wow.mp3"></audio>
<audio id="laugh" src="sounds/laugh.mp3"></audio>

<script>
function playSound(id) {
  document.getElementById(id).play();
}
</script>

</body>
</html>
