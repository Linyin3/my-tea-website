<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>情绪养生茶包</title>
    <!-- 引入 Bootstrap 简化样式 -->
    <link href="https://cdn.bootcdn.net/ajax/libs/twitter-bootstrap/5.3.0/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* 自定义样式 */
        body {
            background: #f0f5e9; /* 柔和的绿色背景 */
            font-family: 'Microsoft YaHei', sans-serif;
        }
        .tea-card {
            transition: transform 0.3s;
            cursor: pointer;
        }
        .tea-card:hover {
            transform: translateY(-5px);
        }
        .acupoint {
            background: #fff;
            border-radius: 10px;
            padding: 15px;
            margin: 10px;
        }
    </style>
</head>
<body>
    <!-- 导航栏 -->
    <nav class="navbar navbar-expand-lg bg-success text-white p-3">
        <div class="container">
            <a class="navbar-brand text-white" href="#">静心养生茶</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link text-white" href="#products">产品</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#acupoints">穴位引导</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#shop">商城</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- 产品展示 -->
    <div class="container py-5" id="products">
        <h2 class="text-center mb-4">养生茶系列</h2>
        <div class="row">
            <div class="col-md-4 tea-card">
                <img src="https://via.placeholder.com/300x200" class="img-fluid rounded">
                <h3 class="mt-3">安神助眠茶</h3>
                <p>主要成分：酸枣仁、茯苓、百合</p>
            </div>
            <div class="col-md-4 tea-card">
                <img src="https://via.placeholder.com/300x200" class="img-fluid rounded">
                <h3 class="mt-3">疏肝解郁茶</h3>
                <p>主要成分：玫瑰花、陈皮、枸杞</p>
            </div>
        </div>
    </div>

    <!-- 穴位引导 -->
    <div class="container py-5 bg-white" id="acupoints">
        <h2 class="text-center mb-4">推荐养生穴位</h2>
        <div class="row">
            <div class="col-md-6 acupoint">
                <h4>太冲穴</h4>
                <p>位置：足背第一、二跖骨结合部前方凹陷处</p>
                <button class="btn btn-outline-success" onclick="showMassageTip()">查看按摩手法</button>
            </div>
            <div class="col-md-6 acupoint">
                <h4>内关穴</h4>
                <p>位置：前臂掌侧，腕横纹上2寸</p>
                <button class="btn btn-outline-success" onclick="showMassageTip()">查看按摩手法</button>
            </div>
        </div>
    </div>

    <!-- 商城按钮 -->
    <div class="container text-center py-5" id="shop">
        <h2>立即购买</h2>
        <button class="btn btn-success btn-lg mt-3" onclick="goToShop()">
            进入商城 → 
        </button>
    </div>

    <!-- 引入 Bootstrap JS -->
    <script src="https://cdn.bootcdn.net/ajax/libs/twitter-bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
    <script>
        // 简单交互功能
        function showMassageTip() {
            alert("按摩手法：用拇指按压穴位，每次3-5分钟，每日2次");
        }

        function goToShop() {
            // 实际开发需跳转到商城页面
            alert("商城功能开发中...");
        }
    </script>
</body>
</html>
