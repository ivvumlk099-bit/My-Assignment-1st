<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Navigation</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        nav {
            background-color: #222;
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            color: white;
            font-size: 24px;
            font-weight: bold;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        .nav-links a:hover {
            color: #00bcd4;
        }

        section {
            padding: 60px 30px;
            text-align: center;
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">My Portfolio</div>

        <div class="nav-links">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <section id="home">
        <h1>Welcome to My Portfolio</h1>
        <p>Hello! I am a BCA student learning web development.</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I am learning HTML, CSS and programming.</p>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <p>My projects will be displayed here.</p>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: student@example.com</p>
    </section>

</body>
</html>
