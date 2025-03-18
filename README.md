# Ingredient Alchemy - The Ultimate Recipe Hub
Ingredient Alchemy is a beautifully designed, user-friendly platform that brings food lovers and home chefs together to explore, create, and organize their culinary adventures. Whether you're a seasoned cook or just getting started, this website provides an intuitive and engaging experience to elevate your cooking game.

Key Features
🌟 Vast Recipe Collection – Discover thousands of mouthwatering recipes across various cuisines, diets, and difficulty levels. Whether you’re craving a quick snack or a gourmet meal, we’ve got something for everyone!

📅 Meal Organizer – Plan your weekly meals effortlessly with the built-in Meal Organizer, ensuring balanced nutrition and hassle-free cooking schedules.

❤️ Recipe Favorites – Save and curate your personal cookbook by starring your favorite recipes for easy access anytime.

📌 Menu Minder – Get curated meal suggestions based on occasions, seasons, or dietary needs, making meal planning stress-free.

📝 Dish Diaries – Maintain a personalized collection of recipes, add custom notes, and tweak ingredients to craft your perfect dish.

🔎 Easy Search & Navigation – Quickly find what you need with an advanced search feature, filtering recipes by ingredients, cooking time, or dietary preferences.

🎨 Aesthetic & Responsive Design – The website features a modern, visually appealing interface with smooth animations and a clean, distraction-free layout. The gradient background enhances the browsing experience, making cooking feel like an adventure!

💡 User-Friendly Interface – Simple navigation, mobile responsiveness, and an interactive design ensure a seamless experience across all devices.












<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ingredient Alchemy</title>

    <!-- Bootstrap 4 CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

    <style>
        body {
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            font-family: Arial, sans-serif;
        }
        .nav-bar{
            position: relative;
        }
        .hero-text {
            text-align: center;
            margin-top: 50px;
            color: #333;
        }
        .hero-text h2 {
            font-size: 2.5rem;
            font-weight: bold;
        }
        .hero-text p {
            font-size: 1.2rem;
            color: #444;
        }
        .browse-btn {
            margin-top: 20px;
            font-size: 1.2rem;
            padding: 10px 30px;
            background: linear-gradient( #ff758c, #ff7eb3 );
            color: white;
            border: none;
            border-radius: 30px;
            cursor: pointer;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 30px 0;
            text-align: center;
        }
        footer a {
            color: #dcdcde;
            margin: 0 15px;
        }
        footer a:hover {
            font-size: large;
            color: #ffffff;
        }
        .footer-links {
            margin-bottom: 20px;
        }
        .footer-links p {
            margin-bottom: 5px;
            font-size: 1.1rem;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <a class="navbar-brand" href="#">INGREDIENT ALCHEMY</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link" href="project.html">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="meal planner.html">Meal Organizer</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="starred.html">Recipe Favourites</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="ocassion.html">Menu Minder</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="my recipes.html">Dish Diaries</a>
                </li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero-text">
        <h2>Ready to discover your next favourite dish?</h2>
        <p>Browse thousands of recipes, experiment with new ingredients, and start cooking!</p>
        <button class="browse-btn" onclick="window.location.href='seach.html'">Browse Recipes</button>
    </div>
<br>
    <!-- Footer -->
    <footer>
        <div class="footer-links">
            <p><a href="about.html">About Us</a></p>
            <p><a href="privacy.html">Privacy Policy</a></p>
            <p><a href="feedback.html">Feedback</a></p>
            <p><a href="contact.html">Contact Us</a></p>
        </div>
        <p>&copy; 2024 Ingredient Alchemy. All rights reserved.</p>
    </footer>

    <!-- Bootstrap 4 JS and dependencies -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
