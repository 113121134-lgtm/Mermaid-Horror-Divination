<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>深海之瞳：人魚占卜</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="overlay"></div>

    <div class="container">
        <header>
            <h1 class="glitch" data-text="人魚的低語">人魚的低語</h1>
            <div class="intro-text">
                <p>人類總以為大海是溫暖的搖籃，卻忘了光線照不到的地方，盡是冰冷的惡意。</p>
                <p class="warning">警告：一旦潛入，靈魂概不退還。</p>
            </div>
        </header>

        <main>
            <div class="oracle-box">
                <div id="result-text">水面下...有東西在看著你。</div>
            </div>
            <button id="divine-btn">獻祭一段記憶</button>
        </main>

        <footer>
            <p>© 2026 深淵禁區 - 你的呼吸是她的收藏品</p>
        </footer>
    </div>

    <script src="script.js"></script>
</body>
</html<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>深淵祭壇｜人魚之咒</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="water-overlay"></div>
    
    <div class="container" id="app">
        <section id="step-1" class="scene active">
            <h1 class="glitch" data-text="深淵的契約">深淵的契約</h1>
            <p class="intro-p">在潛入之前，請寫下一個你最想遺忘的記憶或名字...</p>
            <input type="text" id="sacrifice-input" placeholder="輸入祭品..." autocomplete="off">
            <button onclick="startRitual()">開始下潛</button>
        </section>

        <section id="step-2" class="scene">
            <div class="sinking-status">
                <div class="depth-meter">深度：<span id="depth-val">0</span>m</div>
                <p id="status-text">正在排開海水...</p>
            </div>
            <div class="bubbles"></div>
        </section>

        <section id="step-3" class="scene">
            <div class="card" id="divine-card">
                <div class="card-inner">
                    <div class="card-front">?</div>
                    <div class="card-back">
                        <h2 id="card-title">標題</h2>
                        <div class="card-divider"></div>
                        <p id="card-desc">描述</p>
                    </div>
                </div>
            </div>
            <button class="retry-btn" onclick="location.reload()">浮出水面</button>
        </section>
    </div>

    <script src="script.js"></script>
</body>
</html>
