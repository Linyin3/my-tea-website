<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>情绪养生茶包</title>
    <!-- 引入 Bootstrap 简化样式 -->
    <link href="https://cdn.bootcdn.net/ajax/libs/twitter-bootstrap/5.3.0/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* 自定义样式 */
        body {
            background: #f0f5e9; /* 柔和的绿色背景 */
            font-family: 'Microsoft YaHei', sans-serif;
        }
        .section {
            padding: 40px 0;
            border-radius: 10px;
            margin-bottom: 40px;
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
        .section-title {
            text-align: center;
            margin-bottom: 20px;
        }
        .product-image {
            width: 100%;
            border-radius: 10px;
        }
        .video-container {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .video-container iframe {
            width: 80%;
            height: 500px;
        }
        .section-title h2 {
            font-size: 36px;
        }
        .color-band {
            height: 10px;
            background-color: #5bc0de; /* 默认颜色 */
            margin-bottom: 20px;
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
                    <li class="nav-item"><a class="nav-link text-white" href="#products">养生产品</a ></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#acupoints">养生穴位</a ></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#music-therapy">音乐疗愈</a ></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- 养生产品：茶包 -->
    <div class="section" id="products" style="background-color: #f9f9f9;">
        <div class="color-band"></div>
        <h2 class="section-title">养生产品</h2>
        <div class="row">
            <div class="col-md-4 tea-card" data-bs-toggle="modal" data-bs-target="#productModal1">
                < img src="[https://via.placeholder.com](https://www.pexels.com/zh-cn/search/%E8%8A%B1%E8%8C%B6/)/300x200" class="img-fluid rounded product-image" alt="安神助眠茶">
                <h3 class="mt-3">安神助眠茶</h3>
                <p>主要成分：酸枣仁、茯苓、百合</p >
            </div>
            <div class="col-md-4 tea-card" data-bs-toggle="modal" data-bs-target="#productModal2">
                < img src="https://via.placeholder.com/300x200" class="img-fluid rounded product-image" alt="树干解育茶">
                <h3 class="mt-3">树干解育茶</h3>
                <p>主要成分：枸杞、桂圆、菊花</p >
            </div>
        </div>
    </div>

    <!-- 养生穴位 -->
    <div class="section" id="acupoints" style="background-color: #f2fdf0;">
        <div class="color-band"></div>
        <h2 class="section-title">养生穴位引导</h2>
        <div class="row">
            <div class="col-md-4 acupoint">
                <h4>胎充穴</h4>
                < img src="https://via.placeholder.com/300x200" alt="胎充穴" class="img-fluid rounded">
            </div>
            <div class="col-md-4 acupoint">
                <h4>内关穴</h4>
                < img src="https://via.placeholder.com/300x200" alt="内关穴" class="img-fluid rounded">
            </div>
        </div>
    </div>

    <!-- 音乐疗愈：养生医疗 -->
    <div class="section" id="music-therapy" style="background-color: #e3f9f1;">
        <div class="color-band"></div>
        <h2 class="section-title">音乐疗愈</h2>
        <p>点击下面的视频链接，了解如何使用音乐疗愈来改善身心健康。</p >
        <div class="row">
            <div class="col-md-6">
                <h4>音乐疗愈模块1</h4>
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
                </div>
            </div>
            <div class="col-md-6">
                <h4>音乐疗愈模块2</h4>
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>
                </div>
            </div>
        </div>
    </div>

    <!-- 模态框 - 安神助眠茶 -->
    <div class="modal fade" id="productModal1" tabindex="-1" aria-labelledby="productModal1Label" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="productModal1Label">安神助眠茶</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    < img src="https://via.placeholder.com/300x200" class="img-fluid rounded" alt="安神助眠茶">
                    <p>安神助眠茶的配方包括酸枣仁、茯苓和百合，能够帮助安抚神经，促进睡眠。</p >
                </div>
            </div>
        </div>
    </div>

    <!-- 模态框 - 疏肝解郁茶 -->
    <div class="modal fade" id="productModal2" tabindex="-1" aria-labelledby="productModal2Label" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="productModal2Label">疏肝解郁茶</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">
                    < img src="https://via.placeholder.com/300x200" class="img-fluid rounded" alt="疏肝解郁茶">
                    <p>疏肝解郁由枸杞、桂圆和菊花混合而成，帮助舒缓压力，提升免疫力。</p >
                </div>
            </div>
        </div>
    </div>

    <!-- 引入 Bootstrap JS 和 Popper -->
    <script src="https://cdn.bootcdn.net/ajax/libs/popper.js/2.11.6/umd/popper.min.js"></script>
    <script src="https://cdn.bootcdn.net/ajax/libs/bootstrap/5.3.0/js/bootstrap.min.js"></script>
</body>
</html>
