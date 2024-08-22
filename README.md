<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Illumination Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: #fff;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #575757;
        }
        .hero {
            background: url('https://via.placeholder.com/1500x500') no-repeat center center/cover;
            height: 500px;
            color: white;
            text-align: center;
            padding-top: 100px;
        }
        .hero h1 {
            font-size: 3em;
            margin: 0;
        }
        .content {
            padding: 20px;
        }
        .services {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .service {
            background-color: #fff;
            padding: 20px;
            width: 30%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Illumination Project</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero">
        <h1>Shining a Light on Your Digital Success</h1>
    </section>

    <section class="content">
        <h2 id="services">Our Services</h2>
        <div class="services">
            <div class="service">
                <h3>SEO Optimization</h3>
                <p>Improve your search engine rankings with our expert SEO services.</p>
            </div>
            <div class="service">
                <h3>Social Media Marketing</h3>
                <p>Boost your brand’s presence on social media with tailored strategies.</p>
            </div>
            <div class="service">
                <h3>Content Creation</h3>
                <p>Create engaging content that resonates with your audience.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Illumination Project. All rights reserved.</p>
    </footer>

</body>
</html>
