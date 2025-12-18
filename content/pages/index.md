*CNAME*
(no extension, one line)
risetogethertrust.org

index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>RiseTogether Trust</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="logo.svg" alt="RiseTogether Trust logo" class="logo">
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="mission.html">Mission</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <main>
        <h1>Welcome to RiseTogether Trust</h1>
        <p>Empowering communities, one step at a time.</p>
    </main>

    <footer>
        © 2025 RiseTogether Trust
    </footer>
</body>
</html>

about.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>About – RiseTogether Trust</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="logo.svg" alt="RiseTogether Trust logo" class="logo">
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="mission.html">Mission</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <main>
        <h1>About Us</h1>
        <p>We’re a nonprofit dedicated to fostering collaboration and growth in the community.</p>
    </main>

    <footer>
        © 2025 RiseTogether Trust
    </footer>
</body>
</html>

mission.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Mission – RiseTogether Trust</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="logo.svg" alt="RiseTogether Trust logo" class="logo">
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="mission.html">Mission</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <main>
        <h1>Our Mission</h1>
        <p>To uplift underserved communities through education, resources, and partnership.</p>
    </main>

    <footer>
        © 2025 RiseTogether Trust
    </footer>
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact – RiseTogether Trust</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="logo.svg" alt="RiseTogether Trust logo" class="logo">
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="mission.html">Mission</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <main>
        <h1>Get in Touch</h1>
        <form action="thankyou.html" method="GET">
            <label>Name:</label><br>
            <input type="text" name="name" required><br><br>
            <label>Email:</label><br>
            <input type="email" name="email" required><br><br>
            <label>Message:</label><br>
            <textarea name="msg" rows="4" required></textarea><br><br>
            <button type="submit">Send</button>
        </form>
    </main>

    <footer>
        © 2025 RiseTogether Trust
    </footer>
</body>
</html>

thankyou.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Thank You – RiseTogether Trust</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="logo.svg" alt="RiseTogether Trust logo" class="logo">
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="mission.html">Mission</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <main>
        <h1>Thanks for reaching out!</h1>
        <p>We’ll get back to you soon.</p>
    </main>

    <footer>
        © 2025 RiseTogether Trust
    </footer>
</body>
</html>

style.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
}
header, footer {
    background: #004d40;
    color: #fff;
    padding: 1rem;
    text-align: center;
}
.logo {
    max-height: 60px;
}
nav a {
    margin: 0 1rem;
    color: #fff;
    text-decoration: none;
}
nav a:hover {
    text-decoration: underline;
}
main {
    max-width: 800px;
    margin: 2rem auto;
    padding: 0 1rem;
}
footer {
    font-size: 0.9rem;
}

logo.svg – you can use any SVG you like; here’s a quick placeholder you can paste into `logo.svg`:
<svg xmlns="http:                                                                    
    <text x="0" y="40" font-family="Arial" font-size="30" fill="#fff">RiseTogether</text>
</svg>

*What to do next*

1. Create a new GitHub repo (e.g., `risetogether`).
2. Add all the files above (copy‑paste into the repo).
3. Push the repo.
4. In repo *Settings → Pages*, set source to `main` (or `gh-pages`).
5. Add the DNS records (CNAME + A records) as we discussed earlier.

Let me know if you need a hand with any of the steps or if you want a different layout! 🚀
