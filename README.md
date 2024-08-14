<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome Home</title>
    <style>
        /* General styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #faf8f8;
            background-color: #090000;
        }

        header {
            background-color: #1e90ff;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }

        header .logo {
            font-size: 24px;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 15px;
        }

        nav ul li a {
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        .home {
            padding: 20px;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background-color: #1e90ff;
            color: #ffffff;
            border-radius: 5px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            margin: 20px auto;
            max-width: 800px;
        }

        .hero h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.5em;
            margin-bottom: 30px;
        }

        .cta-button {
            display: inline-block;
            background-color: #ffffff;
            color: #1e90ff;
            padding: 15px 30px;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 5px;
            margin: 5px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }

        .cta-button:hover {
            background-color: #e0e0e0;
        }

        footer {
            background-color: #1e90ff;
            color: #ffffff;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Learning  Ninja</div>
        <nav>
            <ul>
                <li><a href="main.html">Home</a></li>
                <li><a href="HTML Learning.html">HTML</a></li>
                <li><a href="CSS Learning.html">CSS</a></li>
                <li><a href="JS Learning.html">JavaScript</a></li>
            </ul>
        </nav>
    </header>

    <main class="home">
        <div class="hero">
            <h1>Welcome to Learning Ninja</h1>
            <p>Your gateway to mastering web development. Explore our tutorials and enhance your skills.</p>
            <a href="HTML Learning.html" class="cta-button">Start Learning HTML</a>
            <a href="CSS Learning.html" class="cta-button">Start Learning CSS</a>
            <a href="JS Learning.html" class="cta-button">Start Learning JavaScript</a>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 Learning Ninja Website. All rights reserved.</p>
    </footer>
</body>
</html>
