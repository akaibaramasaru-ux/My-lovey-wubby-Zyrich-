# My-lovey-wubby-Zyrich-
HAPPY BIRTHDAY LOVEY!!
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday, Zyrich 💛</title>

<style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
        font-family: 'Segoe UI', sans-serif;
    }

    body{
        background: linear-gradient(135deg,#fff7c7,#ffe680);
        min-height:100vh;
        display:flex;
        justify-content:center;
        align-items:center;
        padding:20px;
    }

    .card{
        background:white;
        max-width:800px;
        width:100%;
        padding:40px;
        border-radius:25px;
        box-shadow:0 10px 30px rgba(0,0,0,0.1);
        text-align:center;
    }

    h1{
        color:#e0a800;
        margin-bottom:10px;
        font-size:3rem;
    }

    h2{
        color:#555;
        margin-bottom:30px;
        font-weight:normal;
    }

    .letter{
        text-align:left;
        line-height:1.9;
        color:#444;
        font-size:1.1rem;
    }

    .heart{
        font-size:2rem;
        margin:20px 0;
    }

    .footer{
        margin-top:30px;
        color:#888;
        font-style:italic;
    }
</style>
</head>

<body>

<div class="card">

    <h1>Happy Birthday, Zyrich 💛</h1>
    <h2>A little corner of the internet made just for you.</h2>

    <div class="heart">🌼 ☀️ 💛 ☀️ 🌼</div>

    <div class="letter">

        <p>Dear Zyrich,</p>

        <br>

        <p>
        Today is your day, and I hope the world gives back even a small part
        of the kindness, warmth, and happiness you bring to the people around you.
        You deserve moments that make you smile without reason, laugh without
        holding back, and rest without worrying about tomorrow.
        </p>

        <br>

        <p>
        I hope your days ahead are filled with the things you love:
        yellow skies, flowers, books, little comforts, warm meals,
        soft plushies beside you at night, and the people who make
        life feel lighter.
        </p>

        <br>

        <p>
        Thank you for being yourself. The way you care, the way you keep going,
        and the little things that make you uniquely you are more appreciated
        than you probably realize.
        </p>

        <br>

        <p>
        No matter where life takes us, I wanted there to be a place where
        these words could stay—something simple, something honest,
        something made with affection and gratitude.
        </p>

        <br>

        <p>
        May this year bring you peace when you need it, strength when things
        become difficult, and happiness that stays long after today ends.
        </p>

        <br>

        <p>
        Happy Birthday, Zyrich.
        You are loved, appreciated, and celebrated today.
        </p>

        <br>

        <p>
        With all my warm wishes,
        <br><br>
        <strong>— Masaru</strong>
        </p>

    </div>

    <div class="footer">
        Made with love for your special day. 💛
    </div>

</div>

</body>
</html>
<!-- PLAYLIST SECTION -->
<section class="playlist">
    <h2>🎵 Songs That Remind Me of You</h2>

    <iframe style="border-radius:12px"
    src="https://open.spotify.com/embed/playlist/YOUR_PLAYLIST_ID"
    width="100%"
    height="352"
    frameBorder="0"
    allowfullscreen=""
    allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture">
    </iframe>
</section>

<!-- COUNTDOWN -->
<section class="countdown">
    <h2>⏳ Counting Down To Your Birthday</h2>
    <div id="timer"></div>
</section>

<script>
const birthday = new Date("June 5, 2026 00:00:00").getTime();

setInterval(function(){

    const now = new Date().getTime();
    const distance = birthday - now;

    const days = Math.floor(distance/(1000*60*60*24));
    const hours = Math.floor((distance%(1000*60*60*24))/(1000*60*60));
    const minutes = Math.floor((distance%(1000*60*60))/(1000*60));
    const seconds = Math.floor((distance%(1000*60))/1000);

    document.getElementById("timer").innerHTML =
        days + "d " +
        hours + "h " +
        minutes + "m " +
        seconds + "s ";

},1000);
</script>

<!-- 12 FAVORITE THINGS -->
<section class="favorites">

<h2>💛 12 Things That Make Me Think of You</h2>

<div class="item">🌼 Daisies</div>
<div class="item">💛 Yellow everything</div>
<div class="item">🧸 Stuff toys</div>
<div class="item">🎧 Headphones</div>
<div class="item">🍝 Carbonara</div>
<div class="item">✒️ Fountain pens</div>
<div class="item">🎨 Drawing books</div>
<div class="item">👓 Glasses</div>
<div class="item">🏸 Badminton</div>
<div class="item">☀️ Sun plushies</div>
<div class="item">🌻 Flowers</div>
<div class="item">😊 Your smile</div>

</section>

<style>
.playlist,
.countdown,
.favorites{
    margin-top:50px;
}

#timer{
    font-size:2rem;
    color:#e0a800;
    margin-top:10px;
}

.item{
    background:#fff7d6;
    padding:15px;
    margin:10px 0;
    border-radius:12px;
}
</style>
