<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Pengantar Cookies Lucu</title>
    <!-- Link Google Fonts untuk font elegan -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* CSS dengan tema coklat gelap elegan dan cookie */
        body {
            font-family: 'Playfair Display', serif; /* Font elegan serif */
            margin: 0;
            padding: 0;
            background-color: #3E2723; /* Coklat gelap elegan sebagai latar belakang */
            color: #FFF8DC; /* Krem untuk kontras */
            text-align: center;
        }
        header {
            background-color: #5D4037; /* Coklat gelap sedang untuk header */
            padding: 20px;
            border-bottom: 5px solid #4E342E; /* Garis coklat gelap */
        }
        header h1 {
            font-size: 3em;
            margin: 0;
            text-shadow: 2px 2px 4px #1B1B1B; /* Bayangan gelap untuk elegan */
        }
        .hero {
            padding: 50px 20px;
            background-image: url('https://via.placeholder.com/800x400/3E2723/FFF8DC?text=Cookie+Party'); /* Ganti dengan gambar cookie Anda */
            background-size: cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
        }
        .hero h2 {
            font-size: 2.5em;
            margin: 0;
            animation: bounce 2s infinite; /* Animasi lucu */
        }
        .hero p {
            font-size: 1.5em;
            margin: 20px 0;
        }
        .cookie {
            width: 100px;
            height: 100px;
            background-color: #5D4037;
            border-radius: 50%;
            position: relative;
            animation: spin 3s infinite linear; /* Cookie berputar lucu */
        }
        .cookie::before {
            content: '🍪'; /* Emoji cookie */
            font-size: 50px;
            position: absolute;
            top: 25px;
            left: 25px;
        }
        .facts {
            padding: 50px 20px;
            background-color: #4E342E; /* Coklat gelap sedang untuk fakta */
        }
        .fact {
            display: inline-block;
            width: 45%;
            margin: 10px;
            padding: 20px;
            background-color: #5D4037;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.5); /* Bayangan lebih gelap untuk elegan */
        }
        /* CSS untuk mini game */
        .game {
            padding: 50px 20px;
            background-color: #5D4037; /* Coklat gelap sedang untuk game */
        }
        #game-area {
            position: relative;
            width: 100%;
            max-width: 600px;
            height: 400px;
            margin: 0 auto;
            background-color: #4E342E; /* Area game */
            border: 2px solid #FFF8DC;
            border-radius: 10px;
            overflow: hidden;
        }
        .cookie-game {
            position: absolute;
            width: 50px;
            height: 50px;
            background-color: #8D6E63;
            border-radius: 50%;
            cursor: pointer;
            animation: fadeIn 0.5s ease-in;
        }
        .cookie-game::before {
            content: '🍪';
            font-size: 30px;
            position: absolute;
            top: 10px;
            left: 10px;
        }
        #score {
            font-size: 1.5em;
            margin-bottom: 20px;
        }
        footer {
            background-color: #1B1B1B; /* Hitam gelap untuk footer elegan */
            padding: 20px;
            font-size: 1.2em;
        }
        .qr-section {
            margin-top: 20px;
            padding: 20px;
            background-color: #5D4037; /* Coklat gelap sedang untuk QR */
            border-radius: 10px;
            display: inline-block;
        }
        .qr-section img {
            width: 150px; /* Ukuran QR code */
            height: 150px;
            border: 3px solid #FFF8DC; /* Bingkai krem */
            border-radius: 10px;
        }
        button {
            background-color: #8D6E63; /* Coklat pasir gelap */
            color: #FFF8DC;
            border: none;
            padding: 15px 30px;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 20px;
            margin-top: 20px;
        }
        button:hover {
            background-color: #A1887F; /* Lebih terang sedikit */
        }

        /* Animasi lucu */
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }
        @keyframes spin {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <header>
        <h1>🍪 Selamat Datang di Fun with Cherie.vie! 🍪</h1>
    </header>

    <section class="hero">
        <h2>Hai, Dearist Cherie!</h2>
        <p>Nikmati setiap gigitan dari cookies premium yang terbuat dengan bahan-bahan terbaik. Dapatkan kombinasi sempurna antara tekstur luar yang crispy dan kelembutan di dalamnya</p>
        <div class="cookie"></div>
        <button onclick="alert('Yay! Kamu klik cookie! Sekarang makan satu, tapi jangan habis semua ya! 😄')">Mulai Petualangan</button>
    </section>

    <section class="facts">
        <h2>Fakta Lucu tentang Cookies</h2>
        <div class="fact">
            <h3>🍪 Cookie Bisa Terbang?</h3>
            <p>Tidak, tapi kalau kamu makan terlalu banyak, kamu bisa 'terbang' ke dunia mimpi! Zzz...</p>
        </div>
        <div class="fact">
            <h3>🍪 Hari Cookies?</h3>
            <p>Ternyata ada hari Cookies dunia loh! pada tanggal 4 Oktober!</p>
        </div>
        <div class="fact">
            <h3>🍪 Superpower Cookie</h3>
            <p>Mereka bisa membuat hari burukmu jadi manis! Coba deh, makan satu sekarang!</p>
        </div>
        <div class="fact">
            <h3>🍪 Cookie vs. Kue</h3>
            <p>Cookie lebih kecil, tapi lebih lucu! Mereka seperti kue yang pakai topi party.</p>
        </div>
    </section>

    <!-- Bagian Mini Game Baru -->
    <section class="game">
        <h2>🍪 Mini Game: Cookie Catcher! 🍪</h2>
        <p>Klik cookies yang muncul untuk mengumpulkan poin. Jangan biarkan mereka lolos! Skor tertinggi menang!</p>
        <div id="score">Skor: 0</div>
        <div id="game-area"></div>
    </section>

      <footer>
        <p>Terima kasih sudah mampir! Dijamin, sekali makan cookies kami, kamu bakal langsung ngomong: "Kenapa aku nggak coba dari dulu?" 🍪❤️</p>
        
        <!-- Bagian Kode QR Instagram -->
        <div class="qr-section">
            <h3>🍪 Ikuti Kami di Instagram! 🍪</h3>
            <p>Scan kode QR di bawah untuk Instagram dan update terbaru. Jangan lupa follow ya!</p>
            <img src= "cherie.vie_qr.png" alt="Kode QR Instagram" /> <!-- Ganti dengan URL gambar QR asli -->
        </div>
    </footer>

    <script>
        // JavaScript lucu: Tambah interaktivitas
        document.addEventListener('DOMContentLoaded', function() {
            const facts = document.querySelectorAll('.fact');
            facts.forEach(fact => {
                fact.addEventListener('click', function() {
                    alert('Wah, kamu klik fakta lucu! Cookie makin seneng nih! 🍪');
                });
            });
        });

        // JavaScript untuk Mini Game: Cookie Catcher
        let score = 0;
        const gameArea = document.getElementById('game-area');
        const scoreDisplay = document.getElementById('score');

        function createCookie() {
            const cookie = document.createElement('div');
            cookie.classList.add('cookie-game');
            cookie.style.left = Math.random() * (gameArea.clientWidth - 50) + 'px';
            cookie.style.top = Math.random() * (gameArea.clientHeight - 50) + 'px';
            gameArea.appendChild(cookie);

            // Klik cookie untuk tambah skor
            cookie.addEventListener('click', function() {
                score++;
                scoreDisplay.textContent = 'Skor: ' + score;
                cookie.remove();
            });

            // Hapus cookie setelah 2 detik jika tidak diklik
            setTimeout(() => {
                if (cookie.parentNode) {
                    cookie.remove();
                }
            }, 2000);
        }

        // Buat cookie baru setiap 1-2 detik
        setInterval(createCookie, Math.random() * 1000 + 1000);
    </script>
</body>
</html>
