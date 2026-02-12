<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MovieHub</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>🎬 MovieHub</h1>
<input type="text" id="search" placeholder="Search Movie...">
</header>

<section class="movies" id="movieList">

<div class="movie">
<img src="https://via.placeholder.com/200x300">
<h3>Pathaan</h3>
<button onclick="openMovie('Pathaan Movie Detail Page')">View</button>
</div>

<div class="movie">
<img src="https://via.placeholder.com/200x300">
<h3>KGF 2</h3>
<button onclick="openMovie('KGF 2 Movie Detail Page')">View</button>
</div>

<div class="movie">
<img src="https://via.placeholder.com/200x300">
<h3>RRR</h3>
<button onclick="openMovie('RRR Movie Detail Page')">View</button>
</div>

</section>

<script src="script.js"></script>
</body>
</html>
