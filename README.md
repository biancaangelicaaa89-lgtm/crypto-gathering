[Gatheringcrypto25.txt](https://github.com/user-attachments/files/22098224/Gatheringcrypto25.txt)
<!DOCTYPE html>
<index.html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crypto Bitcoin Gathering 2024 - Undangan Acara</title>
    
    <!-- Meta Tags untuk Social Media Sharing -->
    <meta property="og:title" content="Crypto Bitcoin Gathering 2024">
    <meta property="og:description" content="Bergabunglah dengan komunitas crypto terbesar di Indonesia untuk membahas masa depan Bitcoin dan blockchain">
    <meta property="og:image" content="https://i.imgur.com/your-image-url.jpg">
    <meta property="og:url" content="https://your-website-url.com">
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Crypto Bitcoin Gathering 2024">
    
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Crypto Bitcoin Gathering 2024">
    <meta name="twitter:description" content="Bergabunglah dengan komunitas crypto terbesar di Indonesia">
    <meta name="twitter:image" content="https://i.imgur.com/your-image-url.jpg">
    
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Inter:wght@300;400;600&display=swap');
        
        :root {
            --bitcoin-orange: #F7931A;
            --crypto-dark: #0D1117;
            --crypto-blue: #1E40AF;
            --crypto-purple: #7C3AED;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0a0e1a;
            color: #e2e8f0;
            overflow-x: hidden;
        }
        
        .crypto-font {
            font-family: 'Orbitron', monospace;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #0a0e1a 0%, #1a237e 100%);
        }
        
        .bitcoin-gradient {
            background: linear-gradient(90deg, var(--bitcoin-orange) 0%, #ffab00 100%);
        }
        
        .crypto-gradient {
            background: linear-gradient(90deg, var(--crypto-blue) 0%, var(--crypto-purple) 100%);
        }
        
        .glow {
            box-shadow: 0 0 20px rgba(247, 147, 26, 0.5);
        }
        
        .crypto-glow {
            box-shadow: 0 0 20px rgba(124, 58, 237, 0.5);
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
        }
        
        .pulse-animation {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .floating {
            animation: floating 3s ease-in-out infinite;
        }
        
        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
        
        .crypto-border {
            border: 2px solid transparent;
            background: linear-gradient(#0a0e1a, #0a0e1a) padding-box,
                        linear-gradient(90deg, var(--bitcoin-orange), var(--crypto-purple)) border-box;
        }
        
        .timeline-line {
            background: linear-gradient(180deg, var(--bitcoin-orange), var(--crypto-blue));
        }
        
        /* WhatsApp Share Button */
        .whatsapp-btn {
            background-color: #25D366;
            color: white;
            border-radius: 50px;
            padding: 12px 24px;
            font-weight: bold;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .whatsapp-btn:hover {
            background-color: #128C7E;
            transform: translateY(-2px);
            box-shadow: 0 6px 8px rgba(0, 0, 0, 0.15);
        }
        
        /* Copy Link Button */
        .copy-link-btn {
            background-color: #4F46E5;
            color: white;
            border-radius: 50px;
            padding: 12px 24px;
            font-weight: bold;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            cursor: pointer;
            border: none;
        }
        
        .copy-link-btn:hover {
            background-color: #4338CA;
            transform: translateY(-2px);
            box-shadow: 0 6px 8px rgba(0, 0, 0, 0.15);
        }
        
        /* Mobile Menu */
        .mobile-menu {
            transform: translateX(-100%);
            transition: transform 0.3s ease-in-out;
        }
        
        .mobile-menu.active {
            transform: translateX(0);
        }
        
        /* Notification Toast */
        .toast {
            position: fixed;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%) translateY(100px);
            background-color: #10B981;
            color: white;
            padding: 16px 24px;
            border-radius: 8px;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
            z-index: 1000;
            opacity: 0;
            transition: all 0.3s ease;
        }
        
        .toast.show {
            transform: translateX(-50%) translateY(0);
            opacity: 1;
        }
    </style>
</head>
<body class="gradient-bg">
    <!-- Toast Notification -->
    <div id="toast" class="toast">
        <span id="toast-message">Link berhasil disalin!</span>
    </div>

    <!-- Header -->
    <header class="fixed w-full z-50 backdrop-blur-lg bg-black/30">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fab fa-bitcoin text-3xl text-yellow-500"></i>
                <h1 class="crypto-font text-xl font-bold text-white">CRYPTO SUMMIT 2024</h1>
            </div>
            <nav class="hidden md:flex space-x-8">
                <a href="#home" class="hover:text-yellow-400 transition">Beranda</a>
                <a href="#about" class="hover:text-yellow-400 transition">Tentang</a>
                <a href="#agenda" class="hover:text-yellow-400 transition">Agenda</a>
                <a href="#speakers" class="hover:text-yellow-400 transition">Pembicara</a>
                <a href="#location" class="hover:text-yellow-400 transition">Lokasi</a>
                <a href="#register" class="hover:text-yellow-400 transition">Daftar</a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden text-white">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
    </header>

    <!-- Mobile Menu -->
    <div id="mobile-menu" class="mobile-menu fixed top-0 left-0 w-64 h-full bg-black/90 z-40 md:hidden">
        <div class="p-4">
            <button id="close-menu" class="text-white mb-8">
                <i class="fas fa-times text-2xl"></i>
            </button>
            <nav class="flex flex-col space-y-4">
                <a href="#home" class="hover:text-yellow-400 transition">Beranda</a>
                <a href="#about" class="hover:text-yellow-400 transition">Tentang</a>
                <a href="#agenda" class="hover:text-yellow-400 transition">Agenda</a>
                <a href="#speakers" class="hover:text-yellow-400 transition">Pembicara</a>
                <a href="#location" class="hover:text-yellow-400 transition">Lokasi</a>
                <a href="#register" class="hover:text-yellow-400 transition">Daftar</a>
            </nav>
        </div>
    </div>

    <!-- Hero Section -->
    <section id="home" class="min-h-screen flex items-center relative overflow-hidden">
        <div class="absolute inset-0 z-0">
            <div class="absolute top-20 left-10 w-72 h-72 bg-yellow-500/10 rounded-full blur-3xl"></div>
            <div class="absolute bottom-20 right-10 w-96 h-96 bg-purple-600/10 rounded-full blur-3xl"></div>
            <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-80 h-80 bg-blue-500/10 rounded-full blur-3xl"></div>
        </div>
        
        <div class="container mx-auto px-4 relative z-10">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h2 class="crypto-font text-4xl md:text-6xl font-black mb-4">
                        <span class="text-yellow-400">CRYPTO</span> BITCOIN 
                        <span class="text-purple-400">GATHERING</span>
                    </h2>
                    <p class="text-xl mb-6 text-gray-300">
                        Bergabunglah dengan komunitas crypto terbesar di Indonesia untuk membahas masa depan Bitcoin dan blockchain
                    </p>
                    <div class="flex flex-wrap gap-4 mb-8">
                        <div class="flex items-center bg-black/30 p-3 rounded-lg">
                            <i class="far fa-calendar-alt mr-2 text-yellow-400"></i>
                            <span>15 November 2024</span>
                        </div>
                        <div class="flex items-center bg-black/30 p-3 rounded-lg">
                            <i class="far fa-clock mr-2 text-purple-400"></i>
                            <span>09:00 - 17:00 WIB</span>
                        </div>
                        <div class="flex items-center bg-black/30 p-3 rounded-lg">
                            <i class="fas fa-map-marker-alt mr-2 text-blue-400"></i>
                            <span>Jakarta Convention Center</span>
                        </div>
                    </div>
                    <div class="flex flex-wrap gap-4">
                        <a href="#register" class="bitcoin-gradient text-black font-bold py-3 px-8 rounded-full hover:opacity-90 transition glow">
                            DAFTAR SEKARANG
                        </a>
                        <a href="#agenda" class="crypto-border text-white font-bold py-3 px-8 rounded-full hover:bg-white/10 transition">
                            LIHAT AGENDA
                        </a>
                    </div>
                    
                    <!-- Share Buttons -->
                    <div class="mt-8 flex flex-wrap gap-3">
                        <p class="w-full text-gray-400 mb-2">Bagikan undangan ini:</p>
                        <a id="whatsapp-share" class="whatsapp-btn">
                            <i class="fab fa-whatsapp"></i> WhatsApp
                        </a>
                        <button id="copy-link" class="copy-link-btn">
                            <i class="fas fa-copy"></i> Salin Link
                        </button>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <div class="relative floating">
                        <div class="w-64 h-64 md:w-80 md:h-80 rounded-full bg-gradient-to-br from-yellow-500 to-orange-600 flex items-center justify-center glow">
                            <i class="fab fa-bitcoin text-white text-8xl md:text-9xl"></i>
                        </div>
                        <div class="absolute -top-10 -right-10 w-32 h-32 rounded-full bg-gradient-to-br from-blue-500 to-purple-600 flex items-center justify-center crypto-glow">
                            <i class="fab fa-ethereum text-white text-4xl"></i>
                        </div>
                        <div class="absolute -bottom-10 -left-10 w-24 h-24 rounded-full bg-gradient-to-br from-green-400 to-blue-500 flex items-center justify-center">
                            <i class="fas fa-coins text-white text-3xl"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 relative">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="crypto-font text-3xl md:text-4xl font-bold mb-4">
                    TENTANG <span class="text-yellow-400">ACARA</span>
                </h2>
                <div class="w-24 h-1 bitcoin-gradient mx-auto"></div>
            </div>
            
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h3 class="text-2xl font-bold mb-4">Mengapa Anda Harus Hadir?</h3>
                    <p class="mb-6 text-gray-300">
                        Gathering Crypto Bitcoin 2024 adalah acara tahunan terbesar yang mengumpulkan para ahli blockchain, investor, 
                        dan penggemar cryptocurrency untuk berbagi pengetahuan, jaringan, dan membahas tren terkini di industri crypto.
                    </p>
                    <ul class="space-y-3">
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-400 mt-1 mr-3"></i>
                            <span>100+ Pembicara Internasional dan Lokal</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-400 mt-1 mr-3"></i>
                            <span>50+ Booth Ekshibisi Crypto Project</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-400 mt-1 mr-3"></i>
                            <span>Networking Session dengan 5000+ Peserta</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check-circle text-green-400 mr-3 mt-1"></i>
                            <span>Workshop dan Panel Diskusi Eksklusif</span>
                        </li>
                    </ul>
                </div>
                <div class="grid grid-cols-2 gap-6">
                    <div class="bg-black/30 p-6 rounded-xl card-hover">
                        <div class="text-4xl text-yellow-400 mb-3">
                            <i class="fas fa-users"></i>
                        </div>
                        <h4 class="font-bold text-lg mb-2">5000+</h4>
                        <p class="text-gray-400">Peserta</p>
                    </div>
                    <div class="bg-black/30 p-6 rounded-xl card-hover">
                        <div class="text-4xl text-purple-400 mb-3">
                            <i class="fas fa-microphone"></i>
                        </div>
                        <h4 class="font-bold text-lg mb-2">100+</h4>
                        <p class="text-gray-400">Pembicara</p>
                    </div>
                    <div class="bg-black/30 p-6 rounded-xl card-hover">
                        <div class="text-4xl text-blue-400 mb-3">
                            <i class="fas fa-building"></i>
                        </div>
                        <h4 class="font-bold text-lg mb-2">50+</h4>
                        <p class="text-gray-400">Ekshibitor</p>
                    </div>
                    <div class="bg-black/30 p-6 rounded-xl card-hover">
                        <div class="text-4xl text-green-400 mb-3">
                            <i class="fas fa-globe"></i>
                        </div>
                        <h4 class="font-bold text-lg mb-2">20+</h4>
                        <p class="text-gray-400">Negara</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Agenda Section -->
    <section id="agenda" class="py-20 relative">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="crypto-font text-3xl md:text-4xl font-bold mb-4">
                    <span class="text-yellow-400">AGENDA</span> ACARA
                </h2>
                <div class="w-24 h-1 crypto-gradient mx-auto"></div>
            </div>
            
            <div class="max-w-4xl mx-auto">
                <div class="relative">
                    <!-- Timeline Line -->
                    <div class="absolute left-4 md:left-1/2 top-0 bottom-0 w-1 timeline-line transform md:-translate-x-1/2"></div>
                    
                    <!-- Timeline Items -->
                    <div class="space-y-12">
                        <!-- Item 1 -->
                        <div class="relative flex items-center">
                            <div class="absolute left-4 md:left-1/2 w-8 h-8 rounded-full bg-yellow-500 border-4 border-black transform md:-translate-x-1/2 z-10"></div>
                            <div class="ml-16 md:ml-0 md:w-1/2 md:pr-8">
                                <div class="bg-black/30 p-6 rounded-xl card-hover">
                                    <div class="text-yellow-400 font-bold mb-2">09:00 - 10:00</div>
                                    <h3 class="text-xl font-bold mb-2">Registrasi & Sarapan Pagi</h3>
                                    <p class="text-gray-400">Registrasi ulang dan sarapan pagi sambil networking</p>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Item 2 -->
                        <div class="relative flex items-center">
                            <div class="absolute left-4 md:left-1/2 w-8 h-8 rounded-full bg-purple-500 border-4 border-black transform md:-translate-x-1/2 z-10"></div>
                            <div class="ml-16 md:ml-0 md:w-1/2 md:pl-8 md:ml-auto">
                                <div class="bg-black/30 p-6 rounded-xl card-hover">
                                    <div class="text-purple-400 font-bold mb-2">10:00 - 11:00</div>
                                    <h3 class="text-xl font-bold mb-2">Keynote Speech: Masa Depan Bitcoin</h3>
                                    <p class="text-gray-400">Oleh: Andreas Antonopoulos (Pembicara Internasional)</p>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Item 3 -->
                        <div class="relative flex items-center">
                            <div class="absolute left-4 md:left-1/2 w-8 h-8 rounded-full bg-blue-500 border-4 border-black transform md:-translate-x-1/2 z-10"></div>
                            <div class="ml-16 md:ml-0 md:w-1/2 md:pr-8">
                                <div class="bg-black/30 p-6 rounded-xl card-hover">
                                    <div class="text-blue-400 font-bold mb-2">11:00 - 12:30</div>
                                    <h3 class="text-xl font-bold mb-2">Panel Discussion: DeFi Revolution</h3>
                                    <p class="text-gray-400">Moderator: Rudi Faraud (CEO Indodax)</p>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Item 4 -->
                        <div class="relative flex items-center">
                            <div class="absolute left-4 md:left-1/2 w-8 h-8 rounded-full bg-green-500 border-4 border-black transform md:-translate-x-1/2 z-10"></div>
                            <div class="ml-16 md:ml-0 md:w-1/2 md:pl-8 md:ml-auto">
                                <div class="bg-black/30 p-6 rounded-xl card-hover">
                                    <div class="text-green-400 font-bold mb-2">12:30 - 14:00</div>
                                    <h3 class="text-xl font-bold mb-2">Makan Siang & Networking</h3>
                                    <p class="text-gray-400">Makan siang dan kunjungi booth ekshibisi</p>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Item 5 -->
                        <div class="relative flex items-center">
                            <div class="absolute left-4 md:left-1/2 w-8 h-8 rounded-full bg-red-500 border-4 border-black transform md:-translate-x-1/2 z-10"></div>
                            <div class="ml-16 md:ml-0 md:w-1/2 md:pr-8">
                                <div class="bg-black/30 p-6 rounded-xl card-hover">
                                    <div class="text-red-400 font-bold mb-2">14:00 - 15:30</div>
                                    <h3 class="text-xl font-bold mb-2">Workshop: Crypto Trading Strategy</h3>
                                    <p class="text-gray-400">Oleh: Ellen May (Trader Profesional)</p>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Item 6 -->
                        <div class="relative flex items-center">
                            <div class="absolute left-4 md:left-1/2 w-8 h-8 rounded-full bg-indigo-500 border-4 border-black transform md:-translate-x-1/2 z-10"></div>
                            <div class="ml-16 md:ml-0 md:w-1/2 md:pl-8 md:ml-auto">
                                <div class="bg-black/30 p-6 rounded-xl card-hover">
                                    <div class="text-indigo-400 font-bold mb-2">15:30 - 17:00</div>
                                    <h3 class="text-xl font-bold mb-2">Closing & Networking Session</h3>
                                    <p class="text-gray-400">Penutupan dan sesi networking terakhir</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Speakers Section -->
    <section id="speakers" class="py-20 relative">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="crypto-font text-3xl md:text-4xl font-bold mb-4">
                    <span class="text-yellow-400">PEMBICARA</span> UTAMA
                </h2>
                <div class="w-24 h-1 bitcoin-gradient mx-auto"></div>
                <p class="mt-4 max-w-2xl mx-auto text-gray-400">
                    Bertemu dengan para ahli terkemuka di industri cryptocurrency dan blockchain
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Speaker 1 -->
                <div class="bg-black/30 rounded-xl overflow-hidden card-hover">
                    <div class="h-48 bg-gradient-to-br from-yellow-500 to-orange-600 flex items-center justify-center">
                        <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Speaker" class="h-full w-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-lg mb-1">Andreas Antonopoulos</h3>
                        <p class="text-yellow-400 text-sm mb-3">Bitcoin Expert</p>
                        <p class="text-gray-400 text-sm">Author of "Mastering Bitcoin"</p>
                        <div class="flex space-x-3 mt-4">
                            <a href="#" class="text-gray-400 hover:text-yellow-400">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="text-gray-400 hover:text-yellow-400">
                                <i class="fab fa-linkedin"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Speaker 2 -->
                <div class="bg-black/30 rounded-xl overflow-hidden card-hover">
                    <div class="h-48 bg-gradient-to-br from-purple-500 to-indigo-600 flex items-center justify-center">
                        <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Speaker" class="h-full w-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-lg mb-1">Ellen May</h3>
                        <p class="text-purple-400 text-sm mb-3">Crypto Trader</p>
                        <p class="text-gray-400 text-sm">Founder Ellen May Institute</p>
                        <div class="flex space-x-3 mt-4">
                            <a href="#" class="text-gray-400 hover:text-purple-400">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="text-gray-400 hover:text-purple-400">
                                <i class="fab fa-linkedin"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Speaker 3 -->
                <div class="bg-black/30 rounded-xl overflow-hidden card-hover">
                    <div class="h-48 bg-gradient-to-br from-blue-500 to-cyan-600 flex items-center justify-center">
                        <img src="https://images.unsplash.com/photo-1557862921-37829c790f19?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Speaker" class="h-full w-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-lg mb-1">Rudi Faraud</h3>
                        <p class="text-blue-400 text-sm mb-3">CEO Indodax</p>
                        <p class="text-gray-400 text-sm">Crypto Exchange Pioneer</p>
                        <div class="flex space-x-3 mt-4">
                            <a href="#" class="text-gray-400 hover:text-blue-400">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="text-gray-400 hover:text-blue-400">
                                <i class="fab fa-linkedin"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Speaker 4 -->
                <div class="bg-black/30 rounded-xl overflow-hidden card-hover">
                    <div class="h-48 bg-gradient-to-br from-green-500 to-teal-600 flex items-center justify-center">
                        <img src="https://images.unsplash.com/photo-1494790108755-2616b612b786?ixlib=rb-4.0.3&auto=format&fit=crop&w=300&q=80" alt="Speaker" class="h-full w-full object-cover">
                    </div>
                    <div class="p-6">
                        <h3 class="font-bold text-lg mb-1">Sarah Johnson</h3>
                        <p class="text-green-400 text-sm mb-3">Blockchain Developer</p>
                        <p class="text-gray-400 text-sm">Ethereum Core Contributor</p>
                        <div class="flex space-x-3 mt-4">
                            <a href="#" class="text-gray-400 hover:text-green-400">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="text-gray-400 hover:text-green-400">
                                <i class="fab fa-linkedin"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Location Section -->
    <section id="location" class="py-20 relative">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="crypto-font text-3xl md:text-4xl font-bold mb-4">
                    <span class="text-yellow-400">LOKASI</span> ACARA
                </h2>
                <div class="w-24 h-1 crypto-gradient mx-auto"></div>
            </div>
            
            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-2xl font-bold mb-6">Jakarta Convention Center</h3>
                    <div class="space-y-4 mb-8">
                        <div class="flex items-start">
                            <i class="fas fa-map-marker-alt text-yellow-400 mt-1 mr-3 text-xl"></i>
                            <div>
                                <h4 class="font-bold">Alamat</h4>
                                <p class="text-gray-400">Jl. Gatot Subroto, Jakarta Selatan 10270</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <i class="fas fa-phone text-purple-400 mt-1 mr-3 text-xl"></i>
                            <div>
                                <h4 class="font-bold">Kontak</h4>
                                <p class="text-gray-400">+62 21 1234 5678</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <i class="fas fa-envelope text-blue-400 mt-1 mr-3 text-xl"></i>
                            <div>
                                <h4 class="font-bold">Email</h4>
                                <p class="text-gray-400">info@cryptogathering.id</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <i class="fas fa-clock text-green-400 mt-1 mr-3 text-xl"></i>
                            <div>
                                <h4 class="font-bold">Jam Operasional</h4>
                                <p class="text-gray-400">08:00 - 22:00 WIB</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-black/30 p-6 rounded-xl">
                        <h4 class="font-bold mb-3">Akses Transportasi</h4>
                        <ul class="space-y-2 text-gray-400">
                            <li>• 5 menit dari Stasiun MRT Istora Mandiri</li>
                            <li>• 10 menit dari Halte Busway Gelora Bung Karno</li>
                            <li>• Parkir tersedia untuk 1000+ kendaraan</li>
                            <li>• Drop-off zone di depan pintu utama</li>
                        </ul>
                    </div>
                </div>
                
                <div>
                    <div class="rounded-xl overflow-hidden h-96 shadow-xl">
                        <iframe 
                            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3966.521260322283!2d106.81403531475587!3d-6.224389995493371!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69f3e945e34b9d%3A0x5371bf0fdad786a2!2sJakarta%20Convention%20Center!5e0!3m2!1sen!2sid!4v1635957123456!5m2!1sen!2sid" 
                            width="100%" 
                            height="100%" 
                            style="border:0;" 
                            allowfullscreen="" 
                            loading="lazy">
                        </iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Registration Section -->
    <section id="register" class="py-20 relative">
        <div class="container mx-auto px-4">
            <div class="max-w-4xl mx-auto">
                <div class="text-center mb-16">
                    <h2 class="crypto-font text-3xl md:text-4xl font-bold mb-4">
                        <span class="text-yellow-400">DAFTAR</span> SEKARANG
                    </h2>
                    <div class="w-24 h-1 bitcoin-gradient mx-auto"></div>
                    <p class="mt-4 text-gray-400">
                        Bergabunglah dengan 5000+ peserta lainnya dan dapatkan penawaran early bird!
                    </p>
                </div>
                
                <div class="bg-black/30 crypto-border rounded-xl p-8 md:p-12">
                    <form id="registrationForm" class="space-y-6">
                        <div class="grid md:grid-cols-2 gap-6">
                            <div>
                                <label class="block text-sm font-medium mb-2">Nama Lengkap *</label>
                                <input type="text" required class="w-full bg-black/50 border border-gray-700 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-yellow-500">
                            </div>
                            <div>
                                <label class="block text-sm font-medium mb-2">Email *</label>
                                <input type="email" required class="w-full bg-black/50 border border-gray-700 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-yellow-500">
                            </div>
                            <div>
                                <label class="block text-sm font-medium mb-2">Nomor Telepon *</label>
                                <input type="tel" required class="w-full bg-black/50 border border-gray-700 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-yellow-500">
                            </div>
                            <div>
                                <label class="block text-sm font-medium mb-2">Perusahaan/Institusi</label>
                                <input type="text" class="w-full bg-black/50 border border-gray-700 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-yellow-500">
                            </div>
                        </div>
                        
                        <div>
                            <label class="block text-sm font-medium mb-2">Jenis Tiket *</label>
                            <div class="grid md:grid-cols-3 gap-4">
                                <label class="relative">
                                    <input type="radio" name="ticket" class="peer sr-only" checked>
                                    <div class="bg-black/50 border-2 border-gray-700 rounded-lg p-4 cursor-pointer peer-checked:border-yellow-500 peer-checked:bg-yellow-500/10">
                                        <h4 class="font-bold">Early Bird</h4>
                                        <p class="text-2xl font-bold text-yellow-400">Rp 250K</p>
                                        <p class="text-xs text-gray-400">Berlaku sampai 31 Okt</p>
                                    </div>
                                </label>
                                <label class="relative">
                                    <input type="radio" name="ticket" class="peer sr-only">
                                    <div class="bg-black/50 border-2 border-gray-700 rounded-lg p-4 cursor-pointer peer-checked:border-yellow-500 peer-checked:bg-yellow-500/10">
                                        <h4 class="font-bold">Regular</h4>
                                        <p class="text-2xl font-bold">Rp 350K</p>
                                        <p class="text-xs text-gray-400">1 Nov - 14 Nov</p>
                                    </div>
                                </label>
                                <label class="relative">
                                    <input type="radio" name="ticket" class="peer sr-only">
                                    <div class="bg-black/50 border-2 border-gray-700 rounded-lg p-4 cursor-pointer peer-checked:border-yellow-500 peer-checked:bg-yellow-500/10">
                                        <h4 class="font-bold">On The Spot</h4>
                                        <p class="text-2xl font-bold">Rp 500K</p>
                                        <p class="text-xs text-gray-400">Hari H</p>
                                    </div>
                                </label>
                            </div>
                        </div>
                        
                        <div>
                            <label class="block text-sm font-medium mb-2">Kode Referral (Opsional)</label>
                            <input type="text" class="w-full bg-black/50 border border-gray-700 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-yellow-500">
                        </div>
                        
                        <div class="flex items-start">
                            <input type="checkbox" id="terms" class="mt-1 mr-3">
                            <label for="terms" class="text-sm">
                                Saya menyetujui <a href="#" class="text-yellow-400 hover:underline">Syarat & Ketentuan</a> dan <a href="#" class="text-yellow-400 hover:underline">Kebijakan Privasi</a>
                            </label>
                        </div>
                        
                        <button type="submit" class="w-full bitcoin-gradient text-black font-bold py-4 rounded-lg hover:opacity-90 transition glow">
                            DAFTAR SEKARANG
                        </button>
                    </form>
                    
                    <div id="successMessage" class="hidden mt-6 p-4 bg-green-900/30 border border-green-500 rounded-lg text-green-400 text-center">
                        <i class="fas fa-check-circle mr-2"></i>
                        Pendaftaran berhasil! Kami akan mengirimkan e-tiket ke email Anda.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 border-t border-gray-800">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-4 gap-8 mb-8">
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <i class="fab fa-bitcoin text-2xl text-yellow-500"></i>
                        <h3 class="crypto-font text-xl font-bold">CRYPTO SUMMIT</h3>
                    </div>
                    <p class="text-gray-400 text-sm">
                        Acara tahunan terbesar komunitas cryptocurrency di Indonesia
                    </p>
                </div>
                
                <div>
                    <h4 class="font-bold mb-4">Quick Links</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#about" class="hover:text-yellow-400">Tentang</a></li>
                        <li><a href="#agenda" class="hover:text-yellow-400">Agenda</a></li>
                        <li><a href="#speakers" class="hover:text-yellow-400">Pembicara</a></li>
                        <li><a href="#location" class="hover:text-yellow-400">Lokasi</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="font-bold mb-4">Support</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li><a href="#" class="hover:text-yellow-400">FAQ</a></li>
                        <li><a href="#" class="hover:text-yellow-400">Contact</a></li>
                        <li><a href="#" class="hover:text-yellow-400">Sponsorship</a></li>
                        <li><a href="#" class="hover:text-yellow-400">Media Partner</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="font-bold mb-4">Connect With Us</h4>
                    <div class="flex space-x-4 mb-4">
                        <a href="#" class="text-gray-400 hover:text-yellow-400 text-xl">
                            <i class="fab fa-facebook"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-yellow-400 text-xl">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-yellow-400 text-xl">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-yellow-400 text-xl">
                            <i class="fab fa-linkedin"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-yellow-400 text-xl">
                            <i class="fab fa-telegram"></i>
                        </a>
                    </div>
                    <p class="text-gray-400 text-sm">
                        Download our app:<br>
                        <a href="#" class="inline-block mt-2">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg" alt="Google Play" class="h-8">
                        </a>
                    </p>
                </div>
            </div>
            
            <div class="pt-8 border-t border-gray-800 text-center text-gray-500 text-sm">
                <p>&copy; 2024 Crypto Bitcoin Gathering. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        const closeMenu = document.getElementById('close-menu');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.add('active');
        });
        
        closeMenu.addEventListener('click', () => {
            mobileMenu.classList.remove('active');
        });
        
        // Close mobile menu when clicking on a link
        const mobileMenuLinks = mobileMenu.querySelectorAll('a');
        mobileMenuLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.remove('active');
            });
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Registration form handling
        document.getElementById('registrationForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Show success message
            document.getElementById('successMessage').classList.remove('hidden');
            
            // Reset form
            this.reset();
            
            // Scroll to success message
            document.getElementById('successMessage').scrollIntoView({ behavior: 'smooth' });
            
            // Hide message after 5 seconds
            setTimeout(() => {
                document.getElementById('successMessage').classList.add('hidden');
            }, 5000);
        });

        // WhatsApp share functionality
        document.getElementById('whatsapp-share').addEventListener('click', function(e) {
            e.preventDefault();
            
            const url = encodeURIComponent(window.location.href);
            const text = encodeURIComponent("Yuk, hadiri Crypto Bitcoin Gathering 2024! Acara terbesar komunitas crypto di Indonesia. Daftar sekarang juga!");
            
            window.open(`https://wa.me/?text=${text}%20${url}`, '_blank');
        });

        // Copy link functionality
        document.getElementById('copy-link').addEventListener('click', function() {
            const url = window.location.href;
            
            // Copy to clipboard
            navigator.clipboard.writeText(url).then(() => {
                // Show toast notification
                const toast = document.getElementById('toast');
                const toastMessage = document.getElementById('toast-message');
                
                toastMessage.textContent = 'Link berhasil disalin!';
                toast.classList.add('show');
                
                // Hide toast after 3 seconds
                setTimeout(() => {
                    toast.classList.remove('show');
                }, 3000);
            }).catch(err => {
                console.error('Failed to copy: ', err);
                
                // Fallback for older browsers
                const textArea = document.createElement('textarea');
                textArea.value = url;
                document.body.appendChild(textArea);
                textArea.focus();
                textArea.select();
                
                try {
                    document.execCommand('copy');
                    
                    // Show toast notification
                    const toast = document.getElementById('toast');
                    const toastMessage = document.getElementById('toast-message');
                    
                    toastMessage.textContent = 'Link berhasil disalin!';
                    toast.classList.add('show');
                    
                    // Hide toast after 3 seconds
                    setTimeout(() => {
                        toast.classList.remove('show');
                    }, 3000);
                } catch (err) {
                    console.error('Failed to copy: ', err);
                }
                
                document.body.removeChild(textArea);
            });
        });

        // Add animation on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -100px 0px'
        };

        const observer = new IntersectionObserver(function(entries) {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        // Observe all sections
        document.querySelectorAll('section').forEach(section => {
            section.style.opacity = '0';
            section.style.transform = 'translateY(20px)';
            section.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
            observer.observe(section);
        });
    </script>
</body>
</html>
