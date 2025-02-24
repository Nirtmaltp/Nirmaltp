// index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Nirmal Thomas</h1>
        <p>Web Developer | Designer</p>
    </header>
    
    <section id="portfolio">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of your project.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Another great project.</p>
        </div>
    </section>

    <footer>
        <p>Contact: your.email@example.com</p>
    </footer>
</body>
</html>

/* styles.css */
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 20px;
}

header {
    background: #222;
    color: white;
    padding: 20px;
}

.project {
    background: white;
    padding: 10px;
    margin: 10px auto;
    width: 80%;
    border-radius: 5px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}
