# <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Nation Barbers</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Oswald', sans-serif;
            background-color: #111;
            color: white;
        }

        header {
            text-align: center;
            padding: 50px 20px;
            background: linear-gradient(to right, red, white, blue);
            -webkit-background-clip: text;
            color: transparent;
            font-size: 3rem;
            font-weight: 600;
        }

        nav {
            text-align: center;
            padding: 10px 0;
        }

        nav a {
            color: white;
            margin: 0 20px;
            text-decoration: none;
            font-size: 20px;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: 0.3s ease-in-out;
        }

        nav a:hover {
            color: red;
        }

        .barber-pole {
            text-align: center;
            margin: 50px 0;
        }

        .pole {
            width: 120px;
            height: 300px;
            background: repeating-linear-gradient(
                45deg,
                red,
                red 20px,
                white 20px,
                white 40px,
                blue 40px,
                blue 60px
            );
            animation: spin 5s linear infinite;
            border-radius: 10px;
            box-shadow: 0 0 20px red;
        }

        @keyframes spin {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }

        .facts {
            font-style: italic;
            font-size: 22px;
            margin-top: 20px;
            animation: fadeIn 3s infinite alternate;
        }

        @keyframes fadeIn {
            from {
                opacity: 0.3;
            }
            to {
                opacity: 1;
            }
        }

        section {
            padding: 100px 20px;
            text-align: center;
        }

        .about {
            background-color: #222;
            box-shadow: 0 0 30px rgba(255, 255, 255, 0.2);
            border-radius: 20px;
            margin: 20px auto;
            max-width: 900px;
        }

        .contact {
            background-color: #111;
            padding: 50px 20px;
        }

        .contact a {
            color: red;
            text-decoration: none;
            font-size: 20px;
            transition: 0.3s ease-in-out;
        }

        .contact a:hover {
            color: white;
        }

        footer {
            padding: 20px;
            background-color: #000;
            text-align: center;
            font-size: 14px;
            color: gray;
        }

        .social-icons a {
            color: white;
            margin: 0 15px;
            font-size: 24px;
            text-decoration: none;
        }

        .social-icons a:hover {
            color: red;
        }
    </style>
</head>

<body>

    <header>
        The Nation Barbers
    </header>

    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="barber-pole">
        <div class="pole"></div>
        <p class="facts">"Barbering is one of the world's oldest professions dating back to ancient Egypt!"</p>
    </div>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>We are **The Nation Barbers**, a group of young, dedicated barbers providing **legendary cuts & experiences for ALL walks of human life**. Our craft is deeper than just a fade – we’re about **culture, style, and community**.</p>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:manikutzllc@gmail.com">manikutzllc@gmail.com</a></p>
        <p>Phone: <a href="tel:2175600330">217-560-0330</a></p>

        <div class="social-icons">
            <a href="#"><i class="fa fa-instagram"></i></a>
            <a href="#"><i class="fa fa-facebook"></i></a>
            <a href="#"><i class="fa fa-twitter"></i></a>
        </div>
    </section>

    <footer>
        &copy; 2025 The Nation Barbers | All Rights Reserved
    </footer>

</body>

</html>