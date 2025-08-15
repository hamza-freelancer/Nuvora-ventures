# Nuvora-ventures
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nuvora Ventures Pvt. Ltd. | Global Export & Import</title>

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

    <!-- AOS Library for Animations -->
    <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css" />

    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Poppins', sans-serif;
            background: #fff;
            color: #333;
            scroll-behavior: smooth;
        }
        header {
            background: #013220;
            color: #fff;
            padding: 1rem 2rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 8px rgba(0,0,0,0.2);
        }
        header h1 {
            font-size: 1.8rem;
            color: #FFD700;
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin-top: 0.5rem;
        }
        nav ul li { margin: 0 15px; }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #FFD700;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1602751582675-27a9e693d2c8') no-repeat center center/cover;
            height: 75vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 20px;
            position: relative;
        }
        .hero::after {
            content: "";
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background: rgba(0,0,0,0.5);
        }
        .hero-content {
            position: relative;
            z-index: 1;
        }
        .hero h1 {
            font-size: 3rem;
            color: #FFD700;
        }
        .hero p {
            font-size: 1.2rem;
            margin: 15px 0;
        }
        .btn {
            background: #FFD700;
            color: #013220;
            padding: 12px 25px;
            text-decoration: none;
            font-weight: 700;
            border-radius: 5px;
            transition: background 0.3s, transform 0.3s;
            display: inline-block;
        }
        .btn:hover {
            background: #e6c200;
            transform: translateY(-3px);
        }
        section {
            padding: 60px 20px;
            max-width: 1100px;
            margin: auto;
        }
        h2 {
            text-align: center;
            margin-bottom: 30px;
            color: #013220;
            font-size: 2rem;
        }
        .products, .services {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        .card {
            flex: 1 1 calc(33.333% - 20px);
            background: #f8f8f8;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
        }
        /* World Map Section */
        .world-map {
            text-align: center;
        }
        .world-map img {
            max-width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        /* Contact Form */
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form textarea {
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        form button {
            background: #013220;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            font-weight: 600;
            transition: background 0.3s;
        }
        form button:hover {
            background: #025a37;
        }
        footer {
            background: #00251a;
            color: white;
            text-align: center;
            padding: 15px;
        }
        @media (max-width: 768px) {
            .products, .services { flex-direction: column; }
            .card { flex: 1 1 100%; }
        }
    </style>
</head>
<body>

<header>
    <h1>Nuvora Ventures Pvt. Ltd.</h1>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#map">Global Presence</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <div class="hero-content" data-aos="fade-up">
        <h1>Connecting Harvests to Global Markets</h1>
        <p>Premium Cereals & Pulses Exported Worldwide</p>
        <a href="#contact" class="btn">Get in Touch</a>
    </div>
</section>

<section id="about" data-aos="fade-right">
    <h2>About Us</h2>
    <p>
        At Nuvora Ventures Pvt. Ltd., we specialize in exporting and importing premium quality cereals and pulses across the globe. 
        Our mission is to build strong, transparent trade relationships while ensuring product excellence and timely delivery.
    </p>
</section>

<section id="products" data-aos="fade-up">
    <h2>Our Products</h2>
    <div class="products">
        <div class="card" data-aos="zoom-in">
            <img src="https://images.unsplash.com/photo-1600180758895-9ee3d8a8a3db" alt="Cereals">
            <h3>Cereals</h3>
            <p>High-quality wheat, rice, and corn sourced from trusted farms.</p>
        </div>
        <div class="card" data-aos="zoom-in" data-aos-delay="100">
            <img src="https://images.unsplash.com/photo-1600195077074-d9b5c5935d55" alt="Pulses">
            <h3>Pulses</h3>
            <p>Premium lentils, chickpeas, and beans for global distribution.</p>
        </div>
        <div class="card" data-aos="zoom-in" data-aos-delay="200">
            <img src="https://images.unsplash.com/photo-1600180758895-9ee3d8a8a3db" alt="Custom Orders">
            <h3>Custom Orders</h3>
            <p>Tailored sourcing solutions to meet your specific needs.</p>
        </div>
    </div>
</section>

<section id="services" data-aos="fade-left">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">
            <h3>Export</h3>
            <p>Reliable and efficient export services to markets worldwide.</p>
        </div>
        <div class="card">
            <h3>Import</h3>
            <p>Connecting global suppliers to local markets with care.</p>
        </div>
        <div class="card">
            <h3>Logistics</h3>
            <p>End-to-end logistics solutions for smooth delivery.</p>
        </div>
    </div>
</section>

<section id="map" class="world-map" data-aos="fade-up">
    <h2>Global Presence</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/80/World_map_-_low_resolution.svg/2000px-World_map_-_low_resolution.svg.png" alt="World Map">
    <p>We proudly serve clients in over 25 countries worldwide.</p>
</section>

<section id="contact" data-aos="fade-up">
    <h2>Contact Us</h2>
    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" rows="5" required></textarea>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Nuvora Ventures Pvt. Ltd. All Rights Reserved.</p>
</footer>

<!-- AOS Animation Script -->
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  AOS.init({
    duration: 1000,
    once: true
  });
</script>

</body>
</html>
