<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NextGen Bimbel</title>
  <style>
  :root {
    --primary: #6C63FF;
    --secondary: #00C9A7;
    --bg: #f9fbff;
    --text-dark: #2c3e50;
    --text-light: #ffffff;
  }

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: 'Segoe UI', sans-serif;
    background-color: var(--bg);
    color: var(--text-dark);
  }

  .container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
  }

  .header {
    background-color: var(--primary);
    color: var(--text-light);
    padding: 20px 0;
  }

  .logo {
    font-size: 1.8rem;
    font-weight: bold;
  }

  .logo span {
    color: var(--secondary);
  }

  .nav {
    display: flex;
    gap: 20px;
    margin-top: 10px;
    flex-wrap: wrap;
  }

  .nav a {
    color: var(--text-light);
    text-decoration: none;
    font-weight: 500;
  }

  .nav a:hover {
    text-decoration: underline;
  }

  .hero {
    background: linear-gradient(135deg, var(--primary), var(--secondary));
    color: var(--text-light);
    text-align: center;
    padding: 80px 20px;
  }

  .hero h1 {
    font-size: 2.8rem;
    margin-bottom: 15px;
  }

  .hero p {
    font-size: 1.2rem;
    margin-bottom: 30px;
  }

  .btn {
    background-color: #fff;
    color: var(--primary);
    padding: 12px 25px;
    font-weight: bold;
    border-radius: 8px;
    text-decoration: none;
    transition: all 0.3s;
  }

  .btn:hover {
    background-color: #e0e0ff;
  }

  .programs {
    padding: 60px 0;
    text-align: center;
  }

  .programs h2 {
    font-size: 2rem;
    margin-bottom: 40px;
    color: var(--primary);
  }

  .grid {
    display: grid;
    gap: 30px;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  }

  .card {
    background: #ffffff;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
  }

  .card h3 {
    color: var(--secondary);
    margin-bottom: 10px;
  }

  .testimonial {
    background-color: #eef3ff;
    padding: 60px 0;
    text-align: center;
  }

  .testimonial h2 {
    color: var(--primary);
    margin-bottom: 30px;
  }

  .testi {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    font-style: italic;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
  }

  .testi span {
    display: block;
    margin-top: 10px;
    font-weight: bold;
    color: var(--text-dark);
  }

  a.tbl-pink {
    background: #fc5185;
    border-radius: 20px;
    margin-top: 20px;
    padding: 15px 20px 15px 20px;
    color: #FFFFFF;
    cursor: pointer;
    font-weight: bold;
  }

  a.tbl-pink:hover {
    background: #3f72af;
    text-decoration: none;
  }

  p {
    margin: 10px 0px 10px 0px;
    padding: 10px 0px 10px 0px;
  }

  .tengah {
    text-align: center;
    width: 100%;
  }

  .tutor-list {
    width: 100%;
    position: relative;
    display: flex;
    flex-wrap: wrap;
  }

  .kartu-tutor {
    width: 20%;
    margin: 0 auto;
  }

  .kartu-tutor img {
    width: 80%;
    border-radius: 50%;
  }

  .kartu-tutor p {
    font-family: 'comic sans ms';
    font-weight: 800;
    font-size: 25px;
    text-align: center;
    color: #364f6b;
  }

  .partner-list {
    width: 100%;
    position: relative;
    display: flex;
    flex-wrap: wrap;
  }

  .kartu-partner {
    width: 20%;
    margin: 0 auto;
  }

  .kartu-partner img {
    width: 150px;
    border-radius: 50%;
  }

  #contact {
    background: #dedede;
    padding: 50px 0px 50px 0px;
  }

  .footer {
    width: 100%;
    position: relative;
    display: flex;
    flex-wrap: wrap;
    margin: auto;
  }

  .footer-section {
    width: 20%;
    margin: 0 auto;
  }

  h3 {
    font-family: 'comic sans ms';
    font-weight: 800;
    font-size: 30px;
    margin-bottom: 20px;
    color: #364f6b;
    width: 100%;
    line-height: 50px;
  }

  #copyright {
    text-align: center;
    width: 100%;
    padding: 50px 0px 50px 0px;
    margin-top: 50px;
  }

  @media screen and (max-width: 991.98px) {
    .wrapper {
      width: 90%;
    }
    .logo a {
      display: block;
      width: 100%;
      text-align: center;
    }
    nav .menu {
      width: 100%;
      margin: 0;
    }
    nav .menu ul {
      text-align: center;
      margin: auto;
      line-height: 60px;
    }
    nav .menu ul li {
      display: inline-block;
      float: none;
    }
    section {
      display: block;
    }
    section img {
      display: block;
      width: 100%;
      height: auto;
    }
    .kartu-tutor {
      width: 50%;
    }
    .kartu-partner {
      width: 50%;
    }
  }
  </style>
</head>
<body>

  <header class="header">
    <div class="container">
      <div class="logo">NextGen<span>Bimbel</span></div>
      <nav class="nav">
        <a href="#">Beranda</a>
        <a href="#">Tentang Kami</a>
        <a href="#">Program</a>
        <a href="#">Testimoni</a>
        <a href="#">Kontak</a>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container">
      <h1>Solusi Belajar Terbaik untuk Masa Depan Cemerlang</h1>
      <p>Gabung bersama ribuan pelajar sukses bersama NextGen Bimbel.</p>
      <a href="#" class="btn">Daftar Sekarang</a>
    </div>
  </section>

  <section class="programs">
    <div class="container">
      <h2>Program Unggulan</h2>
      <div class="grid">
        <div class="card">
          <h3>Kelas Intensif UTBK</h3>
          <p>Persiapan masuk PTN favorit dengan materi terfokus & try out rutin.</p>
        </div>
        <div class="card">
          <h3>Les Privat</h3>
          <p>Belajar 1-on-1 sesuai gaya belajar dan kebutuhan kamu.</p>
        </div>
        <div class="card">
          <h3>Kelas Reguler SMP/SMA</h3>
          <p>Pendalaman materi sekolah sesuai kurikulum terbaru.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="testimonial">
    <div class="container">
      <h2>Apa Kata Mereka?</h2>
      <div class="grid">
        <div class="testi">
          <p>“Aku jadi ranking 1 di sekolah setelah ikut NextGen. Materinya mudah dipahami banget!”</p>
          <span>- Nisa, Kelas 9</span>
        </div>
        <div class="testi">
          <p>“NextGen bantu aku lolos SBMPTN! Sistem belajarnya bener-bener beda dan efektif.”</p>
          <span>- Ardi, Alumni 2024</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Tutors Section -->
  <section id="tutors" class="tutors-section">
    <div class="tengah">
      <div class="kolom">
        <p class="deskripsi">Tim Pengajar</p>
        <h2>Pengajar Berpengalaman</h2>
        <p>Kami bekerja sama dengan guru-guru terbaik dari berbagai bidang pelajaran untuk memastikan siswa mendapatkan pembelajaran berkualitas.</p>
      </div>
      <div class="tutor-list">
        <div class="kartu-tutor">
          <img src="dan.jpeg" alt="Nur Hasanah Hasibuan" />
          <p>Nur Hasanah Hasibuan</p>
        </div>
        <div class="kartu-tutor">
          <img src="cani.jpeg" alt="Nia Ramadhani" />
          <p>Nia Ramadhani</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact & Footer -->
  <footer id="contact">
    <div class="wrapper footer">
      <section class="footer-section">
        <h3>NextGen Bimbel</h3>
        <p>Platform bimbingan belajar online yang membantu kamu meraih impian akademikmu!</p>
      </section>
      <section class="footer-section">
        <h3>Tentang Kami</h3>
        <p>NextGen Bimbel hadir dengan semangat meningkatkan kualitas pendidikan Indonesia melalui metode pembelajaran yang inovatif.</p>
      </section>
      <section class="footer-section">
        <h3>Kontak</h3>
        <p>Jl. Pendidikan No. 134, Sihitang</p>
        <p>Kode Pos: 55281</p>
      </section>
      <section class="footer-section">
        <h3>Sosial Media</h3>
        <p><strong>YouTube:</strong> NextGen Bimbel Official</p>
      </section>
    </div>
    <div id="copyright">
      <div class="wrapper">&copy; 2025. <b>NextGen Bimbel</b> All Rights Reserved.</div>
    </div>
  </footer>
</body>
</html>
