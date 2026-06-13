<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>✨ Arrafah | Biodata 3D Pink ✨</title>
    <!-- Google Fonts & Font Awesome -->
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Quicksand', sans-serif;
            background: linear-gradient(145deg, #ffe6f0 0%, #ffc0d0 100%);
            min-height: 100vh;
            color: #5e2a3e;
            scroll-behavior: smooth;
            overflow-x: hidden;
            position: relative;
        }

        /* background animasi floating hearts + 3D feel */
        body::before {
            content: "❤️💖🌸";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            font-size: 24px;
            opacity: 0.08;
            z-index: 0;
            animation: floatingBubbles 18s infinite linear;
            white-space: pre;
            letter-spacing: 40px;
        }

        @keyframes floatingBubbles {
            0% { transform: translateY(0%) translateX(-10%); opacity: 0.05; }
            100% { transform: translateY(-100%) translateX(10%); opacity: 0.12; }
        }

        /* layer 3d background shapes */
        .bg-3d {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            pointer-events: none;
        }

        .bg-3d .shape {
            position: absolute;
            background: rgba(255, 215, 225, 0.4);
            border-radius: 50%;
            filter: blur(70px);
            animation: float3d 12s infinite alternate ease-in-out;
        }

        .shape1 { width: 350px; height: 350px; top: -100px; left: -80px; background: #ffb7c5; }
        .shape2 { width: 500px; height: 500px; bottom: -150px; right: -100px; background: #ff9eb5; animation-duration: 14s; }
        .shape3 { width: 200px; height: 200px; top: 40%; left: 70%; background: #ffc0e0; animation-duration: 9s; }

        @keyframes float3d {
            0% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            100% { transform: translateY(-40px) translateX(30px) rotate(5deg); }
        }

        /* container utama */
        .container {
            position: relative;
            z-index: 10;
            max-width: 1300px;
            margin: 0 auto;
            padding: 2rem 1.5rem;
        }

        /* menu navigasi feminin */
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 0.8rem;
            margin-bottom: 3rem;
            background: rgba(255, 245, 248, 0.75);
            backdrop-filter: blur(12px);
            border-radius: 60px;
            padding: 0.8rem 2rem;
            box-shadow: 0 8px 25px rgba(255, 105, 150, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.6);
        }

        .menu a {
            text-decoration: none;
            font-weight: 600;
            padding: 0.6rem 1.5rem;
            border-radius: 40px;
            color: #b3416b;
            background: transparent;
            transition: all 0.3s ease;
            font-size: 1.05rem;
            letter-spacing: 0.5px;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }

        .menu a i {
            font-size: 1.1rem;
        }

        .menu a:hover {
            background: #ff92ae;
            color: white;
            transform: translateY(-4px) scale(1.05);
            box-shadow: 0 12px 20px rgba(255, 80, 120, 0.3);
        }

        /* Tilt 3D CARD UTAMA */
        .card-3d-container {
            perspective: 1200px;
            margin-bottom: 3rem;
            display: flex;
            justify-content: center;
        }

        .tilt-card {
            width: 100%;
            max-width: 700px;
            background: rgba(255, 245, 250, 0.95);
            backdrop-filter: blur(8px);
            border-radius: 48px;
            box-shadow: 0 30px 45px rgba(199, 70, 110, 0.25), inset 0 1px 2px rgba(255,255,240,0.8);
            padding: 2rem 2rem 2rem 2rem;
            transition: transform 0.2s ease-out, box-shadow 0.3s;
            transform-style: preserve-3d;
            border: 1px solid rgba(255, 200, 210, 0.9);
            text-align: center;
        }

        /* avatar 3d subtle */
        .avatar {
            width: 130px;
            height: 130px;
            background: linear-gradient(135deg, #ffb7c5, #ff7b9c);
            border-radius: 50%;
            margin: 0 auto 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 20px 35px rgba(255, 80, 120, 0.3);
            transition: all 0.3s;
            border: 3px solid #fff9f9;
        }

        .avatar i {
            font-size: 4rem;
            color: white;
            text-shadow: 2px 4px 12px rgba(0,0,0,0.1);
        }

        .nama {
            font-size: 2.5rem;
            font-weight: 700;
            background: linear-gradient(135deg, #c0426a, #ff85a8);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            margin-bottom: 0.5rem;
            letter-spacing: -0.5px;
        }

        .detail-info {
            margin: 1rem 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 1rem;
        }

        .info-chip {
            background: #fff0f3;
            border-radius: 50px;
            padding: 0.5rem 1.2rem;
            display: inline-flex;
            align-items: center;
            gap: 10px;
            font-weight: 500;
            color: #b13e66;
            box-shadow: 0 4px 8px rgba(0,0,0,0.02);
            border: 1px solid #ffe3ea;
        }

        .info-chip i {
            font-size: 1.2rem;
            color: #ff6f91;
        }

        .biodata-grid {
            margin-top: 1.4rem;
            text-align: left;
            background: #fff6f9;
            border-radius: 36px;
            padding: 1.4rem 1.8rem;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px,1fr));
            gap: 0.8rem;
        }

        .biodata-item {
            display: flex;
            align-items: center;
            gap: 12px;
            font-size: 1rem;
            font-weight: 500;
            color: #682c46;
            border-bottom: 1px dashed #ffc0ce;
            padding: 8px 5px;
        }

        .biodata-item i {
            width: 28px;
            color: #f55b86;
        }

        /* kartu 3d sederhana untuk hobi & sekolah */
        .cards-section {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: center;
            margin: 3rem 0;
        }

        .float-card {
            background: rgba(255, 248, 250, 0.9);
            backdrop-filter: blur(6px);
            border-radius: 40px;
            padding: 1.5rem;
            flex: 1;
            min-width: 250px;
            transition: all 0.4s cubic-bezier(0.2, 0.9, 0.4, 1.1);
            border: 1px solid #ffdae3;
            box-shadow: 0 15px 30px rgba(170, 70, 100, 0.15);
            text-align: center;
            transform: translateY(0px);
        }

        .float-card:hover {
            transform: translateY(-15px) rotate(1deg);
            box-shadow: 0 28px 40px rgba(226, 96, 136, 0.3);
            background: #fff5f8;
            border-color: #ffa5be;
        }

        .float-card i {
            font-size: 2.8rem;
            background: linear-gradient(145deg, #ff839f, #ff5e86);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            margin-bottom: 1rem;
        }

        .float-card h3 {
            font-size: 1.7rem;
            font-weight: 700;
            color: #bd4270;
            margin-bottom: 0.5rem;
        }

        .float-card p {
            font-size: 1rem;
            color: #86455f;
            font-weight: 500;
        }

        .hobby-icons {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-top: 1rem;
            flex-wrap: wrap;
        }

        .hobby-badge {
            background: #ffeef2;
            border-radius: 60px;
            padding: 0.5rem 1.3rem;
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 600;
        }

        /* sekolah & cita card */
        .dream-card {
            background: linear-gradient(125deg, #ffecf0, #ffe0e8);
            border-radius: 42px;
            padding: 1.8rem;
            text-align: center;
            margin-top: 1rem;
        }

        footer {
            text-align: center;
            margin-top: 3rem;
            padding: 1.5rem;
            color: #b35378;
            font-weight: 500;
        }

        /* responsive */
        @media (max-width: 720px) {
            .container {
                padding: 1rem;
            }
            .nama {
                font-size: 1.8rem;
            }
            .menu a {
                padding: 0.3rem 1rem;
                font-size: 0.85rem;
            }
            .biodata-grid {
                grid-template-columns: 1fr;
            }
            .tilt-card {
                padding: 1.5rem;
            }
        }

        /* scroll highlight */
        section {
            scroll-margin-top: 90px;
        }
    </style>
</head>
<body>

<div class="bg-3d">
    <div class="shape shape1"></div>
    <div class="shape shape2"></div>
    <div class="shape shape3"></div>
</div>

<div class="container">
    <!-- Menu navigasi cantik 3D interaktif -->
    <div class="menu">
        <a href="#home"><i class="fas fa-home"></i> <span>Home</span></a>
        <a href="#biodata"><i class="fas fa-id-card"></i> <span>Biodata</span></a>
        <a href="#hobi-section"><i class="fas fa-heart"></i> <span>Hobi</span></a>
        <a href="#sekolah-cita"><i class="fas fa-graduation-cap"></i> <span>Sekolah & Cita-cita</span></a>
        <a href="#fun"><i class="fas fa-star"></i> <span>✨ Vibes ✨</span></a>
    </div>

    <!-- Section home dengan 3D Tilt Card utama biodata -->
    <section id="home">
        <div class="card-3d-container" id="tiltContainer">
            <div class="tilt-card" id="mainCard">
                <div class="avatar">
                    <i class="fas fa-female"></i>
                </div>
                <div class="nama">Arrafah</div>
                <div class="detail-info">
                    <span class="info-chip"><i class="fas fa-cake-candles"></i> 10 Agustus 2009</span>
                    <span class="info-chip"><i class="fas fa-calculator"></i> <span id="ageDisplay"></span> tahun</span>
                </div>
                <div class="biodata-grid">
                    <div class="biodata-item"><i class="fas fa-user-astronaut"></i> <strong>Nama Lengkap:</strong> Arrafah Anindya</div>
                    <div class="biodata-item"><i class="fas fa-calendar-alt"></i> <strong>Tgl Lahir:</strong> 10 Agustus 2009</div>
                    <div class="biodata-item"><i class="fas fa-hard-hat"></i> <strong>Cita-cita:</strong> Civil Engineer</div>
                    <div class="biodata-item"><i class="fas fa-school"></i> <strong>Sekolah:</strong> SMAN 2 JAKARTA</div>
                    <div class="biodata-item"><i class="fas fa-heart"></i> <strong>Hobi:</strong> Memasak, Menulis, Travelling</div>
                    <div class="biodata-item"><i class="fas fa-star-of-life"></i> <strong>Zodiak:</strong> Leo ♌</div>
                </div>
                <div style="margin-top: 1rem; font-style: italic; color: #f26792;">
                    <i class="fas fa-quote-left"></i> Future Civil Engineer with a heart of creativity
                </div>
            </div>
        </div>
    </section>

    <!-- Section Biodata terperinci (opsional pelengkap) -->
    <section id="biodata" style="margin-top: 1rem;">
        <div style="text-align: center; margin-bottom: 1.5rem;">
            <h2 style="font-size: 2rem; background: linear-gradient(120deg,#b6406b, #f2688b); background-clip:text; -webkit-background-clip:text; color:transparent;"><i class="fas fa-roses"></i> Lebih Dekat dengan Arrafah <i class="fas fa-roses"></i></h2>
        </div>
        <div class="float-card" style="max-width: 800px; margin: 0 auto; text-align: left;">
            <p><i class="fas fa-gem"></i> <strong>✨ Tentangku ✨</strong><br>
            Hai! Aku Arrafah, lahir di Jakarta, 10 Agustus 2009. Sekarang aku bersekolah di SMAN 2 JAKARTA. 
            Aku punya mimpi besar menjadi seorang Civil Engineer yang bisa membangun infrastruktur keren dan bermanfaat untuk banyak orang.
            Selain suka hitungan dan desain, aku juga sangat menikmati aktivitas memasak (juru masak dadakan di dapur), menulis cerita dan puisi, serta travelling untuk mengeksplor tempat-tempat aesthetic.</p>
            <div class="hobby-icons" style="justify-content: flex-start; margin-top: 16px;">
                <span class="hobby-badge"><i class="fas fa-utensils"></i> Memasak</span>
                <span class="hobby-badge"><i class="fas fa-pen-fancy"></i> Menulis</span>
                <span class="hobby-badge"><i class="fas fa-plane-departure"></i> Travelling</span>
            </div>
        </div>
    </section>

    <!-- Hobi section khusus -->
    <section id="hobi-section">
        <div class="cards-section">
            <div class="float-card">
                <i class="fas fa-egg"></i>
                <h3>Memasak</h3>
                <p>Menciptakan resep manis & gurih, dari kue hingga comfort food. <i class="fas fa-heart" style="color:#ff5c8a;"></i> Jago membuat risoles dan pasta!</p>
            </div>
            <div class="float-card">
                <i class="fas fa-feather-alt"></i>
                <h3>Menulis</h3>
                <p>Menulis diary, cerpen, dan puisi. Menyalurkan imajinasi ke dalam kata-kata penuh warna.</p>
            </div>
            <div class="float-card">
                <i class="fas fa-globe-asia"></i>
                <h3>Travelling</h3>
                <p>Menjelajah pantai, gunung, dan kota. Next target: jogja & bali! <i class="fas fa-camera"></i></p>
            </div>
        </div>
    </section>

    <!-- Sekolah dan Cita-cita (civil enginner) -->
    <section id="sekolah-cita">
        <div class="dream-card">
            <i class="fas fa-university" style="font-size: 3rem; color:#f25c89;"></i>
            <h2 style="font-size: 1.9rem; margin: 0.5rem 0;">SMAN 2 JAKARTA</h2>
            <p style="font-size: 1.1rem; margin-bottom: 0.5rem;"><i class="fas fa-map-pin"></i> Jakarta Pusat | Kelas 11 (SMA)</p>
            <div style="margin: 1.5rem 0;">
                <i class="fas fa-hard-hat" style="font-size: 2.5rem; color:#f45c88;"></i>
                <h3 style="font-size: 1.8rem; color:#a73c60;">🎯 Civil Engineer</h3>
                <p>Bercita-cita menjadi insinyur sipil yang handal, merancang jembatan, gedung ramah lingkungan, dan menciptakan infrastruktur masa depan yang estetik & kokoh. Selain itu, gabungkan keahlian teknik dengan sentuhan artistik!</p>
            </div>
            <div class="info-chip" style="background:#ffe2ea; margin-top: 8px;">
                <i class="fas fa-trophy"></i> Mimpi besar: Membangun Taman Pintar untuk anak-anak
            </div>
        </div>
    </section>

    <!-- section fun extra: 3d girly message -->
    <section id="fun" style="text-align: center; margin: 3rem 0 1rem;">
        <div style="background: rgba(255,225,235,0.7); backdrop-filter: blur(12px); border-radius: 70px; padding: 1.2rem; display: inline-block; box-shadow: 0 15px 35px rgba(255,105,140,0.2);">
            <i class="fas fa-crown" style="color:#ff789e;"></i>  
            <span style="font-weight: bold; color:#c4567a;"> “Girlboss, Civil Engineer in progress — with love, cooking, and wanderlust”</span>
            <i class="fas fa-crown" style="color:#ff789e;"></i>
        </div>
    </section>

    <footer>
        <i class="fas fa-heart" style="color:#f05c86;"></i> 🩷 Arrafah's Pink Universe 🩷 <i class="fas fa-heart" style="color:#f05c86;"></i><br>
        🌸 biodata 3d | pink aura | future civil eng 🌸
    </footer>
</div>

<script>
    // Hitung umur dari tanggal lahir 10 Agustus 2009
    function calculateAge(birthDate) {
        const today = new Date();
        let birth = new Date(birthDate);
        let age = today.getFullYear() - birth.getFullYear();
        const monthDiff = today.getMonth() - birth.getMonth();
        if (monthDiff < 0 || (monthDiff === 0 && today.getDate() < birth.getDate())) {
            age--;
        }
        return age;
    }

    const birthString = "2009-08-10";
    const age = calculateAge(birthString);
    const ageSpan = document.getElementById("ageDisplay");
    if (ageSpan) ageSpan.innerText = age;

    // 3D TILT EFFECT untuk main card (efek 3D mengikuti mouse)
    const card = document.getElementById("mainCard");
    const container = document.getElementById("tiltContainer");

    if (card && container) {
        container.addEventListener("mousemove", (e) => {
            const rect = card.getBoundingClientRect();
            const x = e.clientX - rect.left;   // posisi X dalam elemen
            const y = e.clientY - rect.top;    // posisi Y dalam elemen
            const centerX = rect.width / 2;
            const centerY = rect.height / 2;
            const rotateY = ((x - centerX) / centerX) * 12;   // maks 12 derajat
            const rotateX = ((centerY - y) / centerY) * 8;     // maks 8 derajat
            card.style.transform = `perspective(1200px) rotateX(${rotateX}deg) rotateY(${rotateY}deg) translateZ(10px)`;
            card.style.transition = "transform 0.08s linear";
        });
        container.addEventListener("mouseleave", () => {
            card.style.transform = "perspective(1200px) rotateX(0deg) rotateY(0deg) translateZ(0px)";
            card.style.transition = "transform 0.5s cubic-bezier(0.2, 0.9, 0.4, 1.1)";
        });
    }

    // smooth scrolling untuk semua menu links
    document.querySelectorAll('.menu a').forEach(anchor => {
        anchor.addEventListener('click', function(e) {
            e.preventDefault();
            const targetId = this.getAttribute('href').substring(1);
            const targetElement = document.getElementById(targetId);
            if (targetElement) {
                targetElement.scrollIntoView({
                    behavior: 'smooth',
                    block: 'start'
                });
            }
        });
    });

    // efek kilau tambahan untuk 3d floating
    const cards = document.querySelectorAll('.float-card');
    cards.forEach(card => {
        card.addEventListener('mouseenter', function() {
            this.style.transform = 'translateY(-15px) rotate(1.5deg) scale(1.02)';
        });
        card.addEventListener('mouseleave', function() {
            this.style.transform = 'translateY(0px) rotate(0deg) scale(1)';
        });
    });
</script>

<!-- tambahan untuk efek sparkling cursor optional, tapi menambah girly 3d feel -->
<style>
    /* heart sparkle di background */
    .container, .menu, .tilt-card, .float-card, .dream-card {
        transition: all 0.25s;
    }
    ::selection {
        background: #ffacc4;
        color: #440022;
    }
    /* tambahan glow */
    .tilt-card:hover {
        box-shadow: 0 40px 60px rgba(223, 86, 126, 0.3);
    }
    .dream-card {
        transition: all 0.4s;
    }
    .dream-card:hover {
        transform: scale(1.01) translateY(-5px);
        background: linear-gradient(125deg, #ffe3ec, #ffd5e1);
        box-shadow: 0 30px 45px #ffb0c4;
    }
    .info-chip i {
        animation: gentleBeat 1.8s infinite;
    }
    @keyframes gentleBeat {
        0% { transform: scale(1);}
        50% { transform: scale(1.12);}
        100% { transform: scale(1);}
    }
    .avatar i {
        filter: drop-shadow(0 6px 8px rgba(216, 62, 102, 0.4));
        animation: floatAvatar 3s infinite alternate;
    }
    @keyframes floatAvatar {
        0% { transform: translateY(0px);}
        100% { transform: translateY(-6px);}
    }
    /* judul section efek 3D */
    h2 i, .menu a i {
        transition: all 0.2s;
    }
</style>
</body>
</html>

