<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            overflow: hidden;
        }
        .profile {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-top: 20px;
        }
        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .profile h1 {
            margin: 0;
            padding: 0;
        }
        .section {
            background: #fff;
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .section p {
            line-height: 1.6;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Student Portfolio</h1>
    </header>
    <div class="container">
        <div class="profile">
            <img src="profile.jpg" alt="Student Photo">
            <div>
                <h1>John Doe</h1>
                <p>Web Developer | Graphic Designer</p>
            </div>
        </div>
        <div class="section">
            <h2>About Me</h2>
            <p>Hello! I'm John, a passionate web developer and graphic designer with a love for creating intuitive and dynamic web experiences. I have experience in various programming languages and design tools, and I'm constantly learning and evolving in my field.</p>
        </div>
        <div class="section">
            <h2>Projects</h2>
            <p><strong>Project 1:</strong> A responsive website for a local business. <br>
               <strong>Project 2:</strong> An interactive web app for tracking personal goals.</p>
        </div>
        <div class="section">
            <h2>Skills</h2>
            <p>HTML, CSS, JavaScript, React, Photoshop, Illustrator</p>
        </div>
    </div>
    <footer>
        &copy; 2024 John Doe
    </footer>
</body>
</html>
