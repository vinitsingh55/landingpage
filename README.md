<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gambling Landing Page</title>
    <style>
        /* Reset some default styles */
        body, h1, p, a, button {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
        }

        /* Background and color scheme */
        body {
            background-color: #222;
            color: white;
            font-size: 16px;
        }

        header {
            background: #f1c40f;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 36px;
        }

        .hero-section {
            display: flex;
            justify-content: space-between;
            padding: 60px 20px;
            text-align: left;
        }

        .hero-text {
            max-width: 50%;
        }

        .hero-text h2 {
            font-size: 32px;
            margin-bottom: 10px;
        }

        .hero-text p {
            font-size: 18px;
            margin-bottom: 20px;
        }

        .cta-button {
            background-color: #f39c12;
            padding: 15px 30px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            text-transform: uppercase;
        }

        .cta-button:hover {
            background-color: #e67e22;
        }

        .game-preview {
            max-width: 45%;
            height: 300px;
            background-color: #34495e;
            border-radius: 10px;
            position: relative;
        }

        .game-preview img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 10px;
        }

        .footer {
            background-color: #2c3e50;
            padding: 20px;
            text-align: center;
            margin-top: 60px;
        }

        .footer p {
            font-size: 14px;
        }

        .footer a {
            color: #f39c12;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Mahadev Book</h1>
    </header>

    <!-- Hero Section -->
    <section class="hero-section">
        <div class="hero-text">
            <h2>Play & Win Big with the Best Online Gambling Experience!</h2>
            <p>Join us now and enjoy exclusive bonuses, jackpots, and much more. Your winning streak starts here.</p>
            <button class="cta-button">Join Now</button>
        </div>
        <div class="game-preview">
            <!-- Replace with a game preview image -->
            <img src="https://via.placeholder.com/500x300" alt="Game Preview">
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="footer">
        <p>&copy; 2025 Mahadev Book. All rights reserved. | <a href="#">Terms & Conditions</a> | <a href="#">Privacy Policy</a></p>
    </footer>

</body>
</html>
