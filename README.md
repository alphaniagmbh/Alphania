
<html lang="de">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Meine Godot-Projekte</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="site-header">
    <h1>Meine Godot 4-Projekte</h1>
    <p class="subtitle">Hier findest du meine Spiele — lade sie herunter oder spiele die HTML5-Version direkt im Browser.</p>
  </header>

  <main class="container">
    <!-- Projekt: Alphania -->
    <article class="project-card">
      <div class="thumb">
        <!-- Falls du ein Vorschaubild hast, lege es als thumbnails/alphania.png ab -->
        <img src="thumbnails/alphania.png" alt="Alphania Vorschaubild" onerror="this.style.display='none'">
      </div>
      <div class="meta">
        <h2>Alphania</h2>
        <p class="desc">Alphania — (https://drive.google.com/file/d/1wXKh0bfpNuisPDWqFi9Qx2LCmD7CkZ6N). Godot 4 Projekt, ZIP: <code>Alphania.zip</code>.</p>

        <div class="buttons">
          <!-- Download: lege Alphania.zip in /downloads/ -->
          <a class="btn" href="downloads/Alphania.zip" download>Download (ZIP)</a>

          <!-- Play: falls du eine HTML5-Exportversion hast, lege sie in /Alphania/index.html -->
          <a class="btn outline" href="Alphania/index.html" target="_blank" rel="noopener">Play (Browser)</a>
        </div>

        <details class="more">
          <summary>Details & Hinweise</summary>
          <ul>
            <li>ZIP-Datei: <code>/downloads/Alphania.zip</code></li>
            <li>HTML5/Export (optional): <code>/Alphania/index.html</code> + zugehörige .pck/.wasm Dateien</li>
            <li>Wenn du nur die ZIP hochlädst, funktioniert nur der Download; die Play-Funktion öffnet die HTML5-Version (falls vorhanden).</li>
          </ul>
        </details>
      </div>
    </article>

    <!-- Platz für weitere Projekte: kopiere die article-Struktur und passe sie an -->
  </main>

  <footer class="site-footer">
    <p>© <!-- Jahr automatisch --> <span id="year"></span> — Meine Godot Projekte</p>
  </footer>

<script>
  // automatisches Jahr
  document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
