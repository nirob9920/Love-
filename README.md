# Love-
Any
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY Love এর ভালোবাসা 💗🌹</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;600;700&display=swap');
        body { font-family: 'Hind Siliguri', sans-serif; }
        .heart-float {
            position: absolute;
            font-size: 25px;
            color: #ff4d94;
            animation: floatHeart 8s linear infinite;
            pointer-events: none;
            z-index: 10;
        }
        @keyframes floatHeart {
            0% { transform: translateY(100vh) rotate(0deg); opacity: 1; }
            100% { transform: translateY(-100vh) rotate(720deg); opacity: 0; }
        }
        .hero-bg { background: linear-gradient(135deg, #1a0033, #4a0022); }
        #intro { z-index: 9999; }
        .video-container {
            box-shadow: 0 25px 50px -12px rgb(0 0 0 / 0.6);
        }
    </style>
</head>
<body class="bg-black text-white overflow-x-hidden">

    <!-- Dramatic Intro -->
    <div id="intro" class="fixed inset-0 bg-black flex items-center justify-center">
        <canvas id="canvas" width="1200" height="700" class="max-w-full max-h-full"></canvas>
    </div>

    <!-- Main Website -->
    <div id="main-content" class="hidden">

        <!-- Hero Section -->
        <section class="hero-bg min-h-screen flex items-center relative">
            <div class="absolute inset-0 overflow-hidden" id="hearts"></div>
            
            <div class="max-w-4xl mx-auto text-center px-6 relative z-10">
                <div class="mb-8">
                    <i class="fas fa-rose text-8xl text-pink-400 animate-pulse"></i>
                </div>
                <h1 class="text-7xl md:text-8xl font-bold mb-4 tracking-wider">
                    MY Love 💗
                </h1>
                <p class="text-4xl md:text-5xl font-medium text-pink-300 mb-8">
                    আমি তোমাকে অনেক ভালবাসি Lamisa
                </p>
                <p class="text-2xl md:text-3xl text-pink-200 mb-12 max-w-2xl mx-auto">
                    রাজশাহী থেকে তোমার জন্য একটা আকাশভরা ভালোবাসা 🌹<br>
                    তুমি আমার হৃদয়ের রানী 💖
                </p>
                
                <button onclick="sendLove()" 
                        class="bg-pink-600 hover:bg-pink-700 transition-all px-12 py-6 rounded-3xl text-3xl font-semibold flex items-center gap-4 mx-auto shadow-2xl shadow-pink-500/50">
                    <i class="fas fa-heart"></i>
                    তোমাকে আরেকটু ভালবাসি বলি
                </button>
                
                <div class="mt-16 text-pink-400 text-xl flex justify-center gap-8">
                    <div>🌹 রাজশাহী</div>
                    <div>💗 ২০২৬</div>
                    <div>🌹 তোমার জন্য</div>
                </div>
            </div>
        </section>

        <!-- Love Letter -->
        <section class="py-20 bg-gradient-to-b from-pink-950 to-black">
            <div class="max-w-3xl mx-auto px-6 text-center">
                <h2 class="text-5xl font-bold mb-12 text-pink-300">আমার ছোট্ট চিঠি তোমাকে 🌹</h2>
                <div class="bg-white/10 backdrop-blur-xl p-12 rounded-3xl border border-pink-300/30 text-xl leading-relaxed">
                    প্রিয় Lamisa,<br><br>
                    তোমাকে দেখলেই আমার হৃদয়টা লাফিয়ে ওঠে। তুমি আমার জীবনের সবচেয়ে সুন্দর স্বপ্ন, আমার চিরকালের ভালোবাসা।<br><br>
                    তোমার সাথে প্রতিটি মুহূর্ত আমি হাসি, আমি স্বপ্ন দেখি, আমি তোমাকে আরও বেশি করে ভালোবাসি।<br><br>
                    এই ওয়েবসাইটটা শুধু তোমার জন্য বানিয়েছি। যতবার খুলবে, ততবার মনে হবে আমি তোমার পাশেই আছি, তোমার হাত ধরে আছি।<br><br>
                    চিরকাল তোমার,<br>
                    <span class="text-3xl text-pink-400">MY Love 💗</span>
                </div>
            </div>
        </section>

        <!-- New Cute Anime Girl Video Section -->
        <section class="py-20 bg-black">
            <div class="max-w-5xl mx-auto px-6 text-center">
                <h2 class="text-5xl font-bold mb-4 text-pink-300">Lamisa, তোমার জন্য স্পেশাল অ্যানিমে ভিডিও 💗</h2>
                <p class="text-pink-400 text-xl mb-10">যেমন এই মেয়েটা সুন্দর, তেমনি তুমিও আমার কাছে সবচেয়ে সুন্দর 🌹</p>
                
                <div class="video-container mx-auto rounded-3xl overflow-hidden border border-pink-400/30">
                    <video 
                        src="special-video.mp4" 
                        controls 
                        autoplay 
                        loop 
                        muted 
                        playsinline
                        class="w-full h-auto mx-auto block">
                        তোমার ব্রাউজার ভিডিও সাপোর্ট করে না।
                    </video>
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="py-10 text-center border-t border-pink-900">
            <p class="text-pink-400">Made with infinite love by MY Love for Lamisa 💖</p>
            <p class="text-sm mt-2 text-pink-500">রাজশাহী, বাংলাদেশ • ২০২৬</p>
        </footer>
    </div>

    <script>
        // Floating hearts
        function createHeart() {
            const heart = document.createElement('div');
            heart.className = 'heart-float';
            heart.innerHTML = ['💗', '🌹', '💖', '❤️'][Math.floor(Math.random() * 4)];
            heart.style.left = Math.random() * 100 + 'vw';
            heart.style.animationDuration = (Math.random() * 6 + 7) + 's';
            document.getElementById('hearts').appendChild(heart);
            setTimeout(() => heart.remove(), 15000);
        }
        setInterval(createHeart, 200);

        function sendLove() {
            for (let i = 0; i < 150; i++) {
                setTimeout(() => {
                    const confetti = document.createElement('div');
                    confetti.style.position = 'fixed';
                    confetti.style.zIndex = '9999';
                    confetti.style.left = Math.random() * 100 + 'vw';
                    confetti.style.top = '-20px';
                    confetti.style.fontSize = '25px';
                    confetti.textContent = ['💗', '🌹', '💖', '❤️'][Math.floor(Math.random() * 4)];
                    document.body.appendChild(confetti);
                    confetti.animate([{ transform: 'translateY(0) rotate(0deg)' }, { transform: `translateY(\( {window.innerHeight + 100}px) rotate( \){Math.random() * 1000}deg)` }], { duration: Math.random() * 4000 + 3000, easing: 'cubic-bezier(0.25, 0.1, 0.25, 1)' });
                    setTimeout(() => confetti.remove(), 7000);
                }, i * 2);
            }
            alert("💗🌹 তোমাকে আরও অনেক বেশি ভালবাসি Lamisa! এই ভালোবাসা চিরকাল থাকুক 💖");
        }

        // Cinematic Gun Intro (আগের মতোই)
        const canvas = document.getElementById('canvas');
        const ctx = canvas.getContext('2d');
        let particles = [];
        let gunX = 80;
        let gunY = canvas.height / 2 + 30;
        let recoilOffset = 0;
        let heartX = canvas.width / 2 + 80;
        let heartY = canvas.height / 2 + 20;
        let bulletX = gunX + 180;
        let shooting = false;
        let exploded = false;
        let flash = 0;

        class Particle {
            constructor(x, y) {
                this.x = x; this.y = y;
                this.size = Math.random() * 14 + 9;
                this.speedX = Math.random() * 16 - 8;
                this.speedY = Math.random() * 14 - 10;
                this.color = ['#ff4d94', '#ff1a75', '#ff99cc', '#ffeb3b'][Math.floor(Math.random() * 4)];
                this.life = 110;
            }
            update() { this.x += this.speedX; this.y += this.speedY; this.speedY += 0.35; this.life--; }
            draw() {
                ctx.globalAlpha = this.life / 110;
                ctx.font = `${this.size}px Arial`;
                ctx.fillText('💔', this.x, this.y);
            }
        }

        function drawRealisticGun() {
            ctx.save();
            ctx.translate(gunX + recoilOffset, gunY);
            ctx.rotate(-0.08);
            ctx.fillStyle = '#2c2c2c'; ctx.beginPath(); ctx.moveTo(30,45); ctx.lineTo(28,105); ctx.lineTo(68,108); ctx.lineTo(75,52); ctx.fill();
            ctx.fillStyle = '#1f1f1f'; ctx.fillRect(55,22,135,42);
            ctx.fillStyle = '#3a3a3a'; ctx.fillRect(175,29,125,19);
            ctx.fillStyle = '#555'; ctx.fillRect(70,18,120,8);
            ctx.strokeStyle = '#1a1a1a'; ctx.lineWidth = 6; ctx.beginPath(); ctx.moveTo(95,48); ctx.quadraticCurveTo(105,72,80,75); ctx.stroke();
            ctx.fillStyle = '#222'; ctx.fillRect(88,50,9,28);
            ctx.fillStyle = '#ffd700'; ctx.fillRect(240,24,10,6);
            ctx.restore();
        }

        function drawMuzzleFlash() {
            if (flash <= 0) return;
            ctx.save();
            ctx.translate(gunX + 295 + recoilOffset, gunY + 8);
            ctx.fillStyle = `rgba(255, 220, 50, ${flash})`;
            ctx.shadowBlur = 60; ctx.shadowColor = '#ffeb3b';
            ctx.fillRect(0, -22, 55, 44);
            ctx.restore();
        }

        function drawBullet() {
            if (!shooting) return;
            ctx.strokeStyle = '#ffeb3b'; ctx.lineWidth = 7; ctx.shadowBlur = 25; ctx.shadowColor = '#ffeb3b';
            ctx.beginPath(); ctx.moveTo(bulletX - 40, gunY + 12); ctx.lineTo(bulletX, gunY + 12); ctx.stroke();
            ctx.fillStyle = '#fff'; ctx.fillRect(bulletX, gunY + 7, 22, 10);
        }

        function drawHeart() {
            if (exploded) return;
            ctx.save();
            const pulse = Math.sin(Date.now() / 180) * 12 + 135;
            ctx.font = `${pulse}px Arial`;
            ctx.fillText('❤️', heartX - 70, heartY + 45);
            ctx.restore();
        }

        function animateIntro() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            const grad = ctx.createLinearGradient(0, 0, canvas.width, canvas.height);
            grad.addColorStop(0, '#1a0033'); grad.addColorStop(1, '#2a001a');
            ctx.fillStyle = grad; ctx.fillRect(0, 0, canvas.width, canvas.height);

            drawRealisticGun();
            drawMuzzleFlash();
            drawBullet();
            drawHeart();

            particles.forEach((p, i) => { p.update(); p.draw(); if (p.life <= 0) particles.splice(i, 1); });

            if (gunX < 260) gunX += 5.5;

            if (gunX >= 260 && !shooting) {
                setTimeout(() => {
                    shooting = true; bulletX = gunX + 290; recoilOffset = -38; flash = 1.0;
                    setTimeout(() => recoilOffset = 0, 120);
                }, 650);
            }

            if (shooting) {
                bulletX += 32;
                flash = Math.max(0, flash - 0.12);
                if (bulletX > heartX - 70) {
                    shooting = false; exploded = true;
                    for (let i = 0; i < 110; i++) particles.push(new Particle(heartX, heartY));
                    canvas.style.transform = 'translate(4px, 3px)';
                    setTimeout(() => canvas.style.transform = 'translate(-3px, -4px)', 30);
                    setTimeout(() => canvas.style.transform = 'translate(0,0)', 80);

                    setTimeout(() => {
                        document.getElementById('intro').style.transition = 'opacity 1.8s';
                        document.getElementById('intro').style.opacity = '0';
                        setTimeout(() => {
                            document.getElementById('intro').classList.add('hidden');
                            document.getElementById('main-content').classList.remove('hidden');
                            document.getElementById('main-content').style.opacity = '1';
                        }, 1800);
                    }, 1100);
                }
            }
            requestAnimationFrame(animateIntro);
        }

        window.onload = () => {
            canvas.width = 1200;
            canvas.height = 700;
            animateIntro();
        };
    </script>
</body>
</html>
