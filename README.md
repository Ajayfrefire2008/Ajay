<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free Fire Tournament</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #111;
            color: #fff;
        }
        header {
            background-color: #ff4500;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2rem;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            background-color: #222;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('https://freefiremobile-a.akamaihd.net/common/web_event/freefire/images/freefire-og-image.jpg') center/cover no-repeat;
            color: white;
        }
        .hero h2 {
            font-size: 2rem;
            margin: 0 0 10px;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .register {
            padding: 20px;
            text-align: center;
        }
        .register h2 {
            color: #ff4500;
        }
        .register form {
            display: inline-block;
            text-align: left;
        }
        .register input, .register button {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border-radius: 5px;
            border: none;
        }
        .register button {
            background-color: #ff4500;
            color: white;
            font-weight: bold;
            cursor: pointer;
        }
        footer {
            background-color: #222;
            color: #777;
            text-align: center;
            padding: 10px;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>🔥 Free Fire Tournament 🔥</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#register">Register</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero" id="home">
        <h2>Join the Ultimate Battle!</h2>
        <p>Win Cash Prizes, Show Your Skills, and Be the Champion</p>
    </section>

    <section class="register" id="register">
        <h2>Register Now</h2>
        <form>
            <input type="text" placeholder="Player Name" required>
            <input type="text" placeholder="Team Name (optional)">
            <input type="text" placeholder="Free Fire UID" required>
            <input type="email" placeholder="Email Address" required>
            <button type="submit">Join Tournament</button>
        </form>
    </section>

    <footer id="contact">
        <p>Contact us: freefiretourney@email.com | WhatsApp: +91 90000 00000</p>
        <p>&copy; 2025 Free Fire Tournament. All Rights Reserved.</p>
    </footer>

</body>
</html>
