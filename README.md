# iscg-yt.github.io-player
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
    <h1 style="text-align: center;">問題提交表單</h1>
    <form action="https://formspree.io/f/myzzwlwb" method="POST">
        <label for="name">你的名字</label>
        <input type="text" id="name" name="name" required>
        <label for="email">你的電子郵件</label>
        <input type="email" id="email" name="email" required>
        <label for="message">你的問題</label>
        <textarea id="message" name="message" rows="5" required></textarea>
        <button type="submit">提交</button>
    </form>
</body>
</html>
