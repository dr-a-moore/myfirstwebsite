# myfirstwebsite
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dr. Andy Moore - Chief Data Officer at Bentley Motors</title>
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
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #555;
        }
        nav a {
            color: #fff;
            padding: 1rem;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #666;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin-bottom: 2rem;
        }
        h1, h2, h3 {
            color: #333;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: #fff;
        }
        .media-links a {
            margin: 0 1rem;
            color: #1a0dab;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dr. Andy Moore</h1>
        <p>Chief Data Officer at Bentley Motors</p>
         <img src="AM-headshot.jpeg" alt="Dr. Andy Moore">
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#media">Media Links</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Dr. Andy Moore is the Chief Data Officer at Bentley Motors, leading the company's digital transformation and data strategy. With a passion for innovation and future technologies, Dr. Moore has been instrumental in driving Bentley's data initiatives forward.</p>
        </section>
        <section id="media" class="section">
            <h2>Media Links</h2>
            <p class="media-links">
                <a href="https://www.linkedin.com/in/andy-moore-digital?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BOSEJYODdQZ2HVLIu3dC4Dw%3D%3D">LinkedIn</a>
            </p>
        </section>
        <section id="blog" class="section">
            <h2>Blog</h2>
            <p>Coming soon...</p>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <form action="mailto:andy.moore@example.com" method="post" enctype="text/plain">
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name"><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message"></textarea><br>
                <input type="submit" value="Send">
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Dr. Andy Moore</p>
    </footer>
</body>
</html>
