# Introduction-to-css-assignment
HTML 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introduction to CSS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="header">
        <h1>Introduction to CSS</h1>
    </header>
    <section class="content">
        <p class="description">CSS helps style your web pages with colors, fonts, and layout adjustments.</p>
        <img src="image.jpg" alt="Example Image" class="styled-image">
    </section>
</body>
</html>

syles.css
/* Basic page styling */
body {
    font-family: 'Verdana', sans-serif;
    background-color: #f8f9fa;
    margin: 20px;
    padding: 20px;
}

/* Header styling */
.header {
    background-color: #0073e6;
    color: white;
    text-align: center;
    padding: 15px;
    border-radius: 8px;
}

/* Paragraph styling */
.description {
    color: #333;
    font-size: 18px;
    margin: 15px 0;
    padding: 10px;
    border-left: 4px solid #0073e6;
}

/* Image styling */
.styled-image {
    width: 300px;
    height: auto;
    border: 4px solid #0073e6;
    border-radius: 10px;
    margin-top: 10px;
}
