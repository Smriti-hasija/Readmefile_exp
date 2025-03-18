Delicious Cake Bakery

It provides true information of our website .It makes the user aware about our services,our work and to get in touch with the team.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Sh_memorie_bakers</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #f9f9f9;
        }
        header {
            background-color: #ff6f61;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            font-size: 3rem;
            letter-spacing: 2px;
        }
        nav {
            background-color: #333;
            text-align: center;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 10px;
            font-size: 18px;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #6f44c4;
            border-radius: 5px;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1500x600/ff6f61/ffffff?text=Delicious+Cakes');
            background-size: cover;
            background-position: center;
            color: rgb(97, 87, 198);
            padding: 100px 0;
            text-align: center;
        }
        .hero h2 {
            font-size: 3rem;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .services, .gallery {
            padding: 40px 20px;
            text-align: center;
        }
        .services h2, .gallery h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        .services .service-box {
            display: inline-block;
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 30%;
            margin: 20px;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
        }
        .services .service-box h3 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }
        .services .service-box p {
            font-size: 1rem;
        }
        .gallery img {
            width: 30%;
            margin: 15px;
            border-radius: 8px;
            transition: transform 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.1);
        }
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        footer p {
            font-size: 1rem;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1> Memorie Bakers</h1>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#">Home</a>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <h2>Freshly Baked Cakes, Just for You!</h2>
        <p>Delight in the finest, most delicious cakes baked with love and the finest ingredients. Perfect for any occasion!</p>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <h2>Our Services</h2>
        <div class="service-box">
            <h3>Custom Cakes</h3>
            <p>We create personalized cakes for birthdays, weddings, and any special occasion. Choose your design and flavor!</p>
        </div>
        <div class="service-box">
            <h3>Specialty Cakes</h3>
            <p>Indulge in our range of specialty cakes, from chocolate fudge to fruit cakes. Every bite is a treat!</p>
        </div>
        <div class="service-box">
            <h3>Cupcakes & Treats</h3>
            <p>Delicious cupcakes, cookies, and other treats to brighten your day. Perfect for parties or a sweet snack!</p>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery" id="gallery">
        <h2>Our Cake Gallery</h2>
        <div>
            <img src="WhatsApp Image 2025-03-18 at 09.52.30 (1).jpeg" alt="Cake 1">
            <img src="WhatsApp Image 2025-03-18 at 09.52.30.jpeg" alt="Cake 2">
            <img src="WhatsApp Image 2025-03-18 at 09.52.31.jpeg" alt="Cake 3">
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Delicious Cake Bakery. All Rights Reserved.</p>
    </footer>

</body>
</html>
