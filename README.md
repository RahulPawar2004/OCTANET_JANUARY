# OCTANET_JANUARY
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Winter Vacation Plan</title>
    <link rel="stylesheet" href="style.css">
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        /* Navbar */
        .navbar {
            background-color: #2a9d8f;
            padding: 10px 20px;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .navbar ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .navbar ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .navbar ul li a:hover {
            color: #e76f51;
        }

        /* Hero Section */
        .hero {
            background: url('winter.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        .hero h1 {
            font-size: 3rem;
        }

        .hero p {
            font-size: 1.2rem;
        }

        .btn {
            background-color: #e76f51;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn:hover {
            background-color: #f4a261;
        }

        /* Plans Section */
        .plans {
            padding: 50px 20px;
            background: #f8f9fa;
        }

        .plans h2 {
            text-align: center;
            margin-bottom: 40px;
        }

        .plan {
            background: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .plan img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .plan h3 {
            margin-bottom: 10px;
        }

        .plan p {
            text-align: center;
        }

        /* Testimonial Section */
        .testimonials {
            background: #2a9d8f;
            color: white;
            padding: 50px 20px;
            text-align: center;
        }

        .testimonial {
            max-width: 700px;
            margin: 0 auto;
            font-style: italic;
        }

        .testimonial-author {
            margin-top: 10px;
            font-weight: bold;
        }

        /* Contact Section */
        .contact {
            padding: 50px 20px;
            background: #2a9d8f;
            color: white;
        }

        .contact form {
            max-width: 500px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .contact input,
        .contact textarea {
            padding: 10px;
            border: none;
            border-radius: 5px;
        }

        .contact button {
            background-color: #e76f51;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .contact button:hover {
            background-color: #f4a261;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background: #264653;
            color: white;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <header>
        <nav class="navbar">
            <ul>
                <li><a href="#plans">Our Plans</a></li>
                <li><a href="#mountain-adventure">Mountain Adventure</a></li>
                <li><a href="#winter-beach">Winter Beach</a></li>
                <li><a href="#city-light">City Lights Tour</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <header class="hero">
        <h1>Winter Vacation Plan</h1>
        <p>Escape the cold and explore beautiful winter destinations!</p>
        <a href="#plans" class="btn">Explore Now</a>
    </header>

    <!-- Plans Section -->
    <section id="plans" class="plans">
        <h2>Our Winter Vacation Plans</h2>
        <div class="plan" id="mountain-adventure">
            <img src="mountain.jpg" alt="Mountain Adventure">
            <h3>Mountain Adventure</h3>
            <p>Enjoy skiing, snowboarding, and cozy cabins in the mountains.</p>
        </div>
        <div class="plan" id="winter-beach">
            <img src="beach.jpg" alt="Winter Beach">
            <h3>Winter Beach</h3>
            <p>Relax by the beach and experience the serenity of the winter seaside.</p>
        </div>
        <div class="plan" id="city-light">
            <img src="city.jpg" alt="City Lights Tour">
            <h3>City Lights Tour</h3>
            <p>Visit winter festivals and explore vibrant city lights and markets.</p>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="testimonials">
        <h2>What Our Customers Say</h2>
        <div class="testimonial">
            <p>"Our winter vacation was an unforgettable experience! The mountain adventure was breathtaking, and the cozy cabins were perfect." - Jane Doe</p>
            <div class="testimonial-author">Rahul Pawar</div>
        </div>
        <div class="testimonial">
            <p>"I had the best time at the winter beach. It was so peaceful and beautiful. I can't wait to go back next year!" - John Smith</p>
            <div class="testimonial-author">Rohan</div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Your Name</label>
            <input type="text" id="name" placeholder="Your Name" required>

            <label for="email">Your Email</label>
            <input type="email" id="email" placeholder="Your Email" required>

            <label for="message">Your Message</label>
            <textarea id="message" placeholder="Your Message" required></textarea>

            <button type="submit" class="btn">Submit</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Winter Vacation Plans</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Winter Vacation Plan</title>
    <link rel="stylesheet" href="style.css">
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        /* Navbar */
        .navbar {
            background-color: #2a9d8f;
            padding: 10px 20px;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .navbar ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .navbar ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .navbar ul li a:hover {
            color: #e76f51;
        }

        /* Hero Section */
        .hero {
            background: url('winter.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        .hero h1 {
            font-size: 3rem;
        }

        .hero p {
            font-size: 1.2rem;
        }

        .btn {
            background-color: #e76f51;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn:hover {
            background-color: #f4a261;
        }

        /* Plans Section */
        .plans {
            padding: 50px 20px;
            background: #f8f9fa;
        }

        .plans h2 {
            text-align: center;
            margin-bottom: 40px;
        }

        .plan {
            background: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .plan img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }

        .plan h3 {
            margin-bottom: 10px;
        }

        .plan p {
            text-align: center;
        }

        /* Testimonial Section */
        .testimonials {
            background: #2a9d8f;
            color: white;
            padding: 50px 20px;
            text-align: center;
        }

        .testimonial {
            max-width: 700px;
            margin: 0 auto;
            font-style: italic;
        }

        .testimonial-author {
            margin-top: 10px;
            font-weight: bold;
        }

        /* Contact Section */
        .contact {
            padding: 50px 20px;
            background: #2a9d8f;
            color: white;
        }

        .contact form {
            max-width: 500px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .contact input,
        .contact textarea {
            padding: 10px;
            border: none;
            border-radius: 5px;
        }

        .contact button {
            background-color: #e76f51;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .contact button:hover {
            background-color: #f4a261;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background: #264653;
            color: white;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <header>
        <nav class="navbar">
            <ul>
                <li><a href="#plans">Our Plans</a></li>
                <li><a href="#mountain-adventure">Mountain Adventure</a></li>
                <li><a href="#winter-beach">Winter Beach</a></li>
                <li><a href="#city-light">City Lights Tour</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <header class="hero">
        <h1>Winter Vacation Plan</h1>
        <p>Escape the cold and explore beautiful winter destinations!</p>
        <a href="#plans" class="btn">Explore Now</a>
    </header>

    <!-- Plans Section -->
    <section id="plans" class="plans">
        <h2>Our Winter Vacation Plans</h2>
        <div class="plan" id="mountain-adventure">
            <img src="mountain.jpg" alt="Mountain Adventure">
            <h3>Mountain Adventure</h3>
            <p>Enjoy skiing, snowboarding, and cozy cabins in the mountains.</p>
        </div>
        <div class="plan" id="winter-beach">
            <img src="beach.jpg" alt="Winter Beach">
            <h3>Winter Beach</h3>
            <p>Relax by the beach and experience the serenity of the winter seaside.</p>
        </div>
        <div class="plan" id="city-light">
            <img src="city.jpg" alt="City Lights Tour">
            <h3>City Lights Tour</h3>
            <p>Visit winter festivals and explore vibrant city lights and markets.</p>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="testimonials">
        <h2>What Our Customers Say</h2>
        <div class="testimonial">
            <p>"Our winter vacation was an unforgettable experience! The mountain adventure was breathtaking, and the cozy cabins were perfect." - Jane Doe</p>
            <div class="testimonial-author">Rahul Pawar</div>
        </div>
        <div class="testimonial">
            <p>"I had the best time at the winter beach. It was so peaceful and beautiful. I can't wait to go back next year!" - John Smith</p>
            <div class="testimonial-author">Rohan</div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Your Name</label>
            <input type="text" id="name" placeholder="Your Name" required>

            <label for="email">Your Email</label>
            <input type="email" id="email" placeholder="Your Email" required>

            <label for="message">Your Message</label>
            <textarea id="message" placeholder="Your Message" required></textarea>

            <button type="submit" class="btn">Submit</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Winter Vacation Plans</p>
    </footer>
</body>
</html>
