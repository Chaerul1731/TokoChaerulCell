<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chaerul Cell - Top Up Digital Terpercaya</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700;900&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Montserrat', sans-serif;
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 50%, #ff6b6b 100%);
            color: white;
            overflow-x: hidden;
        }
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: url('https://via.placeholder.com/1920x1080/000000/ffffff?text=Background+HP+Icons') no-repeat center/cover;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.3);
            z-index: 1;
        }
        .hero > * {
            z-index: 2;
        }
        .hero h1 {
            font-size: 4rem;
            font-weight: 900;
            text-shadow: 0 0 20px #ff6b6b, 0 0 40px #ff6b6b;
            animation: glow 2s ease-in-out infinite alternate;
        }
        .hero p {
            font-size: 1.5rem;
            margin: 20px 0;
        }
        .badge {
            display: flex;
            gap: 20px;
            margin: 20px 0;
        }
        .badge span {
            background: rgba(255, 255, 255, 0.2);
            padding: 10px 20px;
            border-radius: 20px;
            font-weight: 700;
            animation: pulse 1s infinite;
        }
        .cta-btn {
            background: linear-gradient(45deg, #ff6b6b, #ffd93d);
            color: white;
            border: none;
            padding: 20px 40px;
            font-size: 1.5rem;
            font-weight: 900;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 0 20px #ff6b6b;
            animation: blink 1s infinite, bounce 2s infinite;
            transition: transform 0.3s;
        }
        .cta-btn:hover {
            transform: scale(1.1);
        }
        @keyframes glow {
            from { text-shadow: 0 0 20px #ff6b6b; }
            to { text-shadow: 0 0 30px #ff6b6b, 0 0 40px #ff6b6b; }
        }
        @keyframes blink {
            0%, 50% { opacity: 1; }
            51%, 100% { opacity: 0.8; }
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .promo {
            padding: 50px 20px;
            text-align: center;
            background: rgba(255, 255, 255, 0.1);
            animation: slideIn 1s ease-out;
        }
        .promo h2 {
            font-size: 2rem;
            margin-bottom: 20px;
        }
        .countdown {
            font-size: 1.5rem;
            margin: 20px 0;
        }
        .services {
            padding: 50px 20px;
            text-align: center;
        }
        .services h2 {
            font-size: 2rem;
            margin-bottom: 30px;
        }
        .service-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        .service-item {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            font-size: 1.2rem;
            font-weight: 700;
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.2);
        }
        .advantages {
            padding: 50px 20px;
            text-align: center;
        }
        .advantages h2 {
            font-size: 2rem;
            margin-bottom: 30px;
        }
        .adv-list {
            list-style: none;
            font-size: 1.2rem;
        }
        .adv-list li {
            margin: 10px 0;
        }
        .form {
            padding: 50px 20px;
            text-align: center;
            background: rgba(255, 255, 255, 0.1);
        }
        .form h2 {
            font-size: 2rem;
            margin-bottom: 30px;
        }
        .form input, .form select {
            width: 100%;
            max-width: 300px;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
        }
        .testimonials {
            padding: 50px 20px;
            text-align: center;
        }
        .testimonials h2 {
            font-size: 2rem;
            margin-bottom: 30px;
        }
        .testimonial-slider {
            display: flex;
            overflow: hidden;
            width: 100%;
        }
        .testimonial {
            min-width: 100%;
            font-size: 1.2rem;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            margin: 0 10px;
        }
        .cta-final {
            padding: 50px 20px;
            text-align: center;
            background: rgba(255, 255, 255, 0.1);
        }
        .cta-final h2 {
            font-size: 2rem;
            margin-bottom: 30px;
        }
        .contact {
            padding: 30px 20px;
            text-align: center;
            background: rgba(0, 0, 0, 0.5);
        }
        .contact h2 {
            font-size: 1.5rem;
            margin-bottom: 20px;
        }
        .contact a {
            color: #ffd93d;
            text-decoration: none;
            font-weight: 700;
            margin: 0 10px;
            transition: color 0.3s;
        }
        .contact a:hover {
            color: #ff6b6b;
        }
        .sticky-cta {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: linear-gradient(45deg, #ff6b6b, #ffd93d);
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            font-weight: 900;
            box-shadow: 0 0 20px #ff6b6b;
            animation: bounce 2s infinite;
            cursor: pointer;
            display: none; /* Show on scroll */
        }
        .popup {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: white;
            color: black;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0,0,0,0.5);
            display: none;
            z-index: 1000;
        }
        .popup.show {
            display: block;
        }
        @keyframes slideIn {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .hero p { font-size: 1.2rem; }
            .cta-btn { padding: 15px 30px; font-size: 1.2rem; }
        }
    </style>
</head>
<body>
    <!-- Popup Promo -->
    <div class="popup" id="promoPopup">
        <h3>Promo Spesial!</h3>
        <p>Cashback 10% untuk top up pertama!</p>
        <button onclick="closePopup()">Tutup</button>
    </div>

    <!-- Hero Section -->
    <section class="hero">
        <h1>⚡ TOP UP INSTAN, MASUK SEKETIKA! ⚡</h1>
        <p>Pulsa • Token Listrik • Kuota • E-Wallet • E-Toll</p>
        <div class="badge">
            <span>24 JAM ONLINE</span>
            <span>REAL-TIME</span>
            <span>AMAN</span>
        </div>
        <button class="cta-btn" onclick="alert('Top Up Sekarang!')">🟢 TOP UP SEKARANG</button>
    </section>

    <!-- Promo Flash Sale -->
    <section class="promo">
        <h2>🎁 PROMO FLASH SALE</h2>
        <p>Harga Mulai 5RB 🔥 Cashback Setiap Hari!</p>
        <div class="countdown">Waktu Tersisa: <span id="countdown">00:59:59</span></div>
    </section>

    <!-- Layanan Unggulan -->
    <section class="services">
        <h2>⚡ LAYANAN UNGGULAN</h2>
        <div class="service-grid">
            <div class="service-item">📱 Pulsa Semua Operator</div>
            <div class="service-item">💡 Token PLN</div>
            <div class="service-item">🌐 Paket Data</div>
            <div class="service-item">💰 Top Up DANA / OVO / GoPay / ShopeePay</div>
            <div class="service-item">🚗 E-Toll & E-Money</div>
            <div class="service-item">🎮 Voucher Game</div>
        </div>
    </section>

    <!-- Keunggulan Chaerul Cell -->
    <section class="advantages">
        <h2>💎 KEUNGGULAN CHAERUL CELL</h2>
        <ul class="adv-list">
            <li>⚡ Proses super cepat (hitungan detik)</li>
            <li>🔒 Aman & terpercaya</li>
            <li>💸 Harga murah & transparan</li>
            <li>📱 Bisa diakses kapan saja</li>
        </ul>
    </section>

    <!-- Form Top Up Cepat -->
    <section class="form">
        <h2>🛒 FORM TOP UP CEPAT</h2>
        <select>
            <option>Pilih Layanan</option>
            <option>Pulsa</option>
            <option>Token PLN</option>
            <option>Kuota</option>
            <option>E-Wallet</option>
        </select>
        <input type="text" placeholder="Masukkan Nomor">
        <select>
            <option>Pilih Nominal</option>
            <option>5.000</option>
            <option>10.000</option>
            <option>50.000</option>
        </select>
        <button class="cta-btn" onclick="alert('Bayar & Langsung Masuk!')">BAYAR & LANGSUNG MASUK</button>
    </section>

    <!-- Testimoni Real -->
    <section class="testimonials">
        <h2>🗣️ TESTIMONI REAL</h2>
        <div class="testimonial-slider">
            <div class="testimonial">“Baru bayar, pulsa langsung masuk!” ⭐⭐⭐⭐⭐</div>
            <div class="testimonial">“Murah dan cepat banget” ⭐⭐⭐⭐⭐</div>
            <div class="testimonial">“Layanan top, rekomended!” ⭐⭐⭐⭐⭐</div>
        </div>
    </section>

    <!-- CTA Penutup Agresif -->
    <section class="cta-final">
        <h2>🚨 GAK PERLU NUNGGU, TOP UP SEKARANG!</h2>
        <button class="cta-btn" onclick="alert('Mulai Transaksi!')">🔥 MULAI TRANSAKSI</button>
    </section>

    <!-- Kontak Kami -->
    <section class="contact">
        <h2>📞 HUBUNGI KAMI</h2>
        <p>Butuh bantuan? Chat langsung!</p>
        <a href="https://wa.me/089522913297" target="_blank">📱 WhatsApp: 089522913297</a>
        <a href="tel:083808626971">📞 Telepon: 083808626971</a>
    </section>

    <!-- Sticky CTA -->
    <button class="sticky-cta" onclick="alert('Top Up Cepat!')">🔥 TOP UP</button>

    <script>
        // Popup on load
        window.onload = function() {
            document.getElementById('promoPopup').classList.add('show');
            setTimeout(() => {
                document.getElementById('promoPopup').classList.remove('show');
            }, 5000);
        };

        function closePopup() {
            document.getElementById('promoPopup').classList.remove('show');
        }

        // Countdown Timer
        let time = 3599; // 59:59
        const countdownEl = document.getElementById('countdown');
        setInterval(() => {
            let minutes = Math.floor(time / 60);
            let seconds = time % 60;
            countdownEl.textContent = `${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
            time--;
            if (time < 0) time = 3599;
        }, 1000);

        // Sticky CTA on scroll
        window.addEventListener('scroll', () => {
            const sticky = document.querySelector('.sticky-cta');
            if (window.scrollY > 200) {
                sticky.style.display = 'block';
            } else {
                sticky.style.display = 'none';
            }
        });

        // Animasi scroll
        const sections = document.querySelectorAll('section');
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.animation = 'slideIn 1s ease-out';
                }
            });
        });
        sections.forEach(section => observer.observe(section));
    </script>
</body>
</html>
