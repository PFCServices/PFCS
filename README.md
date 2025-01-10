# PFCS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Consulting Firm</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #343a40;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 2rem;
            background-color: #e9ecef;
        }
        .hero .text {
            flex: 1;
            padding-right: 2rem;
        }
        .hero .text h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        .hero .text p {
            font-size: 1.2rem;
            margin: 1rem 0;
        }
        .hero .image {
            flex: 1;
        }
        .hero .image img {
            max-width: 100%;
            border-radius: 10px;
        }
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2rem;
            background-color: #ffffff;
        }
        .service {
            margin: 1rem;
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            width: 300px;
            text-align: center;
        }
        .service h3 {
            color: #007bff;
        }
        .footer {
            text-align: center;
            padding: 1rem;
            background-color: #343a40;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to [Your Consulting Firm]</h1>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <div class="text">
            <h1>Expert Solutions for Your Business</h1>
            <p>We help businesses achieve their goals with tailored consulting services.</p>
        </div>
        <div class="image">
            <img src="placeholder-image.jpg" alt="Consulting image">
        </div>
    </section>
    <section id="services" class="services">
        <div class="service">
            <h3>Business Strategy</h3>
            <p>Develop strategic plans to drive success and growth.</p>
        </div>
        <div class="service">
            <h3>Financial Consulting</h3>
            <p>Optimize your financial operations for maximum efficiency.</p>
        </div>
        <div class="service">
            <h3>Marketing Solutions</h3>
            <p>Enhance your brand and reach your target audience effectively.</p>
        </div>
    </section>
    <footer class="footer">
        <p>Contact us at <a href="mailto:info@consultingfirm.com">info@consultingfirm.com</a></p>
        <p>&copy; 2025 [Your Consulting Firm]. All Rights Reserved.</p>
    </footer>
</body>
</html>
