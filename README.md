<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GoalShot Studio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #0b0f1a;
            color: white;
        }
        header {
            background: #111;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header h1 {
            color: #00ff99;
        }
        nav a {
            color: white;
            margin-left: 20px;
            text-decoration: none;
        }
        .hero {
            height: 90vh;
            background: url('https://images.unsplash.com/photo-1517927033932-b3d18e61fb3a') center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .hero h2 {
            font-size: 3rem;
            background: rgba(0,0,0,0.6);
            padding: 20px;
        }
        .section {
            padding: 50px 20px;
            text-align: center;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }
        .gallery img {
            width: 100%;
            border-radius: 10px;
        }
        .contact {
            background: #111;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #000;
        }
        button {
            padding: 10px 20px;
            background: #00ff99;
            border: none;
            cursor: pointer;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>GoalShot Studio</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Capturing Football Moments That Matter ⚽</h2>
</section>

<section class="section">
    <h2>About Us</h2>
    <p>We specialize in professional football photography — from grassroots matches to elite competitions. We capture every goal, every tackle, and every emotion.</p>
</section>

<section class="section" id="gallery">
    <h2>Our Work</h2>
    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1508098682722-e99c643e7f0b">
        <img src="https://images.unsplash.com/photo-1522778119026-d647f0596c20">
        <img src="https://images.unsplash.com/photo-1518609878373-06d740f60d8b">
        <img src="https://images.unsplash.com/photo-1517649763962-0c623066013b">
    </div>
</section>

<section class="section contact" id="contact">
    <h2>Contact Us</h2>
    <p>Email: goalshotstudio@gmail.com</p>
    <p>Phone: +233 XXX XXX XXX</p>
    <button>Book a Session</button>
</section>

<footer>
    <p>&copy; 2026 GoalShot Studio. All Rights Reserved.</p>
</footer>

</body>
</html>
