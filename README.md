# portfolio-saya
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chandra Ardyy | Portfolio</title>
  <meta name="description" content="Portfolio mahasiswa modern dengan HTML, CSS, dan JavaScript" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />
  <link rel="stylesheet" href="coba.css" />
</head>
<body>
  <header class="header">
    <nav class="navbar container">
      <div class="logo">
        <span class="logo-mark">C</span>
        PORTOFOLIO
      </div>

      <ul class="nav-menu" id="navMenu">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>

      <button class="menu-toggle" id="menuToggle" aria-label="Toggle navigation">
        <span></span>
        <span></span>
        <span></span>
      </button>
    </nav>
  </header>

  <main>
    <section id="home" class="hero">
      <div class="container hero-content">
        <div class="hero-text">
          <p class="eyebrow">Mahasiswa & Web Developer</p>
          <h1>
            Halo, saya <span>Chandra Ardyy</span>
          </h1>
          <p class="subtitle">
            Saya membangun website yang modern, rapi, dan mudah digunakan.
          </p>
          <p class="desc">
            Saya adalah mahasiswa yang tertarik pada pengembangan web, desain UI/UX, dan teknologi digital.
            Saya suka membuat solusi yang sederhana namun berdampak.
          </p>
          <div class="cta">
            <a href="#projects" class="btn btn-primary">Lihat Proyek</a>
            <a href="#contact" class="btn btn-secondary">Hubungi Saya</a>
          </div>
        </div>

          <div class="profile-card">
         <div class="profile-circle">
         <img src="my-photo.jpeg" alt="Chandra Ardyy">
         </div>
         </div>
        </div>
      </div>
    </section>

    <section id="about" class="about">
      <div class="container">
        <div class="section-title">
          <p>About Me</p>
          <h2>Tentang Saya</h2>
        </div>

        <div class="about-grid">
          <div class="about-text">
            <p>
              Saya adalah mahasiswa yang sedang menempuh pendidikan di bidang teknologi informasi.
              Saya memiliki minat besar pada web development, UI/UX, dan desain digital.
            </p>
            <p>
              Saya berusaha terus belajar agar bisa menciptakan produk yang tidak hanya
              tampil cantik, tetapi juga fungsional dan bermanfaat bagi pengguna.
            </p>

            <div class="stats">
              <div class="stat-box">
                <strong data-target="5">0</strong>
                <span>Proyek</span>
              </div>
              <div class="stat-box">
                <strong data-target="1">0</strong>
                <span>Tahun Belajar</span>
              </div>
              <div class="stat-box">
                <strong data-target="100">0</strong>
                <span>Semangat</span>
              </div>
            </div>
          </div>

          <div class="about-cards">
            <div class="mini-card">
              <i class="fa-solid fa-graduation-cap"></i>
              <h3>Fakultas</h3>
              <p>Teknik Informatika</p>
            </div>
            <div class="mini-card">
              <i class="fa-solid fa-code"></i>
              <h3>Specialty</h3>
              <p>Web Development</p>
            </div>
            <div class="mini-card">
              <i class="fa-solid fa-heart"></i>
              <h3>Passion</h3>
              <p>Design & Coding</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="skills" class="skills">
      <div class="container">
        <div class="section-title">
          <p>Skills</p>
          <h2>Keahlian Saya</h2>
        </div>

        <div class="skills-grid">
          <div class="skill-card">
            <h3>Frontend</h3>
            <div class="tags">
              <span>HTML5</span>
              <span>CSS3</span>
              <span>JavaScript</span>
              <span>React</span>
            </div>
          </div>

          <div class="skill-card">
            <h3>Backend</h3>
            <div class="tags">
              <span>PHP</span>
              <span>Node.js</span>
              <span>MySQL</span>
              <span>MongoDB</span>
            </div>
          </div>

          <div class="skill-card">
            <h3>Design</h3>
            <div class="tags">
              <span>Figma</span>
              <span>Adobe XD</span>
              <span>Photoshop</span>
            </div>
          </div>

          <div class="skill-card">
            <h3>Tools</h3>
            <div class="tags">
              <span>Git</span>
              <span>GitHub</span>
              <span>VS Code</span>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="projects" class="projects">
      <div class="container">
        <div class="section-title">
          <p>Projects</p>
          <h2>Proyek Terbaik</h2>
        </div>

        <div class="project-grid">
          <article class="project-card">
            <div class="project-thumb thumb-one">
              <i class="fa-solid fa-globe"></i>
            </div>
            <div class="project-body">
              <h3>E-Commerce Store</h3>
              <p>
                Website toko online dengan kategori produk, keranjang belanja, dan dashboard admin sederhana.
              </p>
              <div class="tech">
                <span>React</span>
                <span>Node.js</span>
                <span>MongoDB</span>
              </div>
              <div class="project-links">
                <a href="#">Demo</a>
                <a href="#">GitHub</a>
              </div>
            </div>
          </article>

          <article class="project-card">
            <div class="project-thumb thumb-two">
              <i class="fa-solid fa-list-check"></i>
            </div>
            <div class="project-body">
              <h3>Task Management App</h3>
              <p>
                Aplikasi untuk mengelola tugas harian dengan fitur tambah, hapus, dan status pekerjaan.
              </p>
              <div class="tech">
                <span>JavaScript</span>
                <span>CSS</span>
                <span>LocalStorage</span>
              </div>
              <div class="project-links">
                <a href="#">Demo</a>
                <a href="#">GitHub</a>
              </div>
            </div>
          </article>

          <article class="project-card">
            <div class="project-thumb thumb-three">
              <i class="fa-solid fa-camera"></i>
            </div>
            <div class="project-body">
              <h3>Photography Portfolio</h3>
              <p>
                Portfolio foto responsif dengan galeri interaktif dan desain modern untuk menampilkan karya.
              </p>
              <div class="tech">
                <span>HTML</span>
                <span>CSS</span>
                <span>JS</span>
              </div>
              <div class="project-links">
                <a href="#">Demo</a>
                <a href="#">GitHub</a>
              </div>
            </div>
          </article>
        </div>
      </div>
    </section>

    <section id="contact" class="contact">
      <div class="container">
        <div class="section-title">
          <p>Contact</p>
          <h2>Hubungi Saya</h2>
        </div>

        <div class="contact-grid">
          <form class="contact-form" id="contactForm">
            <div class="form-group">
              <input type="text" placeholder="Nama Anda" required />
            </div>
            <div class="form-group">
              <input type="email" placeholder="Email Anda" required />
            </div>
            <div class="form-group">
              <textarea rows="5" placeholder="Pesan Anda" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary full">Kirim Pesan</button>
          </form>

          <div class="contact-info">
            <div class="info-item">
              <i class="fa-solid fa-envelope"></i>
              <div>
                <h4>Email</h4>
                <p>chandrasabeb@gmail.com</p>
              </div>
            </div>

            <div class="info-item">
              <i class="fa-solid fa-phone"></i>
              <div>
                <h4>Telepon</h4>
                <p>+62 82122331692</p>
              </div>
            </div>

            <div class="info-item">
              <i class="fa-solid fa-location-dot"></i>
              <div>
                <h4>Lokasi</h4>
                <p>Jakarta, Indonesia</p>
              </div>
            </div>

            <div class="socials">
              <a href="#"><i class="fa-brands fa-github"></i></a>
              <a href="#"><i class="fa-brands fa-linkedin"></i></a>
              <a href="#"><i class="fa-brands fa-instagram"></i></a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container">
      <p>© 2025 Chandra Ardyy. Made with <i class="fa-solid fa-heart"></i></p>
    </div>
  </footer>

  <button id="scrollTopBtn" class="scroll-top" aria-label="Kembali ke atas">
    <i class="fa-solid fa-arrow-up"></i>
  </button>

  <script src="coba.js"></script>
</body>
</html>
