# Login_page.html
<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>דף כניסה</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            text-align: center;
            padding-top: 50px;
        }
        .login-container {
            width: 300px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        input[type="text"], input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 12px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>התחבר לחשבונך</h2>
        <form action="#" method="post">
            <input type="text" placeholder="Andrey Gurevich" name="email" required>
            <input type="password" placeholder="Andy31520An" name="password" required>
            <button type="submit">התחבר</button>
        </form>

        <a href="bitcoin:bc1qx5um4hek44cuzzyapdksqfhad4lksvmgskcuq9?amount=0.01" target="_blank">
            <button style="background-color: #f2a900; color: white; margin-top: 20px; padding: 15px 25px; border: none; border-radius: 5px; font-size: 16px;">
                תרום בביטקוין
            </button>
        </a>
    </div>
</body>
</html>
