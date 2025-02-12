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
            <a class="navbar-brand text-white" href=" ">静心养生茶</a >
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link text-white" href="#products">产品</a ></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#acupoints">穴位引导</a ></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#shop">商城</a ></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- 产品展示 -->
    <div class="container py-5" id="products">
        <h2 class="text-center mb-4">养生茶系列</h2>
        <div class="row">
            <div class="col-md-4 tea-card">
                < img src="https://via.placeholder.com/300x200" class="img-fluid rounded">
                <h3 class="mt-3">安神助眠茶</h3>
                <p>主要成分：酸枣仁、茯苓、百合</p >
            </div>
            <div class="col-md-4 tea-card">
                < img src="https://via.placeholder.com/300x200" class="img-fluid rounded">
                <h3 class="mt-3">舒缓解压茶</h3>
                <p>主要成分：菊花、甘草、薄荷</p >
            </div>
        </div>
    </div>

    <!-- 引入 Bootstrap JavaScript -->
    <script src="https://cdn.bootcdn.net/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    <script src="https://cdn.bootcdn.net/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
</body>
</html>
