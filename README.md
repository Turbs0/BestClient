<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Discord / Social Meta -->
    <meta property="og:site_name" content="Best Client">
    <meta property="og:type" content="website">
    <meta property="og:image" content="assets/resources/icon.png">
    <meta property="og:title" content="Best Client — Home">
    <meta property="og:url" content="https://bestclient.com">
    <meta name="theme-color" content="#913de2">
    <meta property="og:description" content="The official website for Best Client.">

    <meta charset="utf-8">
    <link rel="icon" href="assets/resources/icon.png">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Best Client</title>

    <style>
        :root {
            --bg-dark: #121216;
            --bg-card: #1c1c24;
            --accent: #913de2;
            --accent-hover: #7a2bc7;
            --text-main: #eaeaea;
            --text-muted: #a0a0b0;
            --discord: #5865F2;
            --paypal: #0070ba;
            --github: #24292e;
            --youtube: #FF0000;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }

        body {
            background-color: var(--bg-dark);
            color: var(--text-main);
            line-height: 1.6;
        }

        /* Navbar */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 5%;
            background-color: var(--bg-card);
            border-bottom: 1px solid #2a2a35;
        }

        .icon {
            width: 36px;
            height: 36px;
            border-radius: 6px;
        }

        .nav-links {
            display: flex;
            gap: 2rem;
        }

        .nav-links a {
            color: var(--text-main);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.2s;
        }

        .nav-links a:hover {
            color: var(--accent);
        }

        nav button {
            background-color: var(--accent);
            color: white;
            border: none;
            padding: 0.5rem 1.2rem;
            border-radius: 6px;
            font-weight: 600;
            cursor: pointer;
            transition: background 0.2s;
        }

        nav button:hover {
            background-color: var(--accent-hover);
        }

        /* Hero Section */
        .main {
            text-align: center;
            padding: 5rem 1rem 3rem;
        }

        .hero-brand {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 1rem;
            margin-bottom: 2rem;
        }

        .hero-logo-img {
            width: 96px;
            height: 96px;
            object-fit: contain;
        }

        .hero-title {
            font-size: 3.5rem;
            font-weight: 800;
            letter-spacing: 4px;
            text-transform: uppercase;
            color: var(--text-main);
        }

        .hero-title span {
            color: var(--accent);
        }

        /* Buttons */
        .buttons {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 1rem;
            margin: 1.5rem 0;
        }

        .button {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            padding: 0.75rem 1.5rem;
            background-color: var(--accent);
            color: white;
            text-decoration: none;
            border-radius: 8px;
            font-weight: 600;
            transition: opacity 0.2s, transform 0.1s;
        }

        .button:hover {
            opacity: 0.9;
            transform: translateY(-1px);
        }

        /* Content Containers */
        .container {
            max-width: 800px;
            margin: 2rem auto;
            padding: 2rem;
            background-color: var(--bg-card);
            border-radius: 12px;
            text-align: center;
            border: 1px solid #2a2a35;
        }

        h2 {
            font-size: 1.8rem;
            margin-bottom: 1rem;
            color: var(--text-main);
        }

        .stats {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-bottom: 1.5rem;
            color: var(--text-muted);
            font-size: 1.1rem;
        }

        .container a:not(.button) {
            color: var(--accent);
            text-decoration: none;
        }

        .container a:not(.button):hover {
            text-decoration: underline;
        }

        .note {
            font-size: 0.85rem;
            color: var(--text-muted);
            margin-top: 1rem;
        }

        /* Dev Team Cards */
        .cont {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .card {
            background-color: var(--bg-dark);
            padding: 1.5rem;
            border-radius: 10px;
            width: 200px;
            border: 1px solid #2a2a35;
        }

        .card img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 0.75rem;
            background-color: #2a2a35;
        }

        .card span {
            font-size: 0.85rem;
            color: var(--text-muted);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 2.5rem 1rem;
            color: var(--text-muted);
            font-size: 0.9rem;
            border-top: 1px solid #2a2a35;
            margin-top: 4rem;
        }
    </style>
</head>
<body>

    <nav>
        <a href="index.html" class="icon-link">
            <img src="assets/resources/icon.png" alt="Best Client Icon" class="icon">
        </a>
        <div class="nav-links">
            <a href="index.html">Home</a>
            <a href="faq.html">FAQ</a>
            <a href="https://github.com" target="_blank">GitHub</a>
        </div>
        <div class="btn-wrapper">
            <button type="button" class="login-btn" disabled>Login</button>
            <span class="corner-ribbon">Currently Disabled</span>
        </div>

    </nav>

    <div class="main">
        <div class="hero-brand">
            <img src="assets/resources/icon.png" alt="Best Client Logo" class="hero-logo-img">
            <h1 class="hero-title">BEST <span>CLIENT</span></h1>
        </div>

        <div class="buttons">
            <a href="https://discord.gg/6cdECSYEbC" target="_blank" class="button" style="background-color: var(--discord);">Discord</a>
            <a href="https://paypal.com" target="_blank" class="button" style="background-color: var(--paypal);">Donate</a>
        </div>
    </div>

    <div class="container">
        <h2>Downloads</h2>
        <div class="stats">
            <p>Downloads: <strong>0</strong></p>
            <p>Online Players: <strong>0</strong></p>
        </div>
        <div class="buttons">
            <a href="#" class="button">Download Best Client [Latest]</a>
            <a href="#" class="button">Download Addon / Baritone</a>
        </div>
        <p>Looking for older versions? Check out the <a href="archive.html">archive</a>.</p>
        <p class="note">* Make sure you have the correct mod loader installed before launching Best Client.</p>
    </div>

    <div class="container">
        <h2>Dev Team</h2>
        <div class="cont">
            <div class="card">
                <img src="assets/resources/dev1.png" alt="Owner Avatar">
                <p><b>Turbs</b></p>
                <span>Owner / Head Developer</span>
            </div>
            <div class="card">
                <img src="assets/resources/dev2.png" alt="Dev Avatar">
                <p><b>ExtemeDmon</b></p>
                <span>Twin</span>
            </div>
        </div>
        <div class="cont">
            <a href="https://discord.gg/6cdECSYEbC" target="_blank" class="button" style="background-color: var(--discord);">Discord</a>
            <a href="https://github.com" target="_blank" class="button" style="background-color: var(--github);">GitHub</a>
            <a href="https://youtube.com" target="_blank" class="button" style="background-color: var(--youtube);">YouTube</a>
            <a href="https://paypal.com" target="_blank" class="button" style="background-color: var(--paypal);">Donate</a>
        </div>
    </div>

    <footer>
        <p>Copyright © 2026 Best Client Development</p>
        <p>All Rights Reserved.</p>
    </footer>

</body>
</html>
