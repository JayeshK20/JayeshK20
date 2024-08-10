<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jayesh Kolambkar's Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #fff 3px solid;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .main {
            display: flex;
            justify-content: space-between;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        .main img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .content {
            flex: 1;
            padding: 0 20px;
        }
        .content h2 {
            color: #333;
        }
        .projects, .skills, .connect {
            margin-top: 20px;
        }
        .projects a, .connect a {
            color: #007bff;
            text-decoration: none;
        }
        .projects a:hover, .connect a:hover {
            text-decoration: underline;
        }
        .github-stats img, .dev-card img {
            max-width: 100%;
            height: auto;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Hi there, I'm Jayesh Kolambkar 👋</h1>
        </div>
    </header>

    <div class="container main">
        <img src="https://avatars.githubusercontent.com/u/42012378?s=460&u=132edc17f743dd087ed1e4892dfc8c589b1a8da6&v=4" alt="Jayesh Kolambkar">
        <div class="content">
            <h2>About Me</h2>
            <p>I'm a passionate Software Developer specializing in building efficient and scalable web applications. With a focus on full-stack development, I work with technologies like Node.js, React, and PostgreSQL to create robust solutions.</p>
            <ul>
                <li>🌱 <strong>Always learning</strong>: Continuously exploring new technologies to stay ahead in the industry.</li>
                <li>🎯 <strong>Tech Enthusiast</strong>: Focused on collaborative tools, real-time applications, and enhancing user experiences.</li>
            </ul>

            <div class="projects">
                <h2>My Projects</h2>
                <p><strong><a href="https://github.com/JayeshK20/jsm-live-docs" target="_blank">jsm-live-docs</a></strong>: A collaborative documentation platform developed using Next.js, featuring authentication with Clerk and real-time updates with Liveblocks.</p>
                <p><strong><a href="https://github.com/JayeshK20/Resume-Builder-Web-Application" target="_blank">Resume Builder Web Application</a></strong>: A web application for creating and managing resumes, designed to simplify the process of building and updating professional resumes.</p>
            </div>

            <div class="skills">
                <h2>Skills</h2>
                <p><strong>Languages</strong>: Java</p>
                <p><strong>Databases</strong>: MySQL</p>
                <p><strong>Tools</strong>: GitHub Actions</p>
            </div>

            <div class="github-stats">
                <h2>GitHub Stats</h2>
                <a href="https://github.com/JayeshK20" target="_blank"><img src="https://github-readme-stats.vercel.app/api?username=JayeshK20&show_icons=true&theme=radical" alt="Jayesh's GitHub stats"></a>
            </div>

            <div class="dev-card">
                <h2>Dev Card</h2>
                <a href="https://app.daily.dev/jayeshkolambkar" target="_blank"><img src="https://api.daily.dev/devcards/v2/vWJGQNhllAEGJOi2E5esb.png?r=qan&type=default" alt="Jayesh Kolambkar's Dev Card"></a>
            </div>

            <div class="connect">
                <h2>Connect with Me</h2>
                <p><a href="https://www.linkedin.com/in/jayesh-kolambkar-9b0185246/" target="_blank">LinkedIn</a></p>
                <p><a href="https://app.daily.dev/jayeshkolambkar" target="_blank">Daily.dev Profile</a></p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Jayesh Kolambkar</p>
    </footer>
</body>
</html>
