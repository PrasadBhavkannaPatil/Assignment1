<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Startup</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <nav>
            <ul>
                <li><a href="#hero">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#team">Team</a></li>
                <li><a href="#achievements">Achievements</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <div class="container">
            <h1>Welcome to Our Tech Startup</h1>
            <p>Innovating the future, one step at a time.</p>
            <a href="#about" class="cta-button">Learn More</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>We are a tech startup focused on bringing innovative solutions to the market. Our vision is to revolutionize the tech industry with our groundbreaking products and services.</p>
        </div>
    </section>

    <!-- Vision Section -->
    <section id="vision">
        <div class="container">
            <h2>Our Vision</h2>
            <p>Our vision is to create a world where technology seamlessly integrates into everyday life, enhancing productivity and improving quality of life.</p>
        </div>
    </section>

    <!-- Team Section -->
    <section id="team">
        <div class="container">
            <h2>Meet the Team</h2>
            <div class="team-members">
                <div class="team-member">
                    <img src="team1.jpg" alt="Team Member 1">
                    <h3>John Doe</h3>
                    <p>CEO & Founder</p>
                </div>
                <div class="team-member">
                    <img src="team2.jpg" alt="Team Member 2">
                    <h3>Jane Smith</h3>
                    <p>CTO</p>
                </div>
                <div class="team-member">
                    <img src="team3.jpg" alt="Team Member 3">
                    <h3>Mike Johnson</h3>
                    <p>Lead Developer</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Achievements Section -->
    <section id="achievements">
        <div class="container">
            <h2>Achievements</h2>
            <ul>
                <li>Won the Best Startup Award 2024</li>
                <li>Featured in TechCrunch and Wired</li>
                <li>Over $10M in funding</li>
                <li>Developed a revolutionary AI product</li>
            </ul>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Submit</button>
            </form>
            <div id="map"></div>
        </div>
    </section>

    <script src="script.js"></script>
</body>
</html>
