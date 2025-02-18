<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Personal CV</title>
    <style>
        .page-content {
            padding: 20px;
        }
        .sharingan {
            width: 150px;
            height: 200px;
            display: block;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <p>I am Header with an unordered list of hyperlinks</p>

    <header>
        <nav>
            <ul>
                <li><a href="#about">I am About link and my href value is #about</a></li>
                <li><a href="#education">I am Education link and my href value is #education</a></li>
                <li><a href="#skills">I am Skills link and my href value is #skills</a></li>
                <li><a href="#portfolio">I am Portfolio link and my href value is #portfolio</a></li>
                <li><a href="#contact">I am Contact link and my href value is #contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Sharingan image -->
    <img src="sharingan.jfif" alt="I am an image and I'm all by myself" class="sharingan">
    
    <p>I am a division with class equal to page-content that encloses all other division elements below</p>

    <div class="page-content">
        <!-- Main heading -->
        <h1>Hello! I am a text with the largest heading</h1>

        <!-- Content sections -->
        <section id="about">
            <h2>About Me</h2>
            <p>Write something about yourself here...</p>
        </section>

        <section id="education">
            <h2>Education</h2>
            <p>Describe your education history here...</p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <p>List your skills here...</p>
        </section>

        <section id="portfolio">
            <h2>Portfolio</h2>
            <p>Showcase your work here...</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Provide your contact details here...</p>
        </section>
    </div>

    <!-- Footer -->
    <footer>I am a footer, the last section of this page</footer>
</body>
</html>
