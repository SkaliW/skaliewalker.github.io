# skaliewalker.github.io
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Skali Walker</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Skali Walker</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="blog.html">Blog</a>
      <a href="gallery.html">Gallery</a>
    </nav>
  </header>
  <section class="hero">
    <h2>Welcome to My World</h2>
    <p>Blog. Art. Life — Skali Walker style.</p>
  </section>
  <section class="instagram">
    <h3>Instagram Feed</h3>
    <iframe src="https://snapwidget.com/embed/1040536" title="Instagram preview"></iframe>
  </section>
  <footer>
    <p>&copy; 2025 Skali Walker</p>
  </footer>
</body>
</html>

<!-- blog.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Blog | Skali Walker</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Skali Walker</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="blog.html">Blog</a>
      <a href="gallery.html">Gallery</a>
    </nav>
  </header>
  <main>
    <h2>Blog</h2>
    <article>
      <h3>First Post</h3>
      <p>Coming soon: Deep thoughts, sharp words.</p>
    </article>
  </main>
  <footer>
    <p>&copy; 2025 Skali Walker</p>
  </footer>
</body>
</html>

<!-- gallery.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gallery | Skali Walker</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Skali Walker</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="blog.html">Blog</a>
      <a href="gallery.html">Gallery</a>
    </nav>
  </header>
  <main>
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200" alt="Artwork 1" />
      <img src="https://via.placeholder.com/300x200" alt="Artwork 2" />
      <img src="https://via.placeholder.com/300x200" alt="Artwork 3" />
    </div>
  </main>
  <footer>
    <p>&copy; 2025 Skali Walker</p>
  </footer>
</body>
</html>

<!-- style.css -->
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background: #f4f4f4;
  color: #111;
}
header {
  background: #0a0a23;
  color: #fff;
  padding: 20px;
  text-align: center;
}
nav a {
  color: #88ccff;
  margin: 0 15px;
  text-decoration: none;
}
.hero {
  padding: 50px;
  background: linear-gradient(to right, #000000, #003366);
  color: #fff;
  text-align: center;
}
.instagram iframe {
  width: 100%;
  height: 300px;
  border: none;
  margin-top: 20px;
}
.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  padding: 20px;
}
.gallery img {
  max-width: 300px;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}
footer {
  background: #0a0a23;
  color: white;
  text-align: center;
  padding: 15px;
  position: relative;
  bottom: 0;
  width: 100%;
}
