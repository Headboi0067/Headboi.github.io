<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Ibrahim's Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Ibrahim Abdullahi</h1>
        <p>Web Designer | Web3 Enthusiast | NFT Raider</p>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hi, I’m Ibrahim. I design clean websites and work with Web3 projects as a community mod and raider. I’m passionate about building and writing, and I love learning new tech.</p>
    </section>

    <!-- Skills / Services -->
    <section id="skills">
        <h2>What I Do</h2>
        <ul>
            <li>✅ Web Design (HTML & CSS)</li>
            <li>✅ Discord & Twitter Raiding</li>
            <li>✅ Community Mod / Writer</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">

            <label for="email">Email:</label>
            <input type="email" id="email" name="email">

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5"></textarea>

            <input type="submit" value="Send">
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Ibrahim Abdullahi. All rights reserved.</p>
    </footer>

</body>
</html>#body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header {
    background-color: #007bff;
    color: white;
    padding: 30px;
    text-align: center;
}

section {
    padding: 30px;
    max-width: 800px;
    margin: auto;
    background-color: white;
    margin-top: 20px;
    border-radius: 8px;
}

h2 {
    color: #007bff;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    background: #e9ecef;
    margin-bottom: 10px;
    padding: 10px;
    border-radius: 4px;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form input[type="submit"] {
    background-color: #007bff;
    color: white;
    border: none;
    cursor: pointer;
}

form input[type="submit"]:hover {
    background-color: #0056b3;
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 15px;
    margin-top: 20px;
} Headboi.github.io
