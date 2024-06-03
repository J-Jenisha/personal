# personal
<h1>index.html</h1>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Data</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Jenisha Jesudhas</h1>
           
        </header>
        <section class="personal-info">
            <h2>Personal Information</h2>
            <p><strong>Age:</strong> 19</p>
            <p><strong>Location:</strong> Kanniyakumari</p>
            <p><strong>Hobbies:</strong> Reading, Traveling, Photography</p>
            <p><strong>Languages:</strong> English, Tamil</p>
        </section>
        
        <section class="contact-info">
            <h2>Contact Details</h2>
            <p><strong>Email:</strong> jenijesudhas@example.com</p>
            <p><strong>Phone:</strong> 9342783497</p>
            <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/johndoe">linkedin.com/in/jenisha</a></p>
            <p><strong>GitHub:</strong> <a href="https://github.com/johndoe">github.com/jenidsha</a></p>
        </section>
    </div>
</body>
</html>

<h1>style.css</h1>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    line-height: 1.6;
}

.container {
    max-width: 800px;
    margin: 20px auto;
    padding: 20px;
    background: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
}

header {
    text-align: center;
    margin-bottom: 20px;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

.profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
}

section {
    margin-bottom: 20px;
}

section h2 {
    font-size: 1.5em;
    margin-bottom: 10px;
    border-bottom: 2px solid #333;
    padding-bottom: 5px;
}

p {
    margin-bottom: 10px;
}

a {
    color: #007BFF;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

