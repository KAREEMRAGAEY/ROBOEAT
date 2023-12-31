<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Restaurant</title>

    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
        }

        header, nav, section, footer {
            padding: 20px;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        nav li {
            display: inline-block;
            margin-right: 20px;
        }

        nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        section {
            margin: 50px 0;
            background-color: #f9f9f9;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 8px;
        }

        footer {
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Restaurant</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#contact">Contact Us</a></li>
        </ul>
    </nav>

    <section id="home">
        <h2>Home Section</h2>
        <!-- Add content for the home section -->
    </section>

    <section id="about">
        <h2>About Us Section</h2>
        <!-- Add content for the about section -->
    </section>

    <section id="contact">
        <h2>Contact Us Section</h2>
        <!-- Add content for the contact section -->
    </section>

    <footer>
        <p>&copy; 2023 Your Restaurant. All rights reserved.</p>
    </footer>

    <script>
        document.addEventListener("DOMContentLoaded", function() {
            // Smooth scroll to anchor links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();

                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            });
        });
    </script>
</body>
</html>