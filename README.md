# Happy-monthsarry-baby
Monthsarry gift
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Monthsary, Baby ❤️</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: "Segoe UI", sans-serif;
    background: linear-gradient(135deg, #fff0f5, #ffe1ec, #fff8fb);
    color: #4a2432;
    min-height: 100vh;
    overflow-x: hidden;
}

/* Floating hearts */
.heart {
    position: fixed;
    bottom: -30px;
    font-size: 22px;
    animation: float 7s linear infinite;
    opacity: 0.6;
    z-index: 0;
}

@keyframes float {
    to {
        transform: translateY(-110vh) rotate(25deg);
        opacity: 0;
    }
}

/* Hero */
.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 30px;
    position: relative;
    z-index: 1;
}

.card {
    max-width: 720px;
    width: 100%;
    background: rgba(255,255,255,0.82);
    backdrop-filter: blur(12px);
    border-radius: 30px;
    padding: 48px 28px;
    box-shadow: 0 20px 60px rgba(190,70,110,0.15);
}

.tiny {
    letter-spacing: 4px;
    text-transform: uppercase;
    font-size: 12px;
    color: #b15a78;
}

h1 {
    font-family: Georgia, serif;
    font-size: clamp(42px, 10vw, 76px);
    margin: 16px 0 8px;
    color: #b72e5b;
}

.subtitle {
    font-size: 18px;
    line-height: 1.7;
    margin: 0 auto 28px;
    max-width: 560px;
}

.date {
    display: inline-block;
    background: white;
    border-radius: 50px;
    padding: 10px 18px;
    color: #a43b61;
    font-weight: 600;
}

button {
    border: 0;
    background: #b72e5b;
    color: white;
    padding: 14px 24px;
    border-radius: 50px;
    font-size: 16px;
    font-weight: 600;
    cursor: pointer;
    margin-top: 22px;
    box-shadow: 0 8px 20px rgba(183,46,91,.22);
}

button:hover {
    transform: scale(1.04);
}

.hidden {
    display: none;
    margin-top: 22px;
    font-size: 18px;
    line-height: 1.7;
}

/* Sections */
section {
    padding: 80px 20px;
    position: relative;
    z-index: 1;
}

.content {
    max-width: 900px;
    margin: auto;
    text-align: center;
}

h2 {
    font-family: Georgia, serif;
    font-size: 38px;
    color: #a92f57;
    margin-bottom: 20px;
}

/* Love letter */
.letter {
    background: white;
    padding: 32px;
    border-radius: 24px;
    text-align: left;
    line-height: 1.9;
    box-shadow: 0 12px 35px rgba(120,40,70,.09);
}

/* Memories */
.memories {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 18px;
    margin-top: 28px;
}

.memory {
    overflow: hidden;
    border-radius: 22px;
    background: white;
    box-shadow: 0 12px 35px rgba(120,40,70,.12);
    transition: .3s;
}

.memory:hover {
    transform: translateY(-7px);
}

.memory img {
    width: 100%;
    height: 300px;
    object-fit: cover;
    display: block;
}

.caption {
    padding: 18px;
    font-weight: 700;
    color: #9d4966;
}

/* Footer */
.footer {
    text-align: center;
    padding: 50px 20px 80px;
    font-family: Georgia, serif;
    font-size: 25px;
    color: #a92f57;
}

/* Mobile */
@media (max-width: 700px) {
    .memories {
        grid-template-columns: 1fr;
    }

    .memory img {
        height: 360px;
    }

    .card {
        padding: 38px 20px;
    }
}
</style>
</head>

<body>

<!-- Floating hearts -->
<div class="heart" style="left:8%;animation-delay:0s">♥</div>
<div class="heart" style="left:25%;animation-delay:2s">♡</div>
<div class="heart" style="left:48%;animation-delay:4s">♥</div>
<div class="heart" style="left:72%;animation-delay:1s">♡</div>
<div class="heart" style="left:90%;animation-delay:3s">♥</div>

<!-- HERO -->
<header class="hero">

<div class="card">

<div class="tiny">
A little website made just for you
</div>

<h1>
Happy Monthsary, Baby ❤️
</h1>

<p class="subtitle">
Another month with you, another month I'm grateful
that I get to call you mine. No matter the distance,
you will always have a special place in my heart.
</p>

<span class="date">
Our Special Day 💗
</span>

<br>

<button onclick="showMessage()">
Open My Message 💌
</button>

<div id="secret" class="hidden">

I love you, baby. Thank you for staying,
understanding me, and loving me through the
good days and the difficult ones.

I may not always find the perfect words,
but I hope you always feel how much you mean to me.

<br><br>

<strong>
I'll keep choosing you.
Today, tomorrow, and every month after this. ❤️
</strong>

</div>

</div>

</header>


<!-- LOVE LETTER -->

<section>

<div class="content">

<h2>
For My Favorite Person ❤️
</h2>

<div class="letter">

<p>
Baby, happy monthsary! 🥺❤️
I just want you to know how thankful I am
that you came into my life.

Every conversation, every laugh,
every reassurance, and even the little moments
we share mean so much to me.
</p>

<br>

<p>
Even when we're far from each other,
you still make me feel loved and cared for.

I know we won't always have perfect days,
but I promise that I'll keep communicating,
understanding, and choosing us.
</p>

<br>

<p>
Thank you for being you.

I hope we get to celebrate many more monthsaries
together until these little celebrations become
years and years of memories.

I love you so much, my baby. 💗
</p>

</div>


<!-- MEMORIES -->

<h2 style="margin-top:65px">
Our Little Memories ✨
</h2>

<div class="memories">

<div class="memory">

<img src="favorite-photo.jpg"
     alt="My favorite photo">

<div class="caption">
My Favorite Photo ❤️
</div>

</div>


<div class="memory">

<img src="cutest-moments.png"
     alt="Our cutest moments">

<div class="caption">
Our Cutest Moments 🥰
</div>

</div>


<div class="memory">

<img src="unforgettable-memory.png"
     alt="A memory I will never forget">

<div class="caption">
Memories I Will Never Forget 💕
</div>

</div>

</div>

</div>

</section>


<!-- FOOTER -->

<div class="footer">

“I wasn't looking for a place to stay.<br>

I was looking for a place to belong,<br>

and I found it in you.” ❤️

</div>


<script>

function showMessage() {

    const message = document.getElementById("secret");

    if (message.style.display === "block") {
        message.style.display = "none";
    } else {
        message.style.display = "block";
    }

}

</script>

</body>
</html>
