<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>旅のしおり - 上高地・飛騨高山・諏訪湖花火 2026</title>
    <style>
        :root {
            --primary-color: #2c5d3f;
            --accent-color: #e67e22;
            --bg-color: #f8f9fa;
            --card-bg: #ffffff;
            --text-color: #333333;
            --border-color: #e0e0e0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: linear-gradient(135deg, #1b4332, #2d6a4f);
            color: white;
            text-align: center;
            padding: 30px 20px;
            border-radius: 12px;
            margin-bottom: 25px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        header h1 {
            margin: 0 0 10px 0;
            font-size: 24px;
        }

        header p {
            margin: 0;
            opacity: 0.9;
            font-size: 14px;
        }

        .meta-info {
            display: flex;
            justify-content: space-around;
            background-color: rgba(255,255,255,0.15);
            padding: 10px;
            border-radius: 8px;
            margin-top: 15px;
            font-size: 13px;
        }

        .card {
            background: var(--card-bg);
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            border: 1px solid var(--border-color);
        }

        h2 {
            color: var(--primary-color);
            border-bottom: 2px solid var(--primary-color);
            padding-bottom: 8px;
            margin-top: 0;
            font-size: 18px;
        }

        .timeline {
            position: relative;
            padding-left: 20px;
        }

        .timeline::before {
            content: "";
            position: absolute;
            left: 4px;
            top: 5px;
            bottom: 5px;
            width: 2px;
            background-color: var(--primary-color);
            opacity: 0.3;
        }

        .timeline-item {
            position: relative;
            margin-bottom: 20px;
        }

        .timeline-item::before {
            content: "";
            position: absolute;
            left: -20px;
            top: 5px;
            width: 10px;
            height: 10px;
            border-radius: 50%;
            background-color: var(--primary-color);
        }

        .time {
            font-weight: bold;
            color: var(--accent-color);
            font-size: 14px;
        }

        .event-title {
            font-weight: bold;
            font-size: 16px;
            margin: 2px 0;
        }

        .event-desc {
            font-size: 13px;
            color: #666;
            margin: 0;
        }

        .checklist {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .checklist li {
            padding: 8px 0;
            border-bottom: 1px dashed var(--border-color);
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 14px;
        }

        input[type="checkbox"] {
            width: 18px;
            height: 18px;
            accent-color: var(--primary-color);
            cursor: pointer;
        }

        .notice-box {
            background-color: #fff3cd;
            border-left: 4px solid #ffc107;
            padding: 12px;
            border-radius: 4px;
            font-size: 13px;
            margin-top: 15px;
        }

        footer {
            text-align: center;
            padding: 20px;
            font-size: 12px;
            color: #888;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>旅のしおり</h1>
            <p>上高地散策・飛騨高山・諏訪湖花火 2026</p>
            <div class="meta-info">
                <span>日程: 2026年8月10日(月)〜12日(水)</span>
                <span>人数: 大人2名</span>
            </div>
        </header>

        <!-- DAY 1 -->
        <div class="card">
            <h2>DAY 1 : 8月10日(月) 【水戸発・松本・沢渡車中泊】</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="time">14:30</div>
                    <div class="event-title">水戸 出発</div>
                    <div class="event-desc">高速道路で松本方面へ移動（途中休憩を取りながら安全運転）</div>
                </div>
                <div class="timeline-item">
                    <div class="time">18:30</div>
                    <div class="event-title">松本市街 到着・寿司ディナー</div>
                    <div class="event-desc">松本市内で美味しい寿司夕食を堪能</div>
                </div>
                <div class="timeline-item">
                    <div class="time">20:30</div>
                    <div class="event-title">沢渡（さわんど）駐車場へ移動</div>
                    <div class="event-desc">国道158号線経由で沢渡へ向かう（約1時間）</div>
                </div>
                <div class="timeline-item">
                    <div class="time">21:30</div>
                    <div class="event-title">沢渡駐車場 到着・車中泊</div>
                    <div class="event-desc">早朝の発車に備えて就寝（防寒・虫除け対策）</div>
                </div>
            </div>
        </div>

        <!-- DAY 2 -->
        <div class="card">
            <h2>DAY 2 : 8月11日(火・祝) 【上高地散策 & 温泉旅館】</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="time">05:30</div>
                    <div class="event-title">沢渡バスターミナル 発</div>
                    <div class="event-desc">マイカー規制のためシャトルバスで上高地へ</div>
                </div>
                <div class="timeline-item">
                    <div class="time">06:00</div>
                    <div class="event-title">大正池 下車・ハイキング開始</div>
                    <div class="event-desc">大正池 〜 河童橋 〜 明神池（約10km歩行）立ち枯れの木々や穂高連峰の絶景を楽しむ</div>
                </div>
                <div class="timeline-item">
                    <div class="time">12:00</div>
                    <div class="event-title">河童橋周辺でランチ</div>
                    <div class="event-desc">山賊焼きやアップルパイで休憩</div>
                </div>
                <div class="timeline-item">
                    <div class="time">13:30</div>
                    <div class="event-title">上高地バスターミナル 発</div>
                    <div class="event-desc">シャトルバスで沢渡へ戻る</div>
                </div>
                <div class="timeline-item">
                    <div class="time">15:00</div>
                    <div class="event-title">温泉旅館 チェックイン</div>
                    <div class="event-desc">源泉かけ流し・貸切風呂で疲労回復。夕食は飛騨牛（信州牛）炭火焼き・会席（※甲殻類・貝類NG対応）</div>
                </div>
            </div>
        </div>

        <!-- DAY 3 -->
        <div class="card">
            <h2>DAY 3 : 8月12日(水) 【飛騨高山・フルーツ狩り・諏訪湖花火】</h2>
            <div class="timeline">
                <div class="timeline-item">
                    <div class="time">10:00</div>
                    <div class="event-title">宿 チェックアウト</div>
                    <div class="event-desc">飛騨高山へ移動（安房トンネル経由、約1時間）</div>
                </div>
                <div class="timeline-item">
                    <div class="time">11:00</div>
                    <div class="event-title">飛騨高山 古い町並み散策</div>
                    <div class="event-desc">飛騨牛握り寿司や五平餅の食べ歩き・散策</div>
                </div>
                <div class="timeline-item">
                    <div class="time">14:30</div>
                    <div class="event-title">信州フルーツ狩り ＆ 蕎麦ランチ</div>
                    <div class="event-desc">松本/塩尻エリアで果物狩り＆本場信州そば</div>
                </div>
                <div class="timeline-item">
                    <div class="time">19:00</div>
                    <div class="event-title">諏訪湖花火 鑑賞</div>
                    <div class="event-desc">諏訪湖畔でナイト花火観賞後、水戸へ帰路</div>
                </div>
            </div>
        </div>

        <!-- CHECKLIST -->
        <div class="card">
            <h2>事前準備・持ち物チェックリスト</h2>
            <ul class="checklist">
                <li><input type="checkbox"> 宿へ甲殻類・貝類NGの事前連絡確認</li>
                <li><input type="checkbox"> トレッキングシューズ（歩きやすい靴）</li>
                <li><input type="checkbox"> レインウェア（雨具）・折りたたみ傘</li>
                <li><input type="checkbox"> 防寒用の上着（早朝の上高地用）</li>
                <li><input type="checkbox"> 車中泊用寝具・サンシェード・ライト</li>
                <li><input type="checkbox"> 虫除けスプレー・日焼け止め・飲み物</li>
            </ul>
            <div class="notice-box">
                <strong>ワンポイント注意点：</strong><br>
                ・上高地は全域マイカー規制のため沢渡でバス乗り換えが必要です。<br>
                ・山の天気は変わりやすいため、晴れていても必ず雨具をお持ちください。<br>
                ・8/12の諏訪湖周辺は花火混雑が予想されるため、早めの移動を心がけましょう。
            </div>
        </div>

        <footer>
            <p>2026年 8月 信州・飛騨ドライブ旅行のしおり</p>
        </footer>
    </div>
</body>
</html>
