<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cửu Âm Chân Kinh - GOSU</title>
    <link rel="stylesheet" href="/css/site.css">
</head>
<body>
    
    <div class="top">  
        <img src="/images/bg-top.jpg" alt=""> 
        <div class="s">
            <ul class="a1">Tin Tức  </ul> <ul>|</ul>
            <ul class="a2"> Giới Thiệu </ul> <ul>|</ul>
            <ul class="a3"> Hướng dẫn </ul> <ul>|</ul>
            <ul class="a4"> Download </ul> <ul>|</ul>
        </div>
        <div class="s1"> <ul>|</ul>
            <ul>Đặc sắc</ul> <ul>|</ul>
            <ul>Thư viện</ul> <ul>|</ul>
            <ul>Hỗ trợ</ul> <ul>|</ul>
            <ul>Cộng đồng</ul> 
        </div>
    </div>
</body>
</html>




.top{
    display: flex;
    flex-direction: row;
    justify-content: center;
    flex-wrap: wrap;
    position: relative;
}
.top .s
{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    position: absolute;
    top: -10px;
    left: 100px;
    font-size: 24px;
    color: rgb(220,235,235);
    cursor: pointer;
}
.top .s1
{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    position: absolute;
    top: -10px;
    left: 1006px;
    font-size: 24px;
    color: rgb(220,235,235);
    cursor: pointer;
}
