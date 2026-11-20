
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QuizHive - Interactive Learning</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f1ff;
            color: #333;
        }

        header {
            background-color: #291653;
            color: white;
            text-align: center;
            padding: 25px;
        }

        header h1 {
            font-size: 36px;
            color: #ffcc4d;
            letter-spacing: 2px;
        }

        header p {
            font-size: 16px;
            margin-top: 8px;
        }

        nav {
            background-color: #493078;
            text-align: center;
            padding: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ffcc4d;
        }

        .container {
            display: flex;
            gap: 20px;
            padding: 25px;
        }

        .sidebar {
            width: 30%;
            background-color: white;
            padding: 25px;
            border-radius: 10px;
        }

        .sidebar h2 {
            color: #493078;
            margin-bottom: 15px;
        }

        .sidebar p {
            line-height: 1.8;
            font-size: 15px;
        }

        .main-content {
            width: 70%;
            background-color: white;
            padding: 25px;
            border-radius: 10px;
        }

        .main-content h2 {
            color: #493078;
            font-size: 26px;
            margin-bottom: 15px;
        }

        .main-content p {
            font-size: 16px;
            line-height: 1.8;
            margin-bottom: 15px;
        }

        .services {
            display: flex;
            gap: 15px;
            margin-top: 20px;
        }

        .card {
            flex: 1;
            background-color: #eee8ff;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }

        .card h3 {
            color: #493078;
            margin-bottom: 10px;
        }

        .card p {
            font-size: 14px;
        }

        button {
            background-color: #493078;
            color: white;
            padding: 12px 25px;
            border: none;
            border-radius: 6px;
            font-size: 15px;
            cursor: pointer;
        }

        button:hover {
            background-color: #ffbd35;
            color: #291653;
        }

        footer {
            background-color: #291653;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        @media (max-width: 600px) {
            .container {
                flex-direction: column;
            }

            .sidebar,
            .main-content {
                width: 100%;
            }

            .services {
                flex-direction: column;
            }

            nav a {
                display: inline-block;
                margin: 8px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>QuizHive 🐝</h1>
        <p>Learn • Play • Grow</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">

        <aside class="sidebar">
            <h2>About Us</h2>

            <p>
                QuizHive is an interactive learning
                platform that makes education
                simple, fun and interesting.
            </p>

            <br>

            <h2>Our Goal</h2>

            <p>
                To improve knowledge through
                fun quizzes and learning games.
            </p>
        </aside>

        <main class="main-content" id="home">

            <h2>Welcome to QuizHive!</h2>

            <p>
                QuizHive provides gamified quizzes
                for interactive learning.
                Students can learn new topics,
                answer questions and improve
                their knowledge in a fun way.
            </p>

            <h2 id="services">Our Services</h2>

            <div class="services">

                <div class="card">
                    <h3>Fun Quizzes</h3>
                    <p>
                        Enjoy interesting quizzes
                        and test your knowledge.
                    </p>
                </div>

                <div class="card">
                    <h3>Interactive Learning</h3>
                    <p>
                        Learn different subjects
                        through fun activities.
                    </p>
                </div>

            </div>

            <br>

            <button onclick="alert('Welcome to QuizHive!')">
                Get Started
            </button>

        </main>

    </div>

    <footer id="contact">
        <p>© 2026 QuizHive. All Rights Reserved.</p>
        <p>Gamified Quizzes for Interactive Learning</p>
    </footer>

</body>
</html>
# p4-
practicum4.html
