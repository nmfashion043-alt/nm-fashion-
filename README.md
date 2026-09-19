# nm-fashion-
Official website of NM Fashion <!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>N M FASHION | Luxury Fashion</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f8f6f1;
    color:#222;
}

header{
    background:#111;
    color:#d6b56d;
    text-align:center;
    padding:25px 15px;
}

.logo{
    font-size:32px;
    font-weight:bold;
    letter-spacing:5px;
}

.tagline{
    color:#eee;
    margin-top:8px;
    font-size:14px;
}

nav{
    background:#1d1d1d;
    display:flex;
    justify-content:center;
    gap:25px;
    padding:14px;
}

nav a{
    color:white;
    text-decoration:none;
    font-size:14px;
}

.hero{
    min-height:430px;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:40px 20px;
    background:linear-gradient(135deg,#111,#3b3428,#111);
    color:white;
}

.hero h1{
    font-size:42px;
    color:#e0bd73;
    margin-bottom:15px;
}

.hero p{
    font-size:17px;
    line-height:1.7;
}

.btn{
    display:inline-block;
    margin-top:25px;
    padding:13px 25px;
    background:#d6b56d;
    color:#111;
    text-decoration:none;
    font-weight:bold;
    border-radius:4px;
}

section{
    padding:45px 20px;
    max-width:1100px;
    margin:auto;
}

.title{
    text-align:center;
    margin-bottom:30px;
}

.title h2{
    font-size:28px;
    color:#222;
}

.title p{
    margin-top:8px;
    color:#777;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    text-align:center;
    border-radius:8px;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.card .icon{
    font-size:55px;
    margin-bottom:15px;
}

.card h3{
    margin-bottom:10px;
}

.card p{
    color:#666;
    line-height:1.6;
}

.about{
    background:#111;
    color:white;
    max-width:none;
    text-align:center;
}

.about h2{
    color:#d6b56d;
    margin-bottom:15px;
}

.about p{
    max-width:700px;
    margin:auto;
    line-height:1.8;
}

.contact{
    text-align:center;
}

.contact p{
    margin:10px;
    font-size:17px;
}

footer{
    background:#111;
    color:#aaa;
    text-align:center;
    padding:25px;
    font-size:13px;
}

.gold{
    color:#d6b56d;
}

@media(max-width:600px){
    .logo{
        font-size:25px;
    }

    .hero h1{
        font-size:32px;
    }

    nav{
        gap:15px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">♛ N M FASHION</div>
    <div class="tagline">Luxury • Modesty • Style</div>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#collection">Collection</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
    <div>
        <h1>Elegant Fashion</h1>
        <p>
            স্বাগতম N M FASHION-এ<br>
            আপনার পছন্দের আধুনিক ও রুচিশীল পোশাকের বিশ্বস্ত ঠিকানা।
        </p>
        <a href="#collection" class="btn">Explore Collection</a>
    </div>
</div>

<section id="collection">

    <div class="title">
        <h2>Our Collection</h2>
        <p>আপনার পছন্দের কালেকশন বেছে নিন</p>
    </div>

    <div class="products">

        <div class="card">
            <div class="icon">🖤</div>
            <h3>Borka Collection</h3>
            <p>
                Premium borka collection with elegant
                embroidery and modest designs.
            </p>
        </div>

        <div class="card">
            <div class="icon">👔</div>
            <h3>Men's Collection</h3>
            <p>
                Stylish shirts, polo shirts, panjabi
                and other men's fashion.
            </p>
        </div>

        <div class="card">
            <div class="icon">👗</div>
            <h3>Three Piece</h3>
            <p>
                সুন্দর ও আধুনিক ডিজাইনের
                থ্রিপিছ কালেকশন।
            </p>
        </div>

        <div class="card">
            <div class="icon">✨</div>
            <h3>More Fashion</h3>
            <p>
                One piece, two piece, genji
                এবং আরও বিভিন্ন তৈরি পোশাক।
            </p>
        </div>

    </div>

</section>

<section class="about" id="about">

    <h2>About N M FASHION</h2>

    <p>
        N M FASHION একটি আধুনিক পোশাকের ব্র্যান্ড।
        মানসম্মত পোশাক, সুন্দর ডিজাইন এবং
        গ্রাহকের সন্তুষ্টিকে আমরা গুরুত্ব দিই।
    </p>

</section>

<section class="contact" id="contact">

    <div class="title">
        <h2>Contact Us</h2>
        <p>অর্ডার বা বিস্তারিত জানতে যোগাযোগ করুন</p>
    </div>

    <p>📍 <span class="gold">Khalashpir, Pirganj, Rangpur</span></p>
    <p>📱 আমাদের সাথে যোগাযোগ করুন</p>

    <a href="#" class="btn">Message Us</a>

</section>

<footer>
    © 2026 N M FASHION — All Rights Reserved
</footer>

</body>
</html>
