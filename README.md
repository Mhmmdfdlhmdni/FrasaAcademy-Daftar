<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Frasa Academy | Pendaftaran</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --biru-muda: #25b6c2;
      --biru-tua: #1a75bc;
      --biru-gradient: linear-gradient(120deg, #25b6c2 0%, #1a75bc 100%);
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(to right, #fdfbfb, #ebedee);
      color: #333;
    }

    nav {
      background: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 999;
    }

    nav img {
      height: 40px;
    }

    .menu {
      display: flex;
      gap: 1.5rem;
    }

    .menu a {
      text-decoration: none;
      color: var(--biru-tua);
      font-weight: 600;
    }

    .hero {
      background: var(--biru-gradient);
      text-align: center;
      padding: 5rem 2rem;
      color: #fff;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.2rem;
      max-width: 600px;
      margin: 0 auto;
    }

    .form-container {
      max-width: 450px;
      background: #fff;
      margin: 3rem auto;
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 8px 24px rgba(0, 0, 0, 0.08);
      border-top: 4px solid var(--biru-muda);
    }

    .form-container h2 {
      text-align: center;
      margin-bottom: 1.5rem;
      color: var(--biru-tua);
    }

    .form-container iframe {
      width: 100%;
      height: 600px;
      border: none;
      border-radius: 0.5rem;
    }

    .chat-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: var(--biru-tua);
      color: #fff;
      border: none;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      font-size: 24px;
      cursor: pointer;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
    }
  </style>
</head>
<body>
  <nav>
    <img src="frasa academy.png" alt="Frasa Academy">
    <div class="menu" id="menu">
      <a href="#">Home</a>
      <a href="#daftar">Daftar</a>
    </div>
  </nav>

  <section class="hero">
    <h1>Selamat Datang di Frasa Academy</h1>
    <p>Tempat terbaik untuk tumbuh, belajar, dan berkembang bersama komunitas yang inspiratif. Bergabunglah bersama kami hari ini.</p>
  </section>

  <section class="form-container" id="daftar">
    <h2>Formulir Pendaftaran</h2>
    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLScxY3H1RSE_SOME_EXAMPLE_LINK/viewform?embedded=true">Memuat…</iframe>
  </section>

  <!-- Live chat button -->
  <a href="https://wa.me/6281234567890" target="_blank">
    <button class="chat-button">💬</button>
  </a>
</body>
</html>
