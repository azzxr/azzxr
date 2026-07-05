<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Modern - azzxr</title>
    <!-- Tailwind CSS CDN untuk styling cepat & modern -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font-Awesome untuk ikon-ikon menarik -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Poppins -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #0b132b;
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0b132b;
        }
        ::-webkit-scrollbar-thumb {
            background: #1c2541;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #3a506b;
        }
        /* Animasi gradasi glow */
        .glow-effect {
            box-shadow: 0 0 25px rgba(0, 180, 216, 0.2);
        }
    </style>
</head>
<body class="text-slate-200 min-h-screen flex flex-col justify-between overflow-x-hidden selection:bg-cyan-500 selection:text-slate-900">

    <!-- Efek Latar Belakang Cahaya Biru Bulat (Glow) -->
    <div class="absolute top-[-10%] left-[-10%] w-[50vw] h-[50vw] rounded-full bg-cyan-600/10 blur-[120px] pointer-events-none"></div>
    <div class="absolute bottom-[-10%] right-[-10%] w-[50vw] h-[50vw] rounded-full bg-blue-600/10 blur-[120px] pointer-events-none"></div>

    <!-- HEADER / NAVIGATION -->
    <header class="sticky top-0 z-50 backdrop-blur-md bg-slate-950/70 border-b border-slate-800/80 transition-all duration-300">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <!-- Logo / Name -->
            <a href="#" class="text-xl font-bold tracking-wider text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500 hover:opacity-80 transition-opacity">
                AZZXR<span class="text-cyan-400">.</span>
            </a>

            <!-- Desktop Nav -->
            <nav class="hidden md:flex space-x-8 text-sm font-medium">
                <a href="#beranda" class="text-cyan-400 hover:text-cyan-300 transition-colors">Beranda</a>
                <a href="#tentang" class="text-slate-300 hover:text-cyan-400 transition-colors">Tentang Saya</a>
                <a href="#proyek" class="text-slate-300 hover:text-cyan-400 transition-colors">Proyek</a>
                <a href="#kontak" class="text-slate-300 hover:text-cyan-400 transition-colors">Kontak</a>
            </nav>

            <!-- Tombol Aksi -->
            <div class="hidden md:block">
                <a href="#kontak" class="px-5 py-2.5 rounded-full bg-gradient-to-r from-cyan-500 to-blue-600 text-slate-950 font-semibold text-sm shadow-lg shadow-cyan-500/20 hover:shadow-cyan-500/40 hover:scale-105 transition-all duration-300">
                    Hubungi Saya
                </a>
            </div>

            <!-- Mobile Menu Button -->
            <button id="menu-btn" class="md:hidden text-2xl text-slate-300 focus:outline-none">
                <i class="fa-solid fa-bars"></i>
            </button>
        </div>

        <!-- Mobile Nav Menu (Hidden by default) -->
        <div id="mobile-menu" class="hidden md:hidden px-6 pt-2 pb-6 bg-slate-950/95 border-b border-slate-850 flex flex-col space-y-4 text-center">
            <a href="#beranda" class="mobile-link text-cyan-400 py-2">Beranda</a>
            <a href="#tentang" class="mobile-link text-slate-300 hover:text-cyan-400 py-2 transition-colors">Tentang Saya</a>
            <a href="#proyek" class="mobile-link text-slate-300 hover:text-cyan-400 py-2 transition-colors">Proyek</a>
            <a href="#kontak" class="mobile-link text-slate-300 hover:text-cyan-400 py-2 transition-colors">Kontak</a>
            <a href="#kontak" class="mobile-link py-2.5 rounded-full bg-gradient-to-r from-cyan-500 to-blue-600 text-slate-950 font-semibold text-sm">Hubungi Saya</a>
        </div>
    </header>

    <main class="flex-grow">
        <!-- HERO SECTION -->
        <section id="beranda" class="max-w-6xl mx-auto px-6 pt-20 pb-16 md:py-32 flex flex-col-reverse md:flex-row items-center justify-between gap-12 relative">
            <div class="flex-1 text-center md:text-left space-y-6">
                <div class="inline-flex items-center gap-2 px-3 py-1.5 rounded-full bg-cyan-500/10 border border-cyan-500/30 text-cyan-400 text-xs font-semibold uppercase tracking-wider">
                    <span class="w-2 h-2 rounded-full bg-cyan-400 animate-pulse"></span> Tersedia Untuk Proyek Baru
                </div>
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight leading-tight">
                    Hai, Saya <span class="text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500">azzxr</span>
                </h1>
                <h2 class="text-xl sm:text-2xl font-medium text-slate-400">
                    Kreator Digital & Pengembang Web Kreatif
                </h2>
                <p class="text-slate-400 max-w-lg mx-auto md:mx-0 leading-relaxed text-sm sm:text-base">
                    Saya membuat pengalaman digital yang menawan, fungsional, dan modern dengan fokus pada keindahan estetika visual biru futuristik serta performa tinggi.
                </p>
                <div class="flex flex-wrap justify-center md:justify-start gap-4 pt-4">
                    <a href="#proyek" class="px-6 py-3 rounded-xl bg-gradient-to-r from-cyan-500 to-blue-600 text-slate-950 font-bold hover:shadow-lg hover:shadow-cyan-500/30 hover:scale-[1.02] transition-all">
                        Lihat Portofolio <i class="fa-solid fa-arrow-right ml-2 text-xs"></i>
                    </a>
                    <a href="#tentang" class="px-6 py-3 rounded-xl bg-slate-900 border border-slate-750 hover:bg-slate-800 text-slate-200 font-semibold transition-all">
                        Selengkapnya
                    </a>
                </div>
            </div>

            <!-- Avatar Placeholder dengan Glow & Animasi Melayang -->
            <div class="flex-1 flex justify-center relative">
                <div class="w-64 h-64 sm:w-80 sm:h-80 rounded-full bg-gradient-to-tr from-cyan-500 to-blue-600 p-[3px] shadow-[0_0_50px_rgba(6,182,212,0.3)] animate-[bounce_5s_infinite_ease-in-out]">
                    <div class="w-full h-full rounded-full bg-slate-950 flex flex-col items-center justify-center overflow-hidden relative">
                        <i class="fa-solid fa-code text-6xl text-cyan-400 mb-2"></i>
                        <span class="text-slate-500 text-xs font-mono">&lt;azzxr /&gt;</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- TENTANG SAYA -->
        <section id="tentang" class="py-20 bg-slate-950/50 border-y border-slate-900">
            <div class="max-w-6xl mx-auto px-6">
                <div class="text-center max-w-xl mx-auto mb-16">
                    <h2 class="text-3xl font-bold tracking-tight text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500 mb-3">Tentang Saya</h2>
                    <div class="h-1 w-16 bg-cyan-500 mx-auto rounded-full mb-4"></div>
                    <p class="text-slate-400 text-sm">Menyelami keindahan dalam baris kode dan desain minimalis.</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                    <div class="space-y-6">
                        <h3 class="text-2xl font-bold text-slate-200">Menciptakan Solusi Digital Terbaik</h3>
                        <p class="text-slate-400 leading-relaxed text-sm">
                            Saya senang mengeksplorasi teknologi baru untuk menciptakan solusi kreatif bagi masalah web modern. Dengan dasar visual yang bersih, navigasi yang intuitif, dan responsivitas penuh, saya memastikan setiap pengguna mendapatkan pengalaman terbaik.
                        </p>
                        <!-- Skill Chips -->
                        <div class="space-y-3">
                            <h4 class="text-sm font-semibold uppercase tracking-wider text-cyan-400">Teknologi Terpilih:</h4>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-800 text-xs text-slate-300 font-medium hover:border-cyan-500/50 hover:text-cyan-400 transition-all"><i class="fa-brands fa-html5 text-orange-500 mr-1.5"></i>HTML5</span>
                                <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-800 text-xs text-slate-300 font-medium hover:border-cyan-500/50 hover:text-cyan-400 transition-all"><i class="fa-brands fa-css3-alt text-blue-500 mr-1.5"></i>CSS3</span>
                                <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-800 text-xs text-slate-300 font-medium hover:border-cyan-500/50 hover:text-cyan-400 transition-all"><i class="fa-brands fa-js text-yellow-500 mr-1.5"></i>JavaScript</span>
                                <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-800 text-xs text-slate-300 font-medium hover:border-cyan-500/50 hover:text-cyan-400 transition-all"><i class="fa-brands fa-github text-slate-200 mr-1.5"></i>Git & GitHub</span>
                                <span class="px-3 py-1.5 rounded-lg bg-slate-900 border border-slate-800 text-xs text-slate-300 font-medium hover:border-cyan-500/50 hover:text-cyan-400 transition-all"><i class="fa-brands fa-css3-alt text-cyan-400 mr-1.5"></i>Tailwind CSS</span>
                            </div>
                        </div>
                    </div>

                    <!-- Statistik Sederhana / Pencapaian -->
                    <div class="grid grid-cols-2 gap-6">
                        <div class="p-6 rounded-2xl bg-slate-900/60 border border-slate-800 hover:border-cyan-500/30 transition-all group">
                            <h4 class="text-4xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500 mb-2 group-hover:scale-105 transition-transform duration-300">10+</h4>
                            <p class="text-xs uppercase tracking-wider font-semibold text-slate-400">Proyek Selesai</p>
                        </div>
                        <div class="p-6 rounded-2xl bg-slate-900/60 border border-slate-800 hover:border-cyan-500/30 transition-all group">
                            <h4 class="text-4xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500 mb-2 group-hover:scale-105 transition-transform duration-300">99%</h4>
                            <p class="text-xs uppercase tracking-wider font-semibold text-slate-400">Kepuasan Desain</p>
                        </div>
                        <div class="p-6 rounded-2xl bg-slate-900/60 border border-slate-800 hover:border-cyan-500/30 transition-all group">
                            <h4 class="text-4xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500 mb-2 group-hover:scale-105 transition-transform duration-300">2+</h4>
                            <p class="text-xs uppercase tracking-wider font-semibold text-slate-400">Tahun Belajar</p>
                        </div>
                        <div class="p-6 rounded-2xl bg-slate-900/60 border border-slate-800 hover:border-cyan-500/30 transition-all group">
                            <h4 class="text-4xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500 mb-2 group-hover:scale-105 transition-transform duration-300">24/7</h4>
                            <p class="text-xs uppercase tracking-wider font-semibold text-slate-400">Dukungan Kreatif</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- PROYEK PILIHAN -->
        <section id="proyek" class="py-20">
            <div class="max-w-6xl mx-auto px-6">
                <div class="text-center max-w-xl mx-auto mb-16">
                    <h2 class="text-3xl font-bold tracking-tight text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500 mb-3">Proyek Unggulan</h2>
                    <div class="h-1 w-16 bg-cyan-500 mx-auto rounded-full mb-4"></div>
                    <p class="text-slate-400 text-sm">Beberapa karya digital yang dirancang dengan dedikasi penuh.</p>
                </div>

                <!-- Grid Proyek -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Proyek 1 -->
                    <div class="rounded-2xl overflow-hidden bg-slate-900 border border-slate-800/80 hover:border-cyan-500/40 hover:-translate-y-2 transition-all duration-300 flex flex-col h-full group">
                        <!-- Preview Box -->
                        <div class="h-48 bg-gradient-to-br from-cyan-900/40 to-slate-950 flex items-center justify-center relative overflow-hidden">
                            <i class="fa-solid fa-laptop-code text-5xl text-cyan-400/80 group-hover:scale-110 transition-transform duration-300"></i>
                            <div class="absolute inset-0 bg-cyan-500/10 opacity-0 group-hover:opacity-100 transition-opacity"></div>
                        </div>
                        <div class="p-6 flex flex-col justify-between flex-grow space-y-4">
                            <div>
                                <h3 class="text-lg font-bold text-slate-100 group-hover:text-cyan-400 transition-colors">Situs Web Pribadi V1</h3>
                                <p class="text-slate-400 text-xs mt-2 line-clamp-2">Situs web portofolio pertama saya yang dibangun sepenuhnya menggunakan HTML semantik dan CSS kustom bertema neon.</p>
                            </div>
                            <div class="flex items-center justify-between pt-2">
                                <span class="text-xs text-slate-500 font-mono">HTML, CSS, JS</span>
                                <a href="#" class="text-cyan-400 hover:text-cyan-300 text-sm font-semibold flex items-center gap-1.5">Demo <i class="fa-solid fa-arrow-up-right-from-square text-xs"></i></a>
                            </div>
                        </div>
                    </div>

                    <!-- Proyek 2 -->
                    <div class="rounded-2xl overflow-hidden bg-slate-900 border border-slate-800/80 hover:border-cyan-500/40 hover:-translate-y-2 transition-all duration-300 flex flex-col h-full group">
                        <!-- Preview Box -->
                        <div class="h-48 bg-gradient-to-br from-blue-900/40 to-slate-950 flex items-center justify-center relative overflow-hidden">
                            <i class="fa-solid fa-cubes text-5xl text-blue-400/80 group-hover:scale-110 transition-transform duration-300"></i>
                            <div class="absolute inset-0 bg-blue-500/10 opacity-0 group-hover:opacity-100 transition-opacity"></div>
                        </div>
                        <div class="p-6 flex flex-col justify-between flex-grow space-y-4">
                            <div>
                                <h3 class="text-lg font-bold text-slate-100 group-hover:text-cyan-400 transition-colors">Dasbor Aplikasi Biru</h3>
                                <p class="text-slate-400 text-xs mt-2 line-clamp-2">Desain antarmuka panel kontrol interaktif yang bersih untuk analisis data visual modern.</p>
                            </div>
                            <div class="flex items-center justify-between pt-2">
                                <span class="text-xs text-slate-500 font-mono">Tailwind, React</span>
                                <a href="#" class="text-cyan-400 hover:text-cyan-300 text-sm font-semibold flex items-center gap-1.5">Demo <i class="fa-solid fa-arrow-up-right-from-square text-xs"></i></a>
                            </div>
                        </div>
                    </div>

                    <!-- Proyek 3 -->
                    <div class="rounded-2xl overflow-hidden bg-slate-900 border border-slate-800/80 hover:border-cyan-500/40 hover:-translate-y-2 transition-all duration-300 flex flex-col h-full group">
                        <!-- Preview Box -->
                        <div class="h-48 bg-gradient-to-br from-indigo-900/40 to-slate-950 flex items-center justify-center relative overflow-hidden">
                            <i class="fa-solid fa-wand-magic-sparkles text-5xl text-indigo-400/80 group-hover:scale-110 transition-transform duration-300"></i>
                            <div class="absolute inset-0 bg-indigo-500/10 opacity-0 group-hover:opacity-100 transition-opacity"></div>
                        </div>
                        <div class="p-6 flex flex-col justify-between flex-grow space-y-4">
                            <div>
                                <h3 class="text-lg font-bold text-slate-100 group-hover:text-cyan-400 transition-colors">Generator Seni AI</h3>
                                <p class="text-slate-400 text-xs mt-2 line-clamp-2">Eksperimen integrasi API kecerdasan buatan untuk menghasilkan aset visual indah secara dinamis.</p>
                            </div>
                            <div class="flex items-center justify-between pt-2">
                                <span class="text-xs text-slate-500 font-mono">API, Tailwind, JS</span>
                                <a href="#" class="text-cyan-400 hover:text-cyan-300 text-sm font-semibold flex items-center gap-1.5">Demo <i class="fa-solid fa-arrow-up-right-from-square text-xs"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- HUBUNGI SAYA -->
        <section id="kontak" class="py-20 bg-slate-950/40 border-t border-slate-900">
            <div class="max-w-4xl mx-auto px-6">
                <div class="text-center max-w-xl mx-auto mb-12">
                    <h2 class="text-3xl font-bold tracking-tight text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500 mb-3">Mulai Berkolaborasi</h2>
                    <div class="h-1 w-16 bg-cyan-500 mx-auto rounded-full mb-4"></div>
                    <p class="text-slate-400 text-sm">Ada pertanyaan, ide proyek, atau sekadar ingin menyapa? Kirim pesan Anda di bawah ini!</p>
                </div>

                <div class="p-8 sm:p-10 rounded-3xl bg-slate-900/80 border border-slate-800 glow-effect">
                    <form id="contact-form" class="space-y-6">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                            <div class="space-y-2">
                                <label for="name" class="text-xs font-semibold uppercase tracking-wider text-slate-400">Nama Lengkap</label>
                                <input type="text" id="name" required class="w-full px-4 py-3 rounded-xl bg-slate-950 border border-slate-800 text-slate-200 focus:outline-none focus:border-cyan-500 transition-colors placeholder:text-slate-600 text-sm" placeholder="Nama Anda">
                            </div>
                            <div class="space-y-2">
                                <label for="email" class="text-xs font-semibold uppercase tracking-wider text-slate-400">Alamat Email</label>
                                <input type="email" id="email" required class="w-full px-4 py-3 rounded-xl bg-slate-950 border border-slate-800 text-slate-200 focus:outline-none focus:border-cyan-500 transition-colors placeholder:text-slate-600 text-sm" placeholder="anda@email.com">
                            </div>
                        </div>
                        <div class="space-y-2">
                            <label for="message" class="text-xs font-semibold uppercase tracking-wider text-slate-400">Pesan Anda</label>
                            <textarea id="message" rows="5" required class="w-full px-4 py-3 rounded-xl bg-slate-950 border border-slate-800 text-slate-200 focus:outline-none focus:border-cyan-500 transition-colors placeholder:text-slate-600 text-sm resize-none" placeholder="Tulis rincian pesan Anda di sini..."></textarea>
                        </div>
                        <button type="submit" class="w-full py-4 rounded-xl bg-gradient-to-r from-cyan-500 to-blue-600 text-slate-950 font-bold hover:shadow-lg hover:shadow-cyan-500/20 active:scale-[0.98] transition-all">
                            Kirim Pesan Sekarang <i class="fa-solid fa-paper-plane ml-2"></i>
                        </button>
                    </form>

                    <!-- Feedback Message Box (Custom modal alert fallback) -->
                    <div id="form-feedback" class="hidden mt-4 p-4 rounded-xl text-center text-sm font-semibold"></div>
                </div>
            </div>
        </section>
    </main>

    <!-- FOOTER -->
    <footer class="bg-slate-950 border-t border-slate-900 py-12">
        <div class="max-w-6xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6">
            <div>
                <a href="#" class="text-lg font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500">
                    AZZXR
                </a>
                <p class="text-xs text-slate-500 mt-2">© 2026 azzxr. Seluruh Hak Cipta Dilindungi.</p>
            </div>
            
            <!-- Sosial Media Ikon -->
            <div class="flex space-x-5 text-lg">
                <a href="https://github.com/azzxr" target="_blank" class="w-10 h-10 rounded-full bg-slate-900 border border-slate-850 flex items-center justify-center text-slate-400 hover:text-cyan-400 hover:border-cyan-500/50 transition-all"><i class="fa-brands fa-github"></i></a>
                <a href="#" class="w-10 h-10 rounded-full bg-slate-900 border border-slate-850 flex items-center justify-center text-slate-400 hover:text-cyan-400 hover:border-cyan-500/50 transition-all"><i class="fa-brands fa-instagram"></i></a>
                <a href="#" class="w-10 h-10 rounded-full bg-slate-900 border border-slate-850 flex items-center justify-center text-slate-400 hover:text-cyan-400 hover:border-cyan-500/50 transition-all"><i class="fa-brands fa-twitter"></i></a>
                <a href="#" class="w-10 h-10 rounded-full bg-slate-900 border border-slate-850 flex items-center justify-center text-slate-400 hover:text-cyan-400 hover:border-cyan-500/50 transition-all"><i class="fa-brands fa-linkedin-in"></i></a>
            </div>
        </div>
    </footer>

    <!-- INTERACTION LOGIC (JAVASCRIPT) -->
    <script>
        // Logika Toggle Menu Ponsel (Responsive Navbar)
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        const mobileLinks = document.querySelectorAll('.mobile-link');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
            const icon = menuBtn.querySelector('i');
            if (mobileMenu.classList.contains('hidden')) {
                icon.className = 'fa-solid fa-bars';
            } else {
                icon.className = 'fa-solid fa-xmark';
            }
        });

        // Menutup menu seluler setelah tautan diklik
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                menuBtn.querySelector('i').className = 'fa-solid fa-bars';
            });
        });

        // Pengiriman Formulir Kontak Simulasian dengan Kotak Pesan Ramah
        const contactForm = document.getElementById('contact-form');
        const feedbackBox = document.getElementById('form-feedback');

        contactForm.addEventListener('submit', (e) => {
            e.preventDefault();
            
            const name = document.getElementById('name').value;
            
            // Simulasikan status loading
            feedbackBox.className = "mt-4 p-4 rounded-xl text-center text-sm font-semibold bg-cyan-950/50 text-cyan-400 border border-cyan-500/30";
            feedbackBox.innerHTML = "<i class='fa-solid fa-circle-notch animate-spin mr-2'></i> Mengirim pesan...";
            feedbackBox.classList.remove('hidden');

            setTimeout(() => {
                // Tampilkan pesan berhasil
                feedbackBox.className = "mt-4 p-4 rounded-xl text-center text-sm font-semibold bg-emerald-950/50 text-emerald-400 border border-emerald-500/30";
                feedbackBox.innerHTML = `<i class="fa-solid fa-circle-check mr-2"></i> Terima kasih, ${name}! Pesan Anda berhasil dikirim secara simulasi.`;
                contactForm.reset();
                
                // Sembunyikan pesan sukses setelah 5 detik
                setTimeout(() => {
                    feedbackBox.classList.add('hidden');
                }, 5000);
            }, 1500);
        });

        // Efek transisi header saat digulir
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if (window.scrollY > 50) {
                header.classList.add('py-3', 'bg-slate-950/90');
                header.classList.remove('py-4', 'bg-slate-950/70');
            } else {
                header.classList.add('py-4', 'bg-slate-950/70');
                header.classList.remove('py-3', 'bg-slate-950/90');
            }
        });
    </script>
</body>
</html>
