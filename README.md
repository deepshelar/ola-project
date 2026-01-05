<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Login | Ride App</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            height: 100vh;
            background: url("https://images.unsplash.com/photo-1502877338535-766e1452684a")
                        no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .login-box {
            background: rgba(0, 0, 0, 0.75);
            padding: 40px;
            width: 350px;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.6);
            color: #fff;
        }

        .login-box h2 {
            text-align: center;
            margin-bottom: 25px;
            font-size: 26px;
            letter-spacing: 1px;
        }

        .input-group {
            margin-bottom: 18px;
        }

        .input-group label {
            display: block;
            margin-bottom: 6px;
            font-size: 14px;
        }

        .input-group input {
            width: 100%;
            padding: 10px;
            border: none;
            outline: none;
            border-radius: 5px;
            font-size: 14px;
        }

        .login-btn {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 5px;
            background: #00c853; /* Uber/Ola style green */
            color: #fff;
            font-size: 16px;
            cursor: pointer;
            margin-top: 10px;
        }

        .login-btn:hover {
            background: #00a846;
        }

        .extra-links {
            text-align: center;
            margin-top: 15px;
            font-size: 13px;
        }

        .extra-links a {
            color: #00c853;
            text-decoration: none;
        }

        .extra-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="login-box">
        <h2>Login</h2>

        <div class="input-group">
            <label>Username or Email</label>
            <input type="text" placeholder="Enter your email or username">
        </div>

        <div class="input-group">
            <label>Password</label>
            <input type="password" placeholder="Enter your password">
        </div>

        <button class="login-btn">Login</button>

        <div class="extra-links">
            <p><a href="#">Forgot Password?</a></p>
            <p>New user? <a href="#">Sign Up</a></p>
        </div>
    </div>

</body>
</html>
