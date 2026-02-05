<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>旭嶼・Sunbay 歲末禮獻</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+TC:wght@400;600;900&display=swap" rel="stylesheet">
    <style>
        :root {
            --deep-red: #721010;
            --velvet-red: #8B0000;
            --brass-gold: #B3925D;
            --dark-bg: #1A1A1A;
            --text-gold: #E5C28B;
        }

        body {
            margin: 0;
            padding: 0;
            background-color: var(--dark-bg);
            color: var(--text-gold);
            font-family: 'Noto Serif TC', serif;
            letter-spacing: 0.15em;
        }

        .hero {
            height: 70vh;
            background: linear-gradient(to bottom, rgba(0,0,0,0.3), var(--dark-bg)), 
                        url('https://images.unsplash.com/photo-1594631252845-29fc4cc8cde9?q=80&w=1500'); 
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            border-bottom: 2px solid var(--brass-gold);
        }

        .hero h1 {
            font-size: clamp(2rem, 8vw, 3.5rem);
            font-weight: 900;
            color: #fff;
            margin: 0;
            text-shadow: 0 4px 15px rgba(0,0,0,0.5);
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 60px 20px;
        }

        .philosophy {
            text-align: center;
            margin-bottom: 60px;
            padding: 40px 20px;
            border: 1px solid var(--brass-gold);
            background: linear-gradient(135deg, #251010 0%, #1A1A1A 100%);
        }

        /* 產品圖片樣式優化 */
        .product-image {
            width: 100%;
            max-height: 500px;
            object-fit: cover;
            border: 1px solid var(--brass-gold);
            margin-bottom: 20px;
            display: block;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
            margin-bottom: 60px;
        }

        .product-card {
            background: #252525;
            padding: 0; /* 讓圖片填滿上方 */
            border: 1px solid #333;
            overflow: hidden;
        }

        .product-info {
            padding: 25px;
        }

        .product-card h3 {
            color: var(--brass-gold);
            margin-top: 0;
        }

        .order-section {
            text-align: center;
            background-color: var(--deep-red);
            padding: 60px 20px;
            border-radius: 2px;
        }

        .price-new {
            display: block;
            font-size: 3rem;
            font-weight: 900;
            color: var(--text-gold);
            margin: 10px 0;
        }

        .cta-button {
            display: inline-block;
            background-color: var(--brass-gold);
            color: var(--dark-bg);
            padding: 18px 40px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 0;
            transition: 0.3s;
        }

        footer { text-align: center; padding: 40px; color: #555; font-size: 0.8rem; }
    </style>
</head>
<body>

    <section class="hero">
        <p style="letter-spacing: 0.5em; margin-bottom: 10px; color: var(--brass-gold);">SUNBAY EXCLUSIVE</p>
        <h1>財聚八方 · 八方聚財</h1>
        <p>旭嶼・Sunbay 歲末聯名禮獻</p>
    </section>

    <div class="container">
        <div class="philosophy">
            <h2>美好開始，始於一席茶香</h2>
            <p>送禮，是表達情誼與珍惜。在馬年新程之際，為您遞上一份福氣與溫度。</p>
        </div>

        <div class="product-grid">
            <div class="product-card" style="grid-column: 1 / -1;">
                <img src="https://raw.githubusercontent.com/freshstart20143-png/888/980ece012235396f393cf80b8007823c1e9c060e/S__33800256.png" alt="嚴選頂級茶" class="product-image">
                <div class="product-info">
                    <h3>🍵 嚴選頂級茶 (10入)</h3>
                    <p>龍藏培韻、蜜琥紅烏、桂花窨春。臺灣在地職人手作，封存高山氣息。這張照片展現了我們對品質的堅持，每一包茶都值得您細細品味。</p>
                </div>
            </div>

            <div class="product-card">
                <div class="product-info">
                    <h3>🍿 茶香爆米花</h3>
                    <p>Sunbay 獨家研發，茶粉細緻包裹，清脆間帶有濃郁餘韻。</p>
                </div>
            </div>

            <div class="product-card">
                <div class="product-info">
                    <h3>🍪 手工茶香餅乾</h3>
                    <p>將茶韻揉入餅皮，低溫慢烤，品味每一口優雅的溫潤。</p>
                </div>
            </div>
        </div>

        <div class="order-section">
            <span class="price-new">🧧 開運價 $688</span>
            <p style="margin-bottom: 30px;">✨ 公司團體/大量訂購另有優惠 ✨</p>
            <a href="https://line.me" class="cta-button">立即洽詢訂購</a>
        </div>
    </div>

    <footer>
        &copy; 2026 旭嶼 · Sunbay｜馬躍新程 福運隨行
    </footer>

</body>
</html>
