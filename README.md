<!doctype html>
<html lang="en">
<head love you html >
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>For Aniska — From Jonathan</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <main class="wrap">
    <h1 class="for">For Aniska</h1>

    <!-- Heart button -->
    <button id="heartBtn" class="heart-btn" aria-label="Click to see a message">
      <!-- SVG heart -->
      <svg class="heart" viewBox="0 0 32 29" xmlns="http://www.w3.org/2000/svg" role="img" aria-hidden="true">
        <defs>
          <linearGradient id="g" x1="0" x2="1" y1="0" y2="1">
            <stop offset="0%" stop-color="#ff6b81"/>
            <stop offset="100%" stop-color="#ff3b60"/>
          </linearGradient>
        </defs>
        <path fill="url(#g)" d="M23.6 0C20.4 0 18 1.9 16 4.6 14 1.9 11.6 0 8.4 0 3.8 0 0 3.6 0 8.2 0 17 16 29 16 29s16-12 16-20.8C32 3.6 28.2 0 23.6 0z"/>
      </svg>
    </button>

    <!-- Hidden message -->
    <div id="message" class="message" aria-live="polite">
      <p class="love-line">Aniska, I love you — always and forever.</p>
      <p class="signature">— Jonathan</p>
    </div>
    <p class="hint">Click the heart</p>
  </main>

  <script src="script.js"></script>
</body>
</html>
