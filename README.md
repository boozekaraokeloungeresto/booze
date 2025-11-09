<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Booze Karaoke Lounge Resto</title>
    <link href="https://fonts.googleapis.com/css?family=Montserrat:700,400&display=swap" rel="stylesheet">
    <style>
        body {
            background: #111;
            color: #fff;
            font-family: 'Montserrat', Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background: linear-gradient(90deg, #111, #e1b84c);
            color: #fff;
            padding: 40px 24px 24px 24px;
            text-align: center;
        }
        .logo {
            width: 120px;
            height: 120px;
            object-fit: contain;
            background: #fff;
            border-radius: 50%;
            margin: 0 auto 16px auto;
            display: block;
            border: 4px solid #e1b84c;
        }
        h1 {
            font-size: 2.7rem;
            color: #e1b84c;
            margin-bottom: 0.2em;
        }
        h2 {
            color: #e1b84c;
            margin-bottom: 0.3em;
        }
        .section {
            margin: 36px auto;
            max-width: 900px;
            background: #181818;
            border-radius: 12px;
            padding: 32px 20px;
            box-shadow: 0 4px 16px #0008;
        }
        .info-table {
            width: 100%;
            color: #fff;
            border-collapse: collapse;
        }
        .info-table th, .info-table td {
            padding: 10px 8px;
            text-align: left;
            font-weight: 400;
        }
        .info-table th {
            color: #e1b84c;
            width: 120px;
        }
        .contact, .socmed { margin-bottom: 18px; }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 18px;
        }
        .gallery img {
            width: 240px;
            height: 150px;
            object-fit: cover;
            border-radius: 7px;
            border: 2px solid #e1b84c;
            background: #fff;
        }
        .menu-list {
            margin: 0;
            padding-left: 18px;
        }
        .footer {
            background: #1a1a1a;
            color: #e1b84c;
            padding: 14px 0 14px 0;
            text-align: center;
            font-size: 1.1em;
            letter-spacing: 1px;
        }
        a {
            color: #ffdb6b;
            text-decoration: none;
        }
        @media (max-width: 600px) {
            h1 { font-size: 2em; }
            .section { padding: 16px 4px; }
            .gallery img { width: 90vw; height: 40vw; }
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo Booze Karaoke Lounge Resto" class="logo"/>
        <h1>Booze Karaoke Lounge Resto</h1>
        <p>
            Tempat santai karaoke yang nyaman, dengan lounge, pub, dan restoran.<br>
            Pengunjung utama anak muda, konsep modern minimalis.
        </p>
    </header>

    <div class="section">
        <h2>Tentang Kami</h2>
        <table class="info-table">
            <tr>
                <th>Alamat</th>
                <td>Jln Veteran Ruko No 64, Banjarmasin, Kalimantan Selatan</td>
            </tr>
            <tr>
                <th>Jam Buka</th>
                <td>Senin, Selasa, Rabu, Jumat, Sabtu, Minggu</td>
            </tr>
            <tr>
                <th>Kontak</th>
                <td class="contact">082250765476</td>
            </tr>
            <tr>
                <th>Instagram</th>
                <td class="socmed"><a href="https://instagram.com/booze_karaoke_cafe" target="_blank">@booze_karaoke_cafe</a></td>
            </tr>
        </table>
    </div>

    <div class="section">
        <h2>Menu & Layanan</h2>
        <ul class="menu-list">
            <li>Paket Karaoke Ruangan (kapasitas 4, 8, 15 orang)</li>
            <li>Makanan: Ricebowl, Pizza, Snack & Paket keluarga</li>
            <li>Minuman: Kopi, Mocktail, Jus segar, Minuman ringan & alkohol</li>
            <li>Layanan reservasi event & ulang tahun</li>
        </ul>
    </div>

    <div class="section">
        <h2>Galeri</h2>
        <div class="gallery">
            <img src="foto1.jpg" alt="Foto Karaoke Lounge 1"/>
            <img src="foto2.jpg" alt="Foto Karaoke Lounge 2"/>
            <img src="foto3.jpg" alt="Foto Makanan"/>
            <!-- Ganti dengan foto Anda sendiri dengan nama yang sama di folder website -->
        </div>
    </div>

    <footer class="footer">
        &copy; 2025 Booze Karaoke Lounge Resto &ndash; Banjarmasin | Website ini gratis &amp; open source
    </footer>
</body>
</html>            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        
        nav {
            background: #34495e;
            padding: 1rem 0;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        
        nav ul li {
            margin: 0 15px;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 500;
        }
        
        .hero {
            background: #3498db;
            color: white;
            padding: 4rem 0;
            text-align: center;
        }
        
        .content {
            padding: 3rem 0;
        }
        
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .feature {
            background: white;
            padding: 1.5rem;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            margin-top: 2rem;
        }
        
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul li {
                margin: 5px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Selamat Datang di Website Saya</h1>
        </div>
    </header>
    
    <nav>
        <div class="container">
            <ul>
                <li><a href="#home">Beranda</a></li>
                <li><a href="#tentang">Tentang</a></li>
                <li><a href="#layanan">Layanan</a></li>
                <li><a href="#kontak">Kontak</a></li>
            </ul>
        </div>
    </nav>
    
    <section class="hero">
        <div class="container">
            <h2>Website Profesional Anda</h2>
            <p>Solusi digital untuk kebutuhan bisnis Anda</p>
            <a href="#kontak" style="display: inline-block; margin-top: 1rem; padding: 10px 20px; background: #e74c3c; color: white; text-decoration: none; border-radius: 5px;">Hubungi Kami</a>
        </div>
    </section>
    
    <section class="content">
        <div class="container">
            <h2>Layanan Kami</h2>
            <div class="features">
                <div class="feature">
                    <h3>Web Development</h3>
                    <p>Pembuatan website profesional dengan teknologi terkini.</p>
                </div>
                <div class="feature">
                    <h3>Mobile Apps</h3>
                    <p>Pengembangan aplikasi mobile untuk bisnis Anda.</p>
                </div>
                <div class="feature">
                    <h3>Digital Marketing</h3>
                    <p>Strategi pemasaran digital untuk menjangkau lebih banyak pelanggan.</p>
                </div>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <p>&copy; 2023 Nama Perusahaan Anda. Semua hak dilindungi.</p>
        </div>
    </footer>
</body>
</html>
