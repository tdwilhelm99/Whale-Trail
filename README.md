# Whale-Trail
<!DOCTYPE html>
<html lang="en">
// You can add fun interactive features here!
// For example, display a random meme message:

const taglines = [
    "To the moon, with memes!",
    "Laugh all the way to the blockchain!",
    "Where memes become millions.",
    "HODL your memes!"
];

document.addEventListener('DOMContentLoaded', function() {
    const taglineEl = document.querySelector('.tagline');
    if (taglineEl) {
        taglineEl.textContent = taglines[Math.floor(Math.random() * taglines.length)];
    }
});
body {
    font-family: 'Comic Sans MS', 'Arial', sans-serif;
    background: #fffbe7;
    margin: 0;
    color: #2d2d2d;
}

header {
    text-align: center;
    padding: 2rem 1rem;
    background: #ffeb3b;
}

.logo {
    width: 100px;
    border-radius: 50%;
    margin-bottom: 1rem;
}

.tagline {
    font-size: 1.2rem;
    font-style: italic;
    color: #ff5722;
}

main {
    max-width: 600px;
    margin: 2rem auto;
    padding: 1rem;
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.08);
}

section {
    margin-bottom: 2rem;
}

h2 {
    color: #ff9800;
    margin-bottom: 0.5rem;
}

ul {
    list-style: disc inside;
    padding-left: 0;
}

.social-link {
    display: inline-block;
    margin: 0.5rem 1rem 0.5rem 0;
    padding: 0.5rem 1.2rem;
    background: #03a9f4;
    color: #fff;
    border-radius: 24px;
    text-decoration: none;
    transition: background 0.2s;
}

.social-link:hover {
    background: #0288d1;
}

footer {
    text-align: center;
    padding: 1rem 0;
    background: #ffd600;
    font-size: 0.9rem;
}
    <head>
    <meta charset="UTF-8">
    <title>MemeCoin - The Funniest Token</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="logo.png" alt="MemeCoin Logo" class="logo">
        <h1>MemeCoin</h1>
        <p class="tagline">The Funniest Token on the Blockchain!</p>
    </header>
    <main>
        <section class="about">
            <h2>What is MemeCoin?</h2>
            <p>MemeCoin is a community-driven meme cryptocurrency that brings laughter, fun, and rewards to its holders. Join the movement and take your memes to the moon!</p>
        </section>
        <section class="tokenomics">
            <h2>Tokenomics</h2>
            <ul>
                <li>Supply: 1,000,000,000 MEME</li>
                <li>80% community, 10% team, 10% liquidity</li>
                <li>No taxes, no rug pulls, just memes!</li>
            </ul>
        </section>
        <section class="social">
            <h2>Join the Community</h2>
            <a href="https://twitter.com/" target="_blank" class="social-link">Twitter</a>
            <a href="https://discord.com/" target="_blank" class="social-link">Discord</a>
            <a href="https://t.me/" target="_blank" class="social-link">Telegram</a>
        </section>
    </main>
    <footer>
        <p>© 2025 MemeCoin. All Rights Reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
