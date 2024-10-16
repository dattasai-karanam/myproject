<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>A brief description about yourself.</p>
        </section>
        <section id="projects">
            <h2>My Projects</h2>
            <div class="project">
                <h3>Project 1</h3>
                <p>Description of your project.</p>
            </div>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <form id="contact-form">
                <input type="text" placeholder="Your Name">
                <input type="email" placeholder="Your Email">
                <textarea placeholder="Your Message"></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

form {
    display: flex;
    flex-direction: column;
}

input, textarea {
    margin-bottom: 10px;
    padding: 10px;
    border: 1px solid #ccc;
}

button {
    padding: 10px;
    border: none;
    background-color: #333;
    color: white;
    cursor: pointer;
}
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

form {
    display: flex;
    flex-direction: column;
}

input, textarea {
    margin-bottom: 10px;
    padding: 10px;
    border: 1px solid #ccc;
}

button {
    padding: 10px;
    border: none;
    background-color: #333;
    color: white;
    cursor: pointer;
}
document.getElementById('contact-form').addEventListener('submit', function(event) {
    event.preventDefault();
    alert('Message sent!');
});
