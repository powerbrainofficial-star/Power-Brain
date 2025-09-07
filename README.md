
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Power Brain - Legendary Channel</title>
<style>
/* ---------- GENERAL STYLES ---------- */
body, html {
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', sans-serif;
    background: #0b0c10;
    color: #fff;
    overflow-x: hidden;
}

h1, h2, h3, p {
    margin: 0;
    padding: 0;
}

a {
    color: #00f7ff;
    text-decoration: none;
    font-weight: bold;
}

a:hover {
    color: #ff00ff;
    text-shadow: 0 0 10px #00f7ff, 0 0 20px #ff00ff;
}

/* ---------- HEADER ---------- */
header {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: relative;
    text-align: center;
    background: linear-gradient(135deg, #0b0c10, #1c1c1c);
    overflow: hidden;
}

header h1 {
    font-size: 3rem;
    text-shadow: 0 0 15px #00f7ff, 0 0 30px #ff00ff;
    margin-bottom: 20px;
}

header p {
    font-size: 1.5rem;
    color: #00f7ffcc;
    max-width: 700px;
}

/* ---------- SCROLLABLE SECTIONS ---------- */
section {
    padding: 80px 20px;
    min-height: 100vh;
    position: relative;
}

/* ---------- NEON BRAIN EMOJI ANIMATION ---------- */
.emoji-brain {
    font-size: 50px;
    position: absolute;
    animation: floatBrain linear infinite;
}

@keyframes floatBrain {
    0% { transform: translateY(0) rotate(0deg); }
    25% { transform: translateY(-30px) rotate(15deg); }
    50% { transform: translateY(0) rotate(0deg); }
    75% { transform: translateY(30px) rotate(-15deg); }
    100% { transform: translateY(0) rotate(0deg); }
}

/* ---------- NEON CARD ---------- */
.card {
    background: rgba(0,0,0,0.8);
    border: 2px solid #00f7ff;
    border-radius: 20px;
    padding: 30px;
    margin: 20px auto;
    max-width: 800px;
    box-shadow: 0 0 20px #00f7ff, 0 0 40px #ff00ff;
    transition: transform 0.3s, box-shadow 0.3s;
}

.card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 30px #00f7ff, 0 0 60px #ff00ff;
}

/* ---------- BUTTON ---------- */
.btn {
    display: inline-block;
    padding: 15px 30px;
    border-radius: 50px;
    border: 2px solid #00f7ff;
    color: #00f7ff;
    background: transparent;
    font-weight: bold;
    font-size: 16px;
    cursor: pointer;
    margin-top: 20px;
    position: relative;
    overflow: hidden;
    transition: 0.3s;
}

.btn::before {
    content: '';
    position: absolute;
    top: 0;
    left: -50%;
    width: 50%;
    height: 100%;
    background: rgba(255,255,255,0.2);
    transform: skewX(-25deg);
    transition: 0.5s;
}

.btn:hover::before {
    left: 125%;
}

.btn:hover {
    color: #ff00ff;
    border-color: #ff00ff;
    box-shadow: 0 0 15px #00f7ff, 0 0 30px #ff00ff;
}

/* ---------- TEXT STYLES ---------- */
.section-title {
    font-size: 2.5rem;
    margin-bottom: 30px;
    text-align: center;
    color: #00f7ff;
    text-shadow: 0 0 10px #00f7ff, 0 0 20px #ff00ff;
}

.section-content p {
    font-size: 1.2rem;
    line-height: 1.8;
    color: #ffffffcc;
}

/* ---------- VIDEO CARD ---------- */
.video-card {
    background: rgba(0,0,0,0.7);
    border: 1px solid #00f7ff;
    border-radius: 15px;
    padding: 15px;
    margin: 20px 0;
    transition: transform 0.3s, box-shadow 0.3s;
}

.video-card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 25px #00f7ff, 0 0 50px #ff00ff;
}

/* ---------- FLOATING EMOJIS ---------- */
.floating-emoji {
    position: absolute;
    font-size: 40px;
    animation: floatEmoji linear infinite;
}

@keyframes floatEmoji {
    0% { transform: translateY(0) rotate(0deg); }
    25% { transform: translateY(-20px) rotate(20deg); }
    50% { transform: translateY(0) rotate(0deg); }
    75% { transform: translateY(20px) rotate(-20deg); }
    100% { transform: translateY(0) rotate(0deg); }
}

/* ---------- FOOTER ---------- */
footer {
    padding: 50px 20px;
    text-align: center;
    background: #0b0c10;
    border-top: 2px solid #00f7ff;
}

footer p {
    font-size: 1rem;
    color: #00f7ffcc;
    margin-bottom: 10px;
}

footer a {
    color: #00f7ff;
    font-weight: bold;
}
</style>
</head>
<body>

<!-- HEADER -->
<header>
    <div class="emoji-brain" style="top: 10%; left: 10%;">🧠</div>
    <div class="emoji-brain" style="top: 20%; right: 15%;">🧠</div>
    <h1>Power Brain</h1>
    <p>The ultimate channel for mind-blowing facts, science mysteries, and amazing animal truths. Every video is designed to expand your brain power and curiosity! 💡</p>
    <a href="https://www.youtube.com/@the_power_brain" target="_blank" class="btn">Subscribe 🔔</a>
</header>

<!-- ABOUT SECTION -->
<section>
    <h2 class="section-title">About Power Brain</h2>
    <div class="section-content">
        <div class="card">
            <p>Power Brain is a legendary YouTube channel providing fascinating facts about science, animals, and the world around us. Every video is crafted to inspire curiosity and expand knowledge. 🧬🌌</p>
        </div>
        <div class="card">
            <p>With regular uploads and incredible research, the channel is perfect for anyone who loves learning amazing facts in an entertaining way. 🚀</p>
        </div>
    </div>
</section>

<!-- VIDEOS SECTION -->
<section>
    <h2 class="section-title">Featured Videos</h2>
    <div class="section-content">
        <div class="video-card">
            <p>🧪 <strong>Top 10 Mind-Blowing Science Facts</strong></p>
            <p>Discover the universe's secrets in under 10 minutes!</p>
        </div>
        <div class="video-card">
            <p>🐾 <strong>Animal Facts You Didn't Know</strong></p>
            <p>From deep-sea creatures to exotic birds, prepare to be amazed!</p>
        </div>
        <div class="video-card">
            <p>🌌 <strong>Hidden Facts About Our Universe</strong></p>
            <p>Expand your brain with cosmic knowledge and mysteries.</p>
        </div>
    </div>
</section>

<!-- FUN FACTS SECTION -->
<section>
    <h2 class="section-title">Fun Brain Animations</h2>
    <div class="section-content">
        <p>Keep your brain active! Scroll, explore, and watch as emojis dance, brain icons float, and neon lights shimmer. 🧠✨ Every scroll is a mini adventure!</p>
        <div class="emoji-brain" style="top: 10%; left: 40%;">🧠</div>
        <div class="emoji-brain" style="top: 30%; left: 70%;">🧠</div>
        <div class="emoji-brain" style="top: 60%; left: 20%;">🧠</div>
    </div>
</section>

<!-- CONNECT SECTION -->
<section>
    <h2 class="section-title">Connect & Explore</h2>
    <div class="section-content">
        <div class="card">
            <p>Follow Power Brain on YouTube and join a community of knowledge seekers. Every video is crafted to make you smarter, more curious, and always entertained. 🔗🖇️</p>
            <a href="https://www.youtube.com/@the_power_brain" target="_blank" class="btn">Subscribe Now</a>
        </div>
    </div>
</section>

<!-- FLOATING EMOJIS -->
<div class="floating-emoji" style="top:80%; left:10%;">💡</div>
<div class="floating-emoji" style="top:70%; left:50%;">🧬</div>
<div class="floating-emoji" style="top:50%; left:80%;">🦄</div>
<div class="floating-emoji" style="top:30%; left:30%;">⚡</div>

<!-- FOOTER -->
<footer>
    <p>Business Enquiries: <a href="mailto:powerbrainofficial@gmail.com">powerbrainofficial@gmail.com</a></p>
    <p>&copy; 2025 Power Brain. All rights reserved.</p>
</footer>

<script>
// Animate random movement for floating emojis
const emojis = document.querySelectorAll('.floating-emoji');
emojis.forEach(emoji => {
    let x = Math.random()*100;
    let y = Math.random()*100;
    let dx = (Math.random()-0.5)*0.5;
    let dy = (Math.random()-0.5)*0.5;
    function animate() {
        x += dx;
        y += dy;
        if(x<0 || x>90) dx*=-1;
        if(y<0 || y>90) dy*=-1;
        emoji.style.left = x + "%";
        emoji.style.top = y + "%";
        requestAnimationFrame(animate);
    }
    animate();
});
</script>

</body>
</html>

