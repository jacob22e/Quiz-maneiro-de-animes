<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Quiz Show - Definitive Edition</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Poppins:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        /* CSS CORE & DESIGN SYSTEM */
        :root {
            --bg-dark: #020617;
            --card-bg: #0f172a;
            --neon-blue: #00f2ff;
            --neon-purple: #bc13fe;
            --neon-red: #ff003c;
            --text-main: #f8fafc;
            --accent-gold: #fde047;
        }

        * { box-sizing: border-box; scroll-behavior: smooth; }
        body { margin: 0; background-color: #000; color: var(--text-main); font-family: 'Poppins', sans-serif; overflow-x: hidden; }

        .slide-container {
            width: 1280px; height: 720px;
            background-color: var(--bg-dark);
            margin: 40px auto;
            position: relative;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            padding: 40px 60px;
            border: 1px solid rgba(255, 255, 255, 0.05);
            box-shadow: 0 0 50px rgba(0, 0, 0, 0.5);
        }

        .slide-container::before {
            content: ''; position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            background: radial-gradient(circle at 20% 30%, rgba(0, 242, 255, 0.05) 0%, transparent 50%),
                        radial-gradient(circle at 80% 70%, rgba(188, 19, 254, 0.05) 0%, transparent 50%);
            pointer-events: none;
        }

        h1, h2, .orbitron { font-family: 'Orbitron', sans-serif; letter-spacing: 2px; }

        /* TABULEIRO (BOARD) */
        .board-grid {
            display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; margin-top: 20px;
        }
        .cat-header {
            background: linear-gradient(90deg, #1e40af, #3b82f6);
            padding: 12px; text-align: center; border-radius: 8px; font-weight: 700;
            text-transform: uppercase; font-size: 14px; color: #fff;
            box-shadow: 0 4px 15px rgba(59, 130, 246, 0.3);
        }
        .prize-btn {
            background: var(--card-bg); border: 1px solid var(--neon-blue);
            color: var(--neon-blue); text-align: center; padding: 15px;
            border-radius: 8px; font-family: 'Orbitron'; font-size: 24px;
            text-decoration: none; transition: 0.3s;
        }
        .prize-btn:hover { background: var(--neon-blue); color: #000; box-shadow: 0 0 20px var(--neon-blue); transform: scale(1.05); }

        .master-row { grid-column: span 4; margin-top: 10px; }
        .master-btn {
            display: block; background: linear-gradient(90deg, #991b1b, #ef4444);
            color: white; text-align: center; padding: 20px; border-radius: 12px;
            font-family: 'Orbitron'; font-size: 32px; text-decoration: none;
            border: 2px solid #fff; box-shadow: 0 0 30px rgba(239, 68, 68, 0.4);
        }

        /* PLACAR INTERATIVO */
        .scoreboard {
            margin-top: auto; display: grid; grid-template-columns: repeat(4, 1fr); gap: 20px;
            background: rgba(15, 23, 42, 0.9); padding: 20px; border-radius: 15px;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .player-box { display: flex; flex-direction: column; gap: 5px; }
        .player-name { background: transparent; border: none; border-bottom: 1px solid #334155; color: #fff; padding: 5px; font-weight: 700; outline: none; }
        .player-score { background: #000; border: 1px solid var(--neon-blue); border-radius: 6px; color: #22c55e; font-family: 'Orbitron'; font-size: 22px; text-align: center; padding: 5px; }

        /* SLIDES DE PERGUNTA */
        .header-nav { display: flex; justify-content: space-between; align-items: center; margin-bottom: 30px; }
        .back-btn { color: #94a3b8; text-decoration: none; font-weight: 700; font-size: 14px; transition: 0.3s; }
        .back-btn:hover { color: var(--neon-blue); }
        .prize-tag { background: var(--accent-gold); color: #000; padding: 5px 25px; border-radius: 50px; font-family: 'Orbitron'; font-weight: 700; font-size: 28px; }

        .question-content { display: grid; grid-template-columns: 1fr 450px; gap: 50px; height: 450px; }
        .details-area { display: flex; flex-direction: column; gap: 15px; }
        
        details { background: rgba(255, 255, 255, 0.03); border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 10px; overflow: hidden; }
        summary { padding: 15px 20px; cursor: pointer; font-weight: 700; outline: none; list-style: none; display: flex; justify-content: space-between; align-items: center; }
        summary::after { content: '\f0fe'; font-family: 'Font Awesome 6 Free'; font-weight: 900; color: var(--neon-blue); }
        details[open] summary::after { content: '\f146'; }
        .hint-text { padding: 20px; background: rgba(0,0,0,0.2); font-size: 20px; border-top: 1px solid rgba(255,255,255,0.05); color: #cbd5e1; }
        
        .solution-box summary { background: var(--neon-blue); color: #000; }
        .solution-box summary::after { color: #000; }
        .answer-text { padding: 25px; text-align: center; font-size: 42px; font-family: 'Orbitron'; font-weight: 700; color: #fff; background: #000; }

        .container-img { width: 100%; height: 100%; border-radius: 15px; overflow: hidden; background: #000; border: 1px solid rgba(255,255,255,0.1); }
        .container-img img { width: 100%; height: 100%; object-fit: cover; opacity: 0.1; filter: blur(30px); transition: 1s cubic-bezier(0.4, 0, 0.2, 1); }
        
        /* MECÂNICA DE REVELAÇÃO */
        details[open].solution-box ~ .container-img img { opacity: 1; filter: blur(0); }

        /* INTRO SLIDE */
        .intro-content { text-align: center; margin: auto; }
        .intro-title { font-size: 80px; margin-bottom: 10px; background: linear-gradient(to right, #00f2ff, #bc13fe); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
    </style>
</head>
<body>

    <div class="slide-container" id="intro">
        <div class="intro-content">
            <h1 class="intro-title">ANIME QUIZ SHOW</h1>
            <p style="font-size: 20px; color: #94a3b8; letter-spacing: 4px;">DESAFIO DOS MESTRES</p>
            <a href="#board" class="master-btn" style="width: 300px; margin: 40px auto; font-size: 24px;">ENTRAR NO ARENA</a>
        </div>
    </div>

    <div class="slide-container" id="board">
        <h2 style="margin-bottom: 20px; border-left: 5px solid var(--neon-blue); padding-left: 15px;">PAINEL DE COMANDO</h2>
        <div class="board-grid">
            <div class="cat-header">Personagens</div>
            <div class="cat-header">Falas</div>
            <div class="cat-header">Músicas</div>
            <div class="cat-header">Sinopses</div>

            <a href="#p100" class="prize-btn">$100</a>
            <a href="#f100" class="prize-btn">$100</a>
            <a href="#m100" class="prize-btn">$100</a>
            <a href="#s100" class="prize-btn">$100</a>

            <a href="#p200" class="prize-btn">$200</a>
            <a href="#f200" class="prize-btn">$200</a>
            <a href="#m200" class="prize-btn">$200</a>
            <a href="#s200" class="prize-btn">$200</a>

            <a href="#p300" class="prize-btn">$300</a>
            <a href="#f300" class="prize-btn">$300</a>
            <a href="#m300" class="prize-btn">$300</a>
            <a href="#s300" class="prize-btn">$300</a>

            <a href="#p400" class="prize-btn">$400</a>
            <a href="#f400" class="prize-btn">$400</a>
            <a href="#m400" class="prize-btn">$400</a>
            <a href="#s400" class="prize-btn">$400</a>

            <a href="#p500" class="prize-btn">$500</a>
            <a href="#f500" class="prize-btn">$500</a>
            <a href="#m500" class="prize-btn">$500</a>
            <a href="#s500" class="prize-btn">$500</a>

            <div class="master-row">
                <a href="#master" class="master-btn">MASTER CHALLENGE: $1000</a>
            </div>
        </div>

        <div class="scoreboard">
            <div class="player-box"><input type="text" class="player-name" value="Jogador 1"><input type="number" class="player-score" value="0"></div>
            <div class="player-box"><input type="text" class="player-name" value="Jogador 2"><input type="number" class="player-score" value="0"></div>
            <div class="player-box"><input type="text" class="player-name" value="Jogador 3"><input type="number" class="player-score" value="0"></div>
            <div class="player-box"><input type="text" class="player-name" value="Jogador 4"><input type="number" class="player-score" value="0"></div>
        </div>
    </div>

    <div class="slide-container" id="p100">
        <div class="header-nav">
            <a href="#board" class="back-btn"><i class="fa-solid fa-chevron-left"></i> VOLTAR AO PAINEL</a>
            <div class="prize-tag">$100</div>
        </div>
        <div class="question-content">
            <div class="details-area">
                <h2 style="color:var(--neon-blue)">QUEM É O PERSONAGEM?</h2>
                <details><summary>DICA 1</summary><div class="hint-text">Conhecido como o "Espadachim Negro".</div></details>
                <details><summary>DICA 2</summary><div class="hint-text">Ele carrega uma espada gigantesca chamada Matadora de Dragões.</div></details>
                <details class="solution-box"><summary>VER SOLUÇÃO</summary><div class="answer-text">GUTS (BERSERK)</div></details>
            </div>
            <div class="container-img"><img src="https://via.placeholder.com/1280x720/000/fff?text=Guts+Image" alt="Solution"></div>
        </div>
    </div>

    <div class="slide-container" id="master">
        <div class="header-nav">
            <a href="#board" class="back-btn"><i class="fa-solid fa-chevron-left"></i> VOLTAR AO PAINEL</a>
            <div class="prize-tag" style="background:var(--neon-red); color:#fff;">$1000</div>
        </div>
        <div class="question-content">
            <div class="details-area">
                <h2 style="color:var(--neon-red)">MASTER CHALLENGE</h2>
                <details><summary>DICA FINAL 1</summary><div class="hint-text">O despertar da fruta Hito Hito no Mi, Modelo: Nika.</div></details>
                <details><summary>DICA FINAL 2</summary><div class="hint-text">Os batimentos de seu coração soam como os "Tambores da Libertação".</div></details>
                <details class="solution-box" style="border-color:var(--neon-red)"><summary style="background:var(--neon-red); color:white">O REI DOS PIRATAS</summary><div class="answer-text" style="color:var(--neon-red)">LUFFY GEAR 5</div></details>
            </div>
            <div class="container-img"><img src="https://via.placeholder.com/1280x720/000/fff?text=Luffy+Gear+5" alt="Master Solution"></div>
        </div>
    </div>

</body>
</html>
