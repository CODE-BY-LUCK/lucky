!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Planner.in</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }


        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .container {
            width: 100%;
            max-width: 100%;
            margin: 0;
            display: flex;
            padding: 0;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            /* border: 2px solid #0f0f0f; */
        }

        header {
            background: #333;
            color: white;
            padding: 10px;    
        }

        header .navbar a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
        }

        header .cta-button {
            background: gold;
            color: black;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
        }

        .logo {
            align-items: center;
            margin: 0;
            padding: 0;
        }

        .container-heading {
            font-size: 2rem;
            color: #000000;
            text-align: center;
        }

        .container-para {
            font-size: 1.5rem;
            color: #000000;
        }

        .hero {
            background: url('hero-bg.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 5rem 1rem;
        }

        .hero .cta-button {
            background: #ffd700;
            color: #000000;
            padding: 0.8rem 1.5rem;
            font-size: 1.2rem;
        }

        .services {
            text-align: center;
            padding: 3rem 1rem;
            background: #f9f9f9;
            display: flex;
            flex-direction: row;
            justify-content: center;
            margin: 0;
        }

        .service-cards {
            display: flex;
            justify-content: space-around;
            gap: 1rem;
            margin-top: 2rem;
            /* border: 2px solid #ffd700; */
        }

        .card {
            display: flex;
            flex-direction: column;
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 1rem;
            text-align: center;
            width: 100%;
            border: 2px solid #000000;
        }

        .card img {
            width: 100%;
            /* Adjust the width as needed */
            height: fit-content;
            /* Maintain aspect ratio */
            margin: 0;
            /* Center the image */
        }

        .service-cards .card img {
            width: 100%;
            /* Adjust the width as needed */
            height: fit-content;
            /* Maintain aspect ratio */
            margin: 0;
            /* Center the image */
        }

        .portfolio-grid {
            display: flex;
            flex-wrap: wrap;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-top: 2rem;
        }

        .portfolio-grid-img {
            width: 100px;
            height: 100%;
            display: flex;
            flex-wrap: nowrap;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            text-align: center;
            margin: 25px;
        }

        .plan-your-event {
            border: 2px solid #000000;
            background: #f9f9f9;
            width: 0 auto;
            background-image: url('event-background.jpg ');
            background-size: cover;
            padding: 50px 0;
            color: white;
        }

        .plan-your-event h2 {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 5px;
        }

        .plan-your-event p {
            text-align: center;
            font-size: 1.2em;
            margin-bottom: 10px;
        }

        .event-form {
            max-width: 1200px;
            width: 100%;
            margin: 0 auto;
            background: rgba(16, 14, 14, 0.7);
            border: 2px solid #000000;
            padding: 20px;
            border-radius: 10px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
        }

        .form-group input,
        .form-group select,
        .form-group textarea {
            width: 100%;
            padding: 10px;
            border: none;
            border-radius: 5px;
        }

        .cta {
            text-align: center;
            margin-top: 30px;
        }

        .cta-button {
            background-color: #ff4081;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .cta-button:hover {
            background-color: #e91e63;
        }

        .contact {
            background: #f4f4f4;
            text-align: center;
            padding: 3rem 1rem;
            border: 2px solid #000000;
        }

        .contact form input,
        .contact form textarea {
            width: 100%;
            padding: 0.5rem;
            margin-bottom: 1rem;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }

        .social-icons a {
            color: gold;
            margin: 0 1rem;
            text-decoration: none;
        }
    </style>
</head>

<body>
    <!-- Header -->
    <header class="header">
        <h1 class="logo">
            <h
        </h1>
        <div class="container">
            <nav class="navbar">
                <a href="#home">Home</a>
                <a href="#services">Services</a>
                <a href="#portfolio">Portfolio</a>
                <a href="#contact">Contact</a>
                <button class="cta-button">Get Started</button>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="hero">
        <div class="container">
            <h2 class="container-heading">Turning Dreams Into Reality</h2><br>
            <p class="container-para">We make every moment magical. Let us plan your perfect event!</p><br><br>
            <a href="#plan-your-event">
                <button class="cta-button">Plan Your Event</button>
            </a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <h2 class="container-heading">Our Services</h2>
            <div class="service-cards">
                <div class="card">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTh4_nHHOYG1TInaqr0sdtJiYoElz4X1WRAQQ&s"
                        alt="Weddings">
                    <h3>Weddings</h3>
                    <p>Make your special day unforgettable.</p>
                </div>
                <div class="card">
                    <img src="https://m.media-amazon.com/images/I/71iuSVGKS2L.jpg" alt="Parties">
                    <h3>Parties</h3>
                    <p>Celebrate with style and fun.</p>
                </div>
                <div class="card">
                    <img src="https://i.pinimg.com/originals/c7/ea/0a/c7ea0a47d2675c42b4851f37a3fa817e.jpg"
                        alt="Corporate Events">
                    <h3>Corporate Events</h3>
                    <p>Professional events, perfectly planned.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section
    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2 class="container-heading">Our Portfolio</h2>
            <div class="portfolio-grid">
                <a href="" class="portfolio-grid-img">
                    <img src="" alt="Event 1">
                </a>
                <a href="" class="portfolio-grid-img">
                    <img src="" alt="Event 2">
                </a>
                <a href="" class="portfolio-grid-img">
                    <img src="" alt="Event 3">
                </a>
            </div>
    </section> -->

    <!-- Plan Your Event Section -->
    <section id="plan-your-event" class="plan-your-event">
        <div class="container">
            <h2 class="container-heading">Plan Your Event</h2>
            <p class="container-para">Tell us about your event, and well take care of the rest. Fill out the form below,
                and our team will get
                in touch with you to create a memorable experience.</p>

            <!-- Event Planning Form -->
            <form action="#" method="post" class="event-form">
                <div class="form-group">
                    <label for="event-type">Event Type</label>
                    <select id="event-type" name="event-type" required>
                        <option value="wedding">Wedding</option>
                        <option value="party">Party</option>
                        <option value="corporate">Corporate Event</option>
                        <option value="Birthday">Birthday</option>
                        <option value="other">Other</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="event-date">Event Date</label>
                    <input type="date" id="event-date" name="event-date" required>
                </div>
                <div class="form-group">
                    <label for="number-of-guests">Number of Guests</label>
                    <input type="number" id="number-of-guests" name="number-of-guests" required>
                </div>
                <div class="form-group">
                    <label for="event-location">Event Location</label>
                    <input type="text" id="event-location" name="event-location" required>
                </div>
                <div class="form-group">
                    <label for="additional-details">Additional Details</label>
                    <textarea id="additional-details" name="additional-details" rows="4"></textarea>
                </div>
                <div class="form-group">
                    <label for="name">Your Name</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Your Email</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" name="phone">
                </div>
                <button type="submit" class="cta-button">Submit Event Details</button>
            </form>

        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="container-heading">Contact Us</h2>
            <form action="#" method="post">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Your Message" required></textarea>
                <button type="submit" class="cta-button">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>© 2024 Event Planner. All rights reserved.</p><br>
            <div class="social-icons">
                <a href="https://www.facebook.com/share/1B2fcFKKPe/" target="_blank">Facebook</a>
                <a href="https://www.instagram.com/mr_luck_09/?__pwa=1" target="_blank">Instagram</a>
                <a href="https://www.linkedin.com/in/lucku-chaveriya-130192332/" target="_blank">Linked-In</a>
            </div>
        </div>
    </footer>
    <script>
        // Import required modules
        const express = require('express');
        const path = require('path');
        const bodyParser = require('body-parser');

        // Initialize Express app
        const app = express();
        const PORT = 3000;

        // Middleware to parse form data
        app.use(bodyParser.urlencoded({ extended: true }));
        app.use(express.static(path.join(__dirname, 'public'))); // Serve static files (CSS, images, etc.)

        // Serve the HTML file
        app.get('/', (req, res) => {
            res.sendFile(path.join(__dirname, 'index.html'));
        });

        // Handle form submission
        app.post('/contact', (req, res) => {
            const { name, email, message } = req.body;

            // Log the form data (you can replace this with database storage or email sending logic)
            console.log('Form Submission Received:');
            console.log(`Name: ${name}`);
            console.log(`Email: ${email}`);
            console.log(`Message: ${message}`);

            // Send a response back to the client
            res.send('Thank you for contacting us! We will get back to you soon.');
        });

        // Start the server
        app.listen(PORT, () => {
            console.log(`Server is running on http://localhost:${PORT}`);
        });
    </script>
</body>

</html>
</body>

</html>
