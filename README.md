<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cửa Hàng Sika Chống Thấm Chính Hãng 421 Lũy Bán Bích - cuahangsika.com</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Inter & FontAwesome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        sikaRed: '#da1a32',
                        sikaDarkRed: '#b51227',
                        sikaDark: '#1e1e1e'
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <style>
        /* Hiệu ứng pulse cho nút Zalo / liên hệ nổi */
        @keyframes pulse-zalo {
            0% { transform: scale(1); box-shadow: 0 0 0 0 rgba(218, 26, 50, 0.5); }
            70% { transform: scale(1.08); box-shadow: 0 0 0 15px rgba(218, 26, 50, 0); }
            100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(218, 26, 50, 0); }
        }
        .float-contact {
            animation: pulse-zalo 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased">

    <!-- Topbar Thông Tin Nhanh -->
    <div class="bg-sikaDark text-white text-xs sm:text-sm py-2 px-4">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-2">
            <div class="flex items-center gap-4">
                <span><i class="fa-solid fa-location-dot text-sikaRed mr-1"></i> 421 Lũy Bán Bích, P. Phú Thạnh, Q. Tân Phú, TP.HCM</span>
                <span class="hidden md:inline"><i class="fa-solid fa-clock text-sikaRed mr-1"></i> Thứ 2 - Chủ Nhật: 7:30 - 18:00</span>
            </div>
            <div class="flex items-center gap-4 font-semibold">
                <a href="tel:0903883507" class="hover:text-sikaRed transition"><i class="fa-solid fa-phone-volume text-sikaRed mr-1"></i> 0903 883 507</a>
                <span>|</span>
                <a href="tel:0975640547" class="hover:text-sikaRed transition">0975 640 547</a>
            </div>
        </div>
    </div>

    <!-- Header & Navbar -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <div class="max-w-7xl mx-auto px-4 py-3 flex justify-between items-center">
            <!-- Logo Thương Hiệu -->
            <a href="#" class="flex items-center gap-3">
                <div class="bg-sikaRed text-white font-black text-2xl sm:text-3xl px-3 py-1 rounded-lg tracking-wider shadow">
                    SIKA
                </div>
                <div>
                    <span class="block font-bold text-base sm:text-lg text-slate-900 leading-tight">CHỐNG THẤM CHÍNH HÃNG</span>
                    <span class="text-xs text-slate-500 font-medium">cuahangsika.com - Tân Phú, TP.HCM</span>
                </div>
            </a>

            <!-- Menu Desktop -->
            <nav class="hidden lg:flex items-center gap-8 font-medium text-slate-700">
                <a href="#home" class="hover:text-sikaRed transition">Trang Chủ</a>
                <a href="#about" class="hover:text-sikaRed transition">Về Chúng Tôi</a>
                <a href="#products" class="hover:text-sikaRed transition">Sản Phẩm Sika</a>
                <a href="#why-us" class="hover:text-sikaRed transition">Cam Kết</a>
                <a href="#contact" class="hover:text-sikaRed transition">Liên Hệ</a>
            </nav>

            <!-- Nút Hành Động Đầu Trang -->
            <div class="hidden sm:flex items-center gap-3">
                <a href="https://zalo.me/0903883507" target="_blank" class="bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-lg font-semibold text-sm flex items-center gap-2 transition shadow">
                    <i class="fa-solid fa-comments"></i> Chat Zalo
                </a>
                <a href="tel:0903883507" class="bg-sikaRed hover:bg-sikaDarkRed text-white px-4 py-2 rounded-lg font-semibold text-sm flex items-center gap-2 transition shadow">
                    <i class="fa-solid fa-phone"></i> Gọi Ngay
                </a>
            </div>

            <!-- Nút Menu Mobile -->
            <button id="menu-btn" class="lg:hidden text-slate-700 text-2xl focus:outline-none">
                <i class="fa-solid fa-bars"></i>
            </button>
        </div>

        <!-- Menu Mobile Dropdown -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t px-4 pt-3 pb-4 space-y-3 font-medium">
            <a href="#home" class="block py-2 border-b border-slate-100 hover:text-sikaRed">Trang Chủ</a>
            <a href="#about" class="block py-2 border-b border-slate-100 hover:text-sikaRed">Về Chúng Tôi</a>
            <a href="#products" class="block py-2 border-b border-slate-100 hover:text-sikaRed">Sản Phẩm Sika</a>
            <a href="#why-us" class="block py-2 border-b border-slate-100 hover:text-sikaRed">Cam Kết</a>
            <a href="#contact" class="block py-2 hover:text-sikaRed">Liên Hệ</a>
            <div class="flex gap-2 pt-2">
                <a href="https://zalo.me/0903883507" target="_blank" class="flex-1 bg-blue-600 text-white text-center py-2 rounded-lg font-semibold text-sm">Zalo</a>
                <a href="tel:0903883507" class="flex-1 bg-sikaRed text-white text-center py-2 rounded-lg font-semibold text-sm">Gọi Hotline</a>
            </div>
        </div>
    </header>

    <!-- Banner / Hero Section -->
    <section id="home" class="relative bg-gradient-to-r from-slate-900 via-slate-800 to-sikaDarkRed text-white py-16 sm:py-24 overflow-hidden">
        <div class="absolute inset-0 opacity-20 bg-[radial-gradient(#da1a32_1px,transparent_1px)] [background-size:16px_16px]"></div>
        <div class="max-w-7xl mx-auto px-4 relative z-10 grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
            <div class="space-y-6 text-center lg:text-left">
                <span class="inline-block bg-sikaRed text-white text-xs sm:text-sm font-bold px-3 py-1.5 rounded-full uppercase tracking-wider">
                    Đại Lý Phân Phối Sika Chính Hãng Tại Tân Phú
                </span>
                <h1 class="text-3xl sm:text-5xl font-extrabold leading-tight">
                    Giải Pháp Chống Thấm & Vật Liệu Xây Dựng <span class="text-sikaRed underline decoration-white decoration-4">Sika Đỉnh Cao</span>
                </h1>
                <p class="text-slate-300 text-base sm:text-lg leading-relaxed">
                    Chuyên cung cấp đầy đủ các dòng sản phẩm phụ gia chống thấm, keo trám, vữa rót gốc xi măng chất lượng cao cho mọi công trình dân dụng và công nghiệp tại TP.HCM.
                </p>
                <div class="flex flex-col sm:flex-row justify-center lg:justify-start gap-4 pt-2">
                    <a href="#products" class="bg-sikaRed hover:bg-sikaDarkRed text-white px-8 py-4 rounded-xl font-bold text-center shadow-lg hover:shadow-xl transition transform hover:-translate-y-0.5">
                        <i class="fa-solid fa-box-open mr-2"></i> Xem Danh Mục Sản Phẩm
                    </a>
                    <a href="https://zalo.me/0903883507" target="_blank" class="bg-white hover:bg-slate-100 text-slate-900 px-8 py-4 rounded-xl font-bold text-center shadow-lg transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-comments text-blue-600"></i> Tư Vấn Miễn Phí Zalo
                    </a>
                </div>
            </div>
            <!-- Thẻ Thông Tin Nhanh Nổi Bật -->
            <div class="bg-white/10 backdrop-blur-md p-6 sm:p-8 rounded-3xl border border-white/20 shadow-2xl space-y-6">
                <h3 class="text-xl font-bold text-white border-b border-white/10 pb-4">
                    <i class="fa-solid fa-store text-sikaRed mr-2"></i> Cửa Hàng Sika 421 Lũy Bán Bích
                </h3>
                <ul class="space-y-4 text-slate-200 text-sm sm:text-base">
                    <li class="flex items-start gap-3">
                        <i class="fa-solid fa-circle-check text-sikaRed mt-1"></i>
                        <span>Cam kết 100% hàng chính hãng Sika Việt Nam, có đầy đủ chứng chỉ chất lượng.</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fa-solid fa-circle-check text-sikaRed mt-1"></i>
                        <span>Giá thành cạnh tranh, chiết khấu tốt cho nhà thầu, thợ xây dựng và công trình lớn.</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fa-solid fa-circle-check text-sikaRed mt-1"></i>
                        <span>Hỗ trợ kỹ thuật thi công chi tiết, giao hàng nhanh chóng nội thành TP.HCM.</span>
                    </li>
                </ul>
                <div class="bg-sikaRed/20 border border-sikaRed/40 p-4 rounded-xl text-center">
                    <p class="text-xs uppercase tracking-wider text-slate-300 font-semibold">Hotline đặt hàng nhanh:</p>
                    <p class="text-2xl font-extrabold text-white mt-1">0903.883.507 - 0975.640.547</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Giới Thiệu Ngắn -->
    <section id="about" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center max-w-3xl mx-auto space-y-4 mb-12">
                <h2 class="text-sikaRed font-bold uppercase tracking-widest text-sm">Về Cửa Hàng Chúng Tôi</h2>
                <h3 class="text-3xl font-extrabold text-slate-900">Địa Chỉ Cung Cấp Vật Liệu Sika Uy Tín Tại Quận Tân Phú</h3>
                <p class="text-slate-600 leading-relaxed">
                    Tọa lạc tại vị trí đắc địa <strong>421 Lũy Bán Bích, Phường Phú Thạnh, TP.HCM</strong>, cửa hàng chúng tôi là đối tác tin cậy chuyên cung cấp các dòng sản phẩm vật liệu xây dựng và phụ gia chống thấm thương hiệu Sika Thụy Sĩ cho hàng ngàn công trình từ nhà ở dân dụng đến cao ốc thương mại.
                </p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-100 text-center space-y-4 hover:shadow-lg transition">
                    <div class="w-16 h-16 bg-sikaRed/10 text-sikaRed rounded-2xl flex items-center justify-center text-2xl mx-auto font-bold">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h4 class="text-xl font-bold text-slate-900">Sản Phẩm Chính Hãng</h4>
                    <p class="text-slate-600 text-sm">Nhập trực tiếp từ nhà máy Sika Việt Nam, nguồn gốc xuất xứ minh bạch, bảo đảm chất lượng tuyệt đối.</p>
                </div>
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-100 text-center space-y-4 hover:shadow-lg transition">
                    <div class="w-16 h-16 bg-sikaRed/10 text-sikaRed rounded-2xl flex items-center justify-center text-2xl mx-auto font-bold">
                        <i class="fa-solid fa-hand-holding-dollar"></i>
                    </div>
                    <h4 class="text-xl font-bold text-slate-900">Giá Cả Cạnh Tranh</h4>
                    <p class="text-slate-600 text-sm">Chính sách giá linh hoạt, chiết khấu hấp dẫn cho các công trình xây dựng, thợ thi công và đại lý nhỏ.</p>
                </div>
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-100 text-center space-y-4 hover:shadow-lg transition">
                    <div class="w-16 h-16 bg-sikaRed/10 text-sikaRed rounded-2xl flex items-center justify-center text-2xl mx-auto font-bold">
                        <i class="fa-solid fa-truck-fast"></i>
                    </div>
                    <h4 class="text-xl font-bold text-slate-900">Giao Hàng Hỏa Tốc</h4>
                    <p class="text-slate-600 text-sm">Giao hàng nhanh tận chân công trình trong khu vực TP.HCM, hỗ trợ vận chuyển linh hoạt theo tiến độ.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Danh Mục Sản Phẩm Chủ Lực -->
    <section id="products" class="py-16 bg-slate-100">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center max-w-2xl mx-auto space-y-4 mb-12">
                <h2 class="text-sikaRed font-bold uppercase tracking-widest text-sm">Sản Phẩm Chủ Lực</h2>
                <h3 class="text-3xl font-extrabold text-slate-900">Danh Mục Vật Liệu & Chống Thấm Sika</h3>
                <p class="text-slate-600">Các dòng sản phẩm chuyên dụng giải quyết mọi vấn đề thấm dột sân thượng, ban công, tầng hầm, nhà vệ sinh và kết cấu bê tông.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                
                <!-- Sản phẩm 1: Sika Latex -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-xl transition flex flex-col border border-slate-200">
                    <div class="h-48 bg-slate-900 relative overflow-hidden flex items-center justify-center">
                        <img src="https://placehold.co/600x400/da1a32/ffffff?text=Sika+Latex" alt="Sika Latex" class="w-full h-full object-cover opacity-90 hover:scale-105 transition duration-500" onerror="this.src='https://placehold.co/600x400/1e1e1e/ffffff?text=Sika+Latex'">
                        <span class="absolute top-3 left-3 bg-sikaRed text-white text-xs font-bold px-3 py-1 rounded-full shadow">Phụ Gia Chống Thấm</span>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <h4 class="text-xl font-bold text-slate-900 mb-2">Sika Latex / Sika Latex TH</h4>
                            <p class="text-slate-600 text-sm leading-relaxed">
                                Nhũ tương cao su tổng hợp trộn với xi măng/vữa cát để tăng độ bám dính, chống thấm tuyệt hảo cho lớp vữa trát và dặm vá.
                            </p>
                        </div>
                        <div class="pt-4 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-xs font-semibold text-slate-500"><i class="fa-solid fa-box text-sikaRed mr-1"></i> Quy cách: Can / Thùng / Phuy</span>
                            <a href="https://zalo.me/0903883507?text=Xin%20tư%20vấn%20giá%20Sika%20Latex" target="_blank" class="bg-sikaRed hover:bg-sikaDarkRed text-white text-xs font-bold px-3 py-2 rounded-lg transition">
                                Báo Giá
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 2: Sika Coat Lus -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-xl transition flex flex-col border border-slate-200">
                    <div class="h-48 bg-slate-900 relative overflow-hidden flex items-center justify-center">
                        <img src="https://placehold.co/600x400/da1a32/ffffff?text=Sika+RainTite" alt="Sika Coat Lus" class="w-full h-full object-cover opacity-90 hover:scale-105 transition duration-500" onerror="this.src='https://placehold.co/600x400/1e1e1e/ffffff?text=Sika+RainTite'">
                        <span class="absolute top-3 left-3 bg-sikaRed text-white text-xs font-bold px-3 py-1 rounded-full shadow">Chống Thấm Lộ Thiên</span>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <h4 class="text-xl font-bold text-slate-900 mb-2">Sika Coat Lus</h4>
                            <p class="text-slate-600 text-sm leading-relaxed">
                                Chất chống thấm đàn hồi gốc Acrylic dạng lộ thiên, dùng cho mái nhà, sân thượng, ban công, tường ngoại thất chống tia UV hiệu quả.
                            </p>
                        </div>
                        <div class="pt-4 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-xs font-semibold text-slate-500"><i class="fa-solid fa-box text-sikaRed mr-1"></i> Quy cách: Thùng 4kg & 20kg</span>
                            <a href="https://zalo.me/0903883507?text=Xin%20tư%20vấn%20giá%20Sika%20RainTite" target="_blank" class="bg-sikaRed hover:bg-sikaDarkRed text-white text-xs font-bold px-3 py-2 rounded-lg transition">
                                Báo Giá
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 3: Sika membrane -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-xl transition flex flex-col border border-slate-200">
                    <div class="h-48 bg-slate-900 relative overflow-hidden flex items-center justify-center">
                        <img src="https://placehold.co/600x400/da1a32/ffffff?text=Sikafill+Power" alt="Sikafill Power" class="w-full h-full object-cover opacity-90 hover:scale-105 transition duration-500" onerror="this.src='https://placehold.co/600x400/1e1e1e/ffffff?text=Sikafill+Power'">
                        <span class="absolute top-3 left-3 bg-sikaRed text-white text-xs font-bold px-3 py-1 rounded-full shadow">Màng Đàn Hồi Cao</span>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <h4 class="text-xl font-bold text-slate-900 mb-2">Sikafill Power</h4>
                            <p class="text-slate-600 text-sm leading-relaxed">
                                Màng chống thấm Acrylic dạng lỏng, đàn hồi cao, chuyên dụng che lấp vết nứt tuyệt vời cho tường đứng và mái nhà không đi lại.
                            </p>
                        </div>
                        <div class="pt-4 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-xs font-semibold text-slate-500"><i class="fa-solid fa-box text-sikaRed mr-1"></i> Quy cách: Thùng 18kg</span>
                            <a href="https://zalo.me/0903883507?text=Xin%20tư%20vấn%20giá%20Sikafill%20Power" target="_blank" class="bg-sikaRed hover:bg-sikaDarkRed text-white text-xs font-bold px-3 py-2 rounded-lg transition">
                                Báo Giá
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 4: Sika Topseal 107 -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-xl transition flex flex-col border border-slate-200">
                    <div class="h-48 bg-slate-900 relative overflow-hidden flex items-center justify-center">
                        <img src="https://placehold.co/600x400/da1a32/ffffff?text=Sika+Topseal+107" alt="Sika Topseal 107" class="w-full h-full object-cover opacity-90 hover:scale-105 transition duration-500" onerror="this.src='https://placehold.co/600x400/1e1e1e/ffffff?text=Sika+Topseal+107'">
                        <span class="absolute top-3 left-3 bg-sikaRed text-white text-xs font-bold px-3 py-1 rounded-full shadow">Chống Thấm 2 Thành Phần</span>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <h4 class="text-xl font-bold text-slate-900 mb-2">Sika Topseal 107</h4>
                            <p class="text-slate-600 text-sm leading-relaxed">
                                Vữa chống thấm gốc xi măng polyme 2 thành phần, chuyên dụng cho nhà vệ sinh, ban công, hồ nước, bể bơi, tầng hầm.
                            </p>
                        </div>
                        <div class="pt-4 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-xs font-semibold text-slate-500"><i class="fa-solid fa-box text-sikaRed mr-1"></i> Quy cách: Bộ 25kg</span>
                            <a href="https://zalo.me/0903883507?text=Xin%20tư%20vấn%20giá%20Sika%20Topseal%20107" target="_blank" class="bg-sikaRed hover:bg-sikaDarkRed text-white text-xs font-bold px-3 py-2 rounded-lg transition">
                                Báo Giá
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 5: SikaGrout 214-11 -->
                <div class="bg-white rounded-2xl overflow-hidden shadow-md hover:shadow-xl transition flex flex-col border border-slate-200">
                    <div class="h-48 bg-slate-900 relative overflow-hidden flex items-center justify-center">
                        <img src="https://placehold.co/600x400/da1a32/ffffff?text=SikaGrout+214-11" alt="SikaGrout 214-11" class="w-full h-full object-cover opacity-90 hover:scale-105 transition duration-500" onerror="this.src='https://placehold.co/600x400/1e1e1e/ffffff?text=SikaGrout+214-11'">
                        <span class="absolute top-3 left-3 bg-sikaRed text-white text-xs font-bold px-3 py-1 rounded-full shadow">Vữa Rót Không Co Ngót</span>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-4">
                        <div>
                            <h4 class="text-xl font-bold text-slate-900 mb-2">SikaGrout 214-11</h4>
                            <p class="text-slate-600 text-sm leading-relaxed">
                                Vữa rót gốc xi măng, tự san bằng, bù co ngót, chịu lực cao chuyên dùng cho bu lông móng, móng máy, bệ cột và định vị kết cấu.
                            </p>
                        </div>
                        <div class="pt-4 border-t border-slate-100 flex items-center justify-between">
                            <span class="text-xs font-semibold text-slate-500"><i class="fa-solid fa-box text-sikaRed mr-1"></i> Quy cách: Bao 25kg</span>
                            <a href="https://zalo.me/0903883507?text=Xin%20tư%20vấn%20giá%20SikaGrout%20214-11" target="_blank" class="bg-sikaRed hover:bg-sikaDarkRed text-white text-xs font-bold px-3 py-2 rounded-lg transition">
                                Báo Giá
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm Khác / Tư vấn thêm -->
                <div class="bg-gradient-to-br from-sikaRed to-sikaDarkRed text-white rounded-2xl overflow-hidden shadow-md hover:shadow-xl transition flex flex-col justify-between p-8 text-center">
                    <div class="space-y-4 my-auto">
                        <div class="w-16 h-16 bg-white/20 rounded-full flex items-center justify-center mx-auto text-3xl">
                            <i class="fa-solid fa-list-check"></i>
                        </div>
                        <h4 class="text-2xl font-bold">Bạn Cần Dòng Sản Phẩm Sika Khác?</h4>
                        <p class="text-slate-100 text-sm">
                            Chúng tôi cung cấp đầy đủ các dòng keo cấy thép (Sika AnchorFix), băng cản nước, chất kết dính (Sikadur)...
                        </p>
                    </div>
                    <div class="pt-6">
                        <a href="https://zalo.me/0903883507" target="_blank" class="bg-white hover:bg-slate-100 text-slate-900 font-bold px-6 py-3 rounded-xl block shadow transition">
                            <i class="fa-solid fa-comments text-blue-600 mr-2"></i> Nhận Tư Vấn Trực Tiếp
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Cam Kết & Lợi Ích -->
    <section id="why-us" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4">
            <div class="text-center max-w-2xl mx-auto space-y-4 mb-12">
                <h2 class="text-sikaRed font-bold uppercase tracking-widest text-sm">Tại Sao Chọn Chúng Tôi</h2>
                <h3 class="text-3xl font-extrabold text-slate-900">Cam Kết Vàng Cho Mọi Công Trình</h3>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="p-6 bg-slate-50 border border-slate-100 rounded-2xl space-y-3">
                    <div class="text-sikaRed text-3xl font-bold"><i class="fa-solid fa-award"></i></div>
                    <h4 class="font-bold text-lg text-slate-900">Chính Hãng 100%</h4>
                    <p class="text-slate-600 text-sm">Nói không với hàng giả, hàng nhái kém chất lượng. Đền bù gấp đôi nếu phát hiện hàng không chính hãng.</p>
                </div>
                <div class="p-6 bg-slate-50 border border-slate-100 rounded-2xl space-y-3">
                    <div class="text-sikaRed text-3xl font-bold"><i class="fa-solid fa-tags"></i></div>
                    <h4 class="font-bold text-lg text-slate-900">Giá Tốt Nhất Khu Vực</h4>
                    <p class="text-slate-600 text-sm">Chiết khấu cao cho nhà thầu, công trình lớn và các đội thợ chuyên thi công chống thấm lâu năm.</p>
                </div>
                <div class="p-6 bg-slate-50 border border-slate-100 rounded-2xl space-y-3">
                    <div class="text-sikaRed text-3xl font-bold"><i class="fa-solid fa-graduation-cap"></i></div>
                    <h4 class="font-bold text-lg text-slate-900">Hỗ Trợ Kỹ Thuật Miễn Phí</h4>
                    <p class="text-slate-600 text-sm">Hướng dẫn định mức pha trộn, quy trình thi công đúng chuẩn kỹ thuật nhà sản xuất Sika.</p>
                </div>
                <div class="p-6 bg-slate-50 border border-slate-100 rounded-2xl space-y-3">
                    <div class="text-sikaRed text-3xl font-bold"><i class="fa-solid fa-truck-ramp-box"></i></div>
                    <h4 class="font-bold text-lg text-slate-900">Giao Hàng Tận Nơi</h4>
                    <p class="text-slate-600 text-sm">Xe máy, xe tải giao hàng nhanh chóng từ cửa hàng 421 Lũy Bán Bích đến tận công trình theo yêu cầu.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Phần Liên Hệ & Bản Đồ -->
    <section id="contact" class="py-16 bg-slate-100 border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                
                <!-- Thông tin liên hệ chi tiết -->
                <div class="space-y-6">
                    <div>
                        <span class="text-sikaRed font-bold uppercase tracking-widest text-sm">Kết Nối Với Chúng Tôi</span>
                        <h3 class="text-3xl font-extrabold text-slate-900 mt-1">Cửa Hàng Sika Chống Thấm Quận Tân Phú</h3>
                        <p class="text-slate-600 mt-2">Hãy ghé trực tiếp cửa hàng hoặc liên hệ qua điện thoại/Zalo để được tư vấn báo giá vật liệu Sika nhanh chóng và chính xác nhất.</p>
                    </div>

                    <div class="space-y-4">
                        <div class="flex items-start gap-4 bg-white p-4 rounded-xl shadow-sm border border-slate-200">
                            <div class="bg-sikaRed text-white w-10 h-10 rounded-lg flex items-center justify-center shrink-0 text-lg">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900">Địa Chỉ Cửa Hàng:</h4>
                                <p class="text-slate-600 text-sm mt-0.5">421 Lũy Bán Bích, Phường Phú Thạnh, Quận Tân Phú, TP.HCM</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4 bg-white p-4 rounded-xl shadow-sm border border-slate-200">
                            <div class="bg-sikaRed text-white w-10 h-10 rounded-lg flex items-center justify-center shrink-0 text-lg">
                                <i class="fa-solid fa-phone-volume"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900">Hotline / Zalo Hỗ Trợ:</h4>
                                <p class="text-slate-800 font-bold text-base mt-0.5">
                                    <a href="tel:0903883507" class="hover:text-sikaRed">0903 883 507</a> - 
                                    <a href="tel:0975640547" class="hover:text-sikaRed">0975 640 547</a>
                                </p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4 bg-white p-4 rounded-xl shadow-sm border border-slate-200">
                            <div class="bg-sikaRed text-white w-10 h-10 rounded-lg flex items-center justify-center shrink-0 text-lg">
                                <i class="fa-solid fa-globe"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-slate-900">Website Chính Thức:</h4>
                                <p class="text-sikaRed font-semibold text-sm mt-0.5">cuahangsika.com</p>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-col sm:flex-row gap-4 pt-2">
                        <a href="https://zalo.me/0903883507" target="_blank" class="flex-1 bg-blue-600 hover:bg-blue-700 text-white font-bold py-3.5 px-6 rounded-xl text-center shadow transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-comments text-xl"></i> Chat Zalo Ngay
                        </a>
                        <a href="tel:0903883507" class="flex-1 bg-sikaRed hover:bg-sikaDarkRed text-white font-bold py-3.5 px-6 rounded-xl text-center shadow transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-phone text-xl"></i> Gọi Hotline
                        </a>
                    </div>
                </div>

                <!-- Khung Bản Đồ / Minh Họa Vị Trí -->
                <div class="bg-white p-3 rounded-2xl shadow-lg border border-slate-200">
                    <div class="w-full h-[380px] bg-slate-200 rounded-xl overflow-hidden relative flex flex-col items-center justify-center text-center p-6">
                        <div class="absolute inset-0 bg-slate-100 flex flex-col items-center justify-center p-6 text-center">
                            <div class="w-16 h-16 bg-sikaRed text-white rounded-full flex items-center justify-center text-3xl mb-3 shadow-md animate-bounce">
                                <i class="fa-solid fa-map-pin"></i>
                            </div>
                            <h4 class="text-lg font-bold text-slate-900">Cửa Hàng Sika 421 Lũy Bán Bích</h4>
                            <p class="text-slate-600 text-sm mt-1 max-w-md">Phường Phú Thạnh, Quận Tân Phú, Thành phố Hồ Chí Minh</p>
                            <a href="https://maps.google.com/?q=421+Luy+Ban+Bich+Phu+Thanh+Tan+Phu+HCMC" target="_blank" class="mt-4 bg-slate-900 hover:bg-slate-800 text-white text-xs font-bold px-4 py-2.5 rounded-lg shadow transition">
                                <i class="fa-solid fa-directions mr-1"></i> Mở Bản Đồ Google Maps
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-sikaDark text-white pt-12 pb-24 sm:pb-12 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 grid grid-cols-1 md:grid-cols-3 gap-8 mb-8">
            <div class="space-y-4">
                <div class="flex items-center gap-3">
                    <div class="bg-sikaRed text-white font-black text-xl px-2.5 py-0.5 rounded">SIKA</div>
                    <span class="font-bold text-lg">CỬA HÀNG CHỐNG THẤM</span>
                </div>
                <p class="text-slate-400 text-sm leading-relaxed">
                    Chuyên cung cấp vật liệu chống thấm và phụ gia xây dựng Sika chính hãng tại 421 Lũy Bán Bích, P. Phú Thạnh, TP.HCM. Uy tín, chất lượng, giá tốt nhất.
                </p>
            </div>
            <div class="space-y-3">
                <h4 class="font-bold text-base text-white border-b border-slate-800 pb-2">Danh Mục Sản Phẩm</h4>
                <ul class="space-y-2 text-sm text-slate-400">
                    <li><a href="#products" class="hover:text-sikaRed transition">• Sika Latex / Sika Latex TH</a></li>
                    <li><a href="#products" class="hover:text-sikaRed transition">• Sika Coat Lus (Chống thấm lộ thiên)</a></li>
                    <li><a href="#products" class="hover:text-sikaRed transition">• Sika membrane (Màng đàn hồi)</a></li>
                    <li><a href="#products" class="hover:text-sikaRed transition">• Sika Topseal 107 (2 thành phần)</a></li>
                    <li><a href="#products" class="hover:text-sikaRed transition">• SikaGrout 214-11 (Vữa không co ngót)</a></li>
                </ul>
            </div>
            <div class="space-y-3">
                <h4 class="font-bold text-base text-white border-b border-slate-800 pb-2">Thông Tin Liên Hệ</h4>
                <p class="text-slate-400 text-sm"><i class="fa-solid fa-location-dot text-sikaRed mr-2"></i> 421 Lũy Bán Bích, P. Phú Thạnh, Q. Tân Phú, TP.HCM</p>
                <p class="text-slate-400 text-sm"><i class="fa-solid fa-phone text-sikaRed mr-2"></i> 0903 883 507 - 0975 640 547</p>
                <p class="text-slate-400 text-sm"><i class="fa-solid fa-globe text-sikaRed mr-2"></i> cuahangsika.com</p>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-4 pt-6 border-t border-slate-800 text-center text-xs text-slate-500">
            &copy; 2026 cuahangsika.com - Cửa Hàng Chống Thấm Sika 421 Lũy Bán Bích. All rights reserved.
        </div>
    </footer>

    <!-- Thanh Nút Liên Hệ Nổi Dưới Màn Hình (Mobile Floating Bar) -->
    <div class="fixed bottom-0 left-0 right-0 z-50 bg-white/95 backdrop-blur border-t border-slate-200 p-2 sm:hidden flex items-center justify-around shadow-lg">
        <a href="tel:0903883507" class="flex flex-col items-center text-slate-700 hover:text-sikaRed">
            <div class="w-10 h-10 bg-sikaRed text-white rounded-full flex items-center justify-center text-lg shadow">
                <i class="fa-solid fa-phone"></i>
            </div>
            <span class="text-[10px] font-bold mt-0.5">Gọi 0903883507</span>
        </a>
        <a href="https://zalo.me/0903883507" target="_blank" class="flex flex-col items-center text-slate-700 hover:text-blue-600 float-contact">
            <div class="w-11 h-11 bg-blue-600 text-white rounded-full flex items-center justify-center text-xl shadow-md">
                <i class="fa-solid fa-comments"></i>
            </div>
            <span class="text-[10px] font-bold mt-0.5">Chat Zalo</span>
        </a>
<a href="tel:0975640547" class="flex flex-col items-center text-slate-700 hover:text-sikaRed">
            <div class="w-10 h-10 bg-slate-800 text-white rounded-full flex items-center justify-center text-lg shadow">
                <i class="fa-solid fa-phone-volume"></i>
            </div>
            <span class="text-[10px] font-bold mt-0.5">Gọi 0975640547</span>
        </a>
    </div>

    <!-- JavaScript Xử Lý Menu Mobile -->
    <script>
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Đóng menu khi chọn link trên mobile
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
