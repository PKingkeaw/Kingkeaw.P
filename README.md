<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .header {
            background: #333;
            color: white;
            padding: 20px;
        }
        .container {
            padding: 20px;
        }
        .projects {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        .project {
            border: 1px solid #ddd;
            padding: 15px;
            margin: 10px;
            width: 300px;
        }
        .footer {
            background: #333;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>My Portfolio</h1>
        <p>Web Developer | Designer | Creator</p>
    </div>
    
    <div class="container">
        <h2>About Me</h2>
        <p>Hello! I'm a passionate web developer with a knack for creating stunning websites.</p>
        
        <h2>Projects</h2>
        <div class="projects">
            <div class="project">
                <h3>Project 1</h3>
                <p>A cool web app built with HTML, CSS, and JavaScript.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>An innovative e-commerce website.</p>
            </div>
        </div>
    </div>
    
    <div class="footer">
        <p>Contact: email@example.com | LinkedIn | GitHub</p>
    </div>
</body>
</html>
