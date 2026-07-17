<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TechStore - Laptops & Accessories</title>

    <link rel="stylesheet" href="style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

</head>
<body>

<header>

    <div class="logo">
        TechStore
    </div>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#store">Store Info</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

</header>

<section class="hero" id="home">

    <div class="hero-text">

        <h1>Find Your Perfect Laptop</h1>

        <p>
            Discover powerful laptops and premium accessories at affordable prices.
        </p>

        <a href="#products" class="btn">
            Shop Now
        </a>

    </div>

</section>

<section id="products">

    <h2>Featured Products</h2>

    <div class="products">

        <div class="card">

            <img src="images/laptop1.jpg" alt="Laptop">

            <h3>Gaming Laptop</h3>

            <p>Intel Core i7 • RTX Graphics • 16GB RAM</p>

            <h4>$1299</h4>

            <button>View Details</button>

        </div>

        <div class="card">

            <img src="images/laptop2.jpg" alt="Laptop">

            <h3>Business Laptop</h3>

            <p>Intel Core i5 • 512GB SSD • 8GB RAM</p>

            <h4>$899</h4>

            <button>View Details</button>

        </div>

        <div class="card">

            <img src="images/mouse.jpg" alt="Mouse">

            <h3>Wireless Mouse</h3>

            <p>Ergonomic Design</p>

            <h4>$29</h4>

            <button>View Details</button>

        </div>

        <div class="card">

            <img src="images/keyboard.jpg" alt="Keyboard">

            <h3>Mechanical Keyboard</h3>

            <p>RGB Backlit Keys</p>

            <h4>$79</h4>

            <button>View Details</button>

        </div>

    </div>

</section>

<section id="about">

    <h2>About Us</h2>

    <p>

        TechStore is your trusted destination for high-quality laptops,
        gaming computers, business notebooks, and premium accessories.

        We focus on excellent customer service, affordable prices,
        and genuine products.

    </p>

</section>

<section id="store">

    <h2>Store Information</h2>

    <div class="info">

        <p><strong>Address:</strong> 123 Main Street</p>

        <p><strong>City:</strong> Your City</p>

        <p><strong>Phone:</strong> +213 555 123 456</p>

        <p><strong>Email:</strong> info@techstore.com</p>

        <p><strong>Opening Hours:</strong></p>

        <ul>
            <li>Monday - Friday: 9:00 AM - 6:00 PM</li>
            <li>Saturday: 10:00 AM - 4:00 PM</li>
            <li>Sunday: Closed</li>
        </ul>

    </div>

</section>

<section id="contact">

    <h2>Contact Us</h2>

    <form>

        <input
            type="text"
            placeholder="Your Name"
            required
        >

        <input
            type="email"
            placeholder="Your Email"
            required
        >

        <textarea
            placeholder="Your Message"
            rows="6"
            required
        ></textarea>

        <button type="submit">
            Send Message
        </button>

    </form>

</section>

<footer>

    <p>

        © 2026 TechStore.
        All Rights Reserved.

    </p>

</footer>

<script src="script.js"></script>

</body>
</html>
