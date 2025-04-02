# assing3.web

## THE STYLING CODE CSS

/* General page styling */
body {
    font-family: 'Arial', sans-serif;
    background-color: #3b3737;
    margin: 0;
    padding: 0;
}

/* Header styling using an ID */
#header {
    background-color: #333;
    color: white;
    text-align: left;
    padding: 20px;
    font-size: 30px;
}

/* Styling paragraphs using a class */
.paragraph {
    color: #555;
    font-size: 18px;
    line-height: 1.6;
    margin: 20px;
    padding: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    background-color: #fff;
}

/* Styling an image */
.image-style {
    float: center;
    margin-left: 20px;
    width: 300px;
    border: 5px solid #333;
    border-radius: 10px;
    margin: 20px auto;
    display: block;
}

/* Button styling */
.button {
    display: inline-block;
    background-color: #007BFF;
    color: red;
    padding: 10px 20px;
    margin: 10px;
    border: none;
    border-radius: 5px;
    text-decoration: wavy;
    font-size: 16px;
    cursor: pointer;
    }

.button:hover {
    background-color: #021b35;
}

/* Styling the list  */
.list{
    list-style-type: square;
    margin: 20px;
    padding: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    background-color: #fff;
    color: #555;
}

# THE HTML CODE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introduction to CSS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div id="header">Introduction to CSS</div>

    <h3><p class="paragraph">Web pages can be styled so well by only just using CSS styling.</p><h3></h3>
    <h5> Types of styling in CSS</h5>
    <ul class="list">
        <li>Inline css</li>
        <li>Internal css</li>
        <li>External css</li>
    </ul>
    <br>

    <img src="/styles/images/programmmer.jpg" alt="Styled Image" class="image-style">
<br><br>
    <a href="#" class="button">Click Me</a>

</body>
</html>


