<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Selamat Ulang Tahun Audry 💖</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;500&display=swap" rel="stylesheet">
  <style>
    html, body {
      height: 100%;
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #ffb6c1; /* Warna pink muda */
      overflow: hidden;
      color: #fff;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      padding: 3em 2em;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      min-height: 100vh;
      box-sizing: border-box;
      position: relative;
      z-index: 1;
    }

    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 4em;
      margin-bottom: 0.5em;
      animation: fadeInDown 1.5s ease-out;
    }

    .message {
      width: 100%;
      max-width: 900px;
      background: rgba(255, 255, 255, 0.15);
      padding: 25px;
      border-radius: 20px;
      font-size: 1.3em;
      line-height: 1.8;
      margin-bottom: 2em;
      backdrop-filter: blur(5px);
      animation: fadeIn 2s ease-in-out;
      white-space: pre-line;
    }

    .message[contenteditable="true"] {
      outline: none;
      color: #fff;
    }

    .slideshow {
      width: 100%;
      max-width: 900px;
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 0 25px rgba(0,0,0,0.4);
      margin-bottom: 2em;
      animation: fadeIn 3s ease-in-out;
    }

    .slideshow img {
      width: 100%;
      display: none;
      border-radius: 20px;
    }

    .slideshow img.active {
      display: block;
    }

    audio {
      display: none;
    }

    footer {
      margin-top: auto;
      font-size: 0.9em;
      color: #fff;
      padding: 1em;
      animation: fadeInUp 2s ease-in;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    @keyframes fadeInDown {
      from {opacity: 0; transform: translateY(-30px);}
      to {opacity: 1; transform: translateY(0);}
    }

    @keyframes fadeInUp {
      from {opacity: 0; transform: translateY(30px);}
      to {opacity: 1; transform: translateY(0);}
    }

    /* Efek bunga */
    .flower {
      position: absolute;
      width: 30px;
      height: 30px;
      background: url('https://cdn-icons-png.flaticon.com/512/826/826953.png') no-repeat center/contain;
      animation: fall 10s linear infinite;
      pointer-events: none;
      z-index: 0;
    }

    @keyframes fall {
      0% {
        transform: translateY(-100vh) translateX(0) rotate(0deg);
        opacity: 1;
      }
      100% {
        transform: translateY(100vh) translateX(20px) rotate(360deg);
        opacity: 0;
      }
    }

    @media (max-width: 768px) {
      h1 {
        font-size: 2.8em;
      }

      .message {
        font-size: 1em;
        padding: 15px;
      }

      .slideshow {
        width: 95%;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Selamat Ulang Tahun Audry 💖</h1>

    <div class="message" contenteditable="true">
Hai Audry sayang, 💌

Di hari spesialmu ini, aku ingin kamu tahu bahwa kamu adalah sosok yang luar biasa. Senyumanmu bisa mencerahkan hariku, tawamu adalah melodi paling indah, dan kehadiranmu selalu jadi kebahagiaan yang tak ternilai.

Seperti lagu Bruno Mars bilang: "You're amazing just the way you are." 🎶

Tetaplah jadi kamu yang apa adanya, karena kamu begitu istimewa. Semoga ulang tahunmu membawa banyak cinta, harapan baru, dan mimpi-mimpi yang jadi nyata.

Dengan cinta seluas langit,
💗 [Namamu]
    </div>

    <div class="slideshow">
      <img src="foto1.jpg" class="active">
      <img src="foto2.jpg">
      <img src="foto3.jpg">
    </div>

    <footer>
      Dibuat khusus untuk Audry oleh seseorang yang sangat menyayanginya 💕
    </footer>
  </div>

  <audio autoplay loop>
    <source src="just-the-way-you-
::contentReference[oaicite:13]{index=13}
 
