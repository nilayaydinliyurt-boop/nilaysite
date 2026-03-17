<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nilay Aydınlıyurt | Official Website</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root { --accent: #d4af37; --bg: #0a0a0a; --card-bg: #151515; }
        body { background: var(--bg); color: #e0e0e0; font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; margin: 0; line-height: 1.6; }
        nav { padding: 25px; text-align: center; border-bottom: 1px solid #222; position: sticky; top: 0; background: rgba(10,10,10,0.95); z-index: 1000; }
        nav a { color: #fff; text-decoration: none; margin: 0 20px; font-size: 0.9rem; letter-spacing: 2px; transition: 0.3s; }
        nav a:hover { color: var(--accent); }
        .hero { text-align: center; padding: 120px 20px; background: linear-gradient(rgba(0,0,0,0.8), rgba(0,0,0,0.8)), url('https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?auto=format&fit=crop&w=1350&q=80'); background-size: cover; border-bottom: 2px solid var(--accent); }
        .hero h1 { font-size: 3.5rem; margin-bottom: 15px; color: #fff; letter-spacing: 4px; }
        .hero p { font-size: 1.2rem; color: var(--accent); letter-spacing: 1px; max-width: 800px; margin: auto; }
        .section { padding: 80px 20px; max-width: 1100px; margin: auto; text-align: center; }
        .section h2 { font-size: 2rem; border-bottom: 1px solid var(--accent); display: inline-block; padding-bottom: 10px; margin-bottom: 40px; }
        .featured-track { background: #000; padding: 40px; border-radius: 10px; border: 1px solid var(--accent); margin-bottom: 50px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 30px; margin-top: 20px; }
        .card { background: var(--card-bg); padding: 30px; border-radius: 4px; transition: 0.3s; border-left: 3px solid transparent; }
        .card:hover { border-left: 3px solid var(--accent); transform: translateY(-5px); }
        .card i { font-size: 35px; color: var(--accent); margin-bottom: 20px; }
        .social-links a { color: #fff; font-size: 28px; margin: 0 15px; transition: 0.3s; display: inline-block; }
        .social-links a:hover { color: var(--accent); transform: scale(1.2); }
        footer { padding: 50px; text-align: center; background: #050505; font-size: 0.8rem; opacity: 0.6; }
        .btn { border: 1px solid var(--accent); color: var(--accent); padding: 12px 30px; text-decoration: none; font-weight: bold; margin-top: 30px; display: inline-block; transition: 0.3s; cursor: pointer; }
        .btn:hover { background: var(--accent); color: #000; }
        @media (max-width: 768px) { .hero h1 { font-size: 2.2rem; } }
    </style>
</head>
<body>

<nav>
    <a href="#about">BIOGRAPHY</a>
    <a href="#music">MUSIC</a>
    <a href="#contact">CONTACT</a>
</nav>

<section class="hero">
    <h1>Nilay Aydınlıyurt</h1>
    <p>Official Website. MESAM member songwriter, composer, and artist.<br>
       <small>Nilay Aydınlıyurt Resmi Web Sitesi. MESAM üyesi söz yazarı, besteci ve sanatçı.</small></p>
</section>

<section id="music" class="section">
    <h2>LATEST RELEASE / YENİ ÇIKIŞ</h2>
    <div class="featured-track">
        <i class="fas fa-play-circle" style="font-size: 50px; color: var(--accent); margin-bottom: 15px;"></i>
        <h3>OYNA BE HAYAT</h3>
        <p>Nilay Aydınlıyurt'un en yeni ve öne çıkan eseri şimdi yayında.</p>
        <a href="https://open.spotify.com/search/Oyna%20Be%20Hayat%20Nilay%20Ayd%C4%B1nl%C4%B1yurt" target="_blank" class="btn">SPOTIFY'DA DİNLE</a>
    </div>

    <h2>DISCOGRAPHY / DİSKOGRAFİ</h2>
    <div class="grid">
        <div class="card">
            <i class="fab fa-spotify"></i>
            <h3>Digital Tracks</h3>
            <p>"Vay Anasını Vay", "Deli Deli", "Adaçayı" ve diğer tüm eserlerim dijital platformlarda.</p>
            <a href="https://open.spotify.com/artist/YOUR_SPOTIFY_ARTIST_ID" target="_blank" class="btn" style="padding: 8px 15px;">Listen Now</a>
        </div>
        <div class="card">
            <i class="fab fa-youtube"></i>
            <h3>Video Projects</h3>
            <p>@melora.x ve @Djmuziktr kanallarındaki en yeni klipler ve DJ setleri.</p>
            <a href="https://youtube.com/@melora.x" target="_blank" class="btn" style="padding: 8px 15px;">Watch on YouTube</a>
        </div>
    </div>
</section>

<section id="about" class="section">
    <h2>Biography / Biyografi</h2>
    <div style="max-width: 800px; margin: auto; text-align: justify;">
        <p><strong>EN:</strong> As an active member of MESAM, Nilay Aydınlıyurt creates a unique bridge between traditional soul and modern digital sounds. From songwriting to complex compositions, her work spans genres including Pop, EDM, and world music. Under the "MeloraX" brand, she manages high-impact digital music projects and YouTube strategies.</p>
        <p><strong>TR:</strong> MESAM asil üyesi olan Nilay Aydınlıyurt, geleneksel duygular ile modern dijital sesler arasında eşsiz bir köprü kurmaktadır. Söz yazarlığından karmaşık bestelere kadar uzanan çalışmaları Pop, EDM ve dünya müziği türlerini kapsamaktadır. "MeloraX" markası altında yüksek etkili dijital müzik projeleri ve YouTube stratejileri yönetmektedir.</p>
    </div>
</section>

<section id="contact" class="section">
    <h2>Connect</h2>
    <div class="social-links">
        <a href="https://www.instagram.com/nilayaydinliyurtofficial/" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="https://youtube.com/@melora.x" target="_blank"><i class="fab fa-youtube"></i></a>
        <a href="mailto:contact@melorax.com"><i class="fas fa-envelope"></i></a>
    </div>
</section>

<footer>
    <p>© 2026 Nilay Aydınlıyurt. All Rights Reserved. / Tüm Hakları Saklıdır.</p>
</footer>

</body>
</html>
