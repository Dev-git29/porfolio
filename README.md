<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Devansh Vashishth - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2e;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff5733;
            text-align: center;
            padding: 20px;
            animation: fadeIn 2s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        section {
            padding: 20px;
            margin: 20px auto;
            width: 80%;
            background-color: #2a2a3b;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.2);
            animation: slideIn 1.5s;
        }
        @keyframes slideIn {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        h2 {
            border-bottom: 2px solid #ff5733;
            padding-bottom: 5px;
        }
        a {
            color: #ff5733;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Devansh Vashishth</h1>
        <p>Software Engineer | Python | C | Data Analysis</p>
    </header>
    
    <section id="Portfolio">
        <h2>Portfolio </h2>
        <p>Hello! I'm a passionate software engineer with expertise in Python, C, and data analysis. I love solving problems and building efficient solutions.</p>
    </section>
    
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>C</li>
            <li>Data Analysis</li>
            <li>Web Development</li>
        </ul>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li><strong>Project 1:</strong> Data Analysis Dashboard</li>
            <li><strong>Project 2:</strong> Web Scraper using Python</li>
            <li><strong>Project 3:</strong> Portfolio Website</li>
        </ul>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>mobile no:8630701833</p>
        <p>Email: vaibhavvashishth029@gmail.com</p>
        <p>LinkedIn: <a href="#">linkedin.com/in/devansh</a></p>
        <p>GitHub: <a href="#">github.com/devansh</a></p>
    </section>
</body>
</html>
