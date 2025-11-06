<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Pertamaku</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }
        
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background: #2c3e50;
            color: white;
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
