<html></html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Car Dealership</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f4f4f4; }
    header { background: #333; color: white; text-align: center; padding: 20px; }
    nav { background: #444; overflow: hidden; }
    nav a { color: white; padding: 14px 20px; text-decoration: none; float: left; }
    nav a:hover { background: #ddd; color: black; }
    section { padding: 20px; margin: 20px; background: white; border-radius: 8px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); }
    .car-list { display: flex; justify-content: space-around; flex-wrap: wrap; }
    .car { width: 30%; margin: 10px 0; text-align: center; background: #fff; border-radius: 8px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); }
    .car img { width: 100%; border-radius: 8px 8px 0 0; }
    footer { text-align: center; padding: 10px; background: #333; color: white; }
  </style>
</head>
<body>

<header>
  <h1>Welcome to Our Car Dealership</h1>
  <p>Your trusted partner in finding the perfect vehicle</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#inventory">Inventory</a>
  <a href="#services">Services</a>
  <a href="#contact">Contact</a>
</nav>

<section id="home">
  <h2>Featured Cars</h2>
  <div class="car-list">
    <div class="car">
      <img src="https://imgd.aeplcdn.com/370x208/n/cw/ec/203832/m340i-exterior-right-front-three-quarter.jpeg?isig=0&wm=1&q=80" alt="Car 1">
      <h3>BMW 340i</h3>
      <p>Price: ₹80,00,000</p>
    </div>
    <div class="car">
      <img src="https://tse4.mm.bing.net/th/id/OIP.eQ9_Hc_VPaZd2n3NXwT4gQHaEL?rs=1&pid=ImgDetMain&o=7&rm=3 " alt="Car 2">
      <h3>Poarsha 911 GT</h3>
      <p>Price: ₹1,200,000</p>
    </div>
    <div class="car">
      <img src="" alt="Land Cruser 300">
      <h3>Car Model 3</h3>
      <p>Price: ₹2,00,00,000</p>
    </div>
  </div>
</section>

<footer>
  <p>&copy; 2025 Car Dealership. All rights reserved.</p>
</footer>

</body>
</html>
