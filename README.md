# sorry-for-you
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>I'm Sorry</title>
<style>
body {
  background: linear-gradient(to bottom, #f8f9fa, #ffe4e6);
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 40px;
}
h1 {
  color: #8b0000;
  font-weight: normal;
}
p {
  font-size: 18px;
  color: #333;
  line-height: 1.6;
  max-width: 600px;
  margin: 15px auto;
}
.timer {
  margin-top: 30px;
  font-size: 15px;
  color: #555;
  font-style: italic;
}
</style>
</head>
<body>

<h1>I’m Truly Sorry</h1>

<p>
Agar meri kisi baat ya behaviour se tumhe dukh pahucha ho,
toh uske liye main dil se maafi chahta hoon.
</p>

<p>
Meri niyat kabhi galat nahi thi,
lekin main maanta hoon ki galti ho sakti hai.
Aur uski zimmedaari main leta hoon.
</p>

<p>
Tumhari feelings mere liye bahut important hain,
aur main unka poora respect karta hoon.
</p>

<p>
Agar tum ek mauka do,
toh main cheezon ko behtar banane ki poori koshish karunga.
</p>

<div class="timer" id="timer"></div>

<script>
let seconds = 0;
setInterval(() => {
  seconds++;
  document.getElementById("timer").innerHTML =
    "Time since I’ve been reflecting on my mistake: " + seconds + " seconds";
}, 1000);
</script>

</body>
</html>
