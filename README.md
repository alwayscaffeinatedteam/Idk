# Idk
Idk
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Blog</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #E0E0E0;
            line-height: 1.6;
        }
        header {
            background-color: #1F1F1F;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            color: #BB86FC;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #1F1F1F;
            padding: 10px 0;
        }
        nav a {
            color: #E0E0E0;
            text-decoration: none;
            margin: 0 15px;
            padding: 5px 10px;
            border-radius: 5px;
        }
        nav a:hover {
            background-color: #BB86FC;
            color: #121212;
        }
        .container {
            padding: 20px;
            max-width: 800px;
            margin: auto;
        }
        .about-me, .blog-posts {
            margin-bottom: 40px;
        }
        .about-me h2, .blog-posts h2 {
            color: #BB86FC;
            border-bottom: 2px solid #BB86FC;
            padding-bottom: 5px;
        }
        .blog-post {
            background-color: #1F1F1F;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        .blog-post h3 {
            margin-top: 0;
            color: #BB86FC;
        }
        .blog-post p {
            margin: 10px 0;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #1F1F1F;
            color: #E0E0E0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Personal Blog</h1>
    </header>
    <nav>
        <a href="#about-me">About Me</a>
        <a href="#blog-posts">Blog Posts</a>
    </nav>
    <div class="container">
        <section id="about-me" class="about-me">
            <h2>About Me</h2>
            <p>Hello! I'm [Your Name], a passionate writer and enthusiast of [Your Interests]. This blog is my space to share thoughts, stories, and insights on topics that inspire me. Join me on this journey as I explore the world through words.</p>
        </section>
        <section id="blog-posts" class="blog-posts">
            <h2>Blog Posts</h2>
            <div class="blog-post">
                <h3>Blog Post Title 1</h3>
                <p>Published on: <time datetime="2024-12-30">December 30, 2024</time></p>
                <p>Excerpt of the first blog post goes here...</p>
            </div>
            <div class="blog-post">
                <h3>Blog Post Title 2</h3>
                <p>Published on: <time datetime="2024-12-25">December 25, 2024</time></p>
                <p>Excerpt of the second blog post goes here...</p>
            </div>
            <!-- Add more blog posts as needed -->
        </section>
    </div>
    <footer>
        <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    </footer>
</body>
</html>
