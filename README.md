/ (root)
│── index.html
│── style.css
│── script.js
css/
js/
embed_website.min.js
websiteTrack.js

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My GitHub Website</title>

    <!-- CSS -->
    <link rel="stylesheet" href="style.css" />
</head>
<body>

    <header>
        <h1>Welcome to My Website 🚀</h1>
        <p>Edit this file directly on GitHub Pages</p>
    </header>

    <main>
        <button onclick="sayHello()">Click Me</button>
    </main>

    <!-- JS -->
    <script src="script.js"></script>

</body>
</html>
body {
    font-family: Arial, sans-serif;
    background: #f5f5f5;
    text-align: center;
    margin: 0;
    padding: 40px;
}

header {
    background: #222;
    color: white;
    padding: 20px;
    border-radius: 10px;
}

button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}
function sayHello() {
    alert("Hello! Your site is working 🎉");
}
