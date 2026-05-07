<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oktay Konak - Kişisel Web Sayfası</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
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

    <div class="max-w-4xl mx-auto px-6 py-12">

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
            
            <div class="flex justify-center space-x-6 text-2xl">
                <a href="https://konoktayak-tech.github.io/" class="text-slate-400 hover:text-blue-400 transition" target="_blank" title="Web Sitem"><i class="fas fa-globe"></i></a>
                <a href="#" class="text-slate-400 hover:text-blue-600 transition" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="https://github.com/konoktayak-tech" class="text-slate-400 hover:text-white transition" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
                <a href="mailto:konoktayak@gmail.com" class="text-slate-400 hover:text-red-500 transition" target="_blank" title="E-Posta"><i class="fas fa-envelope"></i></a>
            </div>
        </header>

        <section class="bg-slate-800 rounded-2xl p-8 mb-10 shadow-lg fade-in" style="animation-delay: 0.2s;">
            <h2 class="text-2xl font-semibold mb-4 border-b border-slate-700 pb-2 flex items-center">
                <i class="fas fa-user-astronaut mr-3 text-blue-400"></i> Hakkımda
            </h2>
            <p class="text-slate-300 leading-relaxed">
                Merhaba, ben <strong>Oktay Konak</strong>. 1997-2007 yılları arasında turizm sektöründe çalışarak önemli operasyonel deneyimler kazandım. 2007 yılından itibaren MEB bünyesinde Sosyal Bilgiler Öğretmeni olarak görev yapmaktayım. Eğitimde yapay zeka entegrasyonu, ekolojik okuryazarlık ve proje tabanlı öğrenme alanlarında aktif çalışmalar yürütüyorum. Aynı zamanda Ankara Üniversitesi Yönetim Bilişim Sistemleri (YBS) bölümünde lisans eğitimime devam ederek teknoloji, sistem analizi ve proje yönetimi alanlarındaki vizyonumu genişletiyorum.
            </p>
        </section>

        <section class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-10 fade-in" style="animation-delay: 0.4s;">
            <div class="bg-slate-800 rounded-2xl p-8 shadow-lg
