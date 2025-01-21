<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Welcome to the Water Park - Enjoy fun rides, pools, and unforgettable experiences!">
    <meta name="keywords" content="water park, fun, attractions, rides, swimming">
    <title>Water Park - Fun & Adventure</title>
    <link rel="stylesheet" href="index.css">
</head>

<body>

    <!-- Navigation Bar -->
    <nav>
        <div class="logo">
            <a href="#">Water Park</a>
        </div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#attractions">Attractions</a></li>
            <li><a href="#tickets">Tickets</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to the Water Park!</h1>
            <p>Get ready for a splash of fun with thrilling rides and relaxing pools.</p>
            <a href="#tickets" class="btn">Book Tickets Now</a>
        </div>
    </section>

    <!-- Attractions Section -->
    <section id="attractions" class="attractions">
        <h2>Our Attractions</h2>
        <div class="attractions-container">
            <div class="attraction">
                <img src="images/slide1.jpg" alt="Water Slide">
                <h3>Water Slides</h3>
                <p>Experience the thrill of high-speed water slides.</p>
            </div>
            <div class="attraction">
                <img src="images/pool1.jpg" alt="Swimming Pool">
                <h3>Wave Pool</h3>
                <p>Relax and enjoy the waves in our giant wave pool.</p>
            </div>
            <div class="attraction">
                <img src="images/ride1.jpg" alt="Lazy River">
                <h3>Lazy River</h3>
                <p>Take a relaxing ride down the lazy river.</p>
            </div>
        </div>
    </section>

    <!-- Ticket Booking Section -->
    <section id="tickets" class="tickets">
        <h2>Ticket Pricing</h2>
        <div class="ticket-options">
            <div class="ticket">
                <h3>Adult Ticket</h3>
                <p>$30</p>
                <button class="btn">Book Now</button>
            </div>
            <div class="ticket">
                <h3>Child Ticket</h3>
                <p>$20</p>
                <button class="btn">Book Now</button>
            </div>
            <div class="ticket">
                <h3>Family Pass</h3>
                <p>$80</p>
                <button class="btn">Book Now</button>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <div class="gallery-container">
            <img src="images/pool2.jpg" alt="Pool">
            <img src="images/slide2.jpg" alt="Slide">
            <img src="images/ride2.jpg" alt="Ride">
            <img src="images/park.jpg" alt="Water Park">
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form action="submit_form.php" method="POST">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Your Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Water Park. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>

</html>
# seodemo
