<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASTANA ELEKTRONİK MAKİNA VE SANAYİ DIŞ TİCARET LTD. ŞTİ.</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #0A2647 0%, #144272 100%);
        }
        .accent-blue {
            color: #2C74B3;
        }
        .bg-accent-blue {
            background-color: #2C74B3;
        }
    </style>
</head>
<body class="font-sans bg-gray-50">
    <!-- Navigation -->
    <nav class="gradient-bg text-white p-4 fixed w-full z-50">
        <div class="container mx-auto flex justify-between items-center">
            <div class="text-xl font-bold">ASTANA ELEKTRONİK</div>
            <div class="hidden md:flex space-x-6">
                <a href="#home" class="hover:text-blue-200">Ana Sayfa</a>
                <a href="#about" class="hover:text-blue-200">Hakkımızda</a>
                <a href="#services" class="hover:text-blue-200">Hizmetler</a>
                <a href="#office" class="hover:text-blue-200">Ofisimiz</a>
                <a href="#contact" class="hover:text-blue-200">İletişim</a>
            </div>
            <button class="md:hidden">
                <i class="fas fa-bars"></i>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-24 pb-12 gradient-bg text-white">
        <div class="container mx-auto px-4 py-32">
            <div class="text-center">
                <h1 class="text-5xl font-bold mb-4">ASTANA ELEKTRONİK</h1>
                <p class="text-2xl mb-4">MAKİNA VE SANAYİ DIŞ TİCARET LTD. ŞTİ.</p>
                <p class="text-xl mb-8">Elektronik, Makina ve Dış Ticaret Alanında Güvenilir Çözüm Ortağınız</p>
                <button class="bg-white text-[#0A2647] px-8 py-3 rounded-full font-bold hover:bg-gray-100">
                    Hizmetlerimizi Keşfedin
                </button>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Hakkımızda</h2>
            <div class="max-w-3xl mx-auto text-center">
                <p class="text-gray-600 mb-6">
                    2024 yılında İstanbul'da kurulan firmamız, elektronik, makina ve dış ticaret alanlarında 
                    profesyonel çözümler sunmaktadır. Müşterilerimize en kaliteli hizmeti sunmak için sürekli 
                    gelişen ve yenilenen bir yapıya sahibiz.
                </p>
            </div>
        </div>
    </section>

    <!-- Office Showcase Section -->
    <section id="office" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Modern Ofisimiz</h2>
            <div class="grid md:grid-cols-2 gap-8 items-center">
                <img src="https://d41chssnpqdne.cloudfront.net/user_upload_by_module/chat_bot/files/65995943/SKjDtTYS90mh7KvR.jpg" 
                     alt="Astana Elektronik Modern Ofis" 
                     class="rounded-lg shadow-xl w-full">
                <div class="space-y-4">
                    <h3 class="text-2xl font-bold text-[#0A2647]">Kadıköy'deki Merkez Ofisimiz</h3>
                    <p class="text-gray-600">
                        Modern ve dinamik çalışma ortamımızda, en son teknoloji ile donatılmış ofisimizde 
                        müşterilerimize profesyonel hizmet sunuyoruz.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Hizmetlerimiz</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition-shadow">
                    <i class="fas fa-microchip text-4xl text-[#2C74B3] mb-4"></i>
                    <h3 class="text-xl font-bold mb-2">Elektronik Sistemler</h3>
                    <p class="text-gray-600">Endüstriyel elektronik çözümler ve otomasyon sistemleri</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition-shadow">
                    <i class="fas fa-cogs text-4xl text-[#2C74B3] mb-4"></i>
                    <h3 class="text-xl font-bold mb-2">Makina Üretimi</h3>
                    <p class="text-gray-600">Özel tasarım endüstriyel makina üretimi ve tedariki</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-xl transition-shadow">
                    <i class="fas fa-globe text-4xl text-[#2C74B3] mb-4"></i>
                    <h3 class="text-xl font-bold mb-2">Dış Ticaret</h3>
                    <p class="text-gray-600">Uluslararası ticaret ve aracılık hizmetleri</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">İletişime Geçin</h2>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="space-y-4">
                    <h3 class="text-xl font-bold text-[#0A2647]">İletişim Bilgileri</h3>
                    <p><i class="fas fa-map-marker-alt mr-2 text-[#2C74B3]"></i> Sahrayıcedit Mah. Atatürk Cad. No: 69 İç Kapı No: 235, Kadıköy/İstanbul</p>
                    <p><i class="fas fa-phone mr-2 text-[#2C74B3]"></i> Telefon: [Telefon Numarası]</p>
                    <p><i class="fas fa-envelope mr-2 text-[#2C74B3]"></i> E-posta: info@astanaelektronik.com</p>
                </div>
                <form class="space-y-4">
                    <input type="text" placeholder="Adınız" class="w-full p-2 border rounded">
                    <input type="email" placeholder="E-posta Adresiniz" class="w-full p-2 border rounded">
                    <textarea placeholder="Mesajınız" class="w-full p-2 border rounded h-32"></textarea>
                    <button class="gradient-bg text-white px-6 py-2 rounded hover:opacity-90">
                        Gönder
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="gradient-bg text-white py-8">
        <div class="container mx-auto px-4">
            <div class="text-center">
                <p class="mb-2">ASTANA ELEKTRONİK MAKİNA VE SANAYİ DIŞ TİCARET LİMİTED ŞİRKETİ</p>
                <p>&copy; 2025 Tüm hakları saklıdır.</p>
            </div>
        </div>
    </footer>
</body>
</html>
