<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luki Club | Sophisticated Y2K</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Three.js -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@700;900&family=Playfair+Display:ital,wght@0,700;1,700;1,900&family=Plus+Jakarta+Sans:wght@400;700;800&family=Instrument+Serif:ital@0;1&family=VT323&display=swap" rel="stylesheet">
    
    <!-- Icons -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'royal-blue': '#050B18',
                        'cherry-wine': '#8B0000',
                        'princess-pink': '#FFC0CB',
                        'y2k-purple': '#C084FC',
                        'soft-ivory': '#FFFFFF',
                        'cyber-green': '#00FF41'
                    },
                    fontFamily: {
                        'serif': ['"Playfair Display"', 'serif'],
                        'display': ['"Cinzel"', 'serif'],
                        'sans': ['"Plus Jakarta Sans"', 'sans-serif'],
                        'hand': ['"Instrument Serif"', 'serif'],
                        'pixel': ['"VT323"', 'monospace'],
                    }
                }
            }
        }
    </script>

    <style>
        body {
            background-color: #050B18;
            color: #FFFFFF;
            overflow-x: hidden;
            cursor: none;
        }
        
        #custom-cursor {
            width: 20px;
            height: 20px;
            background: #FFC0CB;
            border-radius: 50%;
            position: fixed;
            pointer-events: none;
            z-index: 9999;
            mix-blend-mode: difference;
            box-shadow: 0 0 20px #FFC0CB;
        }

        /* Estética de Navegador Vintage */
        .browser-bar {
            background: #F3F3F3;
            border-bottom: 2px solid #D1D1D1;
            color: #000;
            font-family: 'Plus Jakarta Sans', sans-serif;
            font-weight: 600;
        }

        .address-bar {
            background: #FFF;
            border: 1px solid #D1D1D1;
            padding: 4px 15px;
            flex-grow: 1;
            border-radius: 4px;
            font-size: 0.8rem;
            letter-spacing: 0.05em;
        }

        /* Scanline Effect */
        .scanlines {
            position: relative;
            overflow: hidden;
        }
        .scanlines::after {
            content: "";
            position: absolute;
            inset: 0;
            background: linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.05) 50%);
            background-size: 100% 4px;
            pointer-events: none;
            z-index: 2;
        }

        .y2k-window-bold {
            border: 3px solid #FFC0CB;
            box-shadow: 12px 12px 0px #8B0000;
            background: #050B18;
        }

        .window-header {
            background: #FFC0CB;
            color: #050B18;
            padding: 6px 12px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-family: 'Cinzel', serif;
            font-weight: 900;
            font-size: 0.75rem;
            border-bottom: 3px solid #FFC0CB;
        }

        .card-glow {
            border: 1px solid rgba(255, 192, 203, 0.2);
            transition: all 0.6s cubic-bezier(0.16, 1, 0.3, 1);
            position: relative;
            overflow: hidden;
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(10px);
        }
        
        .card-glow:hover {
            transform: translateY(-10px);
            border-color: #FFC0CB;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4), 0 0 20px rgba(255, 192, 203, 0.2);
        }

        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 1s cubic-bezier(0.22, 1, 0.36, 1);
        }
        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        @keyframes marquee {
            0% { transform: translateX(0); }
            100% { transform: translateX(-50%); }
        }
        .animate-marquee {
            display: flex;
            width: 200%;
            animation: marquee 25s linear infinite;
        }

        .sticker-bold {
            background: #FFFFFF;
            color: #050B18;
            padding: 6px 16px;
            font-family: 'Cinzel', serif;
            font-weight: 900;
            text-transform: uppercase;
            border: 2px solid #050B18;
            box-shadow: 4px 4px 0px #FFC0CB;
            transform: rotate(-3deg);
            font-size: 0.8rem;
        }

        /* Botones de navegación SOFISTICADOS */
        .tab-btn {
            font-family: 'Cinzel', serif;
            font-weight: 700;
            font-size: 0.9rem;
            letter-spacing: 0.2em;
            text-transform: uppercase;
            padding: 8px 24px;
            position: relative;
            transition: all 0.4s;
            color: #FFFFFF;
            opacity: 0.7;
        }
        
        .tab-btn::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            width: 0;
            height: 2px;
            background: #FFC0CB;
            transition: all 0.4s;
            transform: translateX(-50%);
        }

        .tab-btn:hover {
            opacity: 1;
            color: #FFC0CB;
        }
        
        .tab-btn:hover::after, .tab-btn.active::after {
            width: 60%;
        }

        .tab-btn.active {
            opacity: 1;
            color: #FFC0CB;
        }

        /* Botón Pánico con estilo */
        .panic-btn {
            font-family: 'Instrument Serif', serif;
            font-style: italic;
            font-size: 1.2rem;
            color: #8B0000;
            border: 1px solid #8B0000;
            padding: 4px 16px;
            transition: all 0.3s;
        }
        .panic-btn:hover {
            background: #8B0000;
            color: #FFF;
        }
    </style>
</head>
<body class="antialiased">

    <div id="custom-cursor"></div>

    <!-- Retro Browser Header -->
    <header class="fixed top-0 w-full z-[60]">
        <div class="browser-bar px-6 py-2 flex items-center gap-6">
            <div class="flex gap-3">
                <button class="w-6 h-6 rounded-full bg-red-400 border border-red-600/20 shadow-inner"></button>
                <button class="w-6 h-6 rounded-full bg-yellow-400 border border-yellow-600/20 shadow-inner"></button>
                <button class="w-6 h-6 rounded-full bg-green-400 border border-green-600/20 shadow-inner"></button>
            </div>
            <div class="address-bar flex items-center gap-3 italic font-sans text-gray-500">
                <i class="fas fa-lock text-[10px]"></i>
                <span class="truncate">lukiclub.atelier/digital-vault_v2</span>
            </div>
            <div class="hidden md:block font-sans text-[10px] font-black uppercase tracking-[0.2em] text-gray-400">
                System Status: <span class="text-green-600">Iconic</span>
            </div>
        </div>
        
        <!-- Categorías de la Tienda SOFISTICADAS -->
        <nav class="bg-royal-blue/90 backdrop-blur-2xl border-b border-white/10 px-8 py-5 flex flex-wrap justify-center items-center gap-2 md:gap-10">
            <a href="#vault" class="tab-btn active">Archive</a>
            <a href="#shop" class="tab-btn">Shop All</a>
            <div class="h-4 w-[1px] bg-white/20 hidden md:block"></div>
            <a href="#" class="tab-btn">Planners</a>
            <a href="#" class="tab-btn">Presets</a>
            <a href="#" class="panic-btn ml-4">Panic Mode</a>
        </nav>
    </header>

    <!-- Loader -->
    <div id="loader" class="fixed inset-0 bg-royal-blue z-[100] flex flex-col items-center justify-center transition-opacity duration-1000">
        <div class="y2k-window-bold p-1 bg-white scale-75 md:scale-100">
            <div class="window-header mb-1">
                <span>INITIALIZING_LUXURY.EXE</span>
            </div>
            <div class="p-12 bg-royal-blue text-center">
                <h1 class="font-display text-2xl text-princess-pink mb-8 tracking-[0.3em] uppercase">Loading Luki Club</h1>
                <div class="w-64 h-[2px] bg-gray-800 relative">
                    <div id="progress" class="h-full bg-princess-pink shadow-[0_0_15px_#FFC0CB] transition-all duration-300" style="width: 0%"></div>
                </div>
            </div>
        </div>
    </div>

    <!-- Main Section -->
    <main class="pt-40">
        <section class="h-[85vh] relative flex items-center justify-center overflow-hidden">
            <div id="canvas-container" class="absolute inset-0 z-0"></div>
            <div class="absolute inset-0 bg-gradient-to-b from-transparent via-royal-blue/10 to-royal-blue"></div>
            
            <div class="relative z-10 text-center space-y-8 px-4">
                <div class="reveal">
                    <span class="font-display text-white text-xs tracking-[0.5em] uppercase border-b border-princess-pink pb-2">The Digital Atelier</span>
                </div>
                <h1 class="font-display text-[7rem] md:text-[14rem] leading-none tracking-tighter reveal delay-100">
                    <span class="text-white drop-shadow-[15px_15px_0px_#8B0000]">LUKI</span><br>
                    <span class="font-hand italic text-princess-pink text-6xl md:text-9xl block -mt-8 md:-mt-12">Sophistiquée</span>
                </h1>
                <div class="flex flex-col md:flex-row justify-center items-center gap-6 reveal delay-200">
                    <button class="bg-white text-royal-blue px-10 py-4 font-display text-sm tracking-[0.2em] hover:bg-princess-pink transition-all shadow-[8px_8px_0px_#8B0000]">SHOP THE VAULT</button>
                    <a href="#" class="font-hand text-3xl text-white italic border-b border-white/30 hover:border-princess-pink transition-all">Discover the Lookbook</a>
                </div>
            </div>

            <!-- Sticker Ornaments -->
            <div class="absolute top-[25%] left-[8%] sticker-bold rotate-[-8deg] bg-y2k-purple">EST. 2024</div>
            <div class="absolute bottom-[25%] right-[8%] sticker-bold rotate-[5deg] bg-white text-cherry-wine">COLLECTOR'S ITEM</div>
        </section>

        <!-- High-Contrast Marquee -->
        <div class="bg-white py-4 border-y border-white/10 overflow-hidden relative z-20">
            <div class="animate-marquee font-display text-xs text-royal-blue uppercase tracking-[0.4em] whitespace-nowrap">
                ✦ BORN TO BE ICONIC ✦ NO PHYSICAL LIMITS ✦ DIGITAL LUXURY ONLY ✦ BORN TO BE ICONIC ✦ NO PHYSICAL LIMITS ✦ DIGITAL LUXURY ONLY ✦ 
            </div>
        </div>

        <!-- Section: The Archive -->
        <section id="vault" class="py-48 bg-royal-blue relative">
            <div class="container mx-auto px-6">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-24 items-center">
                    <div class="reveal">
                        <div class="y2k-window-bold">
                            <div class="window-header">
                                <span>MANIFESTO_VOL_01.PDF</span>
                                <div class="flex gap-1"><div class="w-2 h-2 rounded-full bg-white/40"></div></div>
                            </div>
                            <div class="p-16 space-y-10 bg-royal-blue">
                                <h2 class="font-serif italic text-6xl md:text-7xl text-princess-pink leading-[1.1]">Tu estética, ahora bajo control.</h2>
                                <p class="font-sans text-lg leading-relaxed text-white/80 font-medium tracking-tight">
                                    Creamos herramientas digitales para quienes entienden que la organización no es una tarea, es un arte. Luki Club es el punto donde el lujo clásico y la rebeldía Y2K convergen.
                                </p>
                                <div class="pt-6">
                                    <button class="font-display text-xs tracking-[0.3em] text-white border border-white/20 px-8 py-4 hover:bg-white hover:text-royal-blue transition-all">READ THE STORY</button>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="relative reveal delay-200 scanlines px-4">
                        <div class="y2k-window-bold p-3 rotate-1 bg-white">
                            <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?auto=format&fit=crop&q=80&w=800" class="w-full h-[600px] object-cover grayscale hover:grayscale-0 transition-all duration-1000 ease-in-out">
                        </div>
                        <div class="absolute -bottom-8 -left-4 sticker-bold bg-cherry-wine text-white p-5 rotate-[-12deg]">EDITORIAL_01</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Product Grid: Collector Cards -->
        <section id="shop" class="py-40 bg-royal-blue border-t border-white/5">
            <div class="container mx-auto px-6">
                <div class="mb-32 text-center reveal">
                    <h2 class="font-display text-7xl md:text-[10rem] text-white tracking-tighter uppercase leading-none opacity-90">Digital_Curations</h2>
                    <p class="font-hand text-4xl text-princess-pink italic mt-4">Elevate your daily routine.</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-16">
                    
                    <!-- Card 1 -->
                    <div class="reveal group">
                        <div class="card-glow p-8 rounded-[2rem]">
                            <div class="window-header mb-6 !bg-transparent !text-princess-pink border-b border-white/10 p-0 pb-4">
                                <span>ITEM_001 // REGINA</span>
                                <span class="text-[10px] tracking-widest font-sans font-bold">EDITION: 1/1</span>
                            </div>
                            <div class="aspect-[4/5] overflow-hidden rounded-xl mb-8 scanlines border border-white/10">
                                <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&q=80&w=800" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-1000">
                            </div>
                            <h3 class="font-display text-2xl text-white mb-3">ULTRA_PLANNER</h3>
                            <div class="flex justify-between items-center mb-8">
                                <span class="font-hand text-2xl text-princess-pink italic">Classic Royal</span>
                                <span class="font-display text-lg text-white">$24.00</span>
                            </div>
                            <button class="w-full py-5 bg-white text-royal-blue font-display text-[10px] tracking-[0.4em] uppercase hover:bg-princess-pink transition-all font-black">
                                Add to Archive
                            </button>
                        </div>
                    </div>

                    <!-- Card 2 -->
                    <div class="reveal delay-200 group">
                        <div class="card-glow p-8 rounded-[2rem]">
                            <div class="window-header mb-6 !bg-transparent !text-y2k-purple border-b border-white/10 p-0 pb-4">
                                <span>ITEM_002 // MILLION</span>
                                <span class="text-[10px] tracking-widest font-sans font-bold">LIMITED DROP</span>
                            </div>
                            <div class="aspect-[4/5] overflow-hidden rounded-xl mb-8 scanlines border border-white/10">
                                <img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f?auto=format&fit=crop&q=80&w=800" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-1000">
                            </div>
                            <h3 class="font-display text-2xl text-white mb-3">MANIFEST_GUIDE</h3>
                            <div class="flex justify-between items-center mb-8">
                                <span class="font-hand text-2xl text-y2k-purple italic">Future Self</span>
                                <span class="font-display text-lg text-white">$19.00</span>
                            </div>
                            <button class="w-full py-5 bg-white text-royal-blue font-display text-[10px] tracking-[0.4em] uppercase hover:bg-y2k-purple transition-all font-black">
                                Add to Archive
                            </button>
                        </div>
                    </div>

                    <!-- Card 3 -->
                    <div class="reveal delay-400 group">
                        <div class="card-glow p-8 rounded-[2rem]">
                            <div class="window-header mb-6 !bg-transparent !text-white border-b border-white/10 p-0 pb-4">
                                <span>ITEM_003 // CYBER</span>
                                <span class="text-[10px] tracking-widest font-sans font-bold">ALL IN ONE</span>
                            </div>
                            <div class="aspect-[4/5] overflow-hidden rounded-xl mb-8 scanlines border border-white/10">
                                <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&q=80&w=800" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-1000">
                            </div>
                            <h3 class="font-display text-2xl text-white mb-3">BUNDLE_PACK</h3>
                            <div class="flex justify-between items-center mb-8">
                                <span class="font-hand text-2xl text-white/60 italic">Elite Access</span>
                                <span class="font-display text-lg text-white">$45.00</span>
                            </div>
                            <button class="w-full py-5 bg-white text-royal-blue font-display text-[10px] tracking-[0.4em] uppercase hover:bg-white/80 transition-all font-black">
                                Add to Archive
                            </button>
                        </div>
                    </div>

                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-white text-royal-blue py-40 border-t-[15px] border-cherry-wine">
        <div class="container mx-auto px-6 text-center">
            <h4 class="font-display text-[10rem] md:text-[18rem] tracking-tighter text-royal-blue leading-[0.8] mb-20">LUKI</h4>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-20 text-left pt-20 border-t border-royal-blue/10">
                <div class="space-y-6">
                    <h5 class="font-display text-xs tracking-[0.3em] uppercase opacity-40">Atelier Navigation</h5>
                    <ul class="font-hand text-3xl space-y-2 italic">
                        <li><a href="#" class="hover:text-cherry-wine transition-colors">The Vault</a></li>
                        <li><a href="#" class="hover:text-cherry-wine transition-colors">Lookbook v.2</a></li>
                        <li><a href="#" class="hover:text-cherry-wine transition-colors">Private Access</a></li>
                    </ul>
                </div>
                <div class="space-y-6">
                    <h5 class="font-display text-xs tracking-[0.3em] uppercase opacity-40">Social Channels</h5>
                    <ul class="font-hand text-3xl space-y-2 italic">
                        <li><a href="#" class="hover:text-cherry-wine transition-colors">TikTok</a></li>
                        <li><a href="#" class="hover:text-cherry-wine transition-colors">Instagram</a></li>
                        <li><a href="#" class="hover:text-cherry-wine transition-colors">Pinterest</a></li>
                    </ul>
                </div>
                <div class="bg-royal-blue p-12 text-white flex flex-col justify-center">
                    <h5 class="font-display text-xs tracking-[0.4em] mb-8 text-center uppercase">Join the Membership</h5>
                    <input type="text" placeholder="your@email.com" class="bg-transparent border-b border-white/20 p-3 font-sans text-sm mb-8 focus:outline-none focus:border-princess-pink transition-all">
                    <button class="bg-white text-royal-blue py-4 font-display text-[10px] tracking-[0.3em] uppercase font-black hover:bg-princess-pink transition-colors">Register</button>
                </div>
            </div>
            
            <div class="mt-40 font-sans text-[10px] tracking-[0.5em] uppercase opacity-30">
                © 2026 Luki Club Atelier ✦ Digital Royalty Worldwide
            </div>
        </div>
    </footer>

    <script>
        // Cursor Logic
        const cursor = document.getElementById('custom-cursor');
        let mouseX = 0, mouseY = 0;
        let ballX = 0, ballY = 0;

        document.addEventListener('mousemove', (e) => {
            mouseX = e.clientX;
            mouseY = e.clientY;
        });

        function animateCursor() {
            ballX += (mouseX - ballX) * 0.12;
            ballY += (mouseY - ballY) * 0.12;
            cursor.style.left = ballX - 10 + 'px';
            cursor.style.top = ballY - 10 + 'px';
            requestAnimationFrame(animateCursor);
        }
        animateCursor();

        // Loader
        let progress = 0;
        const interval = setInterval(() => {
            progress += Math.random() * 30;
            if(progress >= 100) {
                progress = 100;
                clearInterval(interval);
                setTimeout(() => {
                    document.getElementById('loader').style.opacity = '0';
                    setTimeout(() => document.getElementById('loader').style.display = 'none', 1000);
                }, 800);
            }
            document.getElementById('progress').style.width = progress + '%';
        }, 200);

        // Scroll Reveal
        const reveals = document.querySelectorAll('.reveal');
        const revealHandler = () => {
            reveals.forEach(el => {
                const elementTop = el.getBoundingClientRect().top;
                if (elementTop < window.innerHeight - 80) {
                    el.classList.add('active');
                }
            });
        };
        window.addEventListener('scroll', revealHandler);
        revealHandler();

        // Three.js Sparkle Background (Subtle Luxe Version)
        const initThree = () => {
            const container = document.getElementById('canvas-container');
            const scene = new THREE.Scene();
            const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
            const renderer = new THREE.WebGLRenderer({ alpha: true, antialias: true });
            renderer.setSize(window.innerWidth, window.innerHeight);
            container.appendChild(renderer.domElement);

            const particlesGeometry = new THREE.BufferGeometry();
            const count = 2000;
            const positions = new Float32Array(count * 3);

            for(let i=0; i<count * 3; i++) {
                positions[i] = (Math.random() - 0.5) * 20;
            }
            particlesGeometry.setAttribute('position', new THREE.BufferAttribute(positions, 3));

            const particlesMaterial = new THREE.PointsMaterial({
                color: 0xFFFFFF,
                size: 0.02,
                transparent: true,
                opacity: 0.3,
                blending: THREE.AdditiveBlending
            });

            const particles = new THREE.Points(particlesGeometry, particlesMaterial);
            scene.add(particles);

            camera.position.z = 5;

            function animate() {
                requestAnimationFrame(animate);
                particles.rotation.y += 0.0003;
                particles.rotation.x += 0.0001;
                renderer.render(scene, camera);
            }
            animate();
            
            window.addEventListener('resize', () => {
                camera.aspect = window.innerWidth / window.innerHeight;
                camera.updateProjectionMatrix();
                renderer.setSize(window.innerWidth, window.innerHeight);
            });
        };
        initThree();
    </script>
</body>
</html>
