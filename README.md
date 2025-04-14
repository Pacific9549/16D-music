<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>16D Music</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Welcome to 16D Music</h1>
    <p>Experience music like never before – surround yourself with sound.</p>
    <a href="download.html" class="btn">Go to Downloader</a>
  </header>

  <main>
    <section class="feature">
      <h2>Featured Track</h2>
      <audio controls>
        <source src="sample.mp3" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </section>
  </main>

  <footer>
    <p>Powered by Pacific Jaat</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Download 16D Music</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Download 16D Tracks</h1>
    <a href="index.html" class="btn">Back to Home</a>
  </header>

  <main>
    <section class="downloads">
      <h2>Available Downloads</h2>
      <ul>
        <li>
          Track 1 – <a href="track1.mp3" download>Download</a>
        </li>
        <li>
          Track 2 – <a href="track2.mp3" download>Download</a>
        </li>
        <!-- Add more tracks as needed -->
      </ul>
    </section>
  </main>

  <footer>
    <p>Powered by Pacific Jaat</p>
  </footer>
</body>
</html>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background-color: #121212;
  color: #f0f0f0;
}

header, footer {
  text-align: center;
  padding: 2rem;
  background-color: #1f1f1f;
}

main {
  padding: 2rem;
  text-align: center;
}

h1, h2 {
  color: #00ffd5;
}

.btn {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #00ffd5;
  color: #121212;
  text-decoration: none;
  border-radius: 8px;
  transition: background 0.3s ease;
}

.btn:hover {
  background-color: #00c7aa;
}

audio {
  margin-top: 1rem;
  width: 80%;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  margin: 1rem 0;
}
