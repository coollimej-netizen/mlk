<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>사이트 이동</title>

<style>
    body {
        font-family: Arial, sans-serif;
        background: #f6f6f6;
        margin: 0;
        padding: 20px;
    }

    .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background: #fff;
        padding: 15px 20px;
        border-radius: 12px;
        font-size: 24px;
        font-weight: bold;
    }

    .header img {
        height: 40px;
        border-radius: 8px;
        object-fit: cover;
    }

    .container {
        margin-top: 25px;
        background: #fff;
        border-radius: 15px;
        padding: 20px;
    }

    .site-box {
        border: 2px solid #ddd;
        border-radius: 15px;
        padding: 20px;
        margin-bottom: 15px;
        background: #fafafa;
        transition: 0.2s;
    }

    .site-box:hover {
        border-color: #000;
        box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .site-title {
        font-size: 18px;
        font-weight: bold;
        margin-bottom: 10px;
    }

    .go-btn {
        display: inline-block;
        background: #000;
        color: #fff;
        padding: 12px 20px;
        border-radius: 10px;
        text-decoration: none;
        font-weight: bold;
    }

    .desc {
        margin-top: 12px;
        font-size: 14px;
        color: #555;
    }

</style>
</head>

<body>

<div class="header">
    <div>사이트바로가기</div>
    <img src="이미지경로.png" alt="logo">
</div>

<div class="container">

    <div class="site-box">
        <div class="site-title">
            <!-- HTML 코드 직접 적기 -->
            <code>https://example.com</code>
        </div>

        <a class="go-btn" href="https://example.com" target="_blank">사이트 이동</a>

        <div class="desc">
            이 사이트는 디자인 샘플을 확인할 수 있는 페이지입니다.
        </div>
    </div>

</div>

</body>
</html>
