<html lang="vi" class="scroll-smooth overflow-x-hidden">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH THÙY DUNG FOODS - thuydungfoods.com.com | Nông Sản & Quà Tặng Tự Nhiên</title>
    <meta name="description" content="CÔNG TY TNHH THÙY DUNG FOODS (thuydungfoods.com.com) chuyên sản xuất và cung ứng Hạt điều, Hạt sen, Macca, Đậu phộng, Gừng nướng mật ong, Trái cây sấy và Hộp quà tặng doanh nghiệp cao cấp.">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://thuydungfoods.com.com/">
    <meta property="og:title" content="CÔNG TY TNHH THÙY DUNG FOODS - Nông Sản & Hộp Quà Tặng Cao Cấp">
    <meta property="og:description" content="Tinh hoa nông sản Việt: Hạt sấy dinh dưỡng, Gừng nướng mật ong, Trái cây sấy dẻo, Trà & Cà phê, Hộp quà tặng doanh nghiệp. Hotline: 0984.113.366">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns" type="image/png">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f2fbf5',
                            100: '#e1f6e8',
                            500: '#1f7a3e',
                            600: '#166534', // Xanh lá chủ đạo đồng bộ logo & nông sản tự nhiên
                            700: '#14532d',
                            800: '#0f3f22',
                            accent: '#d97706', // Vàng cam mật ong / nông sản chín
                            light: '#f8faf7'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền tuyệt đối và lệch phải trên cả điện thoại & máy tính */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            background-color: #f9fbf9;
            color: #1f2937;
        }

        /* Khung chuẩn Flatsome: rộng 95% trên màn hình máy tính, 100% có padding an toàn trên điện thoại */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder (Section Title Center) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            margin-bottom: 1.25rem;
        }
        .flatsome-section-title b {
            display: block;
            flex: 1;
            height: 2px;
            background-color: #d1fae5;
        }
        .flatsome-section-title span {
            padding: 0 14px;
            text-align: center;
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            text-transform: uppercase;
            color: #166534;
            letter-spacing: 0.02em;
        }

        /* Hiệu ứng nút nổi bật Zalo, Facebook, Hotline */
        @keyframes pulse-ring {
            0% { transform: scale(0.92); box-shadow: 0 0 0 0 rgba(22, 101, 52, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(22, 101, 52, 0); }
            100% { transform: scale(0.92); box-shadow: 0 0 0 0 rgba(22, 101, 52, 0); }
        }
        .floating-btn-pulse {
            animation: pulse-ring 2s infinite;
        }

        /* Ẩn thanh cuộn phụ nếu có */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>

    <script>
        // Hàm tự động chuyển đổi sang link dự phòng Google Drive nếu ảnh chính bị chặn cache
        function handleDriveImageError(imgElement, fileId, fallbackLabel) {
            const step = imgElement.getAttribute('data-fallback-step') || '0';
            if (step === '0') {
                imgElement.setAttribute('data-fallback-step', '1');
                imgElement.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
            } else if (step === '1') {
                imgElement.setAttribute('data-fallback-step', '2');
                imgElement.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                imgElement.onerror = null;
                imgElement.src = 'https://placehold.co/600x600/f2fbf5/166534?text=' + encodeURIComponent(fallbackLabel || 'Thuy+Dung+Foods');
            }
        }
    </script>
</head>
<body class="font-sans antialiased selection:bg-brand-600 selection:text-white">

    <!-- ==========================================
         1. TOP BAR (CHUẨN FLATSOME - KHÔNG CÓ THANH UXBUILDER)
         ========================================== -->
    <div class="bg-brand-700 text-white text-[11px] sm:text-xs py-1.5 border-b border-brand-800">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate">
                <i class="fa-solid fa-leaf text-amber-400"></i>
                <span class="font-semibold tracking-wide">CÔNG TY TNHH THÙY DUNG FOODS</span>
                <span class="hidden sm:inline text-emerald-200">|</span>
                <span class="hidden sm:inline text-emerald-100">Website: thuydungfoods.com.com</span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-emerald-100">
                <span><i class="fa-solid fa-circle-check text-amber-400 mr-1"></i>Hàng nông sản chọn lọc kỹ càng</span>
                <span><i class="fa-solid fa-truck-fast text-amber-400 mr-1"></i>Phân phối sỉ & lẻ toàn quốc</span>
                <span><i class="fa-solid fa-envelope text-amber-400 mr-1"></i>lkdanangvn@gmail.com</span>
            </div>
        </div>
    </div>

    <!-- ==========================================
         2. HEADER MAIN & NAVIGATION (CHUẨN FLATSOME, KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ========================================== -->
    <header id="header" class="sticky top-0 z-40 bg-white shadow-sm border-b border-gray-100">
        <!-- Header Main -->
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-2 sm:gap-4">
            <!-- Nút mở menu trên điện thoại -->
            <button onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg text-brand-700 hover:bg-brand-50 border border-gray-200 shrink-0">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>

            <!-- Logo (Chỉnh gọn nhỏ lại theo đúng yêu cầu) -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg bg-white border border-emerald-100 p-0.5 flex items-center justify-center overflow-hidden shadow-xs shrink-0">
                    <img src="https://lh3.googleusercontent.com/d/1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns"
                         onerror="handleDriveImageError(this, '1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns', 'LOGO')"
                         alt="Logo Công Ty TNHH Thùy Dung Foods"
                         class="max-h-9 sm:max-h-10 w-auto object-contain transition-transform duration-300 group-hover:scale-105">
                </div>
                <div class="leading-tight">
                    <span class="block font-heading font-extrabold text-brand-600 text-xs sm:text-sm md:text-base tracking-tight">THÙY DUNG FOODS</span>
                    <span class="block text-[10px] sm:text-[11px] text-gray-500 font-medium">thuydungfoods.com.com</span>
                </div>
            </a>

            <!-- Ô tìm kiếm ở giữa chuẩn Flatsome -->
            <div class="hidden md:flex flex-1 max-w-xl mx-2">
                <div class="relative flex w-full items-center">
                    <input id="desktopSearchInput" type="text" oninput="filterProductsBySearch(this.value)"
                           placeholder="Tìm hạt điều, gừng nướng mật ong, hạt sen, hộp quà..."
                           class="w-full pl-3.5 pr-10 py-2 text-xs lg:text-sm bg-gray-50 border border-gray-300 rounded-full focus:outline-none focus:border-brand-600 focus:bg-white transition">
                    <button onclick="filterProductsBySearch(document.getElementById('desktopSearchInput').value)"
                            aria-label="Tìm kiếm"
                            class="absolute right-1.5 w-7 h-7 rounded-full bg-brand-600 text-white flex items-center justify-center hover:bg-brand-700 transition">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </div>
            </div>

            <!-- Khu vực Giỏ hàng & Báo giá (Không để nút Gọi ngay trên Header để tránh tràn viền) -->
            <div class="flex items-center gap-2 shrink-0">
                <a href="#form-bao-gia" class="hidden sm:inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full text-xs font-semibold bg-amber-50 text-amber-800 border border-amber-200 hover:bg-amber-100 transition whitespace-nowrap">
                    <i class="fa-solid fa-file-invoice text-amber-600"></i>
                    <span>Nhận Báo Giá</span>
                </a>
                <button onclick="toggleCartModal()" class="relative inline-flex items-center gap-1.5 px-3 py-1.5 rounded-full text-xs font-semibold bg-brand-50 text-brand-700 border border-brand-100 hover:bg-brand-100 transition shrink-0">
                    <i class="fa-solid fa-basket-shopping text-brand-600 text-sm"></i>
                    <span class="hidden sm:inline">Giỏ hàng</span>
                    <span id="cartCountBadge" class="w-5 h-5 rounded-full bg-brand-600 text-white text-[11px] flex items-center justify-center font-bold">0</span>
                </button>
            </div>
        </div>

        <!-- Thanh tìm kiếm gọn trên điện thoại -->
        <div class="md:hidden flatsome-container pb-2">
            <div class="relative flex w-full items-center">
                <input id="mobileSearchInput" type="text" oninput="filterProductsBySearch(this.value)"
                       placeholder="Tìm sản phẩm Thùy Dung Foods..."
                       class="w-full pl-3 pr-9 py-1.5 text-xs bg-gray-50 border border-gray-200 rounded-full focus:outline-none focus:border-brand-600">
                <i class="fa-solid fa-magnifying-glass text-gray-400 text-xs absolute right-3"></i>
            </div>
        </div>

        <!-- Header Bottom: Thanh Danh Mục Máy Tính
             Yêu cầu: Tên danh mục trên máy tính viết liền trên 1 hàng chữ nhỏ lại để nằm trên cùng 1 hàng hoặc xuống hàng 2, KHÔNG ĐƯỢC xuống dòng tên danh mục -->
        <nav class="hidden lg:block bg-brand-600 text-white border-t border-brand-700">
            <div class="flatsome-container">
                <ul class="flex flex-wrap items-center justify-center gap-x-1 gap-y-1 py-1.5 text-[11.5px] xl:text-[12.5px] font-semibold tracking-tight">
                    <li><a href="#trang-chu" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">TRANG CHỦ</a></li>
                    <li><a href="#ve-chung-toi" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">CÔNG TY</a></li>
                    <li><a href="#sec-hat-say" onclick="filterCategory('Hạt Điều')" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">HẠT ĐIỀU</a></li>
                    <li><a href="#sec-hat-say" onclick="filterCategory('Hạt Sen & Macca')" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">HẠT SEN & MACCA</a></li>
                    <li><a href="#sec-hat-say" onclick="filterCategory('Đậu Phộng & Đậu Nành')" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">ĐẬU PHỘNG & ĐẬU NÀNH</a></li>
                    <li><a href="#sec-gung-trai-cay" onclick="filterCategory('Gừng Nướng Mật Ong')" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">GỪNG NƯỚNG MẬT ONG</a></li>
                    <li><a href="#sec-gung-trai-cay" onclick="filterCategory('Trái Cây Sấy')" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">TRÁI CÂY SẤY</a></li>
                    <li><a href="#sec-hop-qua" onclick="filterCategory('Hộp Quà Tặng')" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">NHỮNG HỘP QUÀ BIẾT KỂ CHUYỆN</a></li>
                    <li><a href="#sec-tra-ca-phe" onclick="filterCategory('Trà & Cà Phê')" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">TRÀ & CÀ PHÊ - GIA VỊ</a></li>
                    <li><a href="#doi-tac" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">ĐỐI TÁC</a></li>
                    <li><a href="#tin-tuc" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">TIN TỨC</a></li>
                    <li><a href="#lien-he-map" class="whitespace-nowrap block px-2.5 py-1 rounded hover:bg-brand-700 transition">LIÊN HỆ</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- MENU TRƯỢT TRÊN ĐIỆN THOẠI (Tối ưu gọn đẹp) -->
    <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
        <div onclick="toggleMobileMenu()" class="absolute inset-0 bg-black/50 backdrop-blur-xs"></div>
        <div class="relative w-72 max-w-[82vw] h-full bg-white shadow-2xl flex flex-col justify-between overflow-y-auto">
            <div>
                <div class="p-3.5 bg-brand-600 text-white flex items-center justify-between">
                    <div class="flex items-center gap-2">
                        <img src="https://lh3.googleusercontent.com/d/1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns"
                             onerror="handleDriveImageError(this, '1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns', 'LOGO')"
                             alt="Logo" class="w-8 h-8 rounded bg-white p-0.5 object-contain">
                        <span class="font-heading font-bold text-xs">THÙY DUNG FOODS</span>
                    </div>
                    <button onclick="toggleMobileMenu()" class="w-7 h-7 rounded-full bg-brand-700 text-white flex items-center justify-center">
                        <i class="fa-solid fa-xmark text-sm"></i>
                    </button>
                </div>
                <div class="p-3">
                    <p class="text-[11px] font-bold uppercase text-gray-400 px-2 mb-1">Danh mục sản phẩm</p>
                    <ul class="space-y-1 text-xs font-semibold text-gray-700">
                        <li><a href="#trang-chu" onclick="toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-house w-5 text-brand-600"></i>Trang chủ</span></a></li>
                        <li><a href="#sec-hat-say" onclick="filterCategory('all'); toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-seedling w-5 text-brand-600"></i>Hạt Điều Bản Địa</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a></li>
                        <li><a href="#sec-hat-say" onclick="filterCategory('Hạt Sen & Macca'); toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-spa w-5 text-brand-600"></i>Hạt Sen & Hạt Macca</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a></li>
                        <li><a href="#sec-hat-say" onclick="filterCategory('Đậu Phộng & Đậu Nành'); toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-bowl-food w-5 text-brand-600"></i>Đậu Phộng & Đậu Nành</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a></li>
                        <li><a href="#sec-gung-trai-cay" onclick="toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-mug-hot w-5 text-brand-600"></i>Gừng Nướng Mật Ong</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a></li>
                        <li><a href="#sec-gung-trai-cay" onclick="toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-apple-whole w-5 text-brand-600"></i>Trái Cây Sấy Dẻo</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a></li>
                        <li><a href="#sec-hop-qua" onclick="toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-gift w-5 text-brand-600"></i>Những Hộp Quà Biết Kể Chuyện</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a></li>
                        <li><a href="#sec-tra-ca-phe" onclick="toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-mortar-pestle w-5 text-brand-600"></i>Trà, Cà Phê & Gia Vị Muối</span><i class="fa-solid fa-chevron-right text-[10px] text-gray-400"></i></a></li>
                        <li><a href="#doi-tac" onclick="toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-handshake w-5 text-brand-600"></i>Đối Tác & Xuất Khẩu</span></a></li>
                        <li><a href="#form-bao-gia" onclick="toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-file-signature w-5 text-brand-600"></i>Yêu Cầu Báo Giá</span></a></li>
                        <li><a href="#tin-tuc" onclick="toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-newspaper w-5 text-brand-600"></i>Tin Tức & Bài Viết</span></a></li>
                        <li><a href="#lien-he-map" onclick="toggleMobileMenu()" class="flex items-center justify-between px-2.5 py-2 rounded-lg hover:bg-brand-50 hover:text-brand-600"><span><i class="fa-solid fa-location-dot w-5 text-brand-600"></i>Bản Đồ & Liên Hệ</span></a></li>
                    </ul>
                </div>
            </div>
            <div class="p-3.5 bg-gray-50 border-t border-gray-200 text-xs text-gray-600 space-y-1">
                <p class="font-bold text-brand-700">CÔNG TY TNHH THÙY DUNG FOODS</p>
                <p>Hotline: <a href="tel:0984113366" class="font-bold text-amber-700">0984.113.366</a></p>
                <p>Email: lkdanangvn@gmail.com</p>
            </div>
        </div>
    </div>

    <!-- ==========================================
         3. BANNER SLIDER TỰ TRƯỢT (2 ẢNH KÍCH THƯỚC BẰNG NHAU)
            - Thiết kế riêng ảnh Banner Máy Tính (hidden md:block) và ảnh Banner Điện Thoại (block md:hidden)
            - Chữ nhỏ gọn nằm hoàn toàn bên trong khung ảnh banner, tuyệt đối không tràn viền
         ========================================== -->
    <section id="trang-chu" class="py-3 sm:py-4">
        <div class="flatsome-container">
            <div class="relative rounded-2xl overflow-hidden shadow-md border border-emerald-100 bg-brand-800">

                <!-- ================= SLIDE 1 ================= -->
                <div class="hero-slide transition-opacity duration-700 ease-in-out" data-slide="0">
                    <!-- PHIÊN BẢN MÁY TÍNH (Desktop Banner 1 - Kích thước cố định h-[370px] lg:h-[400px]) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[370px] lg:h-[400px] bg-gradient-to-r from-[#0f3f22] via-[#166534] to-[#1e7e42] px-8 lg:px-12 py-6 relative overflow-hidden">
                        <div class="col-span-7 z-10 pr-4 space-y-2.5">
                            <span class="inline-block px-3 py-1 rounded-full bg-amber-400/20 border border-amber-300/40 text-amber-200 text-xs font-semibold tracking-wide">
                                TINH HOA NÔNG SẢN TỰ NHIÊN VIỆT NAM
                            </span>
                            <h1 class="font-heading font-extrabold text-white text-xl lg:text-2xl xl:text-3xl leading-snug">
                                HẠT SẤY BẢN ĐỊA & GỪNG NƯỚNG MẬT ONG THÙY DUNG FOODS
                            </h1>
                            <p class="text-emerald-100 text-xs lg:text-sm leading-relaxed max-w-xl">
                                Tuyển chọn nguyên liệu tươi ngon từ Đắk Lắk và các vùng miền Việt Nam: Hạt điều phủ vị tự nhiên, Hạt sen sấy giòn, Macca, Đậu phộng rang không dầu và Gừng nướng mật ong chuẩn ISO.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <a href="#sec-hat-say" class="px-4 py-2 rounded-full bg-amber-500 hover:bg-amber-600 text-white font-bold shadow transition">
                                    Khám Phá Sản Phẩm
                                </a>
                                <a href="#form-bao-gia" class="px-4 py-2 rounded-full bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold transition">
                                    Nhận Báo Giá Sỉ & Đại Lý
                                </a>
                            </div>
                            <div class="pt-1 flex items-center gap-4 text-[11px] text-emerald-200">
                                <span><i class="fa-solid fa-phone-volume text-amber-300 mr-1"></i>Hotline: 0984.113.366</span>
                                <span><i class="fa-solid fa-globe text-amber-300 mr-1"></i>thuydungfoods.com.com</span>
                            </div>
                        </div>
                        <div class="col-span-5 z-10 grid grid-cols-3 gap-2.5 items-center">
                            <div class="bg-white p-1.5 rounded-xl shadow-lg transform -rotate-2">
                                <img src="https://lh3.googleusercontent.com/d/1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4"
                                     onerror="handleDriveImageError(this, '1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4', 'Hat+Dieu')"
                                     alt="Sản phẩm Thùy Dung Foods 1" class="w-full h-36 lg:h-44 object-cover rounded-lg">
                            </div>
                            <div class="bg-white p-1.5 rounded-xl shadow-lg transform scale-105 z-10">
                                <img src="https://lh3.googleusercontent.com/d/1hPY1V760wI9PBk7fXHSrRFZLaiX4apKG"
                                     onerror="handleDriveImageError(this, '1hPY1V760wI9PBk7fXHSrRFZLaiX4apKG', 'Gung+Nuong')"
                                     alt="Sản phẩm Thùy Dung Foods 2" class="w-full h-40 lg:h-48 object-cover rounded-lg">
                            </div>
                            <div class="bg-white p-1.5 rounded-xl shadow-lg transform rotate-2">
                                <img src="https://lh3.googleusercontent.com/d/1PhxQRm0LQ8RBm0nE6VaU6gUcmLsTT04d"
                                     onerror="handleDriveImageError(this, '1PhxQRm0LQ8RBm0nE6VaU6gUcmLsTT04d', 'Hat+Sen')"
                                     alt="Sản phẩm Thùy Dung Foods 3" class="w-full h-36 lg:h-44 object-cover rounded-lg">
                            </div>
                        </div>
                    </div>

                    <!-- PHIÊN BẢN ĐIỆN THOẠI (Mobile Banner 1 - Thiết kế riêng cho màn hình dọc, chữ nhỏ gọn không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between h-[285px] bg-gradient-to-b from-[#134e29] via-[#166534] to-[#0f3f22] px-4 py-3.5 text-center relative overflow-hidden">
                        <div class="space-y-1">
                            <span class="inline-block px-2.5 py-0.5 rounded-full bg-amber-400/20 text-amber-200 text-[10px] font-semibold">
                                CÔNG TY TNHH THÙY DUNG FOODS
                            </span>
                            <h2 class="font-heading font-extrabold text-white text-sm sm:text-base leading-tight px-1">
                                HẠT SẤY BẢN ĐỊA & GỪNG NƯỚNG MẬT ONG TỰ NHIÊN
                            </h2>
                            <p class="text-emerald-100 text-[11px] leading-snug px-2">
                                Hạt điều, hạt sen, macca, đậu phộng & trái cây sấy tuyển chọn. Không chất bảo quản.
                            </p>
                        </div>
                        <div class="grid grid-cols-3 gap-2 px-2 my-1">
                            <div class="bg-white p-1 rounded-lg shadow">
                                <img src="https://lh3.googleusercontent.com/d/1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4"
                                     onerror="handleDriveImageError(this, '1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4', 'SP1')"
                                     alt="SP 1" class="w-full h-20 object-cover rounded">
                            </div>
                            <div class="bg-white p-1 rounded-lg shadow">
                                <img src="https://lh3.googleusercontent.com/d/1hPY1V760wI9PBk7fXHSrRFZLaiX4apKG"
                                     onerror="handleDriveImageError(this, '1hPY1V760wI9PBk7fXHSrRFZLaiX4apKG', 'SP2')"
                                     alt="SP 2" class="w-full h-20 object-cover rounded">
                            </div>
                            <div class="bg-white p-1 rounded-lg shadow">
                                <img src="https://lh3.googleusercontent.com/d/1PhxQRm0LQ8RBm0nE6VaU6gUcmLsTT04d"
                                     onerror="handleDriveImageError(this, '1PhxQRm0LQ8RBm0nE6VaU6gUcmLsTT04d', 'SP3')"
                                     alt="SP 3" class="w-full h-20 object-cover rounded">
                            </div>
                        </div>
                        <div class="flex items-center justify-center gap-2 text-[11px]">
                            <a href="#sec-hat-say" class="px-3 py-1 rounded-full bg-amber-500 text-white font-bold">Xem Sản Phẩm</a>
                            <span class="text-amber-200 font-semibold">SĐT: 0984.113.366</span>
                        </div>
                    </div>
                </div>

                <!-- ================= SLIDE 2 (KÍCH THƯỚC BẰNG HỆT SLIDE 1) ================= -->
                <div class="hero-slide hidden transition-opacity duration-700 ease-in-out" data-slide="1">
                    <!-- PHIÊN BẢN MÁY TÍNH (Desktop Banner 2 - Kích thước cố định h-[370px] lg:h-[400px]) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[370px] lg:h-[400px] bg-gradient-to-r from-[#1c4532] via-[#155e36] to-[#78350f] px-8 lg:px-12 py-6 relative overflow-hidden">
                        <div class="col-span-7 z-10 pr-4 space-y-2.5">
                            <span class="inline-block px-3 py-1 rounded-full bg-amber-300/20 border border-amber-300/40 text-amber-200 text-xs font-semibold tracking-wide">
                                NHỮNG HỘP QUÀ BIẾT KỂ CHUYỆN & CUNG ỨNG 5 SAO
                            </span>
                            <h2 class="font-heading font-extrabold text-white text-xl lg:text-2xl xl:text-3xl leading-snug">
                                QUÀ TẶNG DOANH NGHIỆP & ĐỐI TÁC KHÁCH SẠN - SIÊU THỊ
                            </h2>
                            <p class="text-emerald-100 text-xs lg:text-sm leading-relaxed max-w-xl">
                                Hơn 100 mẫu bao bì quà tặng truyền thống, in ấn logo thương hiệu theo yêu cầu sự kiện, cung ứng Minibar khách sạn 5 sao, hệ thống siêu thị và xuất khẩu quốc tế.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <a href="#sec-hop-qua" class="px-4 py-2 rounded-full bg-amber-500 hover:bg-amber-600 text-white font-bold shadow transition">
                                    Bộ Sưu Tập Hộp Quà
                                </a>
                                <a href="#doi-tac" class="px-4 py-2 rounded-full bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold transition">
                                    Hợp Tác Phân Phối & OEM
                                </a>
                            </div>
                            <div class="pt-1 flex items-center gap-4 text-[11px] text-emerald-200">
                                <span><i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>Đắk Lắk & TP. Đà Nẵng</span>
                                <span><i class="fa-solid fa-phone text-amber-300 mr-1"></i>0984.113.366</span>
                            </div>
                        </div>
                        <div class="col-span-5 z-10 grid grid-cols-3 gap-2.5 items-center">
                            <div class="bg-white p-1.5 rounded-xl shadow-lg transform -rotate-2">
                                <img src="https://lh3.googleusercontent.com/d/1rEBdYsxLOS-NfuzeSxg-gYYinI_McouK"
                                     onerror="handleDriveImageError(this, '1rEBdYsxLOS-NfuzeSxg-gYYinI_McouK', 'Hop+Qua+1')"
                                     alt="Sản phẩm Thùy Dung Foods 4" class="w-full h-36 lg:h-44 object-cover rounded-lg">
                            </div>
                            <div class="bg-white p-1.5 rounded-xl shadow-lg transform scale-105 z-10">
                                <img src="https://lh3.googleusercontent.com/d/19_rIWkN5pWJ2_OniJvHPV07VjZ08pkcX"
                                     onerror="handleDriveImageError(this, '19_rIWkN5pWJ2_OniJvHPV07VjZ08pkcX', 'Hop+Qua+2')"
                                     alt="Sản phẩm Thùy Dung Foods 5" class="w-full h-40 lg:h-48 object-cover rounded-lg">
                            </div>
                            <div class="bg-white p-1.5 rounded-xl shadow-lg transform rotate-2">
                                <img src="https://lh3.googleusercontent.com/d/1zVXgxO5tPyl4iOQ1qBp37t2snTKa-kBt"
                                     onerror="handleDriveImageError(this, '1zVXgxO5tPyl4iOQ1qBp37t2snTKa-kBt', 'Hop+Qua+3')"
                                     alt="Sản phẩm Thùy Dung Foods 6" class="w-full h-36 lg:h-44 object-cover rounded-lg">
                            </div>
                        </div>
                    </div>

                    <!-- PHIÊN BẢN ĐIỆN THOẠI (Mobile Banner 2 - Kích thước h-[285px] bằng hệt Mobile Banner 1) -->
                    <div class="flex md:hidden flex-col justify-between h-[285px] bg-gradient-to-b from-[#1c4532] via-[#166534] to-[#5c2d0c] px-4 py-3.5 text-center relative overflow-hidden">
                        <div class="space-y-1">
                            <span class="inline-block px-2.5 py-0.5 rounded-full bg-amber-400/20 text-amber-200 text-[10px] font-semibold">
                                QUÀ TẶNG DOANH NGHIỆP & ĐỐI TÁC 5 SAO
                            </span>
                            <h2 class="font-heading font-extrabold text-white text-sm sm:text-base leading-tight px-1">
                                NHỮNG HỘP QUÀ BIẾT KỂ CHUYỆN - IN LOGO THEO YÊU CẦU
                            </h2>
                            <p class="text-emerald-100 text-[11px] leading-snug px-2">
                                Cung ứng khách sạn 5 sao, siêu thị, quà tặng lễ Tết & xuất khẩu nông sản chất lượng cao.
                            </p>
                        </div>
                        <div class="grid grid-cols-3 gap-2 px-2 my-1">
                            <div class="bg-white p-1 rounded-lg shadow">
                                <img src="https://lh3.googleusercontent.com/d/1rEBdYsxLOS-NfuzeSxg-gYYinI_McouK"
                                     onerror="handleDriveImageError(this, '1rEBdYsxLOS-NfuzeSxg-gYYinI_McouK', 'SP4')"
                                     alt="SP 4" class="w-full h-20 object-cover rounded">
                            </div>
                            <div class="bg-white p-1 rounded-lg shadow">
                                <img src="https://lh3.googleusercontent.com/d/19_rIWkN5pWJ2_OniJvHPV07VjZ08pkcX"
                                     onerror="handleDriveImageError(this, '19_rIWkN5pWJ2_OniJvHPV07VjZ08pkcX', 'SP5')"
                                     alt="SP 5" class="w-full h-20 object-cover rounded">
                            </div>
                            <div class="bg-white p-1 rounded-lg shadow">
                                <img src="https://lh3.googleusercontent.com/d/1zVXgxO5tPyl4iOQ1qBp37t2snTKa-kBt"
                                     onerror="handleDriveImageError(this, '1zVXgxO5tPyl4iOQ1qBp37t2snTKa-kBt', 'SP6')"
                                     alt="SP 6" class="w-full h-20 object-cover rounded">
                            </div>
                        </div>
                        <div class="flex items-center justify-center gap-2 text-[11px]">
                            <a href="#form-bao-gia" class="px-3 py-1 rounded-full bg-amber-500 text-white font-bold">Nhận Báo Giá</a>
                            <span class="text-amber-200 font-semibold">thuydungfoods.com.com</span>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slider trái/phải & chấm tròn -->
                <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/35 hover:bg-black/55 text-white flex items-center justify-center z-20 transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/35 hover:bg-black/55 text-white flex items-center justify-center z-20 transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button onclick="goToSlide(0)" class="slide-dot w-2.5 h-2.5 rounded-full bg-amber-400 transition"></button>
                    <button onclick="goToSlide(1)" class="slide-dot w-2.5 h-2.5 rounded-full bg-white/50 transition"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         4. DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ NHỎ GỌN, ĐẸP TRÊN CẢ MÁY TÍNH & ĐIỆN THOẠI)
         ========================================== -->
    <section class="py-4">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">DANH MỤC SẢN PHẨM</span>
                <b></b>
            </div>

            <!-- Grid Danh Mục: Chữ danh mục ở trang chủ nhỏ gọn, không xuống dòng lộn xộn -->
            <div class="grid grid-cols-4 sm:grid-cols-4 lg:grid-cols-8 gap-2 sm:gap-3">
                <a href="#sec-hat-say" onclick="filterCategory('Hạt Điều')" class="group bg-white p-2 rounded-xl border border-gray-200 hover:border-brand-600 shadow-2xs hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-emerald-100 mb-1.5 bg-emerald-50 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4"
                             onerror="handleDriveImageError(this, '1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4', 'Hat+Dieu')"
                             alt="Hạt Điều" class="w-full h-full object-cover group-hover:scale-110 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-gray-800 group-hover:text-brand-600 leading-tight whitespace-nowrap">Hạt Điều</span>
                </a>

                <a href="#sec-hat-say" onclick="filterCategory('Hạt Sen & Macca')" class="group bg-white p-2 rounded-xl border border-gray-200 hover:border-brand-600 shadow-2xs hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-emerald-100 mb-1.5 bg-emerald-50 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1hPY1V760wI9PBk7fXHSrRFZLaiX4apKG"
                             onerror="handleDriveImageError(this, '1hPY1V760wI9PBk7fXHSrRFZLaiX4apKG', 'Hat+Sen')"
                             alt="Hạt Sen" class="w-full h-full object-cover group-hover:scale-110 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-gray-800 group-hover:text-brand-600 leading-tight whitespace-nowrap">Hạt Sen Sấy</span>
                </a>

                <a href="#sec-hat-say" onclick="filterCategory('Hạt Sen & Macca')" class="group bg-white p-2 rounded-xl border border-gray-200 hover:border-brand-600 shadow-2xs hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-emerald-100 mb-1.5 bg-emerald-50 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1PhxQRm0LQ8RBm0nE6VaU6gUcmLsTT04d"
                             onerror="handleDriveImageError(this, '1PhxQRm0LQ8RBm0nE6VaU6gUcmLsTT04d', 'Hat+Macca')"
                             alt="Hạt Macca" class="w-full h-full object-cover group-hover:scale-110 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-gray-800 group-hover:text-brand-600 leading-tight whitespace-nowrap">Hạt Macca</span>
                </a>

                <a href="#sec-hat-say" onclick="filterCategory('Đậu Phộng & Đậu Nành')" class="group bg-white p-2 rounded-xl border border-gray-200 hover:border-brand-600 shadow-2xs hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-emerald-100 mb-1.5 bg-emerald-50 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1rEBdYsxLOS-NfuzeSxg-gYYinI_McouK"
                             onerror="handleDriveImageError(this, '1rEBdYsxLOS-NfuzeSxg-gYYinI_McouK', 'Dau+Phong')"
                             alt="Đậu Phộng" class="w-full h-full object-cover group-hover:scale-110 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-gray-800 group-hover:text-brand-600 leading-tight whitespace-nowrap">Đậu Phộng</span>
                </a>

                <a href="#sec-gung-trai-cay" class="group bg-white p-2 rounded-xl border border-gray-200 hover:border-brand-600 shadow-2xs hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-emerald-100 mb-1.5 bg-emerald-50 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/19_rIWkN5pWJ2_OniJvHPV07VjZ08pkcX"
                             onerror="handleDriveImageError(this, '19_rIWkN5pWJ2_OniJvHPV07VjZ08pkcX', 'Gung+Nuong')"
                             alt="Gừng Nướng" class="w-full h-full object-cover group-hover:scale-110 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-gray-800 group-hover:text-brand-600 leading-tight whitespace-nowrap">Gừng Mật Ong</span>
                </a>

                <a href="#sec-gung-trai-cay" class="group bg-white p-2 rounded-xl border border-gray-200 hover:border-brand-600 shadow-2xs hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-emerald-100 mb-1.5 bg-emerald-50 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1zVXgxO5tPyl4iOQ1qBp37t2snTKa-kBt"
                             onerror="handleDriveImageError(this, '1zVXgxO5tPyl4iOQ1qBp37t2snTKa-kBt', 'Trai+Cay+Say')"
                             alt="Trái Cây Sấy" class="w-full h-full object-cover group-hover:scale-110 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-gray-800 group-hover:text-brand-600 leading-tight whitespace-nowrap">Trái Cây Sấy</span>
                </a>

                <a href="#sec-hop-qua" class="group bg-white p-2 rounded-xl border border-gray-200 hover:border-brand-600 shadow-2xs hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-emerald-100 mb-1.5 bg-emerald-50 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/15i-v6OCgNBvR8lCRsbyxrMqL9AYUXxwZ"
                             onerror="handleDriveImageError(this, '15i-v6OCgNBvR8lCRsbyxrMqL9AYUXxwZ', 'Hop+Qua')"
                             alt="Hộp Quà Tặng" class="w-full h-full object-cover group-hover:scale-110 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-gray-800 group-hover:text-brand-600 leading-tight whitespace-nowrap">Hộp Quà Tặng</span>
                </a>

                <a href="#sec-tra-ca-phe" class="group bg-white p-2 rounded-xl border border-gray-200 hover:border-brand-600 shadow-2xs hover:shadow-md transition text-center flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full overflow-hidden border border-emerald-100 mb-1.5 bg-emerald-50 shrink-0">
                        <img src="https://lh3.googleusercontent.com/d/1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4"
                             onerror="handleDriveImageError(this, '1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4', 'Tra+Ca+Phe')"
                             alt="Trà & Cà Phê" class="w-full h-full object-cover group-hover:scale-110 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-gray-800 group-hover:text-brand-600 leading-tight whitespace-nowrap">Trà & Cà Phê</span>
                </a>
            </div>
        </div>
    </section>

    <!-- ==========================================
         5. DANH SÁCH SẢN PHẨM TRANG CHỦ (CHUẨN FLATSOME + DỮ LIỆU NAMXANH.COM.VN + 7 ẢNH GOOGLE DRIVE)
            - Điện thoại chia 2 cột (grid-cols-2), Máy tính chia 4-5 cột
            - Góc trên bên trái có % giảm giá chuẩn Flatsome (-15%, -18%, v.v.)
            - Không để các nhãn dán rườm rà khác
            - Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ
         ========================================== -->

    <!-- SECTION 5.1: NHÓM HẠT SẤY DINH DƯỠNG (HẠT ĐIỀU, HẠT SEN, MACCA, ĐẬU PHỘNG, ĐẬU NÀNH) -->
    <section id="sec-hat-say" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">HẠT SẤY BẢN ĐỊA (HẠT ĐIỀU - HẠT SEN - MACCA - ĐẬU PHỘNG)</span>
                <b></b>
            </div>

            <!-- Bộ lọc nhanh nhỏ gọn -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 mb-4">
                <button onclick="filterCategory('all')" class="cat-filter-btn active px-3 py-1 rounded-full text-xs font-semibold bg-brand-600 text-white transition">Tất cả hạt sấy</button>
                <button onclick="filterCategory('Hạt Điều')" class="cat-filter-btn px-3 py-1 rounded-full text-xs font-semibold bg-white text-gray-700 border border-gray-200 hover:border-brand-600 transition">Hạt Điều</button>
                <button onclick="filterCategory('Hạt Sen & Macca')" class="cat-filter-btn px-3 py-1 rounded-full text-xs font-semibold bg-white text-gray-700 border border-gray-200 hover:border-brand-600 transition">Hạt Sen & Macca</button>
                <button onclick="filterCategory('Đậu Phộng & Đậu Nành')" class="cat-filter-btn px-3 py-1 rounded-full text-xs font-semibold bg-white text-gray-700 border border-gray-200 hover:border-brand-600 transition">Đậu Phộng & Đậu Nành</button>
            </div>

            <!-- Grid sản phẩm: 2 cột trên điện thoại, 4-5 cột trên máy tính -->
            <div id="grid-hat-say" class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-4"></div>
        </div>
    </section>

    <!-- SECTION 5.2: GỪNG NƯỚNG MẬT ONG & TRÁI CÂY SẤY DẺO -->
    <section id="sec-gung-trai-cay" class="py-5 bg-white border-y border-gray-100">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">GỪNG NƯỚNG MẬT ONG & TRÁI CÂY SẤY TỰ NHIÊN</span>
                <b></b>
            </div>
            <div id="grid-gung-trai-cay" class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-4"></div>
        </div>
    </section>

    <!-- SECTION 5.3: HỘP QUÀ TẶNG CAO CẤP - NHỮNG HỘP QUÀ BIẾT KỂ CHUYỆN -->
    <section id="sec-hop-qua" class="py-5">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">HỘP QUÀ TẶNG CAO CẤP - NHỮNG HỘP QUÀ BIẾT KỂ CHUYỆN</span>
                <b></b>
            </div>
            <div id="grid-hop-qua" class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-4"></div>
        </div>
    </section>

    <!-- SECTION 5.4: TRÀ & CÀ PHÊ ĐẮK LẮK - GIA VỊ MUỐI & SẢN PHẨM XUẤT KHẨU -->
    <section id="sec-tra-ca-phe" class="py-5 bg-white border-y border-gray-100">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">TRÀ & CÀ PHÊ ĐẮK LẮK - GIA VỊ MUỐI & XUẤT KHẨU</span>
                <b></b>
            </div>
            <div id="grid-tra-ca-phe" class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-4"></div>
        </div>
    </section>

    <!-- ==========================================
         6. CÂU CHUYỆN THƯƠNG HIỆU & NĂNG LỰC CUNG ỨNG (GIỐNG WEB MẪU NAMXANH.COM.VN)
         ========================================== -->
    <section id="ve-chung-toi" class="py-6">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">VỀ CÔNG TY TNHH THÙY DUNG FOODS</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-3 gap-4">
                <!-- Khối 1 -->
                <div class="bg-white rounded-xl p-4 border border-gray-200 shadow-2xs flex flex-col justify-between">
                    <div>
                        <div class="w-full h-44 rounded-lg overflow-hidden mb-3 bg-emerald-50">
                            <img src="https://lh3.googleusercontent.com/d/1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4"
                                 onerror="handleDriveImageError(this, '1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4', 'Nong+San')"
                                 alt="Tinh hoa nông sản" class="w-full h-full object-cover">
                        </div>
                        <h3 class="font-heading font-bold text-brand-700 text-sm sm:text-base mb-1.5">Sản Phẩm Đa Dạng & Tự Nhiên</h3>
                        <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">
                            Thùy Dung Foods cung cấp hơn 100 sản phẩm nông sản chế biến và bao bì đa dạng. Kết hợp nông sản cao cấp từ Đắk Lắk và kỹ thuật chế biến hiện đại, giữ trọn hương vị tự nhiên, không chất bảo quản.
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-gray-100 flex items-center justify-between text-xs font-semibold text-brand-600">
                        <span>Chuẩn vệ sinh ATTP - ISO 22000</span>
                        <a href="#form-bao-gia" class="hover:underline">Tư vấn ngay →</a>
                    </div>
                </div>

                <!-- Khối 2 -->
                <div class="bg-white rounded-xl p-4 border border-gray-200 shadow-2xs flex flex-col justify-between">
                    <div>
                        <div class="w-full h-44 rounded-lg overflow-hidden mb-3 bg-emerald-50">
                            <img src="https://lh3.googleusercontent.com/d/19_rIWkN5pWJ2_OniJvHPV07VjZ08pkcX"
                                 onerror="handleDriveImageError(this, '19_rIWkN5pWJ2_OniJvHPV07VjZ08pkcX', 'Doi+Tac+5+Sao')"
                                 alt="Nhà cung ứng đối tác 5 sao" class="w-full h-full object-cover">
                        </div>
                        <h3 class="font-heading font-bold text-brand-700 text-sm sm:text-base mb-1.5">Nhà Cung Ứng Uy Tín Cho Đối Tác 5 Sao</h3>
                        <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">
                            Tuyển chọn nguyên liệu ngon nhất của mỗi mùa vụ như mật ong, hạt tiêu, gừng, hạt điều, macca để tạo ra các sản phẩm đặc trưng cho quầy Minibar, Buffet và quà tặng VIP cho khách sạn, resort 5 sao.
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-gray-100 flex items-center justify-between text-xs font-semibold text-brand-600">
                        <span>Cung ứng Khách sạn & Resort</span>
                        <a href="#form-bao-gia" class="hover:underline">Nhận hồ sơ năng lực →</a>
                    </div>
                </div>

                <!-- Khối 3 -->
                <div class="bg-white rounded-xl p-4 border border-gray-200 shadow-2xs flex flex-col justify-between">
                    <div>
                        <div class="w-full h-44 rounded-lg overflow-hidden mb-3 bg-emerald-50">
                            <img src="https://lh3.googleusercontent.com/d/15i-v6OCgNBvR8lCRsbyxrMqL9AYUXxwZ"
                                 onerror="handleDriveImageError(this, '15i-v6OCgNBvR8lCRsbyxrMqL9AYUXxwZ', 'He+Thong+Ban+Le')"
                                 alt="Hệ thống bán lẻ & xuất khẩu" class="w-full h-full object-cover">
                        </div>
                        <h3 class="font-heading font-bold text-brand-700 text-sm sm:text-base mb-1.5">Nhà Sản Xuất Chuẩn Hệ Thống Bán Lẻ & Xuất Khẩu</h3>
                        <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">
                            Tuân thủ nghiêm ngặt quy định an toàn thực phẩm, đáp ứng tiêu chuẩn phân phối vào hệ thống siêu thị, cửa hàng tiện lợi và xuất khẩu sang các thị trường quốc tế (Mỹ, Úc, Nhật Bản, Singapore).
                        </p>
                    </div>
                    <div class="mt-3 pt-2.5 border-t border-gray-100 flex items-center justify-between text-xs font-semibold text-brand-600">
                        <span>Hợp tác Gia công OEM / Xuất khẩu</span>
                        <a href="#form-bao-gia" class="hover:underline">Liên hệ hợp tác →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         7. DANH MỤC CÁC ĐỐI TÁC (ĐỐI TÁC CHIẾN LƯỢC & CÁC KÊNH HỢP TÁC)
         ========================================== -->
    <section id="doi-tac" class="py-6 bg-white border-y border-gray-100">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">DANH MỤC ĐỐI TÁC & HỢP TÁC PHÂN PHỐI</span>
                <b></b>
            </div>

            <!-- 6 Nhóm Đối Tác chuẩn Nam Xanh -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 sm:gap-3 mb-5">
                <div class="bg-brand-50/70 border border-emerald-100 rounded-xl p-3 text-center hover:shadow-sm transition">
                    <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-brand-600 text-white flex items-center justify-center">
                        <i class="fa-solid fa-hotel text-sm"></i>
                    </div>
                    <h4 class="font-bold text-brand-800 text-xs sm:text-sm">Khách Sạn Cao Cấp</h4>
                    <p class="text-[11px] text-gray-600 mt-1">Minibar, Bếp & Khu vực VIP 4-5 sao</p>
                </div>

                <div class="bg-brand-50/70 border border-emerald-100 rounded-xl p-3 text-center hover:shadow-sm transition">
                    <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-brand-600 text-white flex items-center justify-center">
                        <i class="fa-solid fa-gift text-sm"></i>
                    </div>
                    <h4 class="font-bold text-brand-800 text-xs sm:text-sm">Quà Tặng Doanh Nghiệp</h4>
                    <p class="text-[11px] text-gray-600 mt-1">In ấn logo thương hiệu sự kiện & Lễ Tết</p>
                </div>

                <div class="bg-brand-50/70 border border-emerald-100 rounded-xl p-3 text-center hover:shadow-sm transition">
                    <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-brand-600 text-white flex items-center justify-center">
                        <i class="fa-solid fa-store text-sm"></i>
                    </div>
                    <h4 class="font-bold text-brand-800 text-xs sm:text-sm">Hợp Tác Bán Lẻ</h4>
                    <p class="text-[11px] text-gray-600 mt-1">Hệ thống siêu thị & cửa hàng đặc sản</p>
                </div>

                <div class="bg-brand-50/70 border border-emerald-100 rounded-xl p-3 text-center hover:shadow-sm transition">
                    <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-brand-600 text-white flex items-center justify-center">
                        <i class="fa-solid fa-truck-ramp-box text-sm"></i>
                    </div>
                    <h4 class="font-bold text-brand-800 text-xs sm:text-sm">Hợp Tác Phân Phối</h4>
                    <p class="text-[11px] text-gray-600 mt-1">Đại lý & Nhà phân phối toàn quốc</p>
                </div>

                <div class="bg-brand-50/70 border border-emerald-100 rounded-xl p-3 text-center hover:shadow-sm transition">
                    <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-brand-600 text-white flex items-center justify-center">
                        <i class="fa-solid fa-plane-departure text-sm"></i>
                    </div>
                    <h4 class="font-bold text-brand-800 text-xs sm:text-sm">Hợp Tác Xuất Khẩu</h4>
                    <p class="text-[11px] text-gray-600 mt-1">Xuất khẩu nông sản chuẩn FDA, ISO</p>
                </div>

                <div class="bg-brand-50/70 border border-emerald-100 rounded-xl p-3 text-center hover:shadow-sm transition">
                    <div class="w-10 h-10 mx-auto mb-2 rounded-full bg-brand-600 text-white flex items-center justify-center">
                        <i class="fa-solid fa-industry text-sm"></i>
                    </div>
                    <h4 class="font-bold text-brand-800 text-xs sm:text-sm">Hợp Tác Gia Công</h4>
                    <p class="text-[11px] text-gray-600 mt-1">Gia công đóng gói OEM/ODM theo yêu cầu</p>
                </div>
            </div>

            <!-- Danh sách thương hiệu / đối tác tiêu biểu -->
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2.5">
                <div class="border border-gray-200 rounded-lg py-2.5 px-3 text-center bg-gray-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-bold text-xs text-brand-700">LK ĐÀ NẴNG JSC</span>
                    <span class="text-[10px] text-gray-500">Đối tác Chi nhánh phân phối</span>
                </div>
                <div class="border border-gray-200 rounded-lg py-2.5 px-3 text-center bg-gray-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-bold text-xs text-brand-700">HỆ THỐNG SIÊU THỊ</span>
                    <span class="text-[10px] text-gray-500">Kênh bán lẻ hiện đại MT</span>
                </div>
                <div class="border border-gray-200 rounded-lg py-2.5 px-3 text-center bg-gray-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-bold text-xs text-brand-700">RESORT & HOTEL 5*</span>
                    <span class="text-[10px] text-gray-500">Minibar & Quà tặng VIP</span>
                </div>
                <div class="border border-gray-200 rounded-lg py-2.5 px-3 text-center bg-gray-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-bold text-xs text-brand-700">SHOPEE & TMĐT</span>
                    <span class="text-[10px] text-gray-500">Gian hàng chính hãng</span>
                </div>
                <div class="border border-gray-200 rounded-lg py-2.5 px-3 text-center bg-gray-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-bold text-xs text-brand-700">QUÀ DOANH NGHIỆP</span>
                    <span class="text-[10px] text-gray-500">Ngân hàng & Tập đoàn</span>
                </div>
                <div class="border border-gray-200 rounded-lg py-2.5 px-3 text-center bg-gray-50 flex flex-col items-center justify-center">
                    <span class="font-heading font-bold text-xs text-brand-700">ĐỐI TÁC XUẤT KHẨU</span>
                    <span class="text-[10px] text-gray-500">Mỹ, Úc, Nhật, Singapore</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         8. FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ + FANPAGE FACEBOOK NGOÀI TRANG CHỦ
         ========================================== -->
    <section id="form-bao-gia" class="py-6">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">ĐĂNG KÝ YÊU CẦU BÁO GIÁ & KẾT NỐI FANPAGE</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                <!-- Cột Trái (7 cột): Form Yêu Cầu & Báo Giá Trang Chủ -->
                <div class="lg:col-span-7 bg-white rounded-2xl border border-emerald-200 shadow-xs p-4 sm:p-6">
                    <div class="mb-4">
                        <span class="inline-block px-2.5 py-0.5 rounded-full bg-emerald-100 text-brand-700 text-[11px] font-bold mb-1">PHẢN HỒI TRONG 15 PHÚT</span>
                        <h3 class="font-heading font-bold text-brand-700 text-base sm:text-lg">GỬI YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ SỈ / LẺ</h3>
                        <p class="text-xs text-gray-600 mt-0.5">
                            Quý khách hàng, đại lý hoặc doanh nghiệp cần đặt hộp quà in logo, báo giá sỉ nông sản vui lòng điền thông tin bên dưới.
                        </p>
                    </div>

                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs sm:text-sm">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block font-semibold text-gray-700 mb-1">Họ và tên / Tên đơn vị *</label>
                                <input type="text" id="qName" required placeholder="Nhập họ tên hoặc tên công ty"
                                       class="w-full px-3 py-2 rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600">
                            </div>
                            <div>
                                <label class="block font-semibold text-gray-700 mb-1">Số điện thoại liên hệ *</label>
                                <input type="tel" id="qPhone" required placeholder="Ví dụ: 0984113366"
                                       class="w-full px-3 py-2 rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block font-semibold text-gray-700 mb-1">Địa chỉ Email</label>
                                <input type="email" id="qEmail" placeholder="Ví dụ: lkdanangvn@gmail.com"
                                       class="w-full px-3 py-2 rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600">
                            </div>
                            <div>
                                <label class="block font-semibold text-gray-700 mb-1">Hình thức hợp tác / Nhu cầu *</label>
                                <select id="qType" class="w-full px-3 py-2 rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600 bg-white">
                                    <option value="Mua lẻ / Đặt hàng tiêu dùng">Mua lẻ / Đặt hàng tiêu dùng</option>
                                    <option value="Báo giá sỉ Đại lý / Nhà phân phối">Báo giá sỉ Đại lý / Nhà phân phối</option>
                                    <option value="Đặt Hộp Quà Tặng Doanh Nghiệp (In Logo)">Đặt Hộp Quà Tặng Doanh Nghiệp (In Logo)</option>
                                    <option value="Cung ứng Khách sạn 5 Sao / Siêu thị">Cung ứng Khách sạn 5 Sao / Siêu thị</option>
                                    <option value="Hợp tác Gia công OEM / Xuất khẩu">Hợp tác Gia công OEM / Xuất khẩu</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label class="block font-semibold text-gray-700 mb-1">Sản phẩm quan tâm & Số lượng dự kiến</label>
                            <textarea id="qNote" rows="3" placeholder="Nhập tên sản phẩm (Hạt điều, Gừng nướng mật ong, Hạt sen, Macca, Hộp quà Tết...) và số lượng cần báo giá..."
                                      class="w-full px-3 py-2 rounded-lg border border-gray-300 focus:outline-none focus:border-brand-600"></textarea>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                            <div class="text-xs text-gray-500">
                                <i class="fa-solid fa-headset text-brand-600 mr-1"></i>Hotline trực tiếp: <strong class="text-brand-700">0984.113.366</strong>
                            </div>
                            <button type="submit" class="px-5 py-2.5 rounded-lg bg-brand-600 hover:bg-brand-700 text-white font-bold text-xs sm:text-sm shadow transition cursor-pointer">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU & NHẬN BÁO GIÁ
                            </button>
                        </div>
                    </form>
                </div>

                <!-- Cột Phải (5 cột): Đưa Fanpage Ra Ngoài Trang Chủ -->
                <div class="lg:col-span-5 bg-white rounded-2xl border border-gray-200 shadow-xs p-4 sm:p-5 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-3">
                            <h3 class="font-heading font-bold text-brand-700 text-sm sm:text-base flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                                <span>FANPAGE THÙY DUNG FOODS</span>
                            </h3>
                            <span class="text-[11px] text-emerald-700 bg-emerald-50 px-2 py-0.5 rounded font-semibold">Đã xác minh</span>
                        </div>

                        <!-- Khung hiển thị Fanpage trực quan ngoài trang chủ -->
                        <div class="rounded-xl overflow-hidden border border-gray-200 bg-gray-50">
                            <div class="relative h-32 bg-gradient-to-r from-brand-800 to-brand-600 p-3 flex items-end">
                                <img src="https://lh3.googleusercontent.com/d/1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4"
                                     onerror="handleDriveImageError(this, '1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4', 'Fanpage')"
                                     alt="Ảnh bìa Fanpage" class="absolute inset-0 w-full h-full object-cover opacity-35">
                                <div class="relative z-10 flex items-center gap-3">
                                    <img src="https://lh3.googleusercontent.com/d/1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns"
                                         onerror="handleDriveImageError(this, '1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns', 'Logo')"
                                         alt="Logo Fanpage" class="w-14 h-14 rounded-lg bg-white p-1 border-2 border-white shadow object-contain shrink-0">
                                    <div class="text-white">
                                        <h4 class="font-bold text-sm leading-tight">CÔNG TY TNHH THÙY DUNG FOODS</h4>
                                        <p class="text-[11px] text-emerald-100">thuydungfoods.com.com • Thực phẩm & Nông sản tự nhiên</p>
                                        <p class="text-[11px] text-amber-300 font-semibold mt-0.5"><i class="fa-solid fa-thumbs-up mr-1"></i>12.8K người theo dõi</p>
                                    </div>
                                </div>
                            </div>

                            <div class="p-3 bg-white space-y-2.5 text-xs">
                                <div class="flex items-center gap-2">
                                    <a href="https://facebook.com" target="_blank" rel="noopener" class="flex-1 py-1.5 px-3 rounded bg-blue-600 hover:bg-blue-700 text-white font-semibold text-center transition">
                                        <i class="fa-brands fa-facebook-f mr-1"></i>Theo dõi Trang
                                    </a>
                                    <a href="https://m.me/" target="_blank" rel="noopener" class="flex-1 py-1.5 px-3 rounded bg-gray-100 hover:bg-gray-200 text-gray-800 font-semibold text-center transition">
                                        <i class="fa-brands fa-facebook-messenger text-blue-600 mr-1"></i>Gửi tin nhắn
                                    </a>
                                </div>
                                <div class="p-2.5 rounded-lg bg-gray-50 border border-gray-100 text-[11.5px] text-gray-600 space-y-1">
                                    <p class="font-semibold text-gray-800">Bài đăng mới trên Fanpage:</p>
                                    <p>🌿 Bộ sưu tập Hạt điều phủ vị, Hạt sen sấy giòn, Gừng nướng mật ong & Hộp quà doanh nghiệp Thùy Dung Foods đã sẵn sàng phục vụ Quý đối tác trên toàn quốc!</p>
                                    <p class="text-brand-700 font-semibold">📞 Hotline/Zalo: 0984.113.366</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 pt-2.5 border-t border-gray-100 flex items-center justify-between text-xs text-gray-500">
                        <span>Kết nối trực tiếp qua Zalo / Fanpage 24/7</span>
                        <a href="tel:0984113366" class="font-bold text-brand-700">0984.113.366</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         9. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC NỔI BẬT GIỐNG WEB MẪU NAMXANH)
         ========================================== -->
    <section id="tin-tuc" class="py-6 bg-white border-t border-gray-100">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">DANH MỤC BÀI VIẾT & TIN TỨC NỔI BẬT</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-gray-50 rounded-xl overflow-hidden border border-gray-200 hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="relative h-40 overflow-hidden bg-emerald-50">
                            <img src="https://lh3.googleusercontent.com/d/1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4"
                                 onerror="handleDriveImageError(this, '1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4', 'Tin+Tuc+1')"
                                 alt="Hạt Điều Và 10 Công Dụng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                            <span class="absolute top-2 left-2 bg-brand-600 text-white text-[10px] font-bold px-2 py-0.5 rounded">DINH DƯỠNG</span>
                        </div>
                        <div class="p-3.5">
                            <h3 class="font-bold text-gray-800 text-xs sm:text-sm leading-snug mb-1.5">
                                Hạt Điều Và 10 Công Dụng Tuyệt Vời Cho Sức Khỏe Không Thể Bỏ Qua
                            </h3>
                            <p class="text-gray-600 text-xs leading-relaxed">
                                Hạt điều không chỉ thơm ngon giòn béo mà còn chứa hàm lượng khoáng chất, magie, chất chống oxy hóa tốt cho tim mạch...
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 pt-1 flex items-center justify-between text-xs border-t border-gray-100">
                        <span class="text-gray-400">Chuyên mục: Hạt Sấy</span>
                        <button onclick="openArticleModal(0)" class="font-semibold text-brand-600 hover:underline cursor-pointer">Xem thêm →</button>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-gray-50 rounded-xl overflow-hidden border border-gray-200 hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="relative h-40 overflow-hidden bg-emerald-50">
                            <img src="https://lh3.googleusercontent.com/d/1hPY1V760wI9PBk7fXHSrRFZLaiX4apKG"
                                 onerror="handleDriveImageError(this, '1hPY1V760wI9PBk7fXHSrRFZLaiX4apKG', 'Tin+Tuc+2')"
                                 alt="Gừng Mật Ong 7 Lợi Ích" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                            <span class="absolute top-2 left-2 bg-brand-600 text-white text-[10px] font-bold px-2 py-0.5 rounded">SỨC KHỎE</span>
                        </div>
                        <div class="p-3.5">
                            <h3 class="font-bold text-gray-800 text-xs sm:text-sm leading-snug mb-1.5">
                                Gừng Nướng Mật Ong: Khám Phá 7 Lợi Ích Tuyệt Vời Khi Sử Dụng Mỗi Ngày
                            </h3>
                            <p class="text-gray-600 text-xs leading-relaxed">
                                Sự kết hợp giữa gừng bánh tẻ nướng thơm nồng và mật ong tự nhiên giúp giữ ấm cơ thể, tăng đề kháng và hỗ trợ tiêu hóa...
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 pt-1 flex items-center justify-between text-xs border-t border-gray-100">
                        <span class="text-gray-400">Chuyên mục: Gừng Mật Ong</span>
                        <button onclick="openArticleModal(1)" class="font-semibold text-brand-600 hover:underline cursor-pointer">Xem thêm →</button>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-gray-50 rounded-xl overflow-hidden border border-gray-200 hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="relative h-40 overflow-hidden bg-emerald-50">
                            <img src="https://lh3.googleusercontent.com/d/15i-v6OCgNBvR8lCRsbyxrMqL9AYUXxwZ"
                                 onerror="handleDriveImageError(this, '15i-v6OCgNBvR8lCRsbyxrMqL9AYUXxwZ', 'Tin+Tuc+3')"
                                 alt="Quà Tặng In Logo Doanh Nghiệp" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                            <span class="absolute top-2 left-2 bg-amber-600 text-white text-[10px] font-bold px-2 py-0.5 rounded">QUÀ DOANH NGHIỆP</span>
                        </div>
                        <div class="p-3.5">
                            <h3 class="font-bold text-gray-800 text-xs sm:text-sm leading-snug mb-1.5">
                                Quà Tặng In Logo - Giải Pháp Quảng Bá Thương Hiệu Doanh Nghiệp Hiệu Quả
                            </h3>
                            <p class="text-gray-600 text-xs leading-relaxed">
                                Những hộp quà nông sản cao cấp được thiết kế tinh tế và tùy chỉnh in logo giúp gắn kết tình cảm bền chặt với đối tác, khách hàng...
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 pt-1 flex items-center justify-between text-xs border-t border-gray-100">
                        <span class="text-gray-400">Chuyên mục: Quà Tặng</span>
                        <button onclick="openArticleModal(2)" class="font-semibold text-brand-600 hover:underline cursor-pointer">Xem thêm →</button>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-gray-50 rounded-xl overflow-hidden border border-gray-200 hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="relative h-40 overflow-hidden bg-emerald-50">
                            <img src="https://lh3.googleusercontent.com/d/1PhxQRm0LQ8RBm0nE6VaU6gUcmLsTT04d"
                                 onerror="handleDriveImageError(this, '1PhxQRm0LQ8RBm0nE6VaU6gUcmLsTT04d', 'Tin+Tuc+4')"
                                 alt="Hạt Sen Sấy Dừa Mật Ong" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                            <span class="absolute top-2 left-2 bg-brand-600 text-white text-[10px] font-bold px-2 py-0.5 rounded">CẨM NANG</span>
                        </div>
                        <div class="p-3.5">
                            <h3 class="font-bold text-gray-800 text-xs sm:text-sm leading-snug mb-1.5">
                                Hạt Sen Tươi Sấy Giòn & Công Dụng Vàng Cho Giấc Ngủ Và Sức Khỏe
                            </h3>
                            <p class="text-gray-600 text-xs leading-relaxed">
                                Hạt sen tươi sau khi tách vỏ được sấy ngay bằng công nghệ hiện đại giữ nguyên vị ngọt bùi thanh khiết của đất trời Việt Nam...
                            </p>
                        </div>
                    </div>
                    <div class="px-3.5 pb-3 pt-1 flex items-center justify-between text-xs border-t border-gray-100">
                        <span class="text-gray-400">Chuyên mục: Kiến Thức</span>
                        <button onclick="openArticleModal(3)" class="font-semibold text-brand-600 hover:underline cursor-pointer">Xem thêm →</button>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         10. ĐƯA ẢNH & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ
             - Trụ sở chính: Số 169 Thế Lữ, TDP 5, P. Tân lập, Tỉnh Đắk Lắk
             - Chi nhánh: CÔNG TY CỔ PHẦN LK ĐÀ NẴNG - Số 668, đường Trường Sơn, phường Hòa Nhơn, TP. Đà Nẵng
         ========================================== -->
    <section id="lien-he-map" class="py-6">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-sm sm:text-base md:text-lg">BẢN ĐỒ GOOGLE MAP & ĐỊA CHỈ LIÊN HỆ</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 bg-white p-4 sm:p-5 rounded-2xl border border-gray-200 shadow-2xs">
                <!-- Thông tin Trụ sở & Chi nhánh -->
                <div class="lg:col-span-5 flex flex-col justify-between space-y-3">
                    <div class="space-y-3">
                        <!-- Card Trụ sở chính Đắk Lắk -->
                        <div onclick="switchMapLocation('daklak')" id="locCardDakLak" class="p-3.5 rounded-xl border-2 border-brand-600 bg-brand-50/50 cursor-pointer transition">
                            <div class="flex items-center justify-between mb-1">
                                <span class="text-[11px] font-bold uppercase px-2 py-0.5 rounded bg-brand-600 text-white">TRỤ SỞ CHÍNH - ĐẮK LẮK</span>
                                <span class="text-xs font-semibold text-brand-700"><i class="fa-solid fa-map-location-dot mr-1"></i>Xem bản đồ</span>
                            </div>
                            <h4 class="font-heading font-bold text-gray-900 text-xs sm:text-sm mt-1">CÔNG TY TNHH THÙY DUNG FOODS</h4>
                            <p class="text-xs text-gray-700 mt-1 leading-relaxed">
                                <i class="fa-solid fa-location-dot text-brand-600 mr-1.5"></i><strong>Địa chỉ:</strong> Số 169 Thế Lữ, TDP 5, P. Tân lập, Tỉnh Đắk Lắk
                            </p>
                            <p class="text-xs text-gray-700 mt-1">
                                <i class="fa-solid fa-phone text-brand-600 mr-1.5"></i><strong>Điện thoại:</strong> <a href="tel:0984113366" class="font-bold text-brand-700">0984.113.366</a>
                            </p>
                            <p class="text-xs text-gray-700 mt-1">
                                <i class="fa-solid fa-globe text-brand-600 mr-1.5"></i><strong>Website:</strong> thuydungfoods.com.com
                            </p>
                        </div>

                        <!-- Card Chi nhánh Đà Nẵng -->
                        <div onclick="switchMapLocation('danang')" id="locCardDaNang" class="p-3.5 rounded-xl border border-gray-200 hover:border-brand-600 bg-white cursor-pointer transition">
                            <div class="flex items-center justify-between mb-1">
                                <span class="text-[11px] font-bold uppercase px-2 py-0.5 rounded bg-amber-600 text-white">CHI NHÁNH ĐÀ NẴNG</span>
                                <span class="text-xs font-semibold text-brand-700"><i class="fa-solid fa-map-location-dot mr-1"></i>Xem bản đồ</span>
                            </div>
                            <h4 class="font-heading font-bold text-gray-900 text-xs sm:text-sm mt-1">CÔNG TY CỔ PHẦN LK ĐÀ NẴNG</h4>
                            <p class="text-xs text-gray-700 mt-1 leading-relaxed">
                                <i class="fa-solid fa-location-dot text-amber-600 mr-1.5"></i><strong>Địa chỉ:</strong> Số 668, đường Trường Sơn, phường Hòa Nhơn, TP. Đà Nẵng, Việt Nam
                            </p>
                            <p class="text-xs text-gray-700 mt-1">
                                <i class="fa-solid fa-phone text-amber-600 mr-1.5"></i><strong>Điện thoại:</strong> <a href="tel:0984113366" class="font-bold text-brand-700">0984113366</a>
                            </p>
                            <p class="text-xs text-gray-700 mt-1">
                                <i class="fa-solid fa-envelope text-amber-600 mr-1.5"></i><strong>Mail:</strong> <a href="mailto:lkdanangvn@gmail.com" class="text-brand-700 hover:underline">lkdanangvn@gmail.com</a>
                            </p>
                        </div>
                    </div>

                    <div class="p-3 rounded-xl bg-gray-50 border border-gray-200 text-xs text-gray-600 flex items-center justify-between">
                        <span>Giờ làm việc: Thứ 2 - Thứ 7 (08:00 - 17:30)</span>
                        <a id="externalMapLink" href="https://www.google.com/maps/search/?api=1&query=169+Th%E1%BA%BF+L%E1%BB%AF,+T%C3%A2n+L%E1%BA%ADp,+Bu%C3%B4n+Ma+Thu%E1%BB%99t,+%C4%90%E1%BA%AFk+L%E1%BA%AFk" target="_blank" rel="noopener" class="font-bold text-brand-700 hover:underline">
                            Mở Google Maps lớn <i class="fa-solid fa-up-right-from-square ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </div>

                <!-- Khung Bản đồ Google Map hiển thị trực tiếp ngoài trang chủ -->
                <div class="lg:col-span-7 flex flex-col">
                    <div class="relative w-full h-72 sm:h-80 lg:h-full min-h-[290px] rounded-xl overflow-hidden border border-gray-300 bg-emerald-50">
                        <iframe id="googleMapIframe"
                                title="Bản đồ Google Map Công Ty TNHH Thùy Dung Foods"
                                src="https://maps.google.com/maps?q=169%20Th%E1%BA%BF%20L%E1%BB%AF,%20T%C3%A2n%20L%E1%BA%ADp,%20%C4%90%E1%BA%AFk%20L%E1%BA%AFk&t=&z=15&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade"></iframe>
                        <div id="mapActiveBadge" class="absolute bottom-2.5 left-2.5 right-2.5 sm:right-auto bg-white/95 backdrop-blur-xs px-3 py-1.5 rounded-lg shadow border border-emerald-200 text-[11px] font-semibold text-brand-800">
                            <i class="fa-solid fa-location-dot text-red-600 mr-1"></i>Đang hiển thị: Số 169 Thế Lữ, TDP 5, P. Tân lập, Tỉnh Đắk Lắk
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         11. FOOTER CHUẨN FLATSOME
         ========================================== -->
    <footer class="bg-[#0f3f22] text-emerald-50 pt-8 pb-6 border-t-4 border-amber-500">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-emerald-800">
                <!-- Cột 1: Thông tin công ty & Logo gọn -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns"
                             onerror="handleDriveImageError(this, '1cpkCCctuiE5O_FzgwAbpd2oMJcd6mMns', 'LOGO')"
                             alt="Logo Thùy Dung Foods"
                             class="w-11 h-11 rounded-lg bg-white p-1 object-contain shrink-0">
                        <div>
                            <h3 class="font-heading font-extrabold text-white text-sm sm:text-base">CÔNG TY TNHH THÙY DUNG FOODS</h3>
                            <p class="text-xs text-amber-300 font-medium">Website: thuydungfoods.com.com</p>
                        </div>
                    </div>
                    <p class="text-xs text-emerald-100/90 leading-relaxed">
                        Chuyên sản xuất, chế biến và phân phối nông sản tự nhiên cao cấp: Hạt điều bản địa, Hạt sen sấy, Hạt macca, Đậu phộng, Đậu nành, Gừng nướng mật ong, Trái cây sấy dẻo, Trà & Cà phê và Hộp quà tặng doanh nghiệp.
                    </p>
                    <div class="text-xs space-y-1 pt-1">
                        <p><i class="fa-solid fa-location-dot text-amber-400 w-4"></i><strong>Trụ sở:</strong> Số 169 Thế Lữ, TDP 5, P. Tân lập, Tỉnh Đắk Lắk</p>
                        <p><i class="fa-solid fa-building text-amber-400 w-4"></i><strong>Chi nhánh:</strong> CÔNG TY CỔ PHẦN LK ĐÀ NẴNG - Số 668, đường Trường Sơn, phường Hòa Nhơn, TP. Đà Nẵng, Việt Nam</p>
                        <p><i class="fa-solid fa-phone text-amber-400 w-4"></i><strong>Điện thoại:</strong> <a href="tel:0984113366" class="text-amber-300 font-bold">0984.113.366</a> (0984113366)</p>
                        <p><i class="fa-solid fa-envelope text-amber-400 w-4"></i><strong>Email:</strong> <a href="mailto:lkdanangvn@gmail.com" class="hover:underline">lkdanangvn@gmail.com</a></p>
                    </div>
                </div>

                <!-- Cột 2: Nhóm sản phẩm -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="font-heading font-bold text-white text-xs sm:text-sm uppercase tracking-wider border-b border-emerald-700 pb-1.5">NHÓM SẢN PHẨM</h4>
                    <ul class="space-y-1.5 text-xs text-emerald-100">
                        <li><a href="#sec-hop-qua" class="hover:text-amber-300 transition">• Những Hộp Quà Biết Kể Chuyện</a></li>
                        <li><a href="#sec-hat-say" class="hover:text-amber-300 transition">• Hạt Sấy (Hạt Điều, Hạt Sen, Macca)</a></li>
                        <li><a href="#sec-hat-say" class="hover:text-amber-300 transition">• Đậu Phộng & Đậu Nành Sấy Giòn</a></li>
                        <li><a href="#sec-gung-trai-cay" class="hover:text-amber-300 transition">• Gừng Nướng Mật Ong</a></li>
                        <li><a href="#sec-gung-trai-cay" class="hover:text-amber-300 transition">• Trái Cây Sấy Dẻo Tự Nhiên</a></li>
                        <li><a href="#sec-tra-ca-phe" class="hover:text-amber-300 transition">• Trà & Cà Phê Đắk Lắk - Gia Vị Muối</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Dịch vụ & Đối tác -->
                <div class="lg:col-span-4 space-y-2">
                    <h4 class="font-heading font-bold text-white text-xs sm:text-sm uppercase tracking-wider border-b border-emerald-700 pb-1.5">HỢP TÁC & CHÍNH SÁCH</h4>
                    <ul class="space-y-1.5 text-xs text-emerald-100">
                        <li><a href="#doi-tac" class="hover:text-amber-300 transition">• Cung ứng Khách sạn 5 Sao & Resort</a></li>
                        <li><a href="#doi-tac" class="hover:text-amber-300 transition">• Quà tặng Doanh nghiệp in Logo</a></li>
                        <li><a href="#doi-tac" class="hover:text-amber-300 transition">• Hợp tác Đại lý, Siêu thị & Xuất khẩu</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300 transition">• Chính sách vận chuyển & Thanh toán linh hoạt</a></li>
                    </ul>
                    <div class="pt-2">
                        <p class="text-[11px] text-emerald-200 mb-1.5">Thanh toán & Vận chuyển toàn quốc:</p>
                        <div class="flex flex-wrap gap-1.5 text-[10px] font-semibold">
                            <span class="px-2 py-1 rounded bg-white/10">VNPay</span>
                            <span class="px-2 py-1 rounded bg-white/10">MoMo</span>
                            <span class="px-2 py-1 rounded bg-white/10">ZaloPay</span>
                            <span class="px-2 py-1 rounded bg-white/10">COD Nhận Hàng</span>
                            <span class="px-2 py-1 rounded bg-white/10">GHN / J&T</span>
                        </div>
                    </div>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-emerald-200 text-center sm:text-left">
                <p>© 2026 <strong>CÔNG TY TNHH THÙY DUNG FOODS</strong> (thuydungfoods.com.com). Giao diện chuẩn Flatsome UX Builder.</p>
                <p>Hotline: 0984.113.366 | Email: lkdanangvn@gmail.com</p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         12. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
             Tương thích trên cả máy tính và điện thoại, nằm gọn góc phải không tràn viền
         ========================================== -->
    <div class="fixed bottom-4 right-3 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0984113366" target="_blank" rel="noopener"
           aria-label="Chat Zalo 0984.113.366"
           class="group flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-blue-600 font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage -->
        <a href="#form-bao-gia"
           aria-label="Facebook Fanpage"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0984113366"
           aria-label="Gọi Hotline 0984.113.366"
           class="floating-btn-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full p-2 sm:px-3.5 sm:py-2 shadow-xl transition">
            <span class="w-7 h-7 rounded-full bg-white text-red-600 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1 whitespace-nowrap">0984.113.366</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL GIỎ HÀNG & ĐẶT HÀNG NHANH
         ========================================== -->
    <div id="cartModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3">
        <div onclick="toggleCartModal()" class="absolute inset-0 bg-black/50 backdrop-blur-xs"></div>
        <div class="relative bg-white rounded-2xl max-w-lg w-full p-4 sm:p-5 shadow-2xl z-10 max-h-[88vh] flex flex-col justify-between">
            <div class="flex items-center justify-between border-b border-gray-200 pb-3">
                <h3 class="font-heading font-bold text-brand-700 text-sm sm:text-base">
                    <i class="fa-solid fa-basket-shopping mr-1.5"></i>GIỎ HÀNG CỦA BẠN
                </h3>
                <button onclick="toggleCartModal()" class="w-7 h-7 rounded-full bg-gray-100 hover:bg-gray-200 text-gray-600 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="cartItemsContainer" class="py-3 overflow-y-auto space-y-2.5 text-xs sm:text-sm max-h-64">
                <p class="text-center text-gray-500 py-6">Giỏ hàng của bạn đang trống.</p>
            </div>
            <div class="border-t border-gray-200 pt-3 space-y-3">
                <div class="flex items-center justify-between font-bold text-sm">
                    <span>Tổng cộng tạm tính:</span>
                    <span id="cartTotalPrice" class="text-red-600 text-base">0₫</span>
                </div>
                <div class="flex gap-2">
                    <button onclick="toggleCartModal()" class="flex-1 py-2 rounded-lg border border-gray-300 text-xs font-semibold hover:bg-gray-50">Tiếp tục xem</button>
                    <a href="#form-bao-gia" onclick="prefillQuoteFromCart(); toggleCartModal()" class="flex-1 py-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white text-xs font-bold text-center">
                        Gửi Đặt Hàng / Báo Giá
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- MODAL XEM BÀI VIẾT & THÔNG BÁO -->
    <div id="messageModal" class="fixed inset-0 z-50 hidden flex items-center justify-center p-3">
        <div onclick="closeMessageModal()" class="absolute inset-0 bg-black/50 backdrop-blur-xs"></div>
        <div class="relative bg-white rounded-2xl max-w-md w-full p-5 shadow-2xl z-10 text-center space-y-3">
            <div class="w-12 h-12 rounded-full bg-emerald-100 text-brand-600 flex items-center justify-center mx-auto">
                <i class="fa-solid fa-check text-xl"></i>
            </div>
            <h4 id="messageModalTitle" class="font-heading font-bold text-gray-900 text-base">Thông báo</h4>
            <p id="messageModalBody" class="text-xs sm:text-sm text-gray-600 leading-relaxed"></p>
            <button onclick="closeMessageModal()" class="px-5 py-2 rounded-lg bg-brand-600 text-white text-xs font-bold hover:bg-brand-700">Đóng</button>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT: DỮ LIỆU SẢN PHẨM THỰC TẾ (7 ẢNH GOOGLE DRIVE + SẢN PHẨM NAMXANH.COM.VN)
         ========================================== -->
    <script>
        // 7 ID ảnh sản phẩm thực tế từ Google Drive người dùng cung cấp
        const driveImages = [
            '1EgrrnmyjWzrL1jHCs35OceGimsoPO8M4',
            '1hPY1V760wI9PBk7fXHSrRFZLaiX4apKG',
            '1PhxQRm0LQ8RBm0nE6VaU6gUcmLsTT04d',
            '1rEBdYsxLOS-NfuzeSxg-gYYinI_McouK',
            '19_rIWkN5pWJ2_OniJvHPV07VjZ08pkcX',
            '1zVXgxO5tPyl4iOQ1qBp37t2snTKa-kBt',
            '15i-v6OCgNBvR8lCRsbyxrMqL9AYUXxwZ'
        ];

        // Danh mục sản phẩm chuẩn từ namxanh.com.vn kết hợp 7 ảnh thực tế Google Drive
        const productsData = [
            // --- NHÓM 1: HẠT SẤY (HẠT ĐIỀU, HẠT SEN, MACCA, ĐẬU PHỘNG, ĐẬU NÀNH) ---
            {
                id: 'sp1',
                group: 'hat-say',
                category: 'Hạt Điều',
                name: 'Hạt Điều Phủ Dừa Mật Ong 100g (120g)',
                oldPrice: 108000,
                price: 90300,
                discount: 16,
                imgId: driveImages[0]
            },
            {
                id: 'sp2',
                group: 'hat-say',
                category: 'Hạt Điều',
                name: 'Hạt Điều Sấy Tiêu Hồng 100g (120g)',
                oldPrice: 110000,
                price: 90300,
                discount: 18,
                imgId: driveImages[1]
            },
            {
                id: 'sp3',
                group: 'hat-say',
                category: 'Hạt Điều',
                name: 'Hạt Điều Phủ Nghệ Mật Ong 100g (120g)',
                oldPrice: 108000,
                price: 90300,
                discount: 16,
                imgId: driveImages[2]
            },
            {
                id: 'sp4',
                group: 'hat-say',
                category: 'Hạt Điều',
                name: 'Hạt Điều Rang Muối Vỏ Lụa 250g (300g)',
                oldPrice: 180000,
                price: 149100,
                discount: 17,
                imgId: driveImages[3]
            },
            {
                id: 'sp5',
                group: 'hat-say',
                category: 'Hạt Điều',
                name: 'Hạt Điều Tách Vỏ Lụa 250g (300g)',
                oldPrice: 220000,
                price: 185800,
                discount: 15,
                imgId: driveImages[4]
            },
            {
                id: 'sp6',
                group: 'hat-say',
                category: 'Hạt Sen & Macca',
                name: 'Hạt Sen Tươi Sấy Giòn 230g (280g)',
                oldPrice: 345000,
                price: 296200,
                discount: 14,
                imgId: driveImages[5]
            },
            {
                id: 'sp7',
                group: 'hat-say',
                category: 'Hạt Sen & Macca',
                name: 'Hạt Sen Sấy Gừng Mật Ong 100g (140g)',
                oldPrice: 250000,
                price: 210700,
                discount: 16,
                imgId: driveImages[6]
            },
            {
                id: 'sp8',
                group: 'hat-say',
                category: 'Hạt Sen & Macca',
                name: 'Hạt Macca Đắk Lắk Có Vỏ Tuyển Chọn 150g',
                oldPrice: 130000,
                price: 106000,
                discount: 18,
                imgId: driveImages[0]
            },
            {
                id: 'sp9',
                group: 'hat-say',
                category: 'Đậu Phộng & Đậu Nành',
                name: 'Đậu Phộng Rang Không Dầu Tách Vỏ 70g',
                oldPrice: 42000,
                price: 34500,
                discount: 18,
                imgId: driveImages[1]
            },
            {
                id: 'sp10',
                group: 'hat-say',
                category: 'Đậu Phộng & Đậu Nành',
                name: 'Đậu Nành Sấy Giòn Phủ Dừa 80g (100g)',
                oldPrice: 38000,
                price: 30400,
                discount: 20,
                imgId: driveImages[2]
            },

            // --- NHÓM 2: GỪNG NƯỚNG MẬT ONG & TRÁI CÂY SẤY ---
            {
                id: 'sp11',
                group: 'gung-trai-cay',
                category: 'Gừng Nướng Mật Ong',
                name: 'Gừng Nướng Mật Ong - Túi 10 Gói Tiện Dụng',
                oldPrice: 70000,
                price: 58000,
                discount: 17,
                imgId: driveImages[3]
            },
            {
                id: 'sp12',
                group: 'gung-trai-cay',
                category: 'Gừng Nướng Mật Ong',
                name: 'Gừng Nướng Mật Ong Hộp 80g (110g)',
                oldPrice: 95000,
                price: 80000,
                discount: 16,
                imgId: driveImages[4]
            },
            {
                id: 'sp13',
                group: 'gung-trai-cay',
                category: 'Gừng Nướng Mật Ong',
                name: 'Gừng Nướng Nghệ Mật Ong 80g (110g)',
                oldPrice: 102000,
                price: 84300,
                discount: 17,
                imgId: driveImages[5]
            },
            {
                id: 'sp14',
                group: 'gung-trai-cay',
                category: 'Gừng Nướng Mật Ong',
                name: 'Combo 4 Hộp Gừng Nướng Mật Ong 4 Vị',
                oldPrice: 400000,
                price: 336000,
                discount: 16,
                imgId: driveImages[6]
            },
            {
                id: 'sp15',
                group: 'gung-trai-cay',
                category: 'Trái Cây Sấy',
                name: 'Xoài Sấy Dẻo Tự Nhiên Xuất Khẩu 150g',
                oldPrice: 98000,
                price: 79000,
                discount: 19,
                imgId: driveImages[0]
            },

            // --- NHÓM 3: HỘP QUÀ TẶNG CAO CẤP (NHỮNG HỘP QUÀ BIẾT KỂ CHUYỆN) ---
            {
                id: 'sp16',
                group: 'hop-qua',
                category: 'Hộp Quà Tặng',
                name: 'Bộ Hộp Quà Tặng Bạch Mã Vờn Mây Cao Cấp',
                oldPrice: 1560000,
                price: 1326000,
                discount: 15,
                imgId: driveImages[1]
            },
            {
                id: 'sp17',
                group: 'hop-qua',
                category: 'Hộp Quà Tặng',
                name: 'Bộ Hộp Quà Tặng Du Xuân Ba Miền',
                oldPrice: 1750000,
                price: 1493000,
                discount: 15,
                imgId: driveImages[2]
            },
            {
                id: 'sp18',
                group: 'hop-qua',
                category: 'Hộp Quà Tặng',
                name: 'Bộ Hộp Quà Tặng Tết Ngũ Hành',
                oldPrice: 1450000,
                price: 1220000,
                discount: 16,
                imgId: driveImages[3]
            },
            {
                id: 'sp19',
                group: 'hop-qua',
                category: 'Hộp Quà Tặng',
                name: 'Bộ Hộp Quà Tặng Thành Đại Nội Huế',
                oldPrice: 550000,
                price: 466000,
                discount: 15,
                imgId: driveImages[4]
            },
            {
                id: 'sp20',
                group: 'hop-qua',
                category: 'Hộp Quà Tặng',
                name: 'Bộ Hộp Quà Tặng Ông Đồ Ngày Xuân - 5 Món',
                oldPrice: 640000,
                price: 541000,
                discount: 15,
                imgId: driveImages[5]
            },

            // --- NHÓM 4: TRÀ & CÀ PHÊ ĐẮK LẮK - GIA VỊ MUỐI ---
            {
                id: 'sp21',
                group: 'tra-ca-phe',
                category: 'Trà & Cà Phê',
                name: 'Cà Phê Hạt Rang Mộc Đắk Lắk Thùy Dung 500g',
                oldPrice: 210000,
                price: 175000,
                discount: 17,
                imgId: driveImages[6]
            },
            {
                id: 'sp22',
                group: 'tra-ca-phe',
                category: 'Trà & Cà Phê',
                name: 'Cà Phê Bột Nguyên Chất Arabica & Robusta 250g',
                oldPrice: 125000,
                price: 99000,
                discount: 21,
                imgId: driveImages[0]
            },
            {
                id: 'sp23',
                group: 'tra-ca-phe',
                category: 'Trà & Cà Phê',
                name: 'Gừng Nướng Mật Ong - Túi Lớn 100 Gói Pha Trà',
                oldPrice: 690000,
                price: 588000,
                discount: 15,
                imgId: driveImages[1]
            },
            {
                id: 'sp24',
                group: 'tra-ca-phe',
                category: 'Trà & Cà Phê',
                name: 'Hạt Tiêu Đen & Gia Vị Muối Tiêu Hồng Đắk Lắk 120g',
                oldPrice: 85000,
                price: 68000,
                discount: 20,
                imgId: driveImages[2]
            },
            {
                id: 'sp25',
                group: 'tra-ca-phe',
                category: 'Trà & Cà Phê',
                name: 'Tắc Sấy Dẻo & Vỏ Bưởi Sấy Mật Ong 150g',
                oldPrice: 88000,
                price: 72000,
                discount: 18,
                imgId: driveImages[3]
            }
        ];

        function formatVND(amount) {
            return amount.toLocaleString('vi-VN') + '₫';
        }

        // Tạo HTML cho 1 thẻ sản phẩm chuẩn Flatsome
        // - Có % giảm giá góc trên bên trái (top-2 left-2)
        // - Không có các nhãn dán phụ khác
        // - Tên sản phẩm hiển thị đầy đủ (break-words), không bị cắt chữ hay tràn khung
        function createFlatsomeProductCard(product) {
            return `
                <div class="bg-white rounded-xl border border-gray-200 hover:border-brand-600 shadow-2xs hover:shadow-md transition flex flex-col justify-between overflow-hidden group">
                    <div>
                        <div class="relative w-full aspect-square bg-gray-50 overflow-hidden">
                            <!-- Badge % Giảm Giá chuẩn Flatsome ở góc trên bên trái -->
                            <div class="absolute top-2 left-2 z-10 w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-red-600 text-white font-extrabold text-[11px] sm:text-xs flex items-center justify-center shadow">
                                -${product.discount}%
                            </div>
                            <img src="https://lh3.googleusercontent.com/d/${product.imgId}"
                                 onerror="handleDriveImageError(this, '${product.imgId}', '${encodeURIComponent(product.name)}')"
                                 alt="${product.name}"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <p class="text-[10px] sm:text-[11px] text-gray-400 uppercase font-semibold mb-0.5">${product.category}</p>
                            <!-- Tên sản phẩm đầy đủ, tự động xuống hàng mượt mà, không bị tràn hoặc mất chữ -->
                            <h3 class="font-semibold text-gray-800 text-xs sm:text-sm leading-snug break-words min-h-[2.6rem]">
                                ${product.name}
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 sm:px-3 pb-2.5 sm:pb-3 pt-1 border-t border-gray-100">
                        <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                            <del class="text-[11px] text-gray-400">${formatVND(product.oldPrice)}</del>
                            <ins class="no-underline font-extrabold text-red-600 text-xs sm:text-sm">${formatVND(product.price)}</ins>
                        </div>
                        <button onclick="addToCart('${product.id}')"
                                class="w-full py-1.5 px-2 rounded-lg bg-brand-600 hover:bg-brand-700 text-white font-bold text-[11px] sm:text-xs transition flex items-center justify-center gap-1 cursor-pointer">
                            <i class="fa-solid fa-cart-plus text-[11px]"></i>
                            <span>Thêm vào giỏ</span>
                        </button>
                    </div>
                </div>
            `;
        }

        function renderAllProductSections(filterCat = 'all', searchKeyword = '') {
            const kw = searchKeyword.trim().toLowerCase();

            const hatSayList = productsData.filter(p =>
                p.group === 'hat-say' &&
                (filterCat === 'all' || p.category === filterCat) &&
                (kw === '' || p.name.toLowerCase().includes(kw) || p.category.toLowerCase().includes(kw))
            );
            const gungTraiCayList = productsData.filter(p =>
                p.group === 'gung-trai-cay' &&
                (kw === '' || p.name.toLowerCase().includes(kw) || p.category.toLowerCase().includes(kw))
            );
            const hopQuaList = productsData.filter(p =>
                p.group === 'hop-qua' &&
                (kw === '' || p.name.toLowerCase().includes(kw) || p.category.toLowerCase().includes(kw))
            );
            const traCaPheList = productsData.filter(p =>
                p.group === 'tra-ca-phe' &&
                (kw === '' || p.name.toLowerCase().includes(kw) || p.category.toLowerCase().includes(kw))
            );

            document.getElementById('grid-hat-say').innerHTML = hatSayList.length
                ? hatSayList.map(createFlatsomeProductCard).join('')
                : '<p class="col-span-full text-center text-xs text-gray-500 py-4">Không tìm thấy sản phẩm phù hợp.</p>';

            document.getElementById('grid-gung-trai-cay').innerHTML = gungTraiCayList.map(createFlatsomeProductCard).join('');
            document.getElementById('grid-hop-qua').innerHTML = hopQuaList.map(createFlatsomeProductCard).join('');
            document.getElementById('grid-tra-ca-phe').innerHTML = traCaPheList.map(createFlatsomeProductCard).join('');
        }

        function filterCategory(cat) {
            renderAllProductSections(cat, '');
            document.querySelectorAll('.cat-filter-btn').forEach(btn => {
                if (btn.textContent.includes(cat) || (cat === 'all' && btn.textContent.includes('Tất cả'))) {
                    btn.className = 'cat-filter-btn active px-3 py-1 rounded-full text-xs font-semibold bg-brand-600 text-white transition';
                } else {
                    btn.className = 'cat-filter-btn px-3 py-1 rounded-full text-xs font-semibold bg-white text-gray-700 border border-gray-200 hover:border-brand-600 transition';
                }
            });
        }

        function filterProductsBySearch(keyword) {
            renderAllProductSections('all', keyword);
        }

        // ==========================================
        // SLIDER BANNER TỰ TRƯỢT (2 SLIDE KÍCH THƯỚC BẰNG NHAU)
        // ==========================================
        let currentSlideIndex = 0;
        let slideInterval = null;

        function showSlide(index) {
            const slides = document.querySelectorAll('.hero-slide');
            const dots = document.querySelectorAll('.slide-dot');
            if (!slides.length) return;

            currentSlideIndex = (index + slides.length) % slides.length;
            slides.forEach((slide, i) => {
                if (i === currentSlideIndex) {
                    slide.classList.remove('hidden');
                } else {
                    slide.classList.add('hidden');
                }
            });
            dots.forEach((dot, i) => {
                dot.className = i === currentSlideIndex
                    ? 'slide-dot w-2.5 h-2.5 rounded-full bg-amber-400 transition'
                    : 'slide-dot w-2.5 h-2.5 rounded-full bg-white/50 transition';
            });
        }

        function changeSlide(step) {
            showSlide(currentSlideIndex + step);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlideIndex + 1);
            }, 5000);
        }

        // ==========================================
        // GIỎ HÀNG & FORM BÁO GIÁ
        // ==========================================
        let cart = [];

        function addToCart(productId) {
            const product = productsData.find(p => p.id === productId);
            if (!product) return;
            const existing = cart.find(item => item.id === productId);
            if (existing) {
                existing.qty += 1;
            } else {
                cart.push({ ...product, qty: 1 });
            }
            updateCartUI();
            showMessage('Đã thêm vào giỏ hàng', `Sản phẩm "${product.name}" đã được thêm vào giỏ hàng của bạn.`);
        }

        function changeCartQty(productId, delta) {
            const idx = cart.findIndex(item => item.id === productId);
            if (idx === -1) return;
            cart[idx].qty += delta;
            if (cart[idx].qty <= 0) cart.splice(idx, 1);
            updateCartUI();
        }

        function updateCartUI() {
            const count = cart.reduce((sum, item) => sum + item.qty, 0);
            const total = cart.reduce((sum, item) => sum + item.price * item.qty, 0);
            document.getElementById('cartCountBadge').textContent = count;
            document.getElementById('cartTotalPrice').textContent = formatVND(total);

            const container = document.getElementById('cartItemsContainer');
            if (!cart.length) {
                container.innerHTML = '<p class="text-center text-gray-500 py-6">Giỏ hàng của bạn đang trống.</p>';
                return;
            }
            container.innerHTML = cart.map(item => `
                <div class="flex items-center justify-between gap-2 p-2 rounded-lg border border-gray-100 bg-gray-50">
                    <div class="flex-1 min-w-0">
                        <p class="font-semibold text-gray-800 text-xs break-words">${item.name}</p>
                        <p class="text-red-600 font-bold text-xs">${formatVND(item.price)} x ${item.qty}</p>
                    </div>
                    <div class="flex items-center gap-1 shrink-0">
                        <button onclick="changeCartQty('${item.id}', -1)" class="w-6 h-6 rounded bg-white border border-gray-300 text-xs font-bold">-</button>
                        <span class="px-1.5 text-xs font-bold">${item.qty}</span>
                        <button onclick="changeCartQty('${item.id}', 1)" class="w-6 h-6 rounded bg-white border border-gray-300 text-xs font-bold">+</button>
                    </div>
                </div>
            `).join('');
        }

        function toggleCartModal() {
            document.getElementById('cartModal').classList.toggle('hidden');
        }

        function prefillQuoteFromCart() {
            if (!cart.length) return;
            const summary = cart.map(i => `${i.name} (SL: ${i.qty})`).join('; ');
            document.getElementById('qNote').value = 'Đặt hàng / Báo giá các sản phẩm: ' + summary;
        }

        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value;
            const phone = document.getElementById('qPhone').value;
            const type = document.getElementById('qType').value;
            showMessage(
                'Gửi Yêu Cầu Báo Giá Thành Công!',
                `Cảm ơn Quý khách ${name} (${phone}). Yêu cầu "${type}" đã được gửi tới bộ phận kinh doanh CÔNG TY TNHH THÙY DUNG FOODS. Chúng tôi sẽ liên hệ lại ngay qua SĐT 0984.113.366!`
            );
            document.getElementById('quoteForm').reset();
        }

        // ==========================================
        // CHUYỂN ĐỔI BẢN ĐỒ GOOGLE MAP (ĐẮK LẮK & ĐÀ NẴNG)
        // ==========================================
        function switchMapLocation(loc) {
            const iframe = document.getElementById('googleMapIframe');
            const badge = document.getElementById('mapActiveBadge');
            const cardDakLak = document.getElementById('locCardDakLak');
            const cardDaNang = document.getElementById('locCardDaNang');
            const externalLink = document.getElementById('externalMapLink');

            if (loc === 'daklak') {
                iframe.src = 'https://maps.google.com/maps?q=169%20Th%E1%BA%BF%20L%E1%BB%AF,%20T%C3%A2n%20L%E1%BA%ADp,%20%C4%90%E1%BA%AFk%20L%E1%BA%AFk&t=&z=15&ie=UTF8&iwloc=&output=embed';
                badge.innerHTML = '<i class="fa-solid fa-location-dot text-red-600 mr-1"></i>Đang hiển thị: Số 169 Thế Lữ, TDP 5, P. Tân lập, Tỉnh Đắk Lắk';
                externalLink.href = 'https://www.google.com/maps/search/?api=1&query=169+Th%E1%BA%BF+L%E1%BB%AF,+T%C3%A2n+L%E1%BA%ADp,+%C4%90%E1%BA%AFk+L%E1%BA%AFk';
                cardDakLak.className = 'p-3.5 rounded-xl border-2 border-brand-600 bg-brand-50/50 cursor-pointer transition';
                cardDaNang.className = 'p-3.5 rounded-xl border border-gray-200 hover:border-brand-600 bg-white cursor-pointer transition';
            } else {
                iframe.src = 'https://maps.google.com/maps?q=668%20Tr%C6%B0%E1%BB%9Dng%20S%C6%A1n,%20H%C3%B2a%20Nh%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed';
                badge.innerHTML = '<i class="fa-solid fa-location-dot text-amber-600 mr-1"></i>Đang hiển thị Chi nhánh: Số 668 Trường Sơn, P. Hòa Nhơn, TP. Đà Nẵng';
                externalLink.href = 'https://www.google.com/maps/search/?api=1&query=668+Tr%C6%B0%E1%BB%9Dng+S%C6%A1n,+H%C3%B2a+Nh%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng';
                cardDaNang.className = 'p-3.5 rounded-xl border-2 border-brand-600 bg-brand-50/50 cursor-pointer transition';
                cardDakLak.className = 'p-3.5 rounded-xl border border-gray-200 hover:border-brand-600 bg-white cursor-pointer transition';
            }
        }

        // ==========================================
        // XEM CHI TIẾT BÀI VIẾT TRANG CHỦ
        // ==========================================
        const articlesContent = [
            {
                title: 'Hạt Điều Và 10 Công Dụng Tuyệt Vời Cho Sức Khỏe',
                body: 'Hạt điều Thùy Dung Foods được sáng tạo với các nguyên liệu tự nhiên như dừa, tiêu hồng, gấc, nghệ mật ong sấy phủ lên từng hạt mà không chiên qua dầu. Giàu magie, đồng, protein thực vật và chất béo lành mạnh giúp bảo vệ tim mạch và tăng cường năng lượng.'
            },
            {
                title: 'Gừng Nướng Mật Ong: Khám Phá 7 Lợi Ích Tuyệt Vời',
                body: 'Gừng bánh tẻ thu hoạch sau 240 ngày được cắt lát mỏng, ủ cùng mật ong rừng rồi đem nướng ở nhiệt độ tiêu chuẩn. Phương pháp nướng làm dậy mùi thơm tinh dầu gừng, giảm độ cay gắt, giúp giữ ấm cổ họng, tốt cho tiêu hóa và nâng cao sức đề kháng.'
            },
            {
                title: 'Quà Tặng In Logo - Giải Pháp Quảng Bá Doanh Nghiệp',
                body: 'Thùy Dung Foods cung cấp các bộ hộp quà tặng nông sản truyền thống kết hợp hiện đại, hỗ trợ thiết kế và in ấn logo doanh nghiệp theo yêu cầu cho các dịp Lễ, Tết, Hội nghị khách hàng và sự kiện đối tác.'
            },
            {
                title: 'Hạt Sen Tươi Sấy Giòn & Công Dụng Vàng Cho Sức Khỏe',
                body: 'Hạt sen tươi được sấy giòn ngay sau khi thu hoạch, giữ nguyên màu vàng tươi, vị ngọt nhẹ bùi thơm tự nhiên, giúp an thần, cải thiện giấc ngủ và bồi bổ cơ thể cho cả người lớn tuổi lẫn trẻ nhỏ.'
            }
        ];

        function openArticleModal(idx) {
            const art = articlesContent[idx];
            if (!art) return;
            showMessage(art.title, art.body);
        }

        function showMessage(title, body) {
            document.getElementById('messageModalTitle').textContent = title;
            document.getElementById('messageModalBody').textContent = body;
            document.getElementById('messageModal').classList.remove('hidden');
        }

        function closeMessageModal() {
            document.getElementById('messageModal').classList.add('hidden');
        }

        function toggleMobileMenu() {
            document.getElementById('mobileMenuDrawer').classList.toggle('hidden');
        }

        window.onload = function () {
            renderAllProductSections('all', '');
            resetSlideTimer();
        };
    </script>
</body>
</html>
