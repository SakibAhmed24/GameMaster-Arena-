<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GameMaster Arena</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1E1E2F;
            color: #FFFFFF;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
        }
        .header {
            background: #007BFF;
            padding: 20px;
            font-size: 24px;
        }
        .section {
            margin: 20px 0;
            padding: 20px;
            background: #2A2A3A;
            border-radius: 10px;
        }
        .form-group {
            margin: 10px 0;
        }
        .input-field {
            padding: 10px;
            width: 80%;
            border-radius: 5px;
            border: none;
        }
        .submit-btn {
            background: #007BFF;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .contact {
            margin-top: 20px;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <div class="header">GameMaster Arena - Free Fire Tournament</div>
    <div class="container">
        <div class="section">
            <h2>Welcome to GameMaster Arena</h2>
            <p>Register your squad or login below:</p>
            <a href="login.html" class="submit-btn">Go to Login</a>
        </div>
    </div>
    <div class="header">GameMaster Arena - Free Fire Tournament</div>
    <div class="container">
        <div class="section">
            <h2>Squad Login</h2>
            <form>
                <div class="form-group">
                    <input type="text" class="input-field" placeholder="Team Leader Name" required>
                </div>
                <div class="form-group">
                    <input type="text" class="input-field" placeholder="Contact Number" required>
                </div>
                <div class="form-group">
                    <input type="text" class="input-field" placeholder="Squad Member 1 UID" required>
                </div>
                <div class="form-group">
                    <input type="text" class="input-field" placeholder="Squad Member 2 UID" required>
                </div>
                <div class="form-group">
                    <input type="text" class="input-field" placeholder="Squad Member 3 UID" required>
                </div>
                <div class="form-group">
                    <input type="text" class="input-field" placeholder="Squad Member 4 UID" required>
                </div>
                <button type="submit" class="submit-btn">Login</button>
            </form>
        </div>
        <div class="section contact">
            <h2>Contact Us</h2>
            <p>Email: sakibahmed1647@gmail.com</p>
            <p>Phone: 01789746191</p>
        </div>
    </div>
</body>
</html>
