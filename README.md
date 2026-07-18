<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Benalyon | Codex Repository</title>
    <style>
        :root {
            --bg-deep: #0a0908; --bg-surface: #141210; --gold: #e5ad43;
            --text-primary: #f5f2eb; --text-secondary: #baaf9c; --border: #2d261f;
        }
        body { background-color: var(--bg-deep); color: var(--text-primary); font-family: 'Cinzel', serif; margin: 0; }
        .container { max-width: 1000px; margin: 0 auto; padding: 2rem; }
        .image-gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 2rem; }
        .image-card { background: var(--bg-surface); border: 1px solid var(--border); padding: 1rem; text-align: center; }
        .image-card img { width: 100%; height: auto; max-height: 250px; object-fit: cover; }
        .image-card p { color: var(--gold); margin-top: 1rem; text-transform: uppercase; }
        h2 { color: var(--gold); text-align: center; }
    </style>
</head>
<body>
    <div class="container">
        <section id="visuals">
            <h2>System Manifestation</h2>
            <div class="image-gallery">
                <div class="image-card">
                    <img src="sigil.jpg" alt="Sacred Sigil">
                    <p>The Sacred Sigil</p>
                </div>
                <div class="image-card">
                    <img src="shepherd.jpg" alt="The Shepherd">
                    <p>The Primordial Shepherd</p>
                </div>
                <div class="image-card">
                    <img src="ascension.jpg" alt="The Ascension">
                    <p>The Ascension Scene</p>
                </div>
            </div>
        </section>
    </div>
</body>
</html>
