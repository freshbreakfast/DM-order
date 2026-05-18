<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>豆漿優惠活動</title>

<style>
html, body {
    margin: 0;
    padding: 0;
    background: #111;
    font-family: "Noto Sans TC", sans-serif;
    overflow-x: hidden;
}

.page {
    width: 100%;
}

.page img {
    width: 100%;
    display: block;
}

.hint {
    position: fixed;
    bottom: 92px;
    left: 50%;
    transform: translateX(-50%);
    color: rgba(255,255,255,0.75);
    font-size: 14px;
    z-index: 999;
    animation: fade 1.8s infinite;
    letter-spacing: 1px;
}

@keyframes fade {
    0%,100% { opacity: .7; }
    50% { opacity: .25; }
}

.buttons {
    position: fixed;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    gap: 12px;
    z-index: 1000;
}

.btn {
    padding: 14px 24px;
    border-radius: 999px;
    text-decoration: none;
    font-size: 15px;
    font-weight: bold;
    box-shadow: 0 4px 14px rgba(0,0,0,.3);
    transition: all 0.25s ease;
    white-space: nowrap;
}

.btn:hover {
    transform: translateY(-2px);
}

.line-btn {
    background: #06C755;
    color: #fff;
}

.shop-btn {
    background: #fff;
    color: #111;
}

@media (max-width: 768px) {
    .buttons {
        width: 90%;
        gap: 10px;
    }

    .btn {
        flex: 1;
        text-align: center;
        padding: 14px 0;
        font-size: 14px;
    }

    .hint {
        bottom: 78px;
        font-size: 12px;
    }
}
</style>
</head>

<body>

<div class="page">
    <img src="投影片1.jpg" alt="投影片1">
    <img src="投影片2.jpg" alt="投影片2">
    <img src="投影片3.jpg" alt="投影片3">
</div>

<div class="hint">往下滑查看更多｜立即下單</div>

<div class="buttons">
    <a class="btn line-btn" href="line://nv/recommendOA/@567ncwhd">
        門市取貨
    </a>

    <a class="btn shop-btn"
       href="https://famistore.famiport.com.tw/users/2903801"
       target="_blank">
        立即網購
    </a>
</div>

</body>
</html>

然後 GitHub repo 裡確認有這 4 個檔：

index.html
投影片1.jpg
投影片2.jpg
投影片3.jpg
