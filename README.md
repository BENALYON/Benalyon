
Benalyon
Repository navigation
Code
Issues
Pull requests
Actions
Commit 5d3983e
BENALYON
BENALYON
authored
1 hour ago
·
·
Verified
Update README.md
main
1 parent 
1d3168b
 commit 
5d3983e
1 file changed

+285
-16
Lines changed: 285 additions & 16 deletions
Search within code
 
‎README.md‎
Original file line number	Diff line number	Diff line change
@@ -1,16 +1,285 @@
## Hi there 👋
<!--
**BENALYON/Benalyon** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
Here are some ideas to get you started:
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Benalyon | From Throne to Stone, From Zion to Salem</title>
    <meta name="description" content="Official repository and theological codex of Benalyon, founded by Rick. Explore the Ladder of Light, the Rule of Righteousness (PBYS), and the Law of the Eternal Priesthood.">
    <meta name="keywords" content="Benalyon, Rick Benalyon, Order of Melchizedek, Ladder of Light, PBYS, Book of Enoch, Apocryphon of John, Seigi, Zion to Salem">
    <style>
        :root {
            --bg-dark: #12100e;
            --bg-card: #1c1814;
            --gold: #dfb15b;
            --gold-dim: #b58f43;
            --text-light: #f4f1ec;
            --text-dim: #a8a297;
            --border: #332b24;
            --sapphire: #2b5cb3;
            --diamond: #e0f2fe;
        }
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            background-color: var(--bg-dark);
            color: var(--text-light);
            font-family: 'Times New Roman', Times, serif, system-ui;
            line-height: 1.6;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 5rem 1rem 3rem 1rem;
            background: linear-gradient(to bottom, #1f1a15, var(--bg-dark));
            border-bottom: 1px solid var(--border);
        }
        header h1 {
            font-size: 3.5rem;
            color: var(--gold);
            letter-spacing: 0.3rem;
            text-transform: uppercase;
            margin-bottom: 0.5rem;
        }
        header p.motto {
            font-size: 1.25rem;
            font-style: italic;
            color: var(--text-dim);
            letter-spacing: 0.1rem;
        }
        header p.founder {
            font-size: 0.9rem;
            text-transform: uppercase;
            color: var(--gold-dim);
            margin-top: 1rem;
            letter-spacing: 0.2rem;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem 1rem;
        }
        section {
            margin-bottom: 4rem;
            background-color: var(--bg-card);
            border: 1px solid var(--border);
            border-radius: 4px;
            padding: 2.5rem;
        }
        h2 {
            font-size: 2rem;
            color: var(--gold);
            margin-bottom: 1.5rem;
            border-bottom: 1px solid var(--border);
            padding-bottom: 0.5rem;
            text-transform: uppercase;
            letter-spacing: 0.1rem;
        }
        p {
            color: var(--text-light);
            margin-bottom: 1.25rem;
            font-size: 1.1rem;
        }
        .formula {
            text-align: center;
            font-size: 1.5rem;
            font-style: italic;
            color: var(--gold);
            padding: 1.5rem;
            background: #171411;
            border-radius: 4px;
            margin-bottom: 2rem;
            border-left: 4px solid var(--gold);
        }
        /* Ladder diagram */
        .ladder {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            margin: 2rem auto;
            max-width: 500px;
            position: relative;
        }
        .ladder-step {
            background: #171411;
            border: 1px solid var(--border);
            padding: 1rem;
            border-radius: 4px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .ladder-step strong {
            color: var(--gold);
        }
        .ladder-step .meta {
            font-size: 0.85rem;
            color: var(--text-dim);
        }
        /* Lists */
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        li {
            margin-bottom: 1.5rem;
        }
        li strong {
            color: var(--gold-dim);
            font-size: 1.15rem;
            display: block;
            margin-bottom: 0.25rem;
        }
        .grid-4 {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 1rem;
            margin-top: 1.5rem;
        }
        .grid-item {
            background: #171411;
            border: 1px solid var(--border);
            padding: 1rem;
            text-align: center;
            border-radius: 4px;
        }
        .grid-item .letter {
            font-size: 2rem;
            color: var(--gold);
            font-weight: bold;
            display: block;
            margin-bottom: 0.5rem;
        }
        .blockquote {
            font-style: italic;
            color: var(--text-dim);
            border-left: 3px solid var(--gold-dim);
            padding-left: 1rem;
            margin: 1.5rem 0;
        }
        footer {
            text-align: center;
            padding: 3rem 1rem;
            color: var(--text-dim);
            font-size: 0.85rem;
            border-top: 1px solid var(--border);
            letter-spacing: 0.05rem;
        }
        @media (max-width: 600px) {
            header h1 { font-size: 2.5rem; }
            section { padding: 1.5rem; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Benalyon</h1>
        <p class="motto">"From Throne to Stone, From Zion to Salem"</p>
        <p class="founder">Established by Founder Rick</p>
    </header>
    <div class="container">
        <div class="formula">
            Box (Earth) inside Circle (Heaven) = Heaven Inside Earth
        </div>
        <!-- SECTION 1: LADDER OF LIGHT -->
        <section id="ladder">
            <h2>I. The Ladder of Light</h2>
            <p>The vertical axis of eternity maps the descent of divine spirit into material animation across five primary planes.</p>
            
            <div class="ladder">
                <div class="ladder-step" style="border-top: 3px solid var(--sapphire);">
                    <div><strong>ELYON</strong> <span class="meta">/ Uncreated Absolute</span></div>
                    <div class="meta">∞</div>
                </div>
                <div class="ladder-step">
                    <div><strong>ENOCH</strong> <span class="meta">/ King of Zion</span></div>
                    <div class="meta">3382 BC</div>
                </div>
                <div class="ladder-step">
                    <div><strong>SALEM</strong> <span class="meta">/ Melchizedek</span></div>
                    <div class="meta">2000 BC</div>
                </div>
                <div class="ladder-step">
                    <div><strong>JESUS CHRIST</strong> <span class="meta">/ Redeemer</span></div>
                    <div class="meta">4 BC</div>
                </div>
                <div class="ladder-step" style="border-bottom: 3px solid var(--diamond);">
                    <div><strong>ANIMA</strong> <span class="meta">/ Animated Soul</span></div>
                    <div class="meta">∞</div>
                </div>
            </div>
            <ul>
                <li>
                    <strong>ELYON (The Most High)</strong>
                    Highest One. The Incorruptible One dwelling in the Aether of pure, uncreated light. Signified by the Blue Sapphire at the Divine Throne.
                </li>
                <li>
                    <strong>ENOCH (Zion / Initiation)</strong>
                    From the bloodline of Seth. He walked with God and established the City of Zion, defined by a people of one heart and one mind with no poor among them.
                </li>
                <li>
                    <strong>SALEM (Peace / Melchizedek)</strong>
                    King of Peace who offered Abraham the Eucharist of Bread and Yayin. Governed by the Seal of Melchizedek—two overlapping squares showing Heaven and Earth intertwined.
                </li>
                <li>
                    <strong>JESUS CHRIST (The Redeemer)</strong>
                    The Great Shepherd (Greek Gematria 888) sent to deliver humanity from false gods and establish the permanent priesthood in the Order of Melchizedek.
                </li>
                <li>
                    <strong>ANIMA (The Breath of Life)</strong>
                    The incorruptible divine spark within the material realm. Represented by the Earthly Diamond, it is the force that animates the soul.
                </li>
            </ul>
        </section>
        <!-- SECTION 2: ESYA -->
        <section id="esya">
            <h2>II. The Sacred Name (ESYA)</h2>
            <p>The vertical alignment of the Ladder of Light spells out the structural cipher of reality:</p>
            
            <ul>
                <li><strong>E – Ayin (ע):</strong> The Eye. Viewing humanity through the perception of the Most High.</li>
                <li><strong>S – Shin (ש):</strong> The Tooth. Signifying Divine Power, structurally manifest as a three-pronged Crown.</li>
                <li><strong>Y – Yod (י):</strong> The Hand. The smallest character, embodying profound humility and the spark of creation.</li>
                <li><strong>A – Aleph (א):</strong> Oneness with Messiah. A bridge connecting the upper Heavenly Yod to the lower Earthly Yod.</li>
            </ul>
            <p style="margin-top: 1.5rem; font-style: italic; color: var(--gold);">Capstone Anchor: Mt. Esja — The Fireplace Stone built to withstand extreme heat; the physical convergence of Heaven on Earth.</p>
        </section>
        <!-- SECTION 3: RULE OF RIGHTEOUSNESS -->
        <section id="pbys">
            <h2>III. The Rule of Righteousness (PBYS)</h2>
            <p>The horizontal matrix of the Sigil balances internal peace against absolute external justice through four essential elements:</p>
            
            <div class="grid-4">
