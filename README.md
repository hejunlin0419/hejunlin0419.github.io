<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>蚂蚁世界 - 游戏库</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft Yahei", sans-serif;
        }
        body {
            background-color: #1a1a1a;
            color: #fff;
        }
        /* 顶部导航栏 */
        .header {
            background-color: #222;
            padding: 10px 20px;
            display: flex;
            gap: 20px;
            align-items: center;
            border-bottom: 1px solid #333;
        }
        .header a {
            color: #ccc;
            text-decoration: none;
            font-size: 14px;
        }
        .header a:hover {
            color: #fff;
        }
        /* 只修改这里，把LOGO改成你要的链接和文字 */
        .logo {
            color: #ff4444 !important;
            font-weight: bold;
            font-size: 18px;
        }
        /* 内容区 */
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        .section-title {
            background-color: #222;
            display: inline-block;
            padding: 8px 16px;
            border-radius: 4px;
            font-size: 16px;
            margin-bottom: 20px;
        }
        /* 游戏卡片网格 - 只显示一列以突出单款游戏 */
        .game-grid {
            display: grid;
            grid-template-columns: 1fr; /* 只保留一列 */
            gap: 20px;
        }
        .game-card {
            background-color: #222;
            border-radius: 4px;
            overflow: hidden;
            transition: transform 0.2s;
            max-width: 600px; /* 限制宽度，不要太宽 */
        }
        .game-card:hover {
            transform: translateY(-5px);
        }
        .game-cover {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .game-info {
            padding: 15px;
        }
        .game-tag {
            font-size: 12px;
            color: #ffaa00;
            margin-bottom: 6px;
        }
        .game-title {
            font-size: 16px;
            line-height: 1.4;
            margin-bottom: 10px;
            font-weight: bold;
        }
        .game-time {
            font-size: 12px;
            color: #999;
            margin-bottom: 10px;
        }
        .game-free {
            font-size: 12px;
            background-color: #ff4444;
            color: #fff;
            padding: 2px 6px;
            border-radius: 2px;
            display: inline-block;
        }
    </style>
</head>
<body>
    <!-- 顶部导航 -->
    <div class="header">
        <!-- 修改这里的链接为 hejunlin0419.github.io -->
        <a href=" " class="logo">蚂蚁世界</a >
    </div>

    <!-- 内容区 -->
    <div class="container">
        <div class="section-title">游戏列表</div>
        <div class="game-grid">
            <!-- 唯一的一款游戏：蚂蚁世界 -->
            <div class="game-card">
                <!-- 你可以替换图片链接为你蚂蚁世界的封面图 -->
                < img class="game-cover" src="https://picsum.photos/600/200?random=10" alt="蚂蚁世界封面">
                <div class="game-info">
                    <div class="game-tag">PC PLAY | 官方中文</div>
                    <!-- 游戏名字改为蚂蚁世界 -->
                    <div class="game-title">蚂蚁世界</div>
                    <div class="game-time">⚪ 永久更新</div>
                    <div class="game-free">免费</div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
