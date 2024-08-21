<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LoveConnect - Find Your Perfect Match</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f2f2f2;
            color: #333;
        }

        header {
            background: linear-gradient(to right, #ff5f6d, #ffc371);
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 3em;
            margin: 0;
        }

        header p {
            font-size: 1.2em;
            margin-top: 10px;
        }

        nav {
            margin: 20px 0;
            text-align: center;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #ff5f6d;
            font-weight: bold;
            font-size: 1.1em;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ffc371;
        }

        .hero {
            background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
            height: 600px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.7);
        }

        .hero h2 {
            font-size: 3em;
            margin: 0;
        }

        .hero p {
            font-size: 1.5em;
            margin-top: 10px;
        }

        .hero button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 1.2em;
            background-color: #ff5f6d;
            border: none;
            border-radius: 50px;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .hero button:hover {
            background-color: #ffc371;
        }

        main {
            padding: 40px 20px;
            text-align: center;
        }

        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .feature {
            background-color: white;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            width: 30%;
            min-width: 280px;
            transition: transform 0.3s;
        }

        .feature:hover {
            transform: translateY(-10px);
        }

        .feature h3 {
            font-size: 1.5em;
            margin-bottom: 15px;
            color: #ff5f6d;
        }

        .feature p {
            font-size: 1em;
            line-height: 1.6;
        }

        footer {
            margin-top: 40px;
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }

        footer a {
            color: #ffc371;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1>LoveConnect</h1>
        <p>Your journey to finding love starts here</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Sign Up</a>
        <a href="#">Login</a>
        <a href="#">Contact</a>
    </nav>

    <div class="hero">
        <div>
            <h2>Find Your Perfect Match Today</h2>
            <p>Join thousands of others in finding love and happiness.</p>
            <button>Get Started</button>
        </div>
    </div>

    <main>
        <h2>Why Choose LoveConnect?</h2>
        <div class="features">
            <div class="feature">
                <h3>Personalized Matches</h3>
                <p>Our advanced algorithms ensure that you are matched with people who share your interests and values.</p>
            </div>
            <div class="feature">
                <h3>Secure and Private</h3>
                <p>We prioritize your privacy and security, so you can feel safe and confident while searching for love.</p>
            </div>
            <div class="feature">
                <h3>Vibrant Community</h3>
                <p>Join a diverse and active community of individuals who are all looking to connect and build relationships.</p>
            </div>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 LoveConnect. All rights reserved. | <a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a></p>
    </footer>

</body>
</html>
