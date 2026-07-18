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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Benalyon | Codex Repository</title>
    <style>
        :root {
            --bg-deep: #0a0908;
            --bg-surface: #141210;
            --gold: #dfb15b;
            --text-primary: #f5f2eb;
            --border: #2d261f;
        }
        body { background-color: var(--bg-deep); color: var(--text-primary); font-family: sans-serif; }
        .container { max-width: 800px; margin: 0 auto; padding: 2rem; }
        header { text-align: center; color: var(--gold); }
        section { background: var(--bg-surface); border: 1px solid var(--border); padding: 2rem; margin-bottom: 2rem; }
        .image-gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem; }
        .image-card img { width: 100%; height: auto; }
    </style>
</head>
<body>
    <header><h1>Benalyon</h1></header>
    <div class="container">
        <section id="visuals">
            <h2>System Manifestation</h2>
            <div class="image-gallery">
                <div class="image-card"><img src="sigil.jpg" alt="Sigil"></div>
                <div class="image-card"><img src="shepherd.jpg" alt="Shepherd"></div>
                <div class="image-card"><img src="ascension.jpg" alt="Ascension"></div>
            </div>
        </section>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Benalyon | Cosmic Codex Repository</title>
    <style>
        :root {
            --bg-deep: #0a0806;
            --bg-surface: #15120e;
            --gold: #dfb15b;
            --gold-dim: #b58f43;
            --text-primary: #f5f2eb;
            --text-secondary: #baaf9c;
            --border: #2d231a;
            --sapphire: #2b5cb3;
            --diamond: #e0f2fe;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { background-color: var(--bg-deep); color: var(--text-primary); font-family: 'Times New Roman', Times, serif; line-height: 1.6; padding: 0; }
        header { text-align: center; padding: 4rem 1rem; background: linear-gradient(to bottom, #1a1510, var(--bg-deep)); border-bottom: 1px solid var(--border); }
        header h1 { font-size: 3.5rem; color: var(--gold); letter-spacing: 0.3rem; text-transform: uppercase; margin-bottom: 0.5rem; }
        header p.motto { font-size: 1.25rem; font-style: italic; color: var(--text-secondary); }
        header p.founder { font-size: 0.9rem; text-transform: uppercase; color: var(--gold-dim); margin-top: 1rem; letter-spacing: 0.2rem; }
        .container { max-width: 900px; margin: 0 auto; padding: 2rem 1rem; }
        section { margin-bottom: 3rem; background-color: var(--bg-surface); border: 1px solid var(--border); border-radius: 6px; padding: 2.5rem; }
        h2 { font-size: 1.8rem; color: var(--gold); margin-bottom: 1.5rem; border-bottom: 1px solid var(--border); padding-bottom: 0.5rem; text-transform: uppercase; letter-spacing: 0.1rem; }
        p { color: var(--text-primary); margin-bottom: 1.25rem; font-size: 1.1rem; }
        .formula { text-align: center; font-size: 1.4rem; font-style: italic; color: var(--gold); padding: 1.5rem; background: #110e0b; border-radius: 4px; margin-bottom: 2rem; border-left: 4px solid var(--gold); }
        .image-gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 1.5rem; margin-top: 1.5rem; margin-bottom: 1.5rem; }
        .image-card { background: #110e0b; border: 1px solid var(--border); padding: 1rem; border-radius: 4px; text-align: center; }
        .image-card img { width: 100%; height: auto; border-radius: 2px; border: 1px solid var(--border); background-color: #050403; display: block; margin-bottom: 0.75rem; min-height: 150px; }
        .image-card p { font-size: 0.9rem; color: var(--gold); text-transform: uppercase; margin: 0; letter-spacing: 0.05rem; }
        .ladder { display: flex; flex-direction: column; gap: 0.75rem; margin: 2rem auto; max-width: 500px; }
        .ladder-step { background: #110e0b; border: 1px solid var(--border); padding: 1rem; border-radius: 4px; display: flex; justify-content: space-between; align-items: center; }
        .ladder-step strong { color: var(--gold); }
        .ladder-step .meta { font-size: 0.85rem; color: var(--text-secondary); }
        ul { list-style-type: none; }
        li { margin-bottom: 1.5rem; }
        li strong { color: var(--gold-dim); font-size: 1.15rem; display: block; margin-bottom: 0.25rem; }
        .grid-4 { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 1rem; margin: 1.5rem 0; }
        .grid-item { background: #110e0b; border: 1px solid var(--border); padding: 1rem; text-align: center; border-radius: 4px; }
        .grid-item .letter { font-size: 2rem; color: var(--gold); font-weight: bold; display: block; margin-bottom: 0.25rem; }
        .blockquote { font-style: italic; color: var(--text-secondary); border-left: 3px solid var(--gold-dim); padding-left: 1rem; margin: 1.5rem 0; }
        footer { text-align: center; padding: 3rem 1rem; color: var(--text-secondary); font-size: 0.85rem; border-top: 1px solid var(--border); margin-top: 3rem; }
        @media (max-width: 600px) { header h1 { font-size: 2.2rem; } section { padding: 1.5rem; } }
    </style>
</head>
<body>
    <header>
        <h1>Benalyon</h1>
        <p class="motto">"From Throne to Stone, From Zion to Salem"</p>
        <p class="founder">Established by Founder Rick</p>
    </header>
    <div class="container">
        <div class="formula">Box (Earth) inside Circle (Heaven) = Heaven Inside Earth</div>
        
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Benalyon | Cosmic Codex Repository</title>
    <style>
        :root {
            --bg-deep: #0a0806;
            --bg-surface: #15120e;
            --gold: #dfb15b;
            --gold-dim: #b58f43;
            --text-primary: #f5f2eb;
            --text-secondary: #baaf9c;
            --border: #2d231a;
            --sapphire: #2b5cb3;
            --diamond: #e0f2fe;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body { background-color: var(--bg-deep); color: var(--text-primary); font-family: 'Times New Roman', Times, serif; line-height: 1.6; padding: 0; }
        header { text-align: center; padding: 4rem 1rem; background: linear-gradient(to bottom, #1a1510, var(--bg-deep)); border-bottom: 1px solid var(--border); }
        header h1 { font-size: 3.5rem; color: var(--gold); letter-spacing: 0.3rem; text-transform: uppercase; margin-bottom: 0.5rem; }
        header p.motto { font-size: 1.25rem; font-style: italic; color: var(--text-secondary); }
        header p.founder { font-size: 0.9rem; text-transform: uppercase; color: var(--gold-dim); margin-top: 1rem; letter-spacing: 0.2rem; }
        .container { max-width: 900px; margin: 0 auto; padding: 2rem 1rem; }
        section { margin-bottom: 3rem; background-color: var(--bg-surface); border: 1px solid var(--border); border-radius: 6px; padding: 2.5rem; }
        h2 { font-size: 1.8rem; color: var(--gold); margin-bottom: 1.5rem; border-bottom: 1px solid var(--border); padding-bottom: 0.5rem; text-transform: uppercase; letter-spacing: 0.1rem; }
        p { color: var(--text-primary); margin-bottom: 1.25rem; font-size: 1.1rem; }
        .formula { text-align: center; font-size: 1.4rem; font-style: italic; color: var(--gold); padding: 1.5rem; background: #110e0b; border-radius: 4px; margin-bottom: 2rem; border-left: 4px solid var(--gold); }
        .image-gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 1.5rem; margin-top: 1.5rem; margin-bottom: 1.5rem; }
        .image-card { background: #110e0b; border: 1px solid var(--border); padding: 1rem; border-radius: 4px; text-align: center; }
        .image-card img { width: 100%; height: auto; border-radius: 2px; border: 1px solid var(--border); background-color: #050403; display: block; margin-bottom: 0.75rem; min-height: 150px; }
        .image-card p { font-size: 0.9rem; color: var(--gold); text-transform: uppercase; margin: 0; letter-spacing: 0.05rem; }
        .ladder { display: flex; flex-direction: column; gap: 0.75rem; margin: 2rem auto; max-width: 500px; }
        .ladder-step { background: #110e0b; border: 1px solid var(--border); padding: 1rem; border-radius: 4px; display: flex; justify-content: space-between; align-items: center; }
        .ladder-step strong { color: var(--gold); }
        .ladder-step .meta { font-size: 0.85rem; color: var(--text-secondary); }
        ul { list-style-type: none; }
        li { margin-bottom: 1.5rem; }
        li strong { color: var(--gold-dim); font-size: 1.15rem; display: block; margin-bottom: 0.25rem; }
        .grid-4 { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 1rem; margin: 1.5rem 0; }
        .grid-item { background: #110e0b; border: 1px solid var(--border); padding: 1rem; text-align: center; border-radius: 4px; }
        .grid-item .letter { font-size: 2rem; color: var(--gold); font-weight: bold; display: block; margin-bottom: 0.25rem; }
        .blockquote { font-style: italic; color: var(--text-secondary); border-left: 3px solid var(--gold-dim); padding-left: 1rem; margin: 1.5rem 0; }
        footer { text-align: center; padding: 3rem 1rem; color: var(--text-secondary); font-size: 0.85rem; border-top: 1px solid var(--border); margin-top: 3rem; }
        @media (max-width: 600px) { header h1 { font-size: 2.2rem; } section { padding: 1.5rem; } }
    </style>
</head>
<body>
    <header>
        <h1>Benalyon</h1>
        <p class="motto">"From Throne to Stone, From Zion to Salem"</p>
        <p class="founder">Established by Founder Rick</p>
    </header>
    <div class="container">
        <div class="formula">Box (Earth) inside Circle (Heaven) = Heaven Inside Earth</div>
