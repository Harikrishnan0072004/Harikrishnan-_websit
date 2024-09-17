# Harikrishnan-_websit
Html.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Harikrishnan's Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0e76a8;
            color: white;
            padding: 20px;
            text-align: center;
        }
        section {
            padding: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        .bio {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .bio img {
            float: right;
            margin-left: 20px;
            border-radius: 50%;
            width: 150px;
        }
        .gallery img {
            width: 100%;
            border-radius: 8px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Harikrishnan's Personal Website</h1>
        <p>Electrical Engineering | C Programming Enthusiast</p>
    </header>

    <section class="bio">
        <h2>About Me</h2>
        <img src="your-profile-image.jpg" alt="Harikrishnan">
        <p>Hello! My name is Harikrishnan, and I am an Electrical Engineering student with a passion for C programming. I enjoy exploring new technologies, solving problems, and designing electrical systems. My inspiration in the field is Nikola Tesla, whose innovative ideas in electrical engineering still resonate today.</p>
    </section>

    <section>
        <h2>My Inspirations</h2>
        <img src="tesla.jpg" alt="Nikola Tesla" style="float:left; margin-right:20px; width:150px;">
        <p>Nikola Tesla has been a significant influence in my journey as an electrical engineer. His contributions to the development of AC electrical systems, wireless transmission, and countless other innovations have shaped modern technology in ways we still admire and build upon today. His work inspires me to think creatively and push the boundaries of what’s possible in engineering.</p>
    </section>

    <section class="gallery">
        <h2>Electrical Engineering Projects</h2>
        <p>Here are some images related to electrical engineering, showcasing various projects and components that fascinate me:</p>
        <img src="electrical-project1.jpg" alt="Electrical Project 1">
        <img src="electrical-project2.jpg" alt="Electrical Project 2">
    </section>

    <footer>
        <p>&copy; 2024 Harikrishnan. All rights reserved.</p>
    </footer>

</body>
</html>
