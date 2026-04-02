
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0" />
  <title>Renungan Paskah</title>

  <style>
    :root {
      --bg: #f8f4ee;
      --card: #ffffff;
      --text: #3b2f2f;
      --subtext: #6d5d53;
      --primary: #7a4b2f;
      --secondary: #b9805d;
      --accent: #d6a97a;
      --soft: #fdf4ed;
      --shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
      --radius: 20px;
      --max-width: 1100px;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      -webkit-tap-highlight-color: transparent;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(180deg, #fcf8f3 0%, #f4ede6 100%);
      color: var(--text);
      line-height: 1.7;
      overflow-x: hidden;
    }

    img, iframe {
      max-width: 100%;
      display: block;
    }

    a {
      text-decoration: none;
    }

    .hero {
      background: linear-gradient(135deg, rgba(88, 48, 28, 0.92), rgba(185, 128, 93, 0.85)),
                  url('https://images.unsplash.com/photo-1504052434569-70ad5836ab65?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
      color: white;
      min-height: 78vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 24px 18px;
      text-align: center;
    }

    .hero-content {
      width: 100%;
      max-width: 760px;
      background: rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(6px);
      -webkit-backdrop-filter: blur(6px);
      padding: 28px 20px;
      border-radius: 24px;
      border: 1px solid rgba(255,255,255,0.15);
      box-shadow: 0 12px 35px rgba(0,0,0,0.18);
    }

    .hero h1 {
      font-size: clamp(2rem, 5vw, 3.4rem);
      line-height: 1.15;
      margin-bottom: 14px;
    }

    .hero p {
      font-size: clamp(0.98rem, 2.8vw, 1.15rem);
      opacity: 0.96;
      margin-bottom: 24px;
    }

    .btn-group {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      justify-content: center;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-height: 48px;
      padding: 14px 22px;
      border-radius: 999px;
      font-weight: 700;
      font-size: 0.98rem;
      transition: 0.25s ease;
      text-align: center;
    }

    .btn-primary {
      background: white;
      color: var(--primary);
    }

    .btn-primary:hover {
      transform: translateY(-2px);
      background: #fff7ef;
    }

    .btn-outline {
      border: 1.5px solid rgba(255,255,255,0.7);
      color: white;
      background: rgba(255,255,255,0.06);
    }

    .btn-outline:hover {
      background: rgba(255,255,255,0.14);
      transform: translateY(-2px);
    }

    .container {
      width: min(92%, var(--max-width));
      margin: auto;
      padding: 50px 0;
    }

    .section-title {
      font-size: clamp(1.6rem, 4vw, 2.3rem);
      text-align: center;
      color: var(--primary);
      margin-bottom: 14px;
    }

    .section-subtitle {
      text-align: center;
      color: var(--subtext);
      max-width: 700px;
      margin: 0 auto 36px;
      font-size: 1rem;
      padding: 0 8px;
    }

    .card {
      background: var(--card);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding: 26px 20px;
      margin-bottom: 24px;
    }

    .card h2 {
      font-size: clamp(1.35rem, 3.5vw, 1.9rem);
      color: var(--primary);
      margin-bottom: 14px;
      line-height: 1.3;
    }

    .card p {
      color: var(--text);
      font-size: 1rem;
    }

    .verse {
      background: var(--soft);
      border-left: 5px solid var(--accent);
      padding: 18px 16px;
      border-radius: 14px;
      margin: 20px 0;
      font-style: italic;
      font-size: 1rem;
    }

    .verse strong {
      display: inline-block;
      margin-bottom: 8px;
      color: var(--primary);
      font-style: normal;
    }

    .quote {
      margin-top: 20px;
      padding: 16px;
      text-align: center;
      font-size: 1.05rem;
      color: var(--primary);
      background: #fffaf6;
      border-radius: 16px;
      border: 1px dashed #e6c7a9;
    }

    .embed-section p {
      color: var(--subtext);
      margin-bottom: 18px;
    }

    .embed-box {
      width: 100%;
      aspect-ratio: 16 / 9;
      border-radius: 18px;
      overflow: hidden;
      box-shadow: 0 10px 24px rgba(0,0,0,0.12);
      background: #000;
    }

    .embed-box iframe {
      width: 100%;
      height: 100%;
      border: none;
    }

    .cta-box {
      text-align: center;
      background: linear-gradient(135deg, #fff7f0, #fffdf9);
      border: 1px solid #f0dcc8;
    }

    .cta-box p {
      color: var(--subtext);
      margin-top: 10px;
      margin-bottom: 20px;
    }

    footer {
      text-align: center;
      padding: 28px 18px 38px;
      color: #8b7c70;
      font-size: 0.95rem;
    }

    /* Tablet */
    @media (min-width: 768px) {
      .hero {
        min-height: 88vh;
        padding: 32px;
      }

      .hero-content {
        padding: 40px 34px;
      }

      .container {
        padding: 70px 0;
      }

      .card {
        padding: 34px 30px;
      }
    }

    /* Smartphone kecil */
    @media (max-width: 480px) {
      .hero {
        min-height: 72vh;
        padding: 18px 14px;
      }

      .hero-content {
        padding: 22px 16px;
        border-radius: 20px;
      }

      .hero h1 {
        font-size: 1.85rem;
      }

      .hero p {
        font-size: 0.95rem;
      }

      .btn-group {
        flex-direction: column;
      }

      .btn {
        width: 100%;
        font-size: 0.96rem;
        padding: 13px 18px;
      }

      .container {
        width: 93%;
        padding: 38px 0;
      }

      .card {
        padding: 22px 16px;
        border-radius: 18px;
      }

      .card p,
      .verse,
      .section-subtitle {
        font-size: 0.97rem;
      }

      .quote {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-content">
      <h1>Renungan Paskah</h1>
      <p>
        Kebangkitan Kristus membawa harapan baru, pemulihan jiwa,
        dan kemenangan atas kegelapan.
      </p>

      <div class="btn-group">
        <a href="#renungan" class="btn btn-primary">Baca Renungan</a>
        <a href="#embed" class="btn btn-outline">Lihat Renungan</a>
      </div>
    </div>
  </section>

  <!-- KONTEN -->
  <main class="container">
    <h2 class="section-title">Tema Paskah</h2>
    <p class="section-subtitle">
      Paskah mengingatkan kita bahwa tidak ada akhir yang terlalu gelap
      bagi Tuhan untuk ubah menjadi awal yang penuh pengharapan.
    </p>

    <!-- RENUNGAN -->
    <section class="card" id="renungan">
      <h2>Yesus Telah Bangkit</h2>
      <p>
        Paskah bukan hanya tentang peristiwa sejarah, tetapi tentang kabar baik
        yang masih hidup sampai hari ini. Kubur yang kosong menjadi tanda bahwa
        Tuhan sanggup mengubah air mata menjadi sukacita, ketakutan menjadi iman,
        dan keputusasaan menjadi pengharapan.
      </p>

      <div class="verse">
        <strong>Matius 28:6</strong><br>
        “Ia tidak ada di sini, sebab Ia telah bangkit, sama seperti yang telah dikatakan-Nya.”
      </div>

      <p>
        Dalam hidup, kadang kita merasa ada bagian hati yang “mati”:
        semangat yang padam, doa yang terasa sunyi, atau harapan yang tertunda.
        Namun Paskah berkata bahwa Tuhan masih bekerja. Apa yang terlihat selesai,
        bisa saja sedang dipersiapkan untuk dibangkitkan kembali oleh-Nya.
      </p>

      <div class="quote">
        “Kubur yang kosong adalah bukti bahwa harapan kita tidak sia-sia.”
      </div>
    </section>

    <!-- EMBED -->
    <section class="card embed-section" id="embed">
      <h2>Renungan / Video Paskah</h2>
      <p>
        Bagian ini bisa kamu isi dengan video YouTube, khotbah, pujian rohani,
        atau halaman renungan lain menggunakan embed link.
      </p>

      <div class="embed-box">
        <iframe
          src="https://www.youtube.com/embed/dQw4w9WgXcQ"
          title="Renungan Paskah"
          allowfullscreen>
        </iframe>
      </div>
    </section>

    <!-- CTA -->
    <section class="card cta-box">
      <h2>Doa Singkat</h2>
      <p>
        Tuhan Yesus, terima kasih untuk kasih-Mu yang menang atas maut.
        Bangkitkan kembali iman, harapan, dan sukacita di dalam hatiku.
        Tolong aku hidup dalam terang kebangkitan-Mu setiap hari. Amin.
      </p>

      <a href="#top" class="btn btn-primary">Kembali ke Atas</a>
    </section>
  </main>

  <footer>
    © 2026 Renungan Paskah • Dibuat dengan damai dan pengharapan
  </footer>

</body>
</html><!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0" />
  <title>Renungan Paskah</title>

  <style>
    :root {
      --bg: #f8f4ee;
      --card: #ffffff;
      --text: #3b2f2f;
      --subtext: #6d5d53;
      --primary: #7a4b2f;
      --secondary: #b9805d;
      --accent: #d6a97a;
      --soft: #fdf4ed;
      --shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
      --radius: 20px;
      --max-width: 1100px;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      -webkit-tap-highlight-color: transparent;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(180deg, #fcf8f3 0%, #f4ede6 100%);
      color: var(--text);
      line-height: 1.7;
      overflow-x: hidden;
    }

    img, iframe {
      max-width: 100%;
      display: block;
    }

    a {
      text-decoration: none;
    }

    .hero {
      background: linear-gradient(135deg, rgba(88, 48, 28, 0.92), rgba(185, 128, 93, 0.85)),
                  url('https://images.unsplash.com/photo-1504052434569-70ad5836ab65?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
      color: white;
      min-height: 78vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 24px 18px;
      text-align: center;
    }

    .hero-content {
      width: 100%;
      max-width: 760px;
      background: rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(6px);
      -webkit-backdrop-filter: blur(6px);
      padding: 28px 20px;
      border-radius: 24px;
      border: 1px solid rgba(255,255,255,0.15);
      box-shadow: 0 12px 35px rgba(0,0,0,0.18);
    }

    .hero h1 {
      font-size: clamp(2rem, 5vw, 3.4rem);
      line-height: 1.15;
      margin-bottom: 14px;
    }

    .hero p {
      font-size: clamp(0.98rem, 2.8vw, 1.15rem);
      opacity: 0.96;
      margin-bottom: 24px;
    }

    .btn-group {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      justify-content: center;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-height: 48px;
      padding: 14px 22px;
      border-radius: 999px;
      font-weight: 700;
      font-size: 0.98rem;
      transition: 0.25s ease;
      text-align: center;
    }

    .btn-primary {
      background: white;
      color: var(--primary);
    }

    .btn-primary:hover {
      transform: translateY(-2px);
      background: #fff7ef;
    }

    .btn-outline {
      border: 1.5px solid rgba(255,255,255,0.7);
      color: white;
      background: rgba(255,255,255,0.06);
    }

    .btn-outline:hover {
      background: rgba(255,255,255,0.14);
      transform: translateY(-2px);
    }

    .container {
      width: min(92%, var(--max-width));
      margin: auto;
      padding: 50px 0;
    }

    .section-title {
      font-size: clamp(1.6rem, 4vw, 2.3rem);
      text-align: center;
      color: var(--primary);
      margin-bottom: 14px;
    }

    .section-subtitle {
      text-align: center;
      color: var(--subtext);
      max-width: 700px;
      margin: 0 auto 36px;
      font-size: 1rem;
      padding: 0 8px;
    }

    .card {
      background: var(--card);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding: 26px 20px;
      margin-bottom: 24px;
    }

    .card h2 {
      font-size: clamp(1.35rem, 3.5vw, 1.9rem);
      color: var(--primary);
      margin-bottom: 14px;
      line-height: 1.3;
    }

    .card p {
      color: var(--text);
      font-size: 1rem;
    }

    .verse {
      background: var(--soft);
      border-left: 5px solid var(--accent);
      padding: 18px 16px;
      border-radius: 14px;
      margin: 20px 0;
      font-style: italic;
      font-size: 1rem;
    }

    .verse strong {
      display: inline-block;
      margin-bottom: 8px;
      color: var(--primary);
      font-style: normal;
    }

    .quote {
      margin-top: 20px;
      padding: 16px;
      text-align: center;
      font-size: 1.05rem;
      color: var(--primary);
      background: #fffaf6;
      border-radius: 16px;
      border: 1px dashed #e6c7a9;
    }

    .embed-section p {
      color: var(--subtext);
      margin-bottom: 18px;
    }

    .embed-box {
      width: 100%;
      aspect-ratio: 16 / 9;
      border-radius: 18px;
      overflow: hidden;
      box-shadow: 0 10px 24px rgba(0,0,0,0.12);
      background: #000;
    }

    .embed-box iframe {
      width: 100%;
      height: 100%;
      border: none;
    }

    .cta-box {
      text-align: center;
      background: linear-gradient(135deg, #fff7f0, #fffdf9);
      border: 1px solid #f0dcc8;
    }

    .cta-box p {
      color: var(--subtext);
      margin-top: 10px;
      margin-bottom: 20px;
    }

    footer {
      text-align: center;
      padding: 28px 18px 38px;
      color: #8b7c70;
      font-size: 0.95rem;
    }

    /* Tablet */
    @media (min-width: 768px) {
      .hero {
        min-height: 88vh;
        padding: 32px;
      }

      .hero-content {
        padding: 40px 34px;
      }

      .container {
        padding: 70px 0;
      }

      .card {
        padding: 34px 30px;
      }
    }

    /* Smartphone kecil */
    @media (max-width: 480px) {
      .hero {
        min-height: 72vh;
        padding: 18px 14px;
      }

      .hero-content {
        padding: 22px 16px;
        border-radius: 20px;
      }

      .hero h1 {
        font-size: 1.85rem;
      }

      .hero p {
        font-size: 0.95rem;
      }

      .btn-group {
        flex-direction: column;
      }

      .btn {
        width: 100%;
        font-size: 0.96rem;
        padding: 13px 18px;
      }

      .container {
        width: 93%;
        padding: 38px 0;
      }

      .card {
        padding: 22px 16px;
        border-radius: 18px;
      }

      .card p,
      .verse,
      .section-subtitle {
        font-size: 0.97rem;
      }

      .quote {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-content">
      <h1>Renungan Paskah</h1>
      <p>
        Kebangkitan Kristus membawa harapan baru, pemulihan jiwa,
        dan kemenangan atas kegelapan.
      </p>

      <div class="btn-group">
        <a href="#renungan" class="btn btn-primary">Baca Renungan</a>
        <a href="#embed" class="btn btn-outline">Lihat Video / Embed</a>
      </div>
    </div>
  </section>

  <!-- KONTEN -->
  <main class="container">
    <h2 class="section-title">Tema Paskah</h2>
    <p class="section-subtitle">
      Paskah mengingatkan kita bahwa tidak ada akhir yang terlalu gelap
      bagi Tuhan untuk ubah menjadi awal yang penuh pengharapan.
    </p>

    <!-- RENUNGAN -->
    <section class="card" id="renungan">
      <h2>Yesus Telah Bangkit</h2>
      <p>
        Paskah bukan hanya tentang peristiwa sejarah, tetapi tentang kabar baik
        yang masih hidup sampai hari ini. Kubur yang kosong menjadi tanda bahwa
        Tuhan sanggup mengubah air mata menjadi sukacita, ketakutan menjadi iman,
        dan keputusasaan menjadi pengharapan.
      </p>

      <div class="verse">
        <strong>Matius 28:6</strong><br>
        “Ia tidak ada di sini, sebab Ia telah bangkit, sama seperti yang telah dikatakan-Nya.”
      </div>

      <p>
        Dalam hidup, kadang kita merasa ada bagian hati yang “mati”:
        semangat yang padam, doa yang terasa sunyi, atau harapan yang tertunda.
        Namun Paskah berkata bahwa Tuhan masih bekerja. Apa yang terlihat selesai,
        bisa saja sedang dipersiapkan untuk dibangkitkan kembali oleh-Nya.
      </p>

      <div class="quote">
        “Kubur yang kosong adalah bukti bahwa harapan kita tidak sia-sia.”
      </div>
    </section>

    <!-- EMBED -->
    <section class="card embed-section" id="embed">
      <h2>Renungan / Video Paskah</h2>
      <p>
        Bagian ini bisa kamu isi dengan video YouTube, khotbah, pujian rohani,
        atau halaman renungan lain menggunakan embed link.
      </p>

      <div class="embed-box">
        <iframe
          src="https://heyzine.com/flip-book/868b5b107f.html"
          title="Renungan Paskah"
          allowfullscreen>
        </iframe>
      </div>
    </section>

    <!-- CTA -->
    <section class="card cta-box">
      <h2>Doa Singkat</h2>
      <p>
        Tuhan Yesus, terima kasih untuk kasih-Mu yang menang atas maut.
        Bangkitkan kembali iman, harapan, dan sukacita di dalam hatiku.
        Tolong aku hidup dalam terang kebangkitan-Mu setiap hari. Amin.
      </p>

      <a href="#top" class="btn btn-primary">Kembali ke Atas</a>
    </section>
  </main>

  <footer>
    © 2026 Renungan Paskah • Dibuat dengan damai dan pengharapan
  </footer>

</body>
</html>
