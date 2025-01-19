<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tex Electronics</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 50px 20px;
            background: linear-gradient(to right, #4CAF50, #00ACC1);
            color: white;
        }
        .hero h1 {
            font-size: 3em;
        }
        .hero p {
            font-size: 1.2em;
            margin-top: 10px;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .product-card {
            background: white;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            text-align: center;
        }
        .product-card img {
            max-width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
            margin-bottom: 15px;
        }
        .product-card h3 {
            margin-bottom: 10px;
        }
        .product-card p {
            color: #777;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 20px;
            margin-top: 20px;
        }
        footer p {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Tex Electronics</h1>
        <p>Your one-stop shop for all electronics</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero" id="home">
        <h1>Innovative Electronics for a Smarter Tomorrow</h1>
        <p>Explore our latest gadgets and devices</p>
    </section>

    <section class="container" id="products">
        <h2>Our Products</h2>
        <div class="products">
            <!-- TV Products -->
            <div class="product-card">
                <img src="IMAGE_URL_1" alt="Ultra HD Smart TV">
                <h3>Ultra HD Smart TV</h3>
                <p>Experience crystal-clear visuals with 4K UHD technology.</p>
            </div>
            <div class="product-card">
                <img src="IMAGE_URL_2" alt="LED TV 32-inch">
                <h3>LED TV 32-inch</h3>
                <p>Perfect size and display quality for smaller spaces.</p>
            </div>
            <div class="product-card">
                <img src="IMAGE_URL_3" alt="Curved OLED TV">
                <h3>Curved OLED TV</h3>
                <p>Immersive viewing experience with curved design.</p>
            </div>

            <!-- TV Panels -->
            <div class="product-card">
                <img src="IMAGE_URL_4" alt="4K UHD TV Panel">
                <h3>4K UHD TV Panel</h3>
                <p>High-quality panel replacement for 4K televisions.</p>
            </div>
            <div class="product-card">
                <img src="IMAGE_URL_5" alt="LED TV Panel">
                <h3>LED TV Panel</h3>
                <p>Reliable LED panel for superior display quality.</p>
            </div>
            <div class="product-card">
                <img src="IMAGE_URL_6" alt="OLED TV Panel">
                <h3>OLED TV Panel</h3>
                <p>Advanced OLED panel for vibrant colors and deep blacks.</p>
            </div>
        </div>
    </section>

    <section class="container" id="about">
        <h2>About Us</h2>
        <p>Tex Electronics is committed to providing innovative and reliable electronic solutions to customers worldwide. With a focus on quality and customer satisfaction, we strive to bring cutting-edge technology to your doorstep.</p>
    </section>

    <section class="container" id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@texelectronics.com</p>
        <p>Phone: +123-456-7890</p>
        <p>Address: 123 Tech Avenue, Innovation City</p>
    </section>

    <footer>
        <p>&copy; 2025 Tex Electronics. All Rights Reserved.</p>
    </footer>
</body>
</html>
