<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phụ Gia Xây Dựng Sika - 421 Lũy Bán Bích, TP.HCM</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        sikaRed: '#E53E3E',
                        sikaDarkRed: '#C53030',
                        sikaYellow: '#ECC94B',
                        sikaDark: '#1A202C'
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-gray-50 text-sikaDark font-sans">

    <!-- Top Bar -->
    <div class="bg-sikaDark text-white text-sm py-2 px-4">
        <div class="container mx-auto flex flex-col md:flex-row justify-between items-center gap-2">
            <div class="flex items-center gap-4">
                <span><i class="fa-solid fa-location-dot text-sikaYellow mr-1"></i> 421 Lũy Bán Bích, Phường Phú Thạnh, TP.HCM</span>
                <span class="hidden md:inline"><i class="fa-solid fa-clock text-sikaYellow mr-1"></i> 07:30 - 18:00 (Thứ 2 - Chủ Nhật)</span>
            </div>
            <div class="flex items-center gap-4 font-bold">
                <a href="tel:0903883507" class="hover:text-sikaYellow transition"><i class="fa-solid fa-phone text-sikaYellow mr-1"></i> 0903 883 507</a>
                <span>|</span>
                <a href="tel:0975640547" class="hover:text-sikaYellow transition">0975 640 547</a>
            </div>
        </div>
    </div>

    <!-- Header / Navbar -->
    <header class="bg-white shadow-md sticky top-0 z-50 border-b-4 border-sikaRed">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center gap-3">
                <div class="bg-sikaRed text-white font-black text-2xl px-3 py-1 rounded shadow">SIKA</div>
                <div>
                    <h1 class="text-xl font-bold uppercase tracking-wide text-sikaDark">Phụ Gia Xây Dựng</h1>
                    <p class="text-xs text-gray-500 font-semibold">Cửa hàng phân phối chính hãng Sika & Vật liệu chống thấm</p>
                </div>
            </div>
            <nav class="hidden md:flex items-center gap-6 font-semibold">
                <a href="#san-pham" class="hover:text-sikaRed transition">Sản Phẩm</a>
                <a href="#ve-chung-toi" class="hover:text-sikaRed transition">Giới Thiệu</a>
                <a href="#lien-he" class="hover:text-sikaRed transition">Liên Hệ & Bản Đồ</a>
                <a href="tel:0903883507" class="bg-sikaRed text-white px-4 py-2 rounded-lg shadow hover:bg-sikaDarkRed transition flex items-center gap-2">
                    <i class="fa-solid fa-phone-volume"></i> Gọi Ngay
                </a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-sikaDark to-gray-800 text-white py-16 px-4">
        <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 gap-10 items-center">
            <div>
                <span class="bg-sikaYellow text-sikaDark font-bold text-xs uppercase px-3 py-1 rounded-full">Chính hãng 100% - Tư vấn kỹ thuật tận tâm</span>
                <h2 class="text-3xl md:text-5xl font-black mt-4 mb-4 leading-tight">Giải Pháp Chống Thấm & Phụ Gia Xây Dựng Toàn Diện</h2>
                <p class="text-gray-300 mb-6 text-sm md:text-base">Chuyên cung cấp keo dán gạch Sika GP, keo cấy thép 200HP, chất tẩy rỉ và các giải pháp chống thấm hàng đầu phục vụ mọi công trình tại TP.HCM.</p>
                <div class="flex flex-wrap gap-4">
                    <a href="#san-pham" class="bg-sikaRed text-white font-bold px-6 py-3 rounded-lg shadow hover:bg-sikaDarkRed transition">Xem Sản Phẩm</a>
                    <a href="tel:0903883507" class="bg-white text-sikaDark font-bold px-6 py-3 rounded-lg shadow hover:bg-gray-100 transition">Tư Vấn Kỹ Thuật</a>
                </div>
            </div>
            <div class="bg-gray-900 p-4 rounded-xl shadow-2xl border border-gray-700">
                <div class="aspect-video w-full rounded-lg overflow-hidden">
                    <iframe class="w-full h-full" src="https://www.youtube.com/embed/videoseries?list=PL..." title="Sika Video" frameborder="0" allowfullscreen></iframe>
                </div>
                <p class="text-xs text-center text-gray-400 mt-2">Kênh YouTube chính thức: @cuahangsika8908</p>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="san-pham" class="py-16 px-4 max-w-7xl mx-auto">
        <div class="text-center mb-12">
            <h2 class="text-3xl font-black uppercase text-sikaDark">Sản Phẩm Chủ Lực</h2>
            <div class="w-20 h-1 bg-sikaRed mx-auto mt-2"></div>
            <p class="text-gray-600 mt-2">Danh mục keo dán gạch, vật liệu xử lý kết cấu và chống thấm cao cấp sẵn có tại cửa hàng.</p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
            
            <!-- Product 1: Keo GP -->
            <div class="bg-white rounded-xl shadow-md overflow-hidden border border-gray-200 hover:shadow-xl transition flex flex-col">
                <div class="h-56 bg-gray-100 flex items-center justify-center p-4">
                    <img src="https://raw.githubusercontent.com/ductrichita/hinh/main/keo%20gp.jpg" alt="Keo dán gạch Sika GP" class="h-full object-contain">
                </div>
                <div class="p-6 flex-1 flex flex-col justify-between">
                    <div>
                        <span class="text-xs font-bold text-sikaRed uppercase">Keo dán gạch chính hãng</span>
                        <h3 class="text-xl font-bold mt-1 mb-2">Keo Dán Gạch Sika GP</h3>
                        <p class="text-gray-600 text-sm mb-4">Keo dán gạch gốc xi măng trộn sẵn, độ bám dính cực cao, chống trượt tốt cho gạch ốp lát tường và sàn.</p>
                    </div>
                    <div class="flex items-center justify-between pt-4 border-t border-gray-100">
                        <span class="text-sikaRed font-bold">Liên hệ báo giá</span>
                        <a href="tel:0903883507" class="bg-sikaDark text-white text-xs font-bold px-3 py-2 rounded hover:bg-sikaRed transition">Đặt hàng ngay</a>
                    </div>
                </div>
            </div>

            <!-- Product 2: Keo 200HP -->
            <div class="bg-white rounded-xl shadow-md overflow-hidden border border-gray-200 hover:shadow-xl transition flex flex-col">
                <div class="h-56 bg-gray-100 flex items-center justify-center p-4">
                    <img src="https://raw.githubusercontent.com/ductrichita/hinh/main/keo%20200hp.jpg" alt="Keo 200HP cấy thép" class="h-full object-contain">
                </div>
                <div class="p-6 flex-1 flex flex-col justify-between">
                    <div>
                        <span class="text-xs font-bold text-sikaRed uppercase">Neo thép & cấy bu lông</span>
                        <h3 class="text-xl font-bold mt-1 mb-2">Keo Cấy Thép 200HP</h3>
                        <p class="text-gray-600 text-sm mb-4">Hóa chất cấy thép chuyên dụng cường độ cao, chịu lực tốt cho các hạng mục cải tạo và kết cấu bê tông cốt thép.</p>
                    </div>
                    <div class="flex items-center justify-between pt-4 border-t border-gray-100">
                        <span class="text-sikaRed font-bold">Liên hệ báo giá</span>
                        <a href="tel:0903883507" class="bg-sikaDark text-white text-xs font-bold px-3 py-2 rounded hover:bg-sikaRed transition">Đặt hàng ngay</a>
                    </div>
                </div>
            </div>

            <!-- Product 3: Tháo rỉ sắt -->
            <div class="bg-white rounded-xl shadow-md overflow-hidden border border-gray-200 hover:shadow-xl transition flex flex-col">
                <div class="h-56 bg-gray-100 flex items-center justify-center p-4">
                    <img src="https://raw.githubusercontent.com/ductrichita/hinh/main/thao%20ri.jpg" alt="Chất tháo rỉ sắt" class="h-full object-contain">
                </div>
                <div class="p-6 flex-1 flex flex-col justify-between">
                    <div>
                        <span class="text-xs font-bold text-sikaRed uppercase">Xử lý bề mặt kim loại</span>
                        <h3 class="text-xl font-bold mt-1 mb-2">Chất Tháo / Tẩy Rỉ Sắt</h3>
                        <p class="text-gray-600 text-sm mb-4">Dung dịch chuyên dụng tẩy sạch rỉ sét trên cốt pha, sắt thép xây dựng, trả lại bề mặt sạch bảo vệ công trình.</p>
                    </div>
                    <div class="flex items-center justify-between pt-4 border-t border-gray-100">
                        <span class="text-sikaRed font-bold">Liên hệ báo giá</span>
                        <a href="tel:0903883507" class="bg-sikaDark text-white text-xs font-bold px-3 py-2 rounded hover:bg-sikaRed transition">Đặt hàng ngay</a>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- About Section -->
    <section id="ve-chung-toi" class="bg-gray-100 py-16 px-4">
        <div class="container mx-auto max-w-5xl grid grid-cols-1 md:grid-cols-2 gap-10 items-center">
            <div>
                <span class="text-xs font-bold text-sikaRed uppercase">Về cửa hàng chúng tôi</span>
                <h2 class="text-3xl font-black mt-2 mb-4">Uy Tín & Tư Vấn Kỹ Thuật Chuyên Sâu Tại Tân Phú</h2>
                <p class="text-gray-700 mb-4">Được điều hành bởi anh <strong>Nguyễn Đức Trí</strong> - chuyên viên tư vấn kỹ thuật vật liệu xây dựng lâu năm, cửa hàng là địa chỉ tin cậy của các nhà thầu, thợ xây và chủ đầu tư.</p>
                <ul class="space-y-2 text-gray-700 font-medium">
                    <li><i class="fa-solid fa-check text-sikaRed mr-2"></i> Cam kết sản phẩm chính hãng, chất lượng cao.</li>
                    <li><i class="fa-solid fa-check text-sikaRed mr-2"></i> Tư vấn đúng kỹ thuật thi công từng hạng mục.</li>
                    <li><i class="fa-solid fa-check text-sikaRed mr-2"></i> Giá sỉ và lẻ cạnh tranh tại TP.HCM.</li>
                </ul>
            </div>
            <div class="bg-white p-6 rounded-xl shadow-lg border border-gray-200">
                <h3 class="text-xl font-bold mb-4 text-sikaDark"><i class="fa-solid fa-address-card text-sikaRed mr-2"></i> Thông Tin Liên Hệ</h3>
                <p class="text-gray-600 mb-2"><strong>Chủ cửa hàng / Kỹ thuật:</strong> Nguyễn Đức Trí</p>
                <p class="text-gray-600 mb-2"><strong>Địa chỉ:</strong> 421 Lũy Bán Bích, Phường Phú Thạnh, TP.HCM</p>
                <p class="text-gray-600 mb-2"><strong>Hotline 1:</strong> <a href="tel:0903883507" class="text-sikaRed font-bold hover:underline">0903 883 507</a></p>
                <p class="text-gray-600 mb-2"><strong>Hotline 2:</strong> <a href="tel:0975640547" class="text-sikaRed font-bold hover:underline">0975 640 547</a></p>
                <p class="text-gray-600 mb-4"><strong>Email:</strong> ductrichita@gmail.com</p>
                <a href="https://zalo.me/0903883507" target="_blank" class="block text-center bg-blue-600 text-white font-bold py-3 rounded-lg shadow hover:bg-blue-700 transition">
                    <i class="fa-solid fa-comment-sms mr-2"></i> Liên Hệ Zalo Tư Vấn
                </a>
            </div>
        </div>
    </section>

    <!-- Map & Footer -->
    <footer id="lien-he" class="bg-sikaDark text-white pt-16 pb-8">
        <div class="container mx-auto px-4 max-w-7xl grid grid-cols-1 md:grid-cols-3 gap-8 mb-12">
            <div>
                <h3 class="text-lg font-bold mb-4 text-sikaYellow">PHỤ GIA XÂY DỰNG</h3>
                <p class="text-gray-400 text-sm mb-4">Đơn vị chuyên phân phối phụ gia xây dựng và vật liệu chống thấm hàng đầu tại Phường Phú Thạnh, TP.HCM.</p>
                <p class="text-gray-400 text-sm"><i class="fa-solid fa-location-dot text-sikaRed mr-2"></i> 421 Lũy Bán Bích, Phường Phú Thạnh, TP.HCM</p>
            </div>
            <div>
                <h3 class="text-lg font-bold mb-4 text-sikaYellow">SẢN PHẨM CHÍNH</h3>
                <ul class="space-y-2 text-gray-400 text-sm">
                    <li><a href="#san-pham" class="hover:text-white transition">Keo dán gạch Sika GP</a></li>
                    <li><a href="#san-pham" class="hover:text-white transition">Keo cấy thép 200HP</a></li>
                    <li><a href="#san-pham" class="hover:text-white transition">Chất tháo / tẩy rỉ sắt</a></li>
                    <li><a href="#san-pham" class="hover:text-white transition">Giải pháp chống thấm toàn diện</a></li>
                </ul>
            </div>
            <div>
                <h3 class="text-lg font-bold mb-4 text-sikaYellow">BẢN ĐỒ ĐƯỜNG ĐI</h3>
                <div class="rounded-lg overflow-hidden h-40 border border-gray-700">
                    <iframe width="100%" height="100%" frameborder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://maps.google.com/maps?q=421+Luy+Ban+Bich+Phu+Thanh+Tan+Phu+Ho+Chi+Minh&t=&z=15&ie=UTF8&iwloc=&output=embed"></iframe>
                </div>
            </div>
        </div>
        <div class="border-t border-gray-800 pt-6 text-center text-gray-500 text-sm">
            <p>&copy; 2026 Phụ Gia Xây Dựng - 421 Lũy Bán Bích, TP.HCM. Giám sát kỹ thuật: Nguyễn Đức Trí.</p>
        </div>
    </footer>

</body>
</html>
