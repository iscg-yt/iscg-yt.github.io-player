<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formspree Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f9f9f9;
        }
        form {
            max-width: 500px;
            margin: 0 auto;
            padding: 20px;
            background: white;
            border: 1px solid #ccc;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        form label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        form button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1 style="text-align: center;">地圖推薦 Map Recommend</h1>
    <h2 style="text-align: center;">發送後我會審核後考慮加入本網頁</h2>
    <form action="https://formspree.io/f/myzzwlwb" method="POST" enctype="multipart/form-data">
        <!-- 使用者名字 -->
        <label for="name">你的名字</label>
        <input type="text" id="name" name="name" required>
        <!-- 地圖名稱 -->
        <label for="map_name">你的地圖名稱</label>
        <input type="text" id="map_name" name="map_name" required>
        <!-- 地圖代碼 -->
        <label for="map_code">你的地圖代碼</label>
        <input type="text" id="map_code" name="map_code" required>
        <!-- 地圖簡介 -->
        <label for="map_description">你的地圖簡介</label>
        <textarea id="map_description" name="map_description" rows="3" required></textarea>
        <!-- 提交按鈕 -->
        <button type="submit">提交</button>
    </form>
</body>
</html>
