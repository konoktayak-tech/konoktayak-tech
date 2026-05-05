<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oktay Konak - Kişisel Web Sayfası</title>
    <!-- Tailwind CSS (Tasarım için) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome (İkonlar için) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <style>
        body { font-family: 'Inter', sans-serif; }
        /* Özel animasyonlar */
        .fade-in { animation: fadeIn 1s ease-in-out; }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-200 antialiased selection:bg-blue-500 selection:text-white">

    <!-- Ana Konteyner -->
    <div class="max-w-4xl mx-auto px-6 py-12">

        <!-- 1. HERO (GİRİŞ) BÖLÜMÜ -->
        <header class="text-center mb-16 fade-in">
            <h1 class="text-5xl md:text-6xl font-bold mb-4 text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-indigo-500">
                Oktay Konak
            </h1>
            <p class="text-xl text-slate-400 mb-6 font-light">
                Sosyal Bilgiler Öğretmeni | YBS Öğrencisi | Eğitim Teknolojileri
            </p>
            <p class="text-sm text-slate-500 mb-6">
                <i class="fas fa-map-marker-alt mr-1"></i> Konya, Türkiye &nbsp; | &nbsp; <i class="fas fa-phone mr-1"></i> 0539 386 50 55
            </p>
            
            <!-- Sosyal Medya İkonları -->
            <div class="flex justify-center space-x-6 text-2xl">
                <a href="https://konoktayak-tech.github.io/" class="text-slate-400 hover:text-blue-400 transition" target="_blank" title="Web Sitem"><i class="fas fa-globe"></i></a>
                <a href="#" class="text-slate-400 hover:text-blue-600 transition" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="https://github.com/konoktayak-tech" class="text-slate-400 hover:text-white transition" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
                <a href="mailto:konoktayak@gmail.com" class="text-slate-400 hover:text-red-500 transition" target="_blank" title="E-Posta"><i class="fas fa-envelope"></i></a>
            </div>
        </header>

        <!-- 2. HAKKIMDA BÖLÜMÜ -->
        <section class="bg-slate-800 rounded-2xl p-8 mb-10 shadow-lg fade-in" style="animation-delay: 0.2s;">
            <h2 class="text-2xl font-semibold mb-4 border-b border-slate-700 pb-2 flex items-center">
                <i class="fas fa-user-astronaut mr-3 text-blue-400"></i> Hakkımda
            </h2>
            <p class="text-slate-300 leading-relaxed">
                Merhaba, ben <strong>Oktay Konak</strong>. 1997-2007 yılları arasında turizm sektöründe çalışarak önemli operasyonel deneyimler kazandım. 2007 yılından itibaren MEB bünyesinde Sosyal Bilgiler Öğretmeni olarak görev yapmaktayım. Eğitimde yapay zeka entegrasyonu, ekolojik okuryazarlık ve proje tabanlı öğrenme alanlarında aktif çalışmalar yürütüyorum. Aynı zamanda Ankara Üniversitesi Yönetim Bilişim Sistemleri (YBS) bölümünde lisans eğitimime devam ederek teknoloji, sistem analizi ve proje yönetimi alanlarındaki vizyonumu genişletiyorum.
            </p>
        </section>

        <!-- 3. PROJELER VE DENEYİM (2 KOLONLU) -->
        <section class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-10 fade-in" style="animation-delay: 0.4s;">
            <!-- Sol Kolon -->
            <div class="bg-slate-800 rounded-2xl p-8 shadow-lg">
                <h3 class="text-xl font-semibold mb-4 text-indigo-400"><i class="fas fa-lightbulb mr-2"></i> Projelerim</h3>
                <ul class="space-y-4 text-slate-300">
                    <li><strong class="text-white block">ECO-FRIENDS (eTwinning)</strong> Yapay zeka ve çevre bilinci odaklı uluslararası eğitim projesi koordinatörlüğü.</li>
                    <li><strong class="text-white block">TÜBİTAK Bilim Söyleşileri</strong> "Makro Alemden Nano Aleme Yolculuk!" başlıklı organizasyon.</li>
                </ul>

                <h3 class="text-xl font-semibold mt-8 mb-4 text-indigo-400"><i class="fas fa-briefcase mr-2"></i> İş Deneyimi</h3>
                <ul class="space-y-4 text-slate-300">
                    <li><strong class="text-white block">MEB (Milli Eğitim Bakanlığı)</strong> Sosyal Bilgiler Öğretmeni (Şubat 2007 - Devam Ediyor)</li>
                    <li><strong class="text-white block">Turizm Sektörü</strong> Operasyon ve Müşteri İlişkileri (1997 - 2007)</li>
                </ul>
            </div>

            <!-- Sağ Kolon -->
            <div class="bg-slate-800 rounded-2xl p-8 shadow-lg">
                <h3 class="text-xl font-semibold mb-4 text-indigo-400"><i class="fas fa-code-branch mr-2"></i> Çalışma Alanları</h3>
                <ul class="space-y-4 text-slate-300">
                    <li><strong class="text-white block">Eğitimde Yapay Zeka</strong> Ders süreçlerine AI araçlarının, dijital avatarların ve içerik üretiminin entegrasyonu.</li>
                    <li><strong class="text-white block">Öğrenci Gelişim Analizi</strong> Akademik ve davranışsal verilerin sistematik rehabilitasyonu.</li>
                </ul>

                <h3 class="text-xl font-semibold mt-8 mb-4 text-indigo-400"><i class="fas fa-graduation-cap mr-2"></i> Eğitim</h3>
                <ul class="space-y-4 text-slate-300">
                    <li><strong class="text-white block">Ankara Üniversitesi</strong> Yönetim Bilişim Sistemleri (Lisans - Devam Ediyor)</li>
                    <li><strong class="text-white block">Sosyal Bilgiler Öğretmenliği</strong> Lisans Eğitimi</li>
                </ul>
            </div>
        </section>

        <!-- 4. YETKİNLİKLER (TECH STACK) -->
        <section class="bg-slate-800 rounded-2xl p-8 mb-10 shadow-lg fade-in" style="animation-delay: 0.6s;">
            <h2 class="text-2xl font-semibold mb-6 border-b border-slate-700 pb-2 flex items-center">
                <i class="fas fa-laptop-code mr-3 text-blue-400"></i> Yetkinlikler & Araçlar
            </h2>
            <div class="flex flex-wrap gap-4">
                <span class="px-4 py-2 bg-slate-700 rounded-lg flex items-center space-x-2 border border-slate-600 hover:bg-slate-600 transition cursor-default">
                    <i class="fas fa-network-wired text-blue-400"></i><span>Yönetim Bilişim Sistemleri</span>
                </span>
                <span class="px-4 py-2 bg-slate-700 rounded-lg flex items-center space-x-2 border border-slate-600 hover:bg-slate-600 transition cursor-default">
                    <i class="fas fa-robot text-purple-400"></i><span>Yapay Zeka (AI) Araçları</span>
                </span>
                <span class="px-4 py-2 bg-slate-700 rounded-lg flex items-center space-x-2 border border-slate-600 hover:bg-slate-600 transition cursor-default">
                    <i class="fas fa-chart-line text-green-400"></i><span>Proje Yönetimi (PERT/CPM)</span>
                </span>
                <span class="px-4 py-2 bg-slate-700 rounded-lg flex items-center space-x-2 border border-slate-600 hover:bg-slate-600 transition cursor-default">
                    <i class="fab fa-github text-white"></i><span>GitHub & Versiyon Kontrolü</span>
                </span>
                <span class="px-4 py-2 bg-slate-700 rounded-lg flex items-center space-x-2 border border-slate-600 hover:bg-slate-600 transition cursor-default">
                    <i class="fas fa-users text-yellow-400"></i><span>Eğitim Yönetimi ve Liderlik</span>
                </span>
            </div>
        </section>

        <!-- 5. GITHUB İSTATİSTİKLERİ -->
        <section class="mb-12 fade-in" style="animation-delay: 0.8s;">
            <h2 class="text-2xl font-semibold mb-6 text-center text-slate-200">GitHub İstatistiklerim</h2>
            <div class="flex flex-col md:flex-row justify-center items-center gap-4 mb-4">
                <img src="https://github-readme-stats.vercel.app/api?username=konoktayak-tech&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=1e293b" alt="GitHub Stats" class="rounded-xl shadow-lg w-full md:w-auto" />
                <img src="https://github-readme-streak-stats.herokuapp.com/?user=konoktayak-tech&theme=tokyonight&hide_border=true&background=1e293b" alt="GitHub Streak" class="rounded-xl shadow-lg w-full md:w-auto" />
            </div>
            <div class="flex justify-center">
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=konoktayak-tech&layout=compact&theme=tokyonight&hide_border=true&bg_color=1e293b&langs_count=8" alt="Top Languages" class="rounded-xl shadow-lg w-full md:w-auto" />
            </div>
        </section>

        <!-- 6. FOOTER (İLETİŞİM) -->
        <footer class="text-center mt-16 pt-8 border-t border-slate-800 fade-in" style="animation-delay: 1s;">
            <p class="text-slate-400 mb-4">Eğitim, projeler veya YBS odaklı konularda iletişime geçebilirsiniz:</p>
            <a href="mailto:konoktayak@gmail.com" class="inline-flex items-center px-6 py-3 bg-blue-600 hover:bg-blue-500 text-white rounded-full font-medium transition shadow-lg shadow-blue-500/30">
                <i class="fas fa-envelope mr-2"></i> Bana E-Posta Gönder
            </a>
            <p class="text-slate-600 mt-10 text-sm">© 2026 Oktay Konak. Tüm hakları saklıdır.</p>
        </footer>

    </div>

</body>
</html>
