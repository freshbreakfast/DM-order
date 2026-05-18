<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>豆漿三款｜新品上市</title>

<style>
html, body {
    margin: 0;
    padding: 0;
    height: 100%;
    width: 100%;
    background: #111;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    font-family: "Noto Sans TC", sans-serif;
    position: relative;
}

img {
    max-width: 100%;
    max-height: 100%;
    object-fit: contain;
    display: block;
}

.buttons {
    position: absolute;
    bottom: 28px;
    display: flex;
    gap: 14px;
    z-index: 10;
}

.btn {
    padding: 14px 28px;
    border-radius: 999px;
    text-decoration: none;
    font-size: 16px;
    font-weight: 700;
    transition: all 0.25s ease;
    box-shadow: 0 6px 18px rgba(0,0,0,.25);
}

.line-btn {
    background: #06C755;
    color: #fff;
}

.shop-btn {
    background: #fff;
    color: #111;
}

.btn:hover {
    transform: translateY(-2px);
}

.hint {
    position: absolute;
    bottom: 95px;
    color: rgba(255,255,255,0.7);
    font-size: 14px;
    animation: fade 1.8s infinite;
}

@keyframes fade {
    0%,100% { opacity: .7; }
    50% { opacity: .25; }
}

@media (max-width: 768px) {
    .buttons {
        flex-direction: column;
        bottom: 18px;
    }

    .btn {
        text-align: center;
        min-width: 180px;
    }

    .hint {
        bottom: 150px;
    }
}
</style>
</head>

<body>

<img src="dm.jpg" alt="豆漿三款DM">

<div class="hint">輕觸按鈕立即下單</div>

<div class="buttons">
    <a class="btn line-btn" href="line://nv/recommendOA/@567ncwhd">
        門市取貨
    </a>

    <a class="btn shop-btn" href="https://famistore.famiport.com.tw/users/2903801" target="_blank">
        立即網購
    </a>
</div>

</body>
</html>
