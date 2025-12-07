ReallifeMDT/
│
├── index.html
├── about.html
└── style.css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>REALLIFE – Screenplay Summary</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<nav>
    <div class="logo">REALLIFE</div>
    <ul>
        <li><a href="index.html">Summary</a></li>
        <li><a href="about.html">About the Authors</a></li>
    </ul>
</nav>

<header class="hero">
    <h1 class="hero-title">REALLIFE</h1>
    <p class="hero-tagline">Imagine your imagination… or don’t.</p>
</header>

<section class="content">
    <h2>Logline</h2>
    <p>
        A boxer is living his dream life when he glitches into a post-nuclear dystopian reality
        where everyone wears helmets. He must do everything in his power to wake the other Walkers.
    </p>

    <h2>Synopsis</h2>
    <p>
        Chaz, a world-renowned boxer, lives a perfect life with his family. During a flight to Hawai'i,
        he begins glitching into a dystopian world where people march in formation wearing reflective
        helmets that project dream worlds into their minds.
    </p>

    <p>
        Chaz awakens three others trapped in this system and together they attempt to uncover the truth,
        survive "The Gauntlet," and overthrow the ruling power controlling their minds.
    </p>

    <p>
        Their rebellion spirals into a confrontation with the President, who claims the helmet system
        is humanity’s last hope after a nuclear war. Overcome by fear and confusion, Chaz kills the
        President — and then his last remaining ally.
    </p>

    <p>
        As he reaches toward his helmet, BUZZER — and an older, exhausted Chaz awakens in a mall
        Helmet Shop, leaving the audience questioning what was ever real.
    </p>

    <h2>Explore More</h2>
    <p>
        Learn about the writers and the creation of REALLIFE on the 
        <a href="about.html">About the Authors</a> page.
    </p>
</section>

<footer>
    <p>© 2025 REALLIFE – Matt DeTito</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About the Authors – REALLIFE</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<nav>
    <div class="logo">REALLIFE</div>
    <ul>
        <li><a href="index.html">Summary</a></li>
        <li><a href="about.html">About the Authors</a></li>
    </ul>
</nav>

<header class="hero small-hero">
    <h1 class="hero-title">About the Authors</h1>
</header>

<section class="content">
    <h2>The Collective Name: Matt DeTito</h2>
    <p>
        "Matt DeTito" is a unified pseudonym created by merging our names — symbolizing equal
        contribution and shared creativity throughout the writing of REALLIFE.
    </p>

    <h2>Anthony Matarazzo</h2>
    <p>
        Born and raised in Southington, CT. A sports fan, family-oriented, and inspired by
        Rocky IV and producer Avicii.
    </p>

    <h2>Rowan Devlin</h2>
    <p>
        From Newton, MA. A lover of film and music, influenced by directors like Guy Ritchie,
        Quentin Tarantino, and Gus Van Sant.
    </p>

    <h2>Owen Lotito</h2>
    <p>
        From Wrentham, MA. Enjoys golf, 3D design, soccer, and the Harry Potter series.
    </p>

    <h2>Inspiration</h2>
    <p>
        The idea for REALLIFE emerged during a night filled with music, including Daft Punk's
        Random Access Memories. A single question sparked the script:
        “What if helmets showed you your dream world?”
    </p>
</section>

<footer>
    <p>© 2025 REALLIFE – Matt DeTito</p>
</footer>

</body>
</html>
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: #000000;
    color: #e6e6e6;
}

/* Navigation Bar */
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    background: rgba(0, 0, 0, 0.85);
    border-bottom: 1px solid #222;
}

nav .logo {
    color: #00e6ff;
    font-size: 1.5rem;
    letter-spacing: 2px;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #e6e6e6;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #00e6ff;
}

/* Hero Section */
.hero {
    position: relative;
    height: 60vh;
    background-image: url('https://images.unsplash.com/photo-1526401281623-3591d573fd3f?fit=crop&w=1600&q=80');
    background-size: cover;
    background-position: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
}

.small-hero {
    height: 40vh;
}

/* Dark overlay */
.hero::after {
    content: "";
    position: absolute;
    inset: 0;
    background: rgba(0, 0, 0, 0.6);
}

/* Hero Title */
.hero-title {
    position: relative;
    font-size: 4rem;
    color: #00e6ff;
    text-shadow: 0 0 15px #00e6ff;
    z-index: 2;
}

/* Tagline */
.hero-tagline {
    position: relative;
    color: #cccccc;
    font-style: italic;
    margin-top: 10px;
    z-index: 2;
}

/* Main Content */
.content {
    max-width: 900px;
    margin: 40px auto;
    padding: 0 20px;
    line-height: 1.7;
}

h2 {
    color: #00e6ff;
    border-bottom: 1px solid #333;
    padding-bottom: 8px;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    color: #777;
    margin-top: 50px;
    border-top: 1px solid #222;
}
