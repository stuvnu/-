<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>國家隊與八大公股行庫每日動向觀測儀表板</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f4f6f9;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #fff;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }
        h1 {
            color: #1e3a8a;
            font-size: 24px;
            border-bottom: 2px solid #e5e7eb;
            padding-bottom: 10px;
            margin-top: 0;
        }
        p {
            line-height: 1.6;
            color: #4b5563;
        }
        .card-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 25px;
        }
        @media (max-width: 600px) {
            .card-grid { grid-template-columns: 1fr; }
        }
        .card {
            border: 1px solid #e5e7eb;
            border-radius: 8px;
            padding: 20px;
            background: #f9fafb;
            transition: transform 0.2s, box-shadow 0.2s;
        }
        .card:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        .card h3 {
            margin-top: 0;
            color: #2563eb;
            font-size: 18px;
        }
        .btn {
            display: inline-block;
            background-color: #2563eb;
            color: #fff;
            padding: 10px 16px;
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
            margin-top: 10px;
            font-size: 14px;
        }
        .btn:hover {
            background-color: #1d4ed8;
        }
        .notice {
            margin-top: 30px;
            background-color: #eff6ff;
            border-left: 4px solid #3b82f6;
            padding: 15px;
            border-radius: 4px;
            font-size: 14px;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>🏛️ 國家隊與八大公股行庫每日動向觀測</h1>
    <p>由於台灣證券交易所每日盤後會更新各券商進出明細，本頁面整合了市場最常用的公股追蹤入口。建議於<strong>每日下午 4:30 盤後資料更新後</strong>點擊下方連結，即可取得當日最新前10名買超個股與金額。</p>
    
    <div class="card-grid">
        <!-- 區塊一：買賣超排行 -->
        <div class="card">
            <h3>📈 每日公股買賣超排行</h3>
            <p>即時查詢今日八大公股買超張數、買超金額前10名與前20名排行，最直觀看出國家隊護盤力道與點名標的。</p>
            <a href="https://histock.tw" target="_blank" class="btn">前往嗨投資觀看 ➔</a>
        </div>
        
        <!-- 區塊二：詳細進出統計 -->
        <div class="card">
            <h3>📊 官股券商進出總覽</h3>
            <p>提供八大行庫（台銀、土銀、兆豐、合作金庫等）每日與近期的買賣超金額加總，掌握政策關注重點。</p>
            <a href="https://wantgoo.com" target="_blank" class="btn">前往玩股網觀看 ➔</a>
        </div>

        <!-- 區塊三：主力核心權值 -->
        <div class="card">
            <h3>🎯 護盤指標股即時走勢</h3>
            <p>直接觀測國家隊買超金額通常居冠的護盤核心——台積電 (2330) 現階段的法人籌碼與股價波動狀態。</p>
            <a href="https://yahoo.com" target="_blank" class="btn">觀看台積電走勢 ➔</a>
        </div>

        <!-- 區塊四：熱門低接晶圓 -->
        <div class="card">
            <h3>⚡ 熱門低接標的走勢</h3>
            <p>直接觀測大跌時官股經常大量敲進張數的指標股——力積電 (6770) 目前的市場成交明細與即時表現。</p>
            <a href="https://yahoo.com" target="_blank" class="btn">觀看力積電走勢 ➔</a>
        </div>
    </div>

    <div class="notice">
        <strong>💡 使用小叮嚀：</strong>
        八大公股行庫（包含臺銀、土銀、兆豐、合庫、第一、華南、彰銀、台企銀）的進出紀錄屬於盤後統計。每日收盤後，各網站數據會自動抓取交易所券商申報資料同步更新，因此使用此頁面導航即可達到「每日看最新數據」的效果。
    </div>
</div>

</body>
</html>
