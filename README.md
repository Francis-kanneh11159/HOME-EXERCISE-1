<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Personal webpage showing hobbies, goals, and favorites.">
    <meta name="author" content="Alex Student">
    <title>About Me & My Favorites</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
            color: #222;
        }
        header {
            border-top: 4px solid #1b1b87;
            border-bottom: 1px solid #ddd;
            padding: 10px 0;
            margin-bottom: 20px;
        }
        nav a {
            text-decoration: none;
            color: #1b1b87;
            margin-right: 15px;
            font-weight: bold;
        }
        h1, h2, h3 {
            color: #1b1b87;
        }
        .profile-card {
            border: 1px solid #ccc;
            background-color: #f9f9f9;
            padding: 10px 15px;
            border-radius: 8px;
            width: fit-content;
        }
        .highlight {
            color: rgb(220, 20, 60);
            font-weight: bold;
        }
        footer {
            border-top: 1px solid #ccc;
            margin-top: 40px;
            padding-top: 10px;
            font-size: 0.9em;
            color: #555;
        }
    </style>
</head>

<body>

    <header>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Favorites</a>
        </nav>
    </header>

    <h1>About Me & My Favorites</h1>
    <p>Welcome! This simple page shows basic HTML structure and inline styling. 
        Notice how the word <span class="highlight">highlighted</span> uses RGB color inside a paragraph.
    </p>

    <!-- Profile Card Section -->
    <section>
        <h2>About Me</h2>
        <div class="profile-card">
            <p>👋 <b>Hi, I'm Alex Student</b></p>
            <p>I'm learning web development and I enjoy turning ideas into simple webpages.<br>
               Fun fact: I can juggle <span style="color: orange;">three oranges!</span></p>
        </div>
        <p>I built this demo with a focus on the basics: headings, paragraphs, lists, and inline styles.
           My goal is to practice and create a unique page that reflects my personality. 
           I believe consistency matters—so I’ll keep building a little every day.</p>
    </section>

    <section>
        <h2>My Hobbies</h2>
        <ul>
            <li>Drawing and <span style="color: blue;">digital sketching</span></li>
            <li>Playing football with friends</li>
            <li>Listening to podcasts</li>
            <li>Reading short tech articles</li>
        </ul>
    </section>

    <section>
        <h2>Top 3 Goals</h2>
        <ol>
            <li>Build 5 practice webpages and share screenshots</li>
            <li>Learn more CSS for layout and spacing</li>
            <li>Create a simple one-page portfolio</li>
        </ol>
    </section>

    <section>
        <h2>Quick Glossary</h2>
        <dl>
            <dt><b>HTML</b></dt>
            <dd>The structure of a webpage; it uses elements and tags.</dd>

            <dt><b>CSS</b></dt>
            <dd>Styles that control how HTML content looks (colors, spacing, etc.).</dd>

            <dt><b>RGB</b></dt>
            <dd>A color model using Red, Green, and Blue values (0–255), e.g., <span style="color: rgb(220, 20, 60);">rgb(220, 20, 60)</span>.</dd>
        </dl>
    </section>

    <section>
        <h2>My Favorites</h2>
        <p>Favorite color (by name): <span style="color: blue; font-weight:bold;">blue</span>.</p>
        <p>Favorite coding snack: crispy apples. Favorite study trick: short focused sessions with a quick stretch between them.</p>
    </section>

    <section>
        <h3>Contact</h3>
        <p>Reach me at: <a href="mailto:alex.student@example.com">alex.student@example.com</a></p>
        <p>I'm open to feedback and tips!</p>
    </section>

    <footer>
        <p>© 2025 Demo Page — Built with basic HTML and <span style="color:#1b1b87;">inline style attributes</span> only.</p>
    </footer>

</body>
</html>
