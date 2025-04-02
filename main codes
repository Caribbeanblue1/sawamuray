<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>网络画廊</title>
    <style>
        /* 基础样式设置 */
        body {
            margin: 0;
            padding: 20px;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            font-family: 'Microsoft YaHei', sans-serif;
            min-height: 100vh;
        }

        /* 音乐播放器样式 */
        .music-player {
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
            text-align: center;
        }

        .music-player h2 {
            color: #2c3e50;
            margin-bottom: 20px;
            font-size: 24px;
        }

        audio {
            width: 100%;
            max-width: 500px;
            margin: 0 auto;
        }

        /* 画廊容器样式 */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
            padding: 20px;
        }

        /* 单个画廊项目样式 */
        .gallery-item {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .gallery-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
        }

        /* 图片容器样式 */
        .image-container {
            position: relative;
            overflow: hidden;
            padding-top: 75%; /* 4:3 宽高比 */
        }

        .gallery-item img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .gallery-item:hover img {
            transform: scale(1.05);
        }

        /* 图片描述样式 */
        .gallery-item p {
            padding: 15px;
            margin: 0;
            color: #34495e;
            font-size: 16px;
            line-height: 1.6;
        }

        /* 响应式设计 */
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }

            .gallery {
                grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
                gap: 15px;
            }

            .music-player {
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <!-- 音乐播放器部分 -->
    <div class="music-player">
        <h2>背景音乐</h2>
        <audio controls loop>
            <source src="music/大混沌进行曲.mp3" type="audio/mp3">
        </audio>
    </div>

    <!-- 图片画廊部分 -->
    <div class="gallery">
        <!-- 画廊项目1 -->
        <div class="gallery-item">
            <div class="image-container">
                <img src="image/maxiu.jpg" alt="玛修">
            </div>
            <p>这是我家玛修</p>
        </div>

        <!-- 画廊项目2 -->
        <div class="gallery-item">
            <div class="image-container">
                <img src="image/wuwang.jpg" alt="阿尔托莉雅·潘德拉贡">
            </div>
            <p>这是我家吾王</p>
        </div>

        <!-- 画廊项目3 -->
        <div class="gallery-item">
            <div class="image-container">
                <img src="image/beizhai.jpg" alt="葛饰北斋&葛饰应为">
            </div>
            <p>这是我家北斋</p>
        </div>
    </div>
</body>
</html>
