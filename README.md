<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Prime Motors - Car Dealership</title>

<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #f5f5f5;
    }

    /* Header */
    header {
        background: #1e1e2f;
        color: white;
        padding: 20px;
        text-align: center;
        font-size: 30px;
        letter-spacing: 2px;
    }

    /* Navigation */
    nav {
        background: #10101a;
        padding: 10px 0;
        text-align: center;
    }
    nav a {
        color: white;
        margin: 0 18px;
        text-decoration: none;
        font-size: 18px;
    }
    nav a:hover {
        color: #ffae00;
    }

    /* Banner */
    .banner {
        background: url('https://images.unsplash.com/photo-1503376780353-7e6692767b70') no-repeat center/cover;
        height: 350px;
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        font-size: 40px;
        text-shadow: 2px 2px 12px black;
        font-weight: bold;
    }

    /* Car Section */
    .container {
        width: 90%;
        margin: auto;
        padding: 40px 0;
    }

    .container h2 {
        text-align: center;
        font-size: 34px;
        margin-bottom: 20px;
        color: #1e1e2f;
    }

    .cars {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 25px;
    }

    .car-card {
        background: white;
        border-radius: 10px;
        box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        overflow: hidden;
        transition: 0.3s;
    }

    .car-card:hover {
        transform: scale(1.04);
    }

    .car-card img {
        width: 100%;
        height: 180px;
        object-fit: cover;
    }

    .details {
        padding: 15px;
    }

    .details h3 {
        margin: 0;
        font-size: 22px;
        color: #1e1e2f;
    }

    .price {
        color: #e67e22;
        font-size: 20px;
        font-weight: bold;
        margin-top: 10px;
    }

    .btn {
        display: inline-block;
        padding: 10px 18px;
        margin-top: 15px;
        background: #1e1e2f;
        color: white;
        text-decoration: none;
        border-radius: 5px;
        font-size: 16px;
    }

    .btn:hover {
        background: #e67e22;
    }

    /* Footer */
    footer {
        background: #1e1e2f;
        color: white;
        text-align: center;
        padding: 20px;
        margin-top: 30px;
    }

</style>
</head>
<body>

<header>Prime Motors Car Dealership</header>

<nav>
    <a href="#">Home</a>
    <a href="#">New Cars</a>
    <a href="#">Used Cars</a>
    <a href="#">Contact</a>
</nav>

<div class="banner">
    Find Your Perfect Car Today
</div>

<div class="container">
    <h2>Featured Cars</h2>
    <div class="cars">

        <!-- Car 1 -->
        <div class="car-card">
            <img src="https://images.unsplash.com/photo-1511919884226-fd3cad34687c" alt="Audi A6">
            <div class="details">
                <h3>2024 Audi A6</h3>
                <p>Luxury Sedan • Automatic • Turbocharged</p>
                <p class="price">$55,900</p>
                <a class="btn" href="#">View Details</a>
            </div>
        </div>

        <!-- Car 2 -->
        <div class="car-card">
            <img src="https://images.unsplash.com/photo-1503736334956-4c8f8e92946d" alt="BMW M4">
            <div class="details">
                <h3>2024 BMW M4</h3>
                <p>High-Performance Coupe • Sport Mode</p>
                <p class="price">$78,000</p>
                <a class="btn" href="#">View Details</a>
            </div>
        </div>

        <!-- Car 3 -->
        <div class="car-card">
            <img src="https://images.unsplash.com/photo-1502877338535-766e1452684a" alt="Mercedes SUV">
            <div class="details">
                <h3>2024 Mercedes G-Class</h3>
                <p>Luxury SUV • 4x4 • Premium Interior</p>
                <p class="price">$130,000</p>
                <a class="btn" href="#">View Details</a>
            </div>
        </div>

        <!-- Car 4 -->
        <div class="car-card">
            <img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70" alt="Sports Car">
            <div class="details">
                <h3>2024 Ferrari F8</h3>
                <p>Supercar • Twin-Turbo • V8 Engine</p>
                <p class="price">$280,000</p>
                <a class="btn" href="#">View Details</a>
            </div>
        </div>

    </div>
</div>

<footer>
    &copy; 2025 Prime Motors. All Rights Reserved.
</footer>

</body>
</html>

