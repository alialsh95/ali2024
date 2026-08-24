# ali2024
<!DOCTYPE html>
<html lang="ar" dir="rtl" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>عالم علي | Ali's World</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#FBBF24', // أصفر أساسي
                        secondary: '#38BDF8', // أزرق فاتح
                        accent: '#FB923C', // برتقالي
                        softGreen: '#4ADE80', // أخضر فاتح
                        softBg: '#FEFCE8', // خلفية صفراء فاتحة دافئة
                    },
                    fontFamily: {
                        sans: ['Tajawal', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts (Tajawal) -->
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;900&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body class="bg-softBg text-gray-800 font-sans selection:bg-primary selection:text-white">

    <!-- Navbar -->
    <nav class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur-md shadow-sm transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo -->
                <a href="#" class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-primary flex items-center justify-center text-white font-bold text-xl shadow-md">
                        💛
                    </div>
                    <span class="text-xl font-black text-gray-900" data-translate="site-title">عالم علي</span>
                </a>

                <!-- Desktop Menu -->
                <div class="hidden md:flex items-center gap-6 lg:gap-8">
                    <a href="#hero" class="text-gray-600 hover:text-primary font-medium transition" data-translate="nav-home">الرئيسية</a>
                    <a href="#achievements" class="text-gray-600 hover:text-primary font-medium transition" data-translate="nav-achievements">إنجازات علي</a>
                    <a href="#news" class="text-gray-600 hover:text-primary font-medium transition" data-translate="nav-news">آخر الأخبار</a>
                    <a href="#moments" class="text-gray-600 hover:text-primary font-medium transition" data-translate="nav-moments">علي وجدته</a>
                    <a href="#meetings" class="text-gray-600 hover:text-primary font-medium transition" data-translate="nav-meetings">مواعيد اللقاء</a>
                    <a href="#gallery" class="text-gray-600 hover:text-primary font-medium transition" data-translate="nav-gallery">آخر الصور</a>
                    <a href="#message" class="text-gray-600 hover:text-primary font-medium transition" data-translate="nav-message">رسالة من علي</a>
                </div>

                <!-- Actions (Lang Switcher & Mobile Button) -->
                <div class="flex items-center gap-4">
                    <button id="langToggle" class="bg-amber-100 hover:bg-amber-200 text-amber-800 px-3 py-1.5 rounded-full text-sm font-bold transition flex items-center gap-1.5">
                        <i class="fa-solid fa-globe"></i>
                        <span id="langText">English</span>
                    </button>
                    <button id="menuBtn" class="md:hidden text-gray-700 text-2xl focus:outline-none">
                        <i class="fa-solid fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu -->
        <div id="mobileMenu" class="hidden md:hidden bg-white border-b border-gray-100 px-4 pt-2 pb-6 space-y-3 shadow-lg">
            <a href="#hero" class="block text-gray-600 hover:text-primary font-medium py-2" data-translate="nav-home">الرئيسية</a>
            <a href="#achievements" class="block text-gray-600 hover:text-primary font-medium py-2" data-translate="nav-achievements">إنجازات علي</a>
            <a href="#news" class="block text-gray-600 hover:text-primary font-medium py-2" data-translate="nav-news">آخر الأخبار</a>
            <a href="#moments" class="block text-gray-600 hover:text-primary font-medium py-2" data-translate="nav-moments">علي وجدته</a>
            <a href="#meetings" class="block text-gray-600 hover:text-primary font-medium py-2" data-translate="nav-meetings">مواعيد اللقاء</a>
            <a href="#gallery" class="block text-gray-600 hover:text-primary font-medium py-2" data-translate="nav-gallery">آخر الصور</a>
            <a href="#message" class="block text-gray-600 hover:text-primary font-medium py-2" data-translate="nav-message">رسالة من علي</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="hero" class="pt-32 pb-20 md:pt-40 md:pb-32 relative overflow-hidden">
        <!-- Background Decorative Elements -->
        <div class="absolute top-10 left-10 text-primary/20 text-6xl animate-pulse">⭐</div>
        <div class="absolute bottom-10 right-10 text-secondary/30 text-7xl">☁️</div>
        <div class="absolute top-1/2 right-1/4 text-accent/20 text-5xl">🎈</div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div class="space-y-6 text-center lg:text-start">
                    <span class="inline-block bg-primary/20 text-amber-800 text-sm font-bold px-4 py-1.5 rounded-full" data-translate="hero-badge">
                        ✨ مرحباً بكم في عائلة علي
                    </span>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-black text-gray-900 leading-tight" data-translate="hero-title">
                        أهلًا بكم في عالم علي 💛
                    </h1>
                    <p class="text-lg sm:text-xl text-gray-600 max-w-xl mx-auto lg:mx-0" data-translate="hero-desc">
                        هنا تجدون آخر أخبار علي وإنجازاته وصوره ومواعيد لقائه وأجمل لحظاته مع العائلة.
                    </p>
                    <div class="flex flex-wrap justify-center lg:justify-start gap-4 pt-4">
                        <a href="#achievements" class="bg-primary hover:bg-amber-500 text-white font-bold px-8 py-3.5 rounded-2xl shadow-lg shadow-primary/30 transition transform hover:-translate-y-0.5" data-translate="hero-btn-1">
                            اكتشف عالم علي
                        </a>
                        <a href="#news" class="bg-white hover:bg-gray-50 text-gray-800 border border-gray-200 font-bold px-8 py-3.5 rounded-2xl shadow-sm transition" data-translate="hero-btn-2">
                            آخر الأخبار
                        </a>
                    </div>
                </div>

                <!-- Ali Main Image / Placeholder -->
                <div class="flex justify-center">
                    <div class="relative w-72 h-72 sm:w-96 sm:h-96 rounded-3xl bg-gradient-to-tr from-primary/30 to-secondary/35 p-3 shadow-2xl transform rotate-2 hover:rotate-0 transition duration-500">
                        <!-- [ضع صورة علي الرئيسية هنا] -->
                        <div id="ALI_MAIN_IMAGE" class="w-full h-full bg-white rounded-2xl flex flex-col items-center justify-center text-center p-6 border-4 border-dashed border-primary/40">
                            <i class="fa-solid fa-camera-retro text-5xl text-primary mb-3"></i>
                            <span class="text-gray-500 font-bold text-sm">[ضع صورة علي الرئيسية هنا]</span>
                            <span class="text-gray-400 text-xs mt-1">ALI_MAIN_IMAGE</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Achievements Section -->
    <section id="achievements" class="py-20 bg-white/50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl sm:text-4xl font-black text-gray-900 mb-4" data-translate="achievements-title">إنجازات علي 🏆</h2>
                <p class="text-gray-600 text-lg" data-translate="achievements-subtitle">كل خطوة صغيرة يصنعها علي هي إنجاز كبير نفخر به جميعاً.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Achievement Card 1 (Latest) -->
                <div class="bg-white rounded-3xl p-6 shadow-xl border-2 border-primary/40 relative transform hover:-translate-y-1 transition">
                    <span class="absolute -top-3 right-6 bg-primary text-white text-xs font-bold px-3 py-1 rounded-full shadow" data-translate="latest-badge">آخر إنجاز ⭐</span>
                    <!-- [أضف إنجاز علي هنا] -->
                    <div class="text-amber-500 text-3xl mb-4">🚀</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">[أضف إنجاز علي هنا]</h3>
                    <span class="inline-block text-xs font-semibold text-primary bg-primary/10 px-2.5 py-1 rounded-lg mb-3">[تاريخ الإنجاز هنا]</span>
                    <p class="text-gray-600 text-sm leading-relaxed">[وصف الإنجاز هنا]</p>
                </div>

                <!-- Achievement Card 2 -->
                <div class="bg-white rounded-3xl p-6 shadow-md border border-gray-100 hover:shadow-xl transition">
                    <div class="text-secondary text-3xl mb-4">🎈</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">[أضف إنجاز علي هنا]</h3>
                    <span class="inline-block text-xs font-semibold text-secondary bg-secondary/10 px-2.5 py-1 rounded-lg mb-3">[تاريخ الإنجاز هنا]</span>
                    <p class="text-gray-600 text-sm leading-relaxed">[وصف الإنجاز هنا]</p>
                </div>

                <!-- Achievement Card 3 -->
                <div class="bg-white rounded-3xl p-6 shadow-md border border-gray-100 hover:shadow-xl transition">
                    <div class="text-accent text-3xl mb-4">🌟</div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">[أضف إنجاز علي هنا]</h3>
                    <span class="inline-block text-xs font-semibold text-accent bg-accent/10 px-2.5 py-1 rounded-lg mb-3">[تاريخ الإنجاز هنا]</span>
                    <p class="text-gray-600 text-sm leading-relaxed">[وصف الإنجاز هنا]</p>
                </div>
            </div>
        </div>
    </section>

    <!-- News Section -->
    <section id="news" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl sm:text-4xl font-black text-gray-900 mb-4" data-translate="news-title">آخر أخبار علي 📰</h2>
                <p class="text-gray-600 text-lg" data-translate="news-subtitle">تابعوا معنا أحدث التفاصيل والقصص القصيرة اليومية.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- News Card 1 (New) -->
                <div class="bg-white rounded-3xl p-6 shadow-xl border-2 border-secondary/40 relative flex flex-col justify-between">
                    <div>
                        <span class="absolute -top-3 right-6 bg-secondary text-white text-xs font-bold px-3 py-1 rounded-full shadow" data-translate="new-badge">جديد</span>
                        <div class="flex items-center gap-2 text-xs text-gray-400 mb-3">
                            <i class="fa-regular fa-calendar"></i>
                            <span>[ضع تاريخ الخبر هنا]</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">[ضع الخبر هنا]</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-4">[ضع تفاصيل الخبر هنا]</p>
                    </div>
                    <button class="text-secondary font-bold text-sm flex items-center gap-1 hover:underline self-start">
                        <span data-translate="read-more">قراءة المزيد</span>
                        <i class="fa-solid fa-arrow-left"></i>
                    </button>
                </div>

                <!-- News Card 2 -->
                <div class="bg-white rounded-3xl p-6 shadow-md border border-gray-100 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-2 text-xs text-gray-400 mb-3">
                            <i class="fa-regular fa-calendar"></i>
                            <span>[ضع تاريخ الخبر هنا]</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">[ضع الخبر هنا]</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-4">[ضع تفاصيل الخبر هنا]</p>
                    </div>
                    <button class="text-secondary font-bold text-sm flex items-center gap-1 hover:underline self-start">
                        <span data-translate="read-more">قراءة المزيد</span>
                        <i class="fa-solid fa-arrow-left"></i>
                    </button>
                </div>

                <!-- News Card 3 -->
                <div class="bg-white rounded-3xl p-6 shadow-md border border-gray-100 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-2 text-xs text-gray-400 mb-3">
                            <i class="fa-regular fa-calendar"></i>
                            <span>[ضع تاريخ الخبر هنا]</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-900 mb-3">[ضع الخبر هنا]</h3>
                        <p class="text-gray-600 text-sm leading-relaxed mb-4">[ضع تفاصيل الخبر هنا]</p>
                    </div>
                    <button class="text-secondary font-bold text-sm flex items-center gap-1 hover:underline self-start">
                        <span data-translate="read-more">قراءة المزيد</span>
                        <i class="fa-solid fa-arrow-left"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Ali & Grandma (أو جدته) Section -->
    <section id="moments" class="py-20 bg-amber-50/50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl sm:text-4xl font-black text-gray-900 mb-4" data-translate="moments-title">علي وجدته 💛</h2>
                <p class="text-gray-600 text-lg" data-translate="moments-subtitle">أجمل اللحظات وأصدق الضحكات بين علي وجدته الغالية.</p>
            </div>

            <div class="bg-white rounded-3xl p-8 shadow-xl border border-amber-100 max-w-3xl mx-auto">
                <div class="flex items-center gap-4 mb-6">
                    <div class="w-12 h-12 rounded-full bg-amber-100 text-amber-600 flex items-center justify-center text-xl font-bold">
                        👵💛
                    </div>
                    <div>
                        <h3 class="text-xl font-bold text-gray-900">[ضع آخر تطورات علي وجدته هنا]</h3>
                        <span class="text-xs text-gray-400">[ضع التاريخ هنا]</span>
                    </div>
                </div>
                <p class="text-gray-600 leading-relaxed text-base">
                    [ضع التفاصيل هنا] مساحة مخصصة لسرد الحكايات واللحظات الجميلة التي تجمع بين علي وجدته، وكل يوم يحمل معه قصة جديدة ومميزة تملأ القلب سعادة.
                </p>
            </div>
        </div>
    </section>

    <!-- Meetings Section -->
    <section id="meetings" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl sm:text-4xl font-black text-gray-900 mb-4" data-translate="meetings-title">مواعيد لقاء علي 📅</h2>
                <p class="text-gray-600 text-lg" data-translate="meetings-subtitle">ترتيبات ومواعيد اللقاءات العائلية القادمة لزيارة علي.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <!-- Meeting Card 1 -->
                <div class="bg-white rounded-3xl p-6 shadow-xl border-l-8 border-primary flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <h3 class="text-xl font-bold text-gray-900">[اسم المناسبة أو اللقاء هنا]</h3>
                            <span class="bg-primary/20 text-amber-800 text-xs font-bold px-3 py-1 rounded-full">قريب جداً</span>
                        </div>
                        <div class="space-y-2 text-sm text-gray-600 mb-6">
                            <div class="flex items-center gap-2">
                                <i class="fa-regular fa-calendar text-primary"></i>
                                <span>[التاريخ هنا]</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fa-regular fa-clock text-primary"></i>
                                <span>[الوقت هنا]</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fa-solid fa-location-dot text-primary"></i>
                                <span>[المكان هنا]</span>
                            </div>
                        </div>
                    </div>
                    <p class="text-xs text-gray-500 bg-gray-50 p-3 rounded-xl border border-gray-100">
                        <strong data-translate="notes">ملاحظات:</strong> [ملاحظات إضافية هنا]
                    </p>
                </div>

                <!-- Meeting Card 2 -->
                <div class="bg-white rounded-3xl p-6 shadow-md border-l-8 border-secondary flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <h3 class="text-xl font-bold text-gray-900">[اسم المناسبة أو اللقاء هنا]</h3>
                            <span class="bg-secondary/20 text-sky-800 text-xs font-bold px-3 py-1 rounded-full" data-translate="upcoming">قادم</span>
                        </div>
                        <div class="space-y-2 text-sm text-gray-600 mb-6">
                            <div class="flex items-center gap-2">
                                <i class="fa-regular fa-calendar text-secondary"></i>
                                <span>[التاريخ هنا]</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fa-regular fa-clock text-secondary"></i>
                                <span>[الوقت هنا]</span>
                            </div>
                            <div class="flex items-center gap-2">
                                <i class="fa-solid fa-location-dot text-secondary"></i>
                                <span>[المكان هنا]</span>
                            </div>
                        </div>
                    </div>
                    <p class="text-xs text-gray-500 bg-gray-50 p-3 rounded-xl border border-gray-100">
                        <strong data-translate="notes">ملاحظات:</strong> [ملاحظات إضافية هنا]
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-20 bg-white/60">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl sm:text-4xl font-black text-gray-900 mb-4" data-translate="gallery-title">آخر صور علي 📸</h2>
                <p class="text-gray-600 text-lg" data-translate="gallery-subtitle">أجمل اللقطات والذكريات المصورة لعلي.</p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Photo 1 -->
                <div id="ALI_PHOTO_1" class="gallery-item aspect-square bg-gray-100 rounded-3xl border-2 border-dashed border-gray-300 flex flex-col items-center justify-center p-4 cursor-pointer hover:border-primary transition shadow-sm">
                    <i class="fa-solid fa-image text-3xl text-gray-400 mb-2"></i>
                    <span class="text-gray-500 font-bold text-sm">[صورة علي 1 هنا]</span>
                    <span class="text-xs text-gray-400 mt-1">ALI_PHOTO_1</span>
                </div>
                <!-- Photo 2 -->
                <div id="ALI_PHOTO_2" class="gallery-item aspect-square bg-gray-100 rounded-3xl border-2 border-dashed border-gray-300 flex flex-col items-center justify-center p-4 cursor-pointer hover:border-primary transition shadow-sm">
                    <i class="fa-solid fa-image text-3xl text-gray-400 mb-2"></i>
                    <span class="text-gray-500 font-bold text-sm">[صورة علي 2 هنا]</span>
                    <span class="text-xs text-gray-400 mt-1">ALI_PHOTO_2</span>
                </div>
                <!-- Photo 3 -->
                <div id="ALI_PHOTO_3" class="gallery-item aspect-square bg-gray-100 rounded-3xl border-2 border-dashed border-gray-300 flex flex-col items-center justify-center p-4 cursor-pointer hover:border-primary transition shadow-sm">
                    <i class="fa-solid fa-image text-3xl text-gray-400 mb-2"></i>
                    <span class="text-gray-500 font-bold text-sm">[صورة علي 3 هنا]</span>
                    <span class="text-xs text-gray-400 mt-1">ALI_PHOTO_3</span>
                </div>
                <!-- Photo 4 -->
                <div id="ALI_PHOTO_4" class="gallery-item aspect-square bg-gray-100 rounded-3xl border-2 border-dashed border-gray-300 flex flex-col items-center justify-center p-4 cursor-pointer hover:border-primary transition shadow-sm">
                    <i class="fa-solid fa-image text-3xl text-gray-400 mb-2"></i>
                    <span class="text-gray-500 font-bold text-sm">[صورة علي 4 هنا]</span>
                    <span class="text-xs text-gray-400 mt-1">ALI_PHOTO_4</span>
                </div>
                <!-- Photo 5 -->
                <div id="ALI_PHOTO_5" class="gallery-item aspect-square bg-gray-100 rounded-3xl border-2 border-dashed border-gray-300 flex flex-col items-center justify-center p-4 cursor-pointer hover:border-primary transition shadow-sm">
                    <i class="fa-solid fa-image text-3xl text-gray-400 mb-2"></i>
                    <span class="text-gray-500 font-bold text-sm">[صورة علي 5 هنا]</span>
                    <span class="text-xs text-gray-400 mt-1">ALI_PHOTO_5</span>
                </div>
                <!-- Photo 6 -->
                <div id="ALI_PHOTO_6" class="gallery-item aspect-square bg-gray-100 rounded-3xl border-2 border-dashed border-gray-300 flex flex-col items-center justify-center p-4 cursor-pointer hover:border-primary transition shadow-sm">
                    <i class="fa-solid fa-image text-3xl text-gray-400 mb-2"></i>
                    <span class="text-gray-500 font-bold text-sm">[صورة علي 6 هنا]</span>
                    <span class="text-xs text-gray-400 mt-1">ALI_PHOTO_6</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Message Section -->
    <section id="message" class="py-20">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl sm:text-4xl font-black text-gray-900 mb-4" data-translate="message-title">رسالة من علي 💌</h2>
            </div>

            <div class="bg-gradient-to-tr from-amber-100/70 to-orange-100/70 rounded-3xl p-8 sm:p-12 shadow-xl border border-amber-200 relative overflow-hidden">
                <div class="absolute -bottom-10 -left-10 text-primary/10 text-9xl">💌</div>
                <div class="relative z-10 flex flex-col sm:flex-row items-center gap-6">
                    <!-- [صورة علي الصغيرة هنا] -->
                    <div id="ALI_SMALL_PHOTO" class="w-24 h-24 rounded-full bg-white flex-shrink-0 flex flex-col items-center justify-center border-2 border-primary shadow-md text-center p-2">
                        <i class="fa-solid fa-user text-primary text-2xl mb-1"></i>
                        <span class="text-[10px] text-gray-400">[صورة علي الصغيرة]</span>
                    </div>
                    <div class="space-y-4 text-center sm:text-start">
                        <p class="text-gray-700 text-lg sm:text-xl font-medium leading-relaxed italic">
                            "[اكتب رسالة علي هنا]"
                        </p>
                        <span class="block font-bold text-amber-800 text-sm">— علي 💛</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-white border-t border-gray-100 py-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-4 text-center">
            <div class="flex items-center gap-2 font-bold text-gray-900">
                <span>عالم علي 💛</span>
            </div>
            <p class="text-sm text-gray-500" data-translate="footer-made">صنع بكل حب للعائلة</p>
            <p class="text-sm font-semibold text-gray-400">2026</p>
        </div>
    </footer>

    <!-- Floating Back to Top Button -->
    <a href="#hero" id="backToTop" class="fixed bottom-6 right-6 bg-primary text-white w-12 h-12 rounded-full shadow-lg flex items-center justify-center text-xl transition transform hover:scale-110 opacity-0 pointer-events-none z-40">
        <i class="fa-solid fa-arrow-up"></i>
    </a>

    <!-- JavaScript File -->
    <script src="script.js"></script>
</body>
</html>
