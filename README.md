<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
    <title>Tech Skills & AI Prompts</title>
</head>
<body>
    <nav class="container-fluid">
        <ul>
            <li><strong>Tech & AI</strong></li>
        </ul>
        <ul>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#prompts">AI Prompts</a></li>
            <li><a href="#contact" role="button">Contact</a></li>
        </ul>
    </nav>
    <main class="container">
        <div class="grid">
            <section id="skills">
                <hgroup>
                    <h2>Master Tech Skills</h2>
                    <h3>Upgrade your knowledge</h3>
                </hgroup>
                <p>Explore the vast realm of technology with our curated list of skills. From programming to data analysis, elevate your proficiency and stay ahead of the curve.</p>
                <figure>
                    <img src="https://source.unsplash.com/weekly?technology" alt="Technology Skills" />
                    <figcaption><a href="https://unsplash.com/s/photos/technology" target="_blank">Photo by Unsplash</a></figcaption>
                </figure>
                <h3>Programming Languages</h3>
                <p>Delve into Python, JavaScript, and more. Understand the syntax, concepts, and applications of each language.</p>
                <h3>Data Science & Analysis</h3>
                <p>Discover the world of data. Learn how to manipulate, analyze, and visualize data to make informed decisions.</p>
            </section>
        </div>
    </main>
    <section aria-label="AI Prompts" id="prompts">
        <div class="container">
            <article>
                <hgroup>
                    <h2>Engaging AI Prompts</h2>
                    <h3>Spark your creativity</h3>
                </hgroup>
                <form class="grid">
                    <input type="text" id="firstname" name="firstname" placeholder="Enter your name" aria-label="First Name" required />
                    <input type="email" id="email" name="email" placeholder="Enter your email" aria-label="Email" required />
                    <button type="submit" onclick="event.preventDefault()">Subscribe for Prompts</button>
                </form>
            </article>
        </div>
    </section>
    <footer class="container">
        <small><a href="#">Privacy Policy</a> • <a href="#">Terms of Service</a></small>
    </footer>
</body>
</html>
