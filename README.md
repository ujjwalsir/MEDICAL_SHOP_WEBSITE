# MEDICAL_SHOP_WEBSITE
INTERNSHIP TASK MINIWORLD

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Medical Shop Homepage</title>
</head>
<body>
    <header>
        <div class="logo">Medical Shop Logo</div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Products</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to Our Medical Shop</h1>
        <p>Your trusted source for high-quality medical products.</p>
        <a href="#" class="cta-button">Shop Now</a>
    </section>

    <section class="featured-products">
        <h2>Featured Products</h2>
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>High-quality medical equipment.</p>
            <a href="#" class="cta-button">Learn More</a>
        </div>
        <!-- Additional product items -->
    </section>

    <section class="special-offers">
        <h2>Special Offers</h2>
        <div class="offer">
            <h3>Limited-Time Discount</h3>
            <p>Save 20% on select medical supplies.</p>
            <a href="#" class="cta-button">Get Offer</a>
        </div>
        <!-- Additional special offers -->
    </section>

    <section class="testimonials">
        <h2>What Our Customers Say</h2>
        <div class="testimonial">
            <p>"The best medical shop I've ever used. Fast delivery and great prices!"</p>
            <p class="customer-name">- Jane Doe</p>
        </div>
        <!-- Additional testimonials -->
    </section>

    <section class="about-us">
        <h2>About Us</h2>
        <p>We are a leading medical shop committed to providing top-quality products to our customers. With over 10 years of experience...</p>
        <a href="#" class="cta-button">Learn More</a>
    </section>

    <section class="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or inquiries, please feel free to reach out to us. We're here to help!</p>
        <a href="mailto:info@medicalshop.com" class="cta-button">Contact Us</a>
    </section>

    <footer>
        <p>&copy; 2023 Medical Shop. All rights reserved.</p>
    </footer>
</body>
</html>

/* Reset some default styles */
body, h1, h2, h3, p, ul, li {
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
}

/* Header styles */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #f5f5f5;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
}

/* Hero section styles */
.hero {
    text-align: center;
    padding: 100px 0;
    background-image: url('hero-image.jpg');
    background-size: cover;
    color: #fff;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #3498db;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

/* Featured products section styles */
.featured-products {
    padding: 50px 0;
    text-align: center;
}

.product {
    margin: 20px;
}

.product img {
    max-width: 100%;
    height: auto;
}

/* Special offers section styles */
.special-offers {
    padding: 50px 0;
    text-align: center;
    background-color: #f9f9f9;
}

.offer {
    margin: 20px;
}

/* Testimonials section styles */
.testimonials {
    padding: 50px 0;
    text-align: center;
}

.testimonial {
    margin: 20px;
}

.customer-name {
    font-style: italic;
    color: #666;
}

/* About us section styles */
.about-us {
    padding: 50px 0;
    text-align: center;
}

/* Contact section styles */
.contact {
    padding: 50px 0;
    text-align: center;
    background-color: #f9f9f9;
}

/* Footer styles */
footer {
    text-align: center;
    padding: 20px 0;
    background-color: #333;
    color: #fff;
}

/* Other styles for additional sections, footer, etc. */


