<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Halaman Web Pribadi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77a1d3 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        section#showcase {
            min-height: 400px;
            background: url('https://via.placeholder.com/1200x400') no-repeat 0 -400px;
            text-align: center;
            color: #fff;
        }
        section#showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        section#showcase p {
            font-size: 20px;
        }
        section#about, section#portfolio, section#contact {
            padding: 20px;
            margin: 20px 0;
            background: #fff;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 30px 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Nama Lengkap</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">Tentang</a></li>
                    <li><a href="#portfolio">Portofolio</a></li>
                    <li><a href="#contact">Kontak</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section id="showcase">
        <div class="container">
            <h1>Selamat Datang di Halaman Web Pribadi Saya</h1>
            <p>Ini adalah contoh halaman web pribadi sederhana.</p>
        </div>
    </section>
    <section id="about">
        <div class="container">
            <h2>Tentang Saya</h2>
            <p>Deskripsi singkat tentang diri Anda. Anda dapat menyebutkan profesi, hobi, dan informasi penting lainnya di sini.</p>
        </div>
    </section>
    <section id="portfolio">
        <div class="container">
            <h2>Portofolio</h2>
            <p>Di sini Anda dapat menampilkan beberapa contoh pekerjaan atau proyek yang telah Anda selesaikan.</p>
        </div>
    </section>
    <section id="contact">
        <div class="container">
            <h2>Kontak</h2>
            <p>Informasi kontak Anda dapat ditampilkan di sini. Misalnya, alamat email, nomor telepon, atau tautan ke media sosial.</p>
        </div>
    </section>
    <footer>
        <p>Hak Cipta &copy; 2024 Nama Lengkap</p>
    </footer>
</body>
</html>
