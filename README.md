<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG HP HOUSE | Thiết Kế & Thi Công Xây Dựng Đà Nẵng</title>
    <meta name="description" content="Công ty Cổ phần Đầu tư và Xây dựng HP HOUSE - Chuyên Thiết kế Kiến trúc, Thi công phần thô, Thi công hoàn thiện, Nội thất Nhà phố, Biệt thự, Khách sạn, Căn hộ tại Đà Nẵng. Hotline: 0903.578.069.">

    <!-- =========================================================================
         THẺ META THUMBNAIL CHIA SẺ LINK (HIỂN THỊ LOGO HP HOUSE KHI GỬI LINK)
         Khi đưa lên hosting hphouse.com, bạn trỏ đường dẫn og:image tới file logo PNG/JPG
         ========================================================================= -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="HP HOUSE - Đầu Tư & Xây Dựng">
    <meta property="og:url" content="https://hphouse.com">
    <meta property="og:title" content="CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG HP HOUSE - hphouse.com">
    <meta property="og:description" content="Thiết kế Kiến trúc - Thi công Xây dựng trọn gói - Hoàn thiện Nội thất uy tín tại Đà Nẵng. Địa chỉ: 383 Phạm Hùng, P. Hòa Xuân, TP. Đà Nẵng. Hotline: 0903.578.069.">
    <meta property="og:image" content="https://hphouse.com/wp-content/uploads/logo-hp-house-thumbnail.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG HP HOUSE">
    <meta name="twitter:description" content="Chuyên Thiết kế & Thi công Xây dựng trọn gói tại Đà Nẵng - Hotline: 0903.578.069">
    <meta name="twitter:image" content="https://hphouse.com/wp-content/uploads/logo-hp-house-thumbnail.png">

    <!-- Favicon SVG Logo HP HOUSE -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='10' fill='%230F2942'/%3E%3Cpath d='M10 30L32 12L54 30' fill='none' stroke='%23C89B3C' stroke-width='4.5' stroke-linecap='round' stroke-linejoin='round'/%3E%3Ctext x='32' y='47' text-anchor='middle' font-family='Arial,sans-serif' font-weight='800' font-size='21' fill='%23FFFFFF'%3EHP%3C/text%3E%3C/svg%3E">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        hp: {
                            navy: '#0F2942',       // Màu chính theo Logo (Xanh Navy Kiến Trúc)
                            navyDark: '#091B2D',   // Xanh Navy đậm cho Footer & Hover
                            navyLight: '#1A3D5E',  // Xanh Navy sáng hơn cho điểm nhấn
                            gold: '#C89B3C',       // Màu nhấn theo Logo (Vàng Đồng sang trọng)
                            goldDark: '#A87E26',   // Vàng Đồng đậm khi hover
                            goldLight: '#F8F2E4',  // Nền kem vàng nhạt tinh tế
                            bg: '#F6F8FA',         // Nền xám sáng chuẩn Flatsome
                            text: '#1E293B',       // Chữ chính dễ đọc
                            muted: '#64748B'       // Chữ phụ
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* =====================================================================
           CÀI ĐẶT CHỐNG TRÀN VIỀN & KHUNG 95% CHIỀU NGANG TRÊN MÁY TÍNH
           ===================================================================== */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
            -webkit-font-smoothing: antialiased;
        }

        /* Khung nội dung Flatsome Container:
           - Trên di động: 94% chiều ngang, căn giữa chuẩn, không lệch phải
           - Trên máy tính (>= 1024px): ĐÚNG 95% chiều ngang màn hình máy tính */
        .hp-container {
            width: 94%;
            max-width: 94%;
            margin-left: auto;
            margin-right: auto;
        }

        @media (min-width: 1024px) {
            .hp-container {
                width: 95%;
                max-width: 95%;
            }
        }

        /* =====================================================================
           MENU ĐIỀU HƯỚNG & DANH MỤC 1 HÀNG - KHÔNG XUỐNG DÒNG TÊN DANH MỤC
           ===================================================================== */
        .nav-link-nowrap,
        .cat-tab-btn {
            white-space: nowrap;
        }

        /* Dropdown menu chuẩn Flatsome */
        .hp-dropdown {
            position: relative;
        }
        .hp-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            pointer-events: none;
        }
        .hp-dropdown:hover .hp-dropdown-menu,
        .hp-dropdown:focus-within .hp-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
            pointer-events: auto;
        }

        /* =====================================================================
           2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU - CHỮ NẰM GỌN TRONG VÙNG AN TOÀN
           ===================================================================== */
        .hero-slider-wrapper {
            position: relative;
            width: 100%;
            overflow: hidden;
            background-color: #0F2942;
        }

        .hero-slides-track {
            display: flex;
            width: 200%;
            transition: transform 0.7s cubic-bezier(0.25, 0.8, 0.25, 1);
        }

        .hero-slide-item {
            width: 50%;
            flex-shrink: 0;
            position: relative;
            /* Đảm bảo cả 2 banner có kích thước chiều cao BẰNG NHAU trên mọi thiết bị */
            min-height: 360px;
            display: flex;
            align-items: center;
        }

        @media (min-width: 640px) {
            .hero-slide-item {
                min-height: 410px;
            }
        }

        @media (min-width: 1024px) {
            .hero-slide-item {
                min-height: 490px;
            }
        }

        .hero-slide-bg {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
            z-index: 1;
        }

        .hero-slide-overlay {
            position: absolute;
            inset: 0;
            background: linear-gradient(95deg, rgba(9, 27, 45, 0.90) 0%, rgba(15, 41, 66, 0.78) 58%, rgba(15, 41, 66, 0.52) 100%);
            z-index: 2;
        }

        .hero-slide-content {
            position: relative;
            z-index: 3;
            width: 100%;
            /* Vùng đệm an toàn cách xa mép ảnh banner trên cả mobile và desktop */
            padding: 36px 46px 52px 46px;
        }

        @media (min-width: 640px) {
            .hero-slide-content {
                padding: 48px 72px 60px 72px;
            }
        }

        @media (min-width: 1024px) {
            .hero-slide-content {
                padding: 64px 96px 72px 96px;
            }
        }

        /* =====================================================================
           HIỆU ỨNG CARD FLATSOME & NÚT LIÊN HỆ NỔI
           ===================================================================== */
        .flatsome-card {
            transition: transform 0.25s ease, box-shadow 0.25s ease;
        }
        .flatsome-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 24px -6px rgba(15, 41, 66, 0.14);
        }
        .flatsome-card img {
            transition: transform 0.45s ease;
        }
        .flatsome-card:hover img {
            transform: scale(1.04);
        }

        /* Hiệu ứng nhịp tim cho nút Hotline nổi */
        @keyframes hpPulse {
            0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55); }
            70% { box-shadow: 0 0 0 14px rgba(220, 38, 38, 0); }
            100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
        }
        .hotline-pulse {
            animation: hpPulse 2s infinite;
        }

        /* Thanh cuộn ngang mượt cho danh mục trên màn hình siêu nhỏ */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-white text-hp-text overflow-x-hidden">

    <!-- =========================================================================
         1. TOP BAR ĐƠN GIẢN CHUẨN FLATSOME (KHÔNG HIỂN THỊ THANH CHỈNH SỬA UXBUILDER)
         ========================================================================= -->
    <div class="bg-hp-navy text-white text-xs border-b border-white/10">
        <div class="hp-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-hp-gold"></i>
                    <span>383 Phạm Hùng, P. Hòa Xuân, TP. Đà Nẵng</span>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-globe text-hp-gold"></i>
                    <span>hphouse.com</span>
                </span>
            </div>
            <div class="flex items-center gap-4">
                <a href="tel:0903578069" class="inline-flex items-center gap-1.5 font-semibold text-hp-gold hover:text-white transition">
                    <i class="fa-solid fa-phone"></i>
                    <span>0903.578.069</span>
                </a>
                <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" aria-label="Facebook HP HOUSE" class="text-slate-300 hover:text-hp-gold transition">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a href="https://zalo.me/0903578069" target="_blank" rel="noopener noreferrer" aria-label="Zalo HP HOUSE" class="text-slate-300 hover:text-hp-gold transition font-bold text-[11px]">
                    Zalo
                </a>
            </div>
        </div>
    </div>

    <!-- =========================================================================
         2. HEADER CHÍNH (LOGO GỌN NHỎ, MENU 1 HÀNG CHỮ NHỎ, KHÔNG NÚT GỌI NGAY)
         ========================================================================= -->
    <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="hp-container h-16 lg:h-[70px] flex items-center justify-between gap-3">

            <!-- LOGO CÔNG TY CHUYÊN NGHIỆP - CHỈNH GỌN NHỎ LẠI -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" aria-label="HP HOUSE Trang chủ">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo HP HOUSE">
                    <defs>
                        <linearGradient id="hpGoldGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                            <stop offset="0%" stop-color="#E2BA5A"/>
                            <stop offset="100%" stop-color="#B08124"/>
                        </linearGradient>
                    </defs>
                    <rect x="2" y="2" width="60" height="60" rx="11" fill="#0F2942"/>
                    <rect x="5" y="5" width="54" height="54" rx="8.5" fill="none" stroke="url(#hpGoldGrad)" stroke-width="1.5" stroke-opacity="0.55"/>
                    <!-- Biểu tượng mái nhà kiến trúc -->
                    <path d="M13 28 L32 13 L51 28" fill="none" stroke="url(#hpGoldGrad)" stroke-width="3.6" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M43 17 V21.5" stroke="url(#hpGoldGrad)" stroke-width="3" stroke-linecap="round"/>
                    <!-- Chữ lồng kiến trúc HP -->
                    <path d="M18 33 V50 M18 41.5 H28 M28 33 V50" stroke="#FFFFFF" stroke-width="3.4" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M35 50 V33 H42.5 C46.2 33 48.2 35.1 48.2 38.2 C48.2 41.3 46.2 43.3 42.5 43.3 H35" fill="none" stroke="url(#hpGoldGrad)" stroke-width="3.4" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-base sm:text-[17px] font-extrabold tracking-tight text-hp-navy group-hover:text-hp-gold transition">
                        HP <span class="text-hp-gold">HOUSE</span>
                    </div>
                    <div class="text-[9.5px] sm:text-[10px] font-semibold tracking-wider text-hp-muted uppercase">
                        Đầu Tư &amp; Xây Dựng
                    </div>
                </div>
            </a>

            <!-- MENU MÁY TÍNH: VIẾT LIỀN TRÊN 1 HÀNG, CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG TÊN DANH MỤC -->
            <nav class="hidden lg:flex items-center justify-end flex-1 min-w-0" aria-label="Menu chính">
                <ul class="flex flex-wrap items-center justify-end gap-x-3 xl:gap-x-5 gap-y-1 text-[12.5px] xl:text-[13px] font-semibold text-hp-navy uppercase tracking-tight">
                    <li>
                        <a href="#trang-chu" class="nav-link-nowrap py-2 hover:text-hp-gold transition">Trang chủ</a>
                    </li>
                    <li>
                        <a href="#gioi-thieu" class="nav-link-nowrap py-2 hover:text-hp-gold transition">Giới thiệu</a>
                    </li>

                    <!-- Dropdown Công trình thực tế (theo mẫu tintruongthinh.com) -->
                    <li class="hp-dropdown">
                        <a href="#cong-trinh-thuc-te" class="nav-link-nowrap py-2 inline-flex items-center gap-1 hover:text-hp-gold transition">
                            <span>Công trình thực tế</span>
                            <i class="fa-solid fa-chevron-down text-[9px] text-hp-gold"></i>
                        </a>
                        <div class="hp-dropdown-menu absolute left-0 top-full pt-1 w-60 z-50">
                            <ul class="bg-white rounded-lg shadow-xl border border-slate-100 py-2 text-[12.5px] font-medium normal-case text-slate-700">
                                <li><button type="button" onclick="filterConstructionAndScroll('khach-san-can-ho')" class="w-full text-left px-4 py-2 hover:bg-hp-goldLight hover:text-hp-navy transition">Khách sạn – Căn hộ – Phòng trọ</button></li>
                                <li><button type="button" onclick="filterConstructionAndScroll('biet-thu')" class="w-full text-left px-4 py-2 hover:bg-hp-goldLight hover:text-hp-navy transition">Biệt thự</button></li>
                                <li><button type="button" onclick="filterConstructionAndScroll('nha-pho')" class="w-full text-left px-4 py-2 hover:bg-hp-goldLight hover:text-hp-navy transition">Nhà phố</button></li>
                                <li><button type="button" onclick="filterConstructionAndScroll('van-phong')" class="w-full text-left px-4 py-2 hover:bg-hp-goldLight hover:text-hp-navy transition">Văn phòng</button></li>
                            </ul>
                        </div>
                    </li>

                    <!-- Dropdown Lĩnh vực hoạt động -->
                    <li class="hp-dropdown">
                        <a href="#dich-vu" class="nav-link-nowrap py-2 inline-flex items-center gap-1 hover:text-hp-gold transition">
                            <span>Lĩnh vực hoạt động</span>
                            <i class="fa-solid fa-chevron-down text-[9px] text-hp-gold"></i>
                        </a>
                        <div class="hp-dropdown-menu absolute left-0 top-full pt-1 w-56 z-50">
                            <ul class="bg-white rounded-lg shadow-xl border border-slate-100 py-2 text-[12.5px] font-medium normal-case text-slate-700">
                                <li><a href="#dich-vu" class="block px-4 py-2 hover:bg-hp-goldLight hover:text-hp-navy transition">Thiết kế Kiến trúc – Nội thất</a></li>
                                <li><button type="button" onclick="filterConstructionAndScroll('phan-tho')" class="w-full text-left px-4 py-2 hover:bg-hp-goldLight hover:text-hp-navy transition">Thi công phần thô</button></li>
                                <li><button type="button" onclick="filterConstructionAndScroll('hoan-thien')" class="w-full text-left px-4 py-2 hover:bg-hp-goldLight hover:text-hp-navy transition">Thi công hoàn thiện</button></li>
                                <li><a href="#dich-vu" class="block px-4 py-2 hover:bg-hp-goldLight hover:text-hp-navy transition">Thi công nội thất</a></li>
                            </ul>
                        </div>
                    </li>

                    <li>
                        <a href="#du-an-da-nang" class="nav-link-nowrap py-2 hover:text-hp-gold transition">Dự án Đà Nẵng</a>
                    </li>
                    <li>
                        <a href="#bao-gia" class="nav-link-nowrap py-2 hover:text-hp-gold transition">Báo giá</a>
                    </li>
                    <li>
                        <a href="#doi-tac" class="nav-link-nowrap py-2 hover:text-hp-gold transition">Đối tác</a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="nav-link-nowrap py-2 hover:text-hp-gold transition">Tin tức</a>
                    </li>
                    <li>
                        <a href="#lien-he" class="nav-link-nowrap py-2 hover:text-hp-gold transition">Liên hệ</a>
                    </li>
                </ul>
            </nav>

            <!-- NÚT MỞ MENU ĐIỆN THOẠI (KHÔNG CÓ NÚT GỌI NGAY TRÊN HEADER) -->
            <button id="mobile-menu-btn" type="button" class="lg:hidden p-2.5 rounded-lg text-hp-navy border border-slate-200 hover:bg-hp-bg transition" aria-label="Mở menu điều hướng">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- MENU DROPDOWN TRÊN ĐIỆN THOẠI -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="hp-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-hp-navy">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="py-2.5 hover:text-hp-gold">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-2.5 hover:text-hp-gold">Giới thiệu</a>
                <a href="#dich-vu" onclick="closeMobileMenu()" class="py-2.5 hover:text-hp-gold">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="py-2.5 hover:text-hp-gold">Công trình thực tế</a>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-2.5 hover:text-hp-gold">Dự án tại Đà Nẵng</a>
                <a href="#doi-tac" onclick="closeMobileMenu()" class="py-2.5 hover:text-hp-gold">Đối tác chiến lược</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="py-2.5 hover:text-hp-gold">Yêu cầu báo giá</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-2.5 hover:text-hp-gold">Tin tức &amp; Bài viết</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="py-2.5 hover:text-hp-gold">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <!-- =========================================================================
         3. 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU (CHỮ NẰM TRỌN TRONG BANNER)
         ========================================================================= -->
    <section id="trang-chu" class="hero-slider-wrapper" aria-label="Banner nổi bật HP HOUSE">
        <div id="hero-track" class="hero-slides-track">

            <!-- BANNER 1 -->
            <div class="hero-slide-item">
                <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                     data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                     alt="HP HOUSE - Thi công xây dựng trọn gói tại Đà Nẵng"
                     class="hero-slide-bg hp-drive-img">
                <div class="hero-slide-overlay"></div>
                <div class="hero-slide-content">
                    <div class="max-w-2xl">
                        <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.18em] text-hp-gold mb-2.5">
                            CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG HP HOUSE
                        </p>
                        <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3.5">
                            Thiết Kế &amp; Thi Công Xây Dựng Trọn Gói Chuyên Nghiệp Tại Đà Nẵng
                        </h1>
                        <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-6">
                            Kiến tạo không gian sống bền vững cho Nhà phố, Biệt thự, Căn hộ &amp; Khách sạn với tiêu chuẩn kỹ thuật nghiêm ngặt, tiến độ cam kết và chi phí tối ưu.
                        </p>
                        <div class="flex flex-wrap items-center gap-3">
                            <a href="#bao-gia" class="inline-flex items-center gap-2 bg-hp-gold hover:bg-hp-goldDark text-white text-xs sm:text-sm font-bold px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg shadow-md transition">
                                <span>Nhận Báo Giá Miễn Phí</span>
                                <i class="fa-solid fa-arrow-right text-xs"></i>
                            </a>
                            <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-2 bg-white/10 hover:bg-white/20 text-white border border-white/30 text-xs sm:text-sm font-semibold px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg transition">
                                <span>Xem Công Trình Thực Tế</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- BANNER 2 -->
            <div class="hero-slide-item">
                <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                     data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                     alt="HP HOUSE - Các dự án kiến trúc và xây dựng tại Đà Nẵng"
                     class="hero-slide-bg hp-drive-img">
                <div class="hero-slide-overlay"></div>
                <div class="hero-slide-content">
                    <div class="max-w-2xl">
                        <p class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.18em] text-hp-gold mb-2.5">
                            AN TOÀN • CHẤT LƯỢNG • ĐÚNG TIẾN ĐỘ
                        </p>
                        <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3.5">
                            Nâng Tầm Công Trình Hiện Đại — Bảo Hành Kết Cấu Dài Lâu
                        </h2>
                        <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-6">
                            Đội ngũ kiến trúc sư &amp; kỹ sư giàu kinh nghiệm trực tiếp giám sát từ phần thô đến hoàn thiện nội thất tại Hòa Xuân và toàn TP. Đà Nẵng.
                        </p>
                        <div class="flex flex-wrap items-center gap-3">
                            <a href="#du-an-da-nang" class="inline-flex items-center gap-2 bg-hp-gold hover:bg-hp-goldDark text-white text-xs sm:text-sm font-bold px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg shadow-md transition">
                                <span>Khám Phá Dự Án Đà Nẵng</span>
                                <i class="fa-solid fa-arrow-right text-xs"></i>
                            </a>
                            <a href="tel:0903578069" class="inline-flex items-center gap-2 bg-white/10 hover:bg-white/20 text-white border border-white/30 text-xs sm:text-sm font-semibold px-5 py-2.5 sm:px-6 sm:py-3 rounded-lg transition">
                                <i class="fa-solid fa-phone text-hp-gold"></i>
                                <span>Tư Vấn: 0903.578.069</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>

        </div>

        <!-- Nút chuyển trái / phải gọn gàng sát viền, không che chữ -->
        <button id="prev-slide" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-hp-gold text-white flex items-center justify-center transition">
            <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button id="next-slide" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-hp-gold text-white flex items-center justify-center transition">
            <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chỉ báo 2 slide -->
        <div class="absolute bottom-3.5 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2.5">
            <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Xem banner 1" class="w-7 h-2 rounded-full bg-hp-gold transition-all"></button>
            <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Xem banner 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
    </section>

    <!-- =========================================================================
         4. DỊCH VỤ TIÊU BIỂU (3 CỘT CHUẨN FLATSOME GIỐNG WEB MẪU TINTRUONGTHINH)
         ========================================================================= -->
    <section id="dich-vu" class="py-12 lg:py-16 bg-white">
        <div class="hp-container">
            <div class="text-center max-w-2xl mx-auto mb-9">
                <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-hp-navy uppercase tracking-tight">
                    Dịch Vụ Tiêu Biểu
                </h2>
                <div class="w-16 h-1 bg-hp-gold mx-auto mt-3 rounded-full"></div>
                <p class="text-sm text-hp-muted mt-3">
                    Giải pháp đồng bộ từ khâu lên ý tưởng kiến trúc đến thi công xây dựng phần thô và hoàn thiện nội thất
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Dịch vụ 1 -->
                <div class="flatsome-card bg-hp-bg rounded-xl p-6 sm:p-7 border border-slate-200/80 text-center">
                    <div class="w-14 h-14 mx-auto rounded-xl bg-hp-navy text-hp-gold flex items-center justify-center text-2xl mb-4 shadow-sm">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h3 class="text-base sm:text-lg font-bold text-hp-navy uppercase mb-2.5">Thiết Kế Kiến Trúc</h3>
                    <p class="text-sm text-hp-muted leading-relaxed">
                        Thiết kế kiến trúc nhà phố, biệt thự, căn hộ, khách sạn và văn phòng tối ưu công năng, thông gió tự nhiên và chuẩn thẩm mỹ hiện đại.
                    </p>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="flatsome-card bg-hp-bg rounded-xl p-6 sm:p-7 border border-slate-200/80 text-center">
                    <div class="w-14 h-14 mx-auto rounded-xl bg-hp-navy text-hp-gold flex items-center justify-center text-2xl mb-4 shadow-sm">
                        <i class="fa-solid fa-helmet-safety"></i>
                    </div>
                    <h3 class="text-base sm:text-lg font-bold text-hp-navy uppercase mb-2.5">Thi Công Xây Dựng</h3>
                    <p class="text-sm text-hp-muted leading-relaxed">
                        Thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chìa khóa trao tay, vật tư chính hãng, kỹ sư giám sát trực tiếp tại công trường.
                    </p>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="flatsome-card bg-hp-bg rounded-xl p-6 sm:p-7 border border-slate-200/80 text-center">
                    <div class="w-14 h-14 mx-auto rounded-xl bg-hp-navy text-hp-gold flex items-center justify-center text-2xl mb-4 shadow-sm">
                        <i class="fa-solid fa-couch"></i>
                    </div>
                    <h3 class="text-base sm:text-lg font-bold text-hp-navy uppercase mb-2.5">Thi Công Nội Thất</h3>
                    <p class="text-sm text-hp-muted leading-relaxed">
                        Thiết kế và sản xuất lắp đặt nội thất phòng khách, bếp, phòng ngủ, văn phòng chuẩn bản vẽ 3D, sắc nét từng chi tiết và bền đẹp theo thời gian.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         5. GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA HP HOUSE (BỐ CỤC CHUẨN WEB MẪU)
         ========================================================================= -->
    <section id="gioi-thieu" class="py-12 lg:py-16 bg-hp-bg border-y border-slate-200/70">
        <div class="hp-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 lg:gap-10 items-center mb-12">
                <!-- Cột hình ảnh thực tế -->
                <div class="lg:col-span-5">
                    <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
                        <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000"
                             data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                             alt="Đội ngũ thi công Công ty Cổ phần Đầu tư và Xây dựng HP HOUSE"
                             class="w-full h-64 sm:h-80 object-cover hp-drive-img">
                    </div>
                </div>

                <!-- Cột nội dung giới thiệu -->
                <div class="lg:col-span-7">
                    <p class="text-xs font-bold uppercase tracking-widest text-hp-gold mb-2">Về Chúng Tôi</p>
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-hp-navy leading-snug mb-4">
                        CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG HP HOUSE
                    </h2>
                    <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed mb-3.5">
                        <strong>HP HOUSE</strong> chuyên <strong>Thiết kế – Xây dựng – Nội thất</strong> các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại khu vực <strong>Đà Nẵng – Miền Trung</strong>.
                    </p>
                    <p class="text-sm sm:text-[15px] text-slate-600 leading-relaxed mb-5">
                        Đặt chữ <strong>“TÂM”</strong> và uy tín nghề nghiệp lên hàng đầu, mỗi công trình do HP HOUSE thực hiện luôn tuân thủ nghiêm ngặt tiêu chí <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – MINH BẠCH CHI PHÍ”</strong>. Với đội ngũ kiến trúc sư, kỹ sư thực chiến giàu kinh nghiệm, chúng tôi đồng hành trọn vẹn cùng khách hàng từ bản vẽ đầu tiên đến ngày bàn giao tổ ấm.
                    </p>
                    <div class="grid grid-cols-3 gap-3 sm:gap-4 pt-3 border-t border-slate-200">
                        <div class="bg-white rounded-lg p-3 sm:p-4 text-center border border-slate-200/80">
                            <div class="text-lg sm:text-2xl font-extrabold text-hp-navy">100+</div>
                            <div class="text-[11px] sm:text-xs text-hp-muted mt-0.5">Công trình bàn giao</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 sm:p-4 text-center border border-slate-200/80">
                            <div class="text-lg sm:text-2xl font-extrabold text-hp-gold">5 Năm</div>
                            <div class="text-[11px] sm:text-xs text-hp-muted mt-0.5">Bảo hành kết cấu</div>
                        </div>
                        <div class="bg-white rounded-lg p-3 sm:p-4 text-center border border-slate-200/80">
                            <div class="text-lg sm:text-2xl font-extrabold text-hp-navy">24/7</div>
                            <div class="text-[11px] sm:text-xs text-hp-muted mt-0.5">Tư vấn &amp; Giám sát</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Thế mạnh của HP HOUSE (6 ô Icon Box chuẩn Flatsome) -->
            <div class="text-center max-w-2xl mx-auto mb-8">
                <h3 class="text-lg sm:text-xl lg:text-2xl font-extrabold text-hp-navy uppercase">Thế Mạnh Của HP HOUSE</h3>
                <div class="w-14 h-1 bg-hp-gold mx-auto mt-2.5 rounded-full"></div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-5">
                <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-4">
                    <div class="w-11 h-11 shrink-0 rounded-lg bg-hp-goldLight text-hp-goldDark flex items-center justify-center text-lg">
                        <i class="fa-solid fa-users-gear"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-hp-navy text-sm sm:text-[15px] mb-1">Kiến trúc sư &amp; Kỹ sư chuyên nghiệp</h4>
                        <p class="text-xs sm:text-sm text-hp-muted leading-relaxed">Đội ngũ kiến trúc sư sáng tạo cùng kỹ sư công trường và thợ lành nghề trực tiếp thi công.</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-4">
                    <div class="w-11 h-11 shrink-0 rounded-lg bg-hp-goldLight text-hp-goldDark flex items-center justify-center text-lg">
                        <i class="fa-solid fa-layer-group"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-hp-navy text-sm sm:text-[15px] mb-1">Cập nhật xu hướng hiện đại</h4>
                        <p class="text-xs sm:text-sm text-hp-muted leading-relaxed">Ứng dụng vật liệu mới, giải pháp chống nóng, chống thấm tối ưu phù hợp khí hậu Đà Nẵng.</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-4">
                    <div class="w-11 h-11 shrink-0 rounded-lg bg-hp-goldLight text-hp-goldDark flex items-center justify-center text-lg">
                        <i class="fa-solid fa-clipboard-check"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-hp-navy text-sm sm:text-[15px] mb-1">Giám sát tiến độ chuẩn xác</h4>
                        <p class="text-xs sm:text-sm text-hp-muted leading-relaxed">Báo cáo tiến độ và hình ảnh thi công hằng ngày giúp chủ đầu tư dễ dàng theo dõi từ xa.</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-4">
                    <div class="w-11 h-11 shrink-0 rounded-lg bg-hp-goldLight text-hp-goldDark flex items-center justify-center text-lg">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-hp-navy text-sm sm:text-[15px] mb-1">Bảo hành công trình lâu dài</h4>
                        <p class="text-xs sm:text-sm text-hp-muted leading-relaxed">Cam kết bảo hành kết cấu dài hạn, hỗ trợ bảo trì nhanh chóng để khách hàng luôn an tâm.</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-4">
                    <div class="w-11 h-11 shrink-0 rounded-lg bg-hp-goldLight text-hp-goldDark flex items-center justify-center text-lg">
                        <i class="fa-solid fa-file-invoice-dollar"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-hp-navy text-sm sm:text-[15px] mb-1">Chi phí minh bạch, hợp lý</h4>
                        <p class="text-xs sm:text-sm text-hp-muted leading-relaxed">Dự toán chi tiết từng hạng mục vật tư, cam kết không phát sinh chi phí ngoài hợp đồng.</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-4">
                    <div class="w-11 h-11 shrink-0 rounded-lg bg-hp-goldLight text-hp-goldDark flex items-center justify-center text-lg">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-hp-navy text-sm sm:text-[15px] mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
                        <p class="text-xs sm:text-sm text-hp-muted leading-relaxed">Tư vấn pháp lý, xin giấy phép xây dựng, phong thủy và dự toán sơ bộ hoàn toàn miễn phí.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         6. CÔNG TRÌNH THI CÔNG THỰC TẾ (9 ẢNH GOOGLE DRIVE + DANH MỤC WEB MẪU)
            - Chữ danh mục nhỏ gọn, viết liền 1 hàng, không xuống dòng tên danh mục
            - Sản phẩm chia 2 cột trên điện thoại, tên không tràn/thiếu chữ
            - KHÔNG ĐỂ NHÃN DÁN TRÊN ẢNH TRANG CHỦ
         ========================================================================= -->
    <section id="cong-trinh-thuc-te" class="py-12 lg:py-16 bg-white">
        <div class="hp-container">
            <div class="text-center max-w-2xl mx-auto mb-6">
                <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-hp-navy uppercase tracking-tight">
                    Công Trình Thi Công Thực Tế
                </h2>
                <div class="w-16 h-1 bg-hp-gold mx-auto mt-3 rounded-full"></div>
                <p class="text-sm text-hp-muted mt-3">
                    Hình ảnh thi công thực tế tại công trường của HP HOUSE theo từng hạng mục công trình
                </p>
            </div>

            <!-- THANH DANH MỤC TỐI ƯU: CHỮ NHỎ GỌN, VIẾT LIỀN TRÊN 1 HÀNG (KHÔNG NGẮT DÒNG TÊN DANH MỤC) -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-8">
                <button type="button" onclick="filterConstruction('all')" data-cat="all" class="cat-tab-btn construction-tab active px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-hp-navy text-white transition">Tất cả</button>
                <button type="button" onclick="filterConstruction('khach-san-can-ho')" data-cat="khach-san-can-ho" class="cat-tab-btn construction-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-hp-bg text-hp-navy hover:bg-hp-goldLight transition">Khách sạn - Căn hộ - Phòng trọ</button>
                <button type="button" onclick="filterConstruction('biet-thu')" data-cat="biet-thu" class="cat-tab-btn construction-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-hp-bg text-hp-navy hover:bg-hp-goldLight transition">Biệt thự</button>
                <button type="button" onclick="filterConstruction('nha-pho')" data-cat="nha-pho" class="cat-tab-btn construction-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-hp-bg text-hp-navy hover:bg-hp-goldLight transition">Nhà phố</button>
                <button type="button" onclick="filterConstruction('van-phong')" data-cat="van-phong" class="cat-tab-btn construction-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-hp-bg text-hp-navy hover:bg-hp-goldLight transition">Văn phòng</button>
                <button type="button" onclick="filterConstruction('phan-tho')" data-cat="phan-tho" class="cat-tab-btn construction-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-hp-bg text-hp-navy hover:bg-hp-goldLight transition">Thi công phần thô</button>
                <button type="button" onclick="filterConstruction('hoan-thien')" data-cat="hoan-thien" class="cat-tab-btn construction-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-hp-bg text-hp-navy hover:bg-hp-goldLight transition">Thi công hoàn thiện</button>
            </div>

            <!-- LƯỚI SẢN PHẨM / CÔNG TRÌNH: 2 CỘT TRÊN ĐIỆN THOẠI, 3-4 CỘT TRÊN MÁY TÍNH -->
            <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3.5 sm:gap-5">
                <!-- Dữ liệu 9 ảnh thực tế Google Drive được render bằng JS bên dưới -->
            </div>
        </div>
    </section>

    <!-- =========================================================================
         7. DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH THỰC TẾ TỪ GOOGLE DRIVE)
            - Chia 2 cột trên điện thoại, 5 cột trên máy tính, không nhãn dán
         ========================================================================= -->
    <section id="du-an-da-nang" class="py-12 lg:py-16 bg-hp-bg border-y border-slate-200/70">
        <div class="hp-container">
            <div class="text-center max-w-2xl mx-auto mb-6">
                <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-hp-navy uppercase tracking-tight">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <div class="w-16 h-1 bg-hp-gold mx-auto mt-3 rounded-full"></div>
                <p class="text-sm text-hp-muted mt-3">
                    Các công trình thực tế do HP HOUSE thiết kế và thi công tại Hòa Xuân, Hải Châu, Sơn Trà, Ngũ Hành Sơn và Liên Chiểu
                </p>
            </div>

            <!-- Danh mục khu vực Đà Nẵng gọn đẹp, không xuống dòng tên danh mục -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-8">
                <button type="button" onclick="filterDanang('all')" data-area="all" class="cat-tab-btn danang-tab active px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-hp-navy text-white transition">Tất cả Đà Nẵng</button>
                <button type="button" onclick="filterDanang('hoa-xuan')" data-area="hoa-xuan" class="cat-tab-btn danang-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-hp-navy border border-slate-200 hover:bg-hp-goldLight transition">Hòa Xuân</button>
                <button type="button" onclick="filterDanang('hai-chau')" data-area="hai-chau" class="cat-tab-btn danang-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-hp-navy border border-slate-200 hover:bg-hp-goldLight transition">Hải Châu</button>
                <button type="button" onclick="filterDanang('son-tra')" data-area="son-tra" class="cat-tab-btn danang-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-hp-navy border border-slate-200 hover:bg-hp-goldLight transition">Sơn Trà</button>
                <button type="button" onclick="filterDanang('ngu-hanh-son')" data-area="ngu-hanh-son" class="cat-tab-btn danang-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-hp-navy border border-slate-200 hover:bg-hp-goldLight transition">Ngũ Hành Sơn</button>
                <button type="button" onclick="filterDanang('lien-chieu')" data-area="lien-chieu" class="cat-tab-btn danang-tab px-3.5 py-2 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-hp-navy border border-slate-200 hover:bg-hp-goldLight transition">Liên Chiểu</button>
            </div>

            <!-- Lưới 10 dự án Đà Nẵng: 2 cột trên điện thoại -->
            <div id="danang-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3.5 sm:gap-5">
                <!-- Dữ liệu 10 ảnh dự án Đà Nẵng Google Drive được render bằng JS -->
            </div>
        </div>
    </section>

    <!-- =========================================================================
         8. DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC
         ========================================================================= -->
    <section id="doi-tac" class="py-12 lg:py-14 bg-white">
        <div class="hp-container">
            <div class="text-center max-w-2xl mx-auto mb-8">
                <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-hp-navy uppercase tracking-tight">
                    Đối Tác &amp; Nhà Cung Cấp Chiến Lược
                </h2>
                <div class="w-16 h-1 bg-hp-gold mx-auto mt-3 rounded-full"></div>
                <p class="text-sm text-hp-muted mt-3">
                    HP HOUSE cam kết sử dụng 100% vật tư, thiết bị chính hãng từ các thương hiệu hàng đầu
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3.5 sm:gap-4">
                <div class="bg-hp-bg border border-slate-200/80 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-hp-gold transition">
                    <span class="font-extrabold text-sm sm:text-base text-hp-navy tracking-tight">HÒA PHÁT</span>
                    <span class="text-[10px] text-hp-muted mt-0.5">Thép xây dựng</span>
                </div>
                <div class="bg-hp-bg border border-slate-200/80 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-hp-gold transition">
                    <span class="font-extrabold text-sm sm:text-base text-hp-navy tracking-tight">SÔNG GIANH</span>
                    <span class="text-[10px] text-hp-muted mt-0.5">Xi măng PCB40</span>
                </div>
                <div class="bg-hp-bg border border-slate-200/80 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-hp-gold transition">
                    <span class="font-extrabold text-sm sm:text-base text-hp-navy tracking-tight">DULUX</span>
                    <span class="text-[10px] text-hp-muted mt-0.5">Sơn cao cấp</span>
                </div>
                <div class="bg-hp-bg border border-slate-200/80 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-hp-gold transition">
                    <span class="font-extrabold text-sm sm:text-base text-hp-navy tracking-tight">XINGFA</span>
                    <span class="text-[10px] text-hp-muted mt-0.5">Nhôm kính</span>
                </div>
                <div class="bg-hp-bg border border-slate-200/80 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-hp-gold transition">
                    <span class="font-extrabold text-sm sm:text-base text-hp-navy tracking-tight">AN CƯỜNG</span>
                    <span class="text-[10px] text-hp-muted mt-0.5">Gỗ nội thất</span>
                </div>
                <div class="bg-hp-bg border border-slate-200/80 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-hp-gold transition">
                    <span class="font-extrabold text-sm sm:text-base text-hp-navy tracking-tight">TOTO</span>
                    <span class="text-[10px] text-hp-muted mt-0.5">Thiết bị vệ sinh</span>
                </div>
                <div class="bg-hp-bg border border-slate-200/80 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-hp-gold transition">
                    <span class="font-extrabold text-sm sm:text-base text-hp-navy tracking-tight">CADIVI</span>
                    <span class="text-[10px] text-hp-muted mt-0.5">Dây cáp điện</span>
                </div>
                <div class="bg-hp-bg border border-slate-200/80 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-hp-gold transition">
                    <span class="font-extrabold text-sm sm:text-base text-hp-navy tracking-tight">ĐỒNG TÂM</span>
                    <span class="text-[10px] text-hp-muted mt-0.5">Gạch ốp lát</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         9. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ MIỄN PHÍ TRÊN TRANG CHỦ (CHUẨN WEB MẪU)
         ========================================================================= -->
    <section id="bao-gia" class="py-12 lg:py-16 bg-hp-navy text-white">
        <div class="hp-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 lg:gap-10 items-center">
                <!-- Cột thông tin báo giá -->
                <div class="lg:col-span-5">
                    <p class="text-xs font-bold uppercase tracking-widest text-hp-gold mb-2">Miễn Phí Tư Vấn &amp; Khảo Sát</p>
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-snug mb-4">
                        Đăng Ký Nhận Báo Giá Thiết Kế &amp; Thi Công Trọn Gói
                    </h2>
                    <p class="text-sm text-slate-300 leading-relaxed mb-6">
                        Để lại thông tin công trình dự kiến của bạn, kỹ sư trưởng của <strong>HP HOUSE</strong> sẽ liên hệ tư vấn phương án tối ưu và gửi bảng dự toán chi tiết trong vòng 30 phút.
                    </p>

                    <div class="space-y-3 text-sm">
                        <div class="flex items-center gap-3 bg-white/5 border border-white/10 rounded-lg p-3.5">
                            <i class="fa-solid fa-check-circle text-hp-gold text-lg shrink-0"></i>
                            <span>Báo giá Thiết kế Kiến trúc – Nội thất chi tiết theo m²</span>
                        </div>
                        <div class="flex items-center gap-3 bg-white/5 border border-white/10 rounded-lg p-3.5">
                            <i class="fa-solid fa-check-circle text-hp-gold text-lg shrink-0"></i>
                            <span>Báo giá Thi công phần thô &amp; nhân công hoàn thiện</span>
                        </div>
                        <div class="flex items-center gap-3 bg-white/5 border border-white/10 rounded-lg p-3.5">
                            <i class="fa-solid fa-check-circle text-hp-gold text-lg shrink-0"></i>
                            <span>Báo giá Xây nhà trọn gói chìa khóa trao tay tại Đà Nẵng</span>
                        </div>
                    </div>
                </div>

                <!-- Cột Form nhập liệu -->
                <div class="lg:col-span-7">
                    <form id="quote-form" class="bg-white text-hp-text rounded-xl p-5 sm:p-7 shadow-xl">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="q-name" class="block text-xs font-semibold text-hp-navy mb-1.5">Họ và tên *</label>
                                <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-hp-gold focus:ring-2 focus:ring-hp-gold/25 outline-none transition">
                            </div>
                            <div>
                                <label for="q-phone" class="block text-xs font-semibold text-hp-navy mb-1.5">Số điện thoại / Zalo *</label>
                                <input id="q-phone" type="tel" required placeholder="VD: 0903.578.069" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-hp-gold focus:ring-2 focus:ring-hp-gold/25 outline-none transition">
                            </div>
                            <div>
                                <label for="q-email" class="block text-xs font-semibold text-hp-navy mb-1.5">Email</label>
                                <input id="q-email" type="email" placeholder="email@hphouse.com" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-hp-gold focus:ring-2 focus:ring-hp-gold/25 outline-none transition">
                            </div>
                            <div>
                                <label for="q-type" class="block text-xs font-semibold text-hp-navy mb-1.5">Loại công trình</label>
                                <select id="q-type" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-hp-gold focus:ring-2 focus:ring-hp-gold/25 outline-none transition">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label for="q-budget" class="block text-xs font-semibold text-hp-navy mb-1.5">Mức đầu tư dự kiến</label>
                                <select id="q-budget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-hp-gold focus:ring-2 focus:ring-hp-gold/25 outline-none transition">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                    <option value="1 tỷ - 2 tỷ">1 tỷ - 2 tỷ</option>
                                    <option value="2 tỷ - 3 tỷ">2 tỷ - 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                            <div>
                                <label for="q-area" class="block text-xs font-semibold text-hp-navy mb-1.5">Diện tích &amp; Số tầng (nếu có)</label>
                                <input id="q-area" type="text" placeholder="VD: 5x20m, 3 tầng tại Hòa Xuân" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-hp-gold focus:ring-2 focus:ring-hp-gold/25 outline-none transition">
                            </div>
                        </div>

                        <div class="mt-4">
                            <label for="q-note" class="block text-xs font-semibold text-hp-navy mb-1.5">Nội dung yêu cầu</label>
                            <textarea id="q-note" rows="3" placeholder="Mô tả nhu cầu thiết kế, thi công phần thô hoặc xây dựng trọn gói..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-hp-gold focus:ring-2 focus:ring-hp-gold/25 outline-none transition"></textarea>
                        </div>

                        <div id="quote-feedback" class="hidden mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-sm font-medium"></div>

                        <div class="mt-5 flex flex-wrap items-center justify-between gap-3">
                            <button type="submit" class="w-full sm:w-auto inline-flex items-center justify-center gap-2 bg-hp-gold hover:bg-hp-goldDark text-white font-bold text-sm px-7 py-3 rounded-lg shadow-md transition">
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>Gửi Yêu Cầu Báo Giá</span>
                            </button>
                            <span class="text-xs text-hp-muted">Hoặc gọi trực tiếp Hotline: <a href="tel:0903578069" class="font-bold text-hp-navy hover:text-hp-gold">0903.578.069</a></span>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         10. DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
         ========================================================================= -->
    <section id="tin-tuc" class="py-12 lg:py-16 bg-white">
        <div class="hp-container">
            <div class="text-center max-w-2xl mx-auto mb-9">
                <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-hp-navy uppercase tracking-tight">
                    Tin Tức &amp; Cẩm Nang Xây Dựng
                </h2>
                <div class="w-16 h-1 bg-hp-gold mx-auto mt-3 rounded-full"></div>
                <p class="text-sm text-hp-muted mt-3">
                    Chia sẻ kinh nghiệm thiết kế kiến trúc, kỹ thuật thi công và dự toán chi phí xây nhà thực tế
                </p>
            </div>

            <div id="news-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5">
                <!-- Danh sách bài viết render bằng JS -->
            </div>
        </div>
    </section>

    <!-- =========================================================================
         11. BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
         ========================================================================= -->
    <section id="lien-he" class="py-12 lg:py-16 bg-hp-bg border-t border-slate-200/80">
        <div class="hp-container">
            <div class="text-center max-w-2xl mx-auto mb-9">
                <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-hp-navy uppercase tracking-tight">
                    Kết Nối &amp; Chỉ Đường Đến HP HOUSE
                </h2>
                <div class="w-16 h-1 bg-hp-gold mx-auto mt-3 rounded-full"></div>
                <p class="text-sm text-hp-muted mt-3">
                    Trụ sở chính: 383 Phạm Hùng, Phường Hòa Xuân, Thành phố Đà Nẵng
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột 1: Bản đồ Google Maps thực tế 383 Phạm Hùng, Hòa Xuân, Đà Nẵng -->
                <div class="lg:col-span-7 bg-white rounded-xl overflow-hidden shadow-sm border border-slate-200 flex flex-col">
                    <div class="px-5 py-3.5 bg-hp-navy text-white flex flex-wrap items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-sm font-bold">
                            <i class="fa-solid fa-map-location-dot text-hp-gold"></i>
                            <span>Bản Đồ Google Map — 383 Phạm Hùng, Hòa Xuân, Đà Nẵng</span>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=383+Ph%E1%BA%A1m+H%C3%B9ng,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-hp-gold hover:text-white transition">
                            Mở chỉ đường <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i>
                        </a>
                    </div>
                    <div class="flex-1 min-h-[320px] sm:min-h-[360px] w-full bg-slate-100">
                        <iframe
                            title="Bản đồ Công ty Cổ phần Đầu tư và Xây dựng HP HOUSE - 383 Phạm Hùng, Hòa Xuân, Đà Nẵng"
                            src="https://maps.google.com/maps?q=383%20Ph%E1%BA%A1m%20H%C3%B9ng,%20H%C3%B2a%20Xu%C3%A2n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full min-h-[320px] sm:min-h-[360px] border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen>
                        </iframe>
                    </div>
                </div>

                <!-- Cột 2: Fanpage Facebook chính thức của HP HOUSE ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl overflow-hidden shadow-sm border border-slate-200 flex flex-col">
                    <div class="px-5 py-3.5 bg-[#1877F2] text-white flex items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-sm font-bold">
                            <i class="fa-brands fa-facebook text-lg"></i>
                            <span>Fanpage Chính Thức HP HOUSE</span>
                        </div>
                        <span class="text-xs text-white/90">Đà Nẵng</span>
                    </div>

                    <!-- Khung giao diện Fanpage chuyên nghiệp -->
                    <div class="p-5 flex-1 flex flex-col justify-between">
                        <div>
                            <!-- Ảnh bìa Fanpage -->
                            <div class="relative rounded-xl overflow-hidden h-36 bg-hp-navy mb-4 border border-slate-200">
                                <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                                     data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                                     alt="Ảnh bìa Fanpage HP HOUSE"
                                     class="w-full h-full object-cover opacity-80 hp-drive-img">
                                <div class="absolute inset-0 bg-gradient-to-t from-hp-navy/90 via-hp-navy/40 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                    <!-- Avatar Logo HP HOUSE -->
                                    <div class="w-12 h-12 rounded-lg bg-hp-navy border-2 border-hp-gold flex items-center justify-center shrink-0 shadow">
                                        <span class="text-white font-extrabold text-sm">HP</span>
                                    </div>
                                    <div class="min-w-0">
                                        <h3 class="text-white font-bold text-sm leading-tight truncate">HP HOUSE - Đầu Tư &amp; Xây Dựng Đà Nẵng</h3>
                                        <p class="text-[11px] text-slate-200 mt-0.5">Thiết kế kiến trúc • Xây nhà trọn gói</p>
                                    </div>
                                </div>
                            </div>

                            <!-- Bài đăng cập nhật trên Fanpage -->
                            <div class="bg-hp-bg rounded-lg p-3.5 border border-slate-200/80 text-xs sm:text-sm text-slate-600 space-y-2 mb-4">
                                <p class="font-semibold text-hp-navy">Cập nhật tiến độ công trình hàng ngày tại Đà Nẵng</p>
                                <p class="leading-relaxed">
                                    Theo dõi Fanpage HP HOUSE để xem video nghiệm thu thực tế, mẫu nhà phố hiện đại tại Hòa Xuân và ưu đãi miễn phí 100% thiết kế khi thi công trọn gói.
                                </p>
                                <div class="flex items-center gap-4 text-xs text-hp-muted pt-1">
                                    <span><i class="fa-solid fa-thumbs-up text-[#1877F2] mr-1"></i>5.8K lượt thích</span>
                                    <span><i class="fa-solid fa-star text-hp-gold mr-1"></i>5.0/5 đánh giá</span>
                                </div>
                            </div>
                        </div>

                        <!-- Các nút tương tác Fanpage -->
                        <div class="grid grid-cols-2 gap-3 pt-2">
                            <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-2 bg-[#1877F2] hover:bg-[#1464CC] text-white text-xs sm:text-sm font-bold py-2.5 px-3 rounded-lg transition">
                                <i class="fa-brands fa-facebook-f"></i>
                                <span>Thích Fanpage</span>
                            </a>
                            <a href="https://m.me/" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-2 bg-hp-navy hover:bg-hp-navyDark text-white text-xs sm:text-sm font-bold py-2.5 px-3 rounded-lg transition">
                                <i class="fa-brands fa-facebook-messenger"></i>
                                <span>Nhắn Tin Ngay</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         12. FOOTER CHUẨN FLATSOME (CÓ KHOẢNG TRỐNG DƯỚI ĐÁY CHO THANH MOBILE)
         ========================================================================= -->
    <footer class="bg-hp-navyDark text-slate-300 pt-12 pb-20 lg:pb-10">
        <div class="hp-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-9 border-b border-white/10">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-2.5 mb-4">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
                            <rect x="2" y="2" width="60" height="60" rx="11" fill="#0F2942" stroke="#C89B3C" stroke-width="2.5"/>
                            <path d="M13 28 L32 13 L51 28" fill="none" stroke="#C89B3C" stroke-width="3.6" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M18 33 V50 M18 41.5 H28 M28 33 V50" stroke="#FFFFFF" stroke-width="3.4" stroke-linecap="round"/>
                            <path d="M35 50 V33 H42.5 C46.2 33 48.2 35.1 48.2 38.2 C48.2 41.3 46.2 43.3 42.5 43.3 H35" fill="none" stroke="#C89B3C" stroke-width="3.4" stroke-linecap="round"/>
                        </svg>
                        <div>
                            <div class="text-base font-extrabold text-white tracking-tight">HP <span class="text-hp-gold">HOUSE</span></div>
                            <div class="text-[10px] uppercase tracking-wider text-slate-400">hphouse.com</div>
                        </div>
                    </div>
                    <h3 class="text-sm font-bold text-white uppercase mb-3">CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG HP HOUSE</h3>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-hp-gold mt-1 shrink-0"></i>
                            <span>Trụ sở: 383 Phạm Hùng, Phường Hòa Xuân, Thành phố Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-hp-gold shrink-0"></i>
                            <span>Hotline / Zalo: <a href="tel:0903578069" class="font-bold text-white hover:text-hp-gold">0903.578.069</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-hp-gold shrink-0"></i>
                            <span>Website: <a href="https://hphouse.com" class="text-white hover:text-hp-gold">hphouse.com</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-file-contract text-hp-gold shrink-0"></i>
                            <span>Mã số thuế: 0402171365</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="text-sm font-bold text-white uppercase mb-3.5 pb-2 border-b border-hp-gold/40 inline-block">Lĩnh Vực Hoạt Động</h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#dich-vu" class="hover:text-hp-gold transition">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#cong-trinh-thuc-te" class="hover:text-hp-gold transition">Thi công phần thô</a></li>
                        <li><a href="#cong-trinh-thuc-te" class="hover:text-hp-gold transition">Thi công hoàn thiện</a></li>
                        <li><a href="#dich-vu" class="hover:text-hp-gold transition">Thi công nội thất trọn gói</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-hp-gold transition">Dự án xây dựng Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục công trình -->
                <div class="lg:col-span-4">
                    <h4 class="text-sm font-bold text-white uppercase mb-3.5 pb-2 border-b border-hp-gold/40 inline-block">Danh Mục Công Trình</h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><button type="button" onclick="filterConstructionAndScroll('khach-san-can-ho')" class="hover:text-hp-gold transition">Khách sạn – Căn hộ – Phòng trọ</button></li>
                        <li><button type="button" onclick="filterConstructionAndScroll('biet-thu')" class="hover:text-hp-gold transition">Thiết kế &amp; Thi công Biệt thự</button></li>
                        <li><button type="button" onclick="filterConstructionAndScroll('nha-pho')" class="hover:text-hp-gold transition">Xây dựng Nhà phố hiện đại</button></li>
                        <li><button type="button" onclick="filterConstructionAndScroll('van-phong')" class="hover:text-hp-gold transition">Thi công Văn phòng – Showroom</button></li>
                        <li><a href="#bao-gia" class="hover:text-hp-gold transition">Nhận bảng báo giá xây dựng 2026</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-6 text-center text-xs text-slate-400">
                Copyright 2026 © <strong class="text-white">CÔNG TY CỔ PHẦN ĐẦU TƯ VÀ XÂY DỰNG HP HOUSE</strong> (hphouse.com). All rights reserved.
            </div>
        </div>
    </footer>

    <!-- =========================================================================
         13. CÁC NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE
             - Trên Máy tính: Cụm nút tròn nổi bên góc phải màn hình
             - Trên Điện thoại: Thanh liên hệ cố định dưới đáy cực dễ bấm
         ========================================================================= -->
    <!-- Cụm nút nổi trên MÁY TÍNH (Desktop) -->
    <div class="hidden lg:flex fixed right-4 bottom-6 z-50 flex-col items-end gap-3">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0903578069" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo HP HOUSE" class="group flex items-center bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-1.5 pr-4 transition">
            <span class="w-9 h-9 rounded-full bg-white text-[#0068FF] font-extrabold text-xs flex items-center justify-center mr-2.5 shrink-0">Zalo</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" aria-label="Facebook HP HOUSE" class="group flex items-center bg-[#1877F2] hover:bg-[#1464CC] text-white rounded-full shadow-lg p-1.5 pr-4 transition">
            <span class="w-9 h-9 rounded-full bg-white text-[#1877F2] flex items-center justify-center mr-2.5 shrink-0">
                <i class="fa-brands fa-facebook-f text-base"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0903578069" aria-label="Gọi Hotline 0903.578.069" class="hotline-pulse flex items-center bg-red-600 hover:bg-red-700 text-white rounded-full shadow-xl p-1.5 pr-4 transition">
            <span class="w-9 h-9 rounded-full bg-white text-red-600 flex items-center justify-center mr-2.5 shrink-0">
                <i class="fa-solid fa-phone-volume text-base"></i>
            </span>
            <span class="text-xs font-extrabold whitespace-nowrap">0903.578.069</span>
        </a>

        <!-- Nút lên đầu trang -->
        <button id="scroll-top-btn" type="button" onclick="window.scrollTo({top: 0, behavior: 'smooth'})" aria-label="Lên đầu trang" class="w-10 h-10 rounded-full bg-hp-navy hover:bg-hp-gold text-white shadow-lg flex items-center justify-center transition">
            <i class="fa-solid fa-arrow-up text-sm"></i>
        </button>
    </div>

    <!-- Thanh liên hệ nổi bật trên ĐIỆN THOẠI (Mobile Bottom Action Bar) -->
    <div class="lg:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-slate-200 shadow-[0_-4px_16px_rgba(0,0,0,0.10)] px-2 py-2">
        <div class="grid grid-cols-3 gap-2">
            <a href="tel:0903578069" class="flex items-center justify-center gap-1.5 bg-red-600 active:bg-red-700 text-white text-xs font-bold py-2.5 rounded-lg shadow-sm">
                <i class="fa-solid fa-phone"></i>
                <span>Hotline</span>
            </a>
            <a href="https://zalo.me/0903578069" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 bg-[#0068FF] active:bg-[#0055D4] text-white text-xs font-bold py-2.5 rounded-lg shadow-sm">
                <span class="font-extrabold">Zalo</span>
                <span>Tư vấn</span>
            </a>
            <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" class="flex items-center justify-center gap-1.5 bg-[#1877F2] active:bg-[#1464CC] text-white text-xs font-bold py-2.5 rounded-lg shadow-sm">
                <i class="fa-brands fa-facebook-f"></i>
                <span>Facebook</span>
            </a>
        </div>
    </div>

    <!-- =========================================================================
         14. MODAL XEM CHI TIẾT HÌNH ẢNH CÔNG TRÌNH / BÀI VIẾT
         ========================================================================= -->
    <div id="detail-modal" class="hidden fixed inset-0 z-[60] bg-black/75 backdrop-blur-xs flex items-center justify-center p-4" role="dialog" aria-modal="true">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
            <button type="button" onclick="closeDetailModal()" aria-label="Đóng cửa sổ" class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-hp-navy/90 hover:bg-hp-gold text-white flex items-center justify-center transition">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="modal-body"></div>
        </div>
    </div>

    <!-- =========================================================================
         JAVASCRIPT ĐIỀU KHIỂN SLIDER, BỘ LỌC DANH MỤC, DỮ LIỆU GOOGLE DRIVE & FORM
         ========================================================================= -->
    <script>
        /* =====================================================================
           1. DỮ LIỆU 9 HÌNH ẢNH THI CÔNG THỰC TẾ (GOOGLE DRIVE NHÓM 1)
              Đưa vào đúng danh mục web mẫu tintruongthinh.com
           ===================================================================== */
        const constructionProjects = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô & Kết Cấu Nhà Phố Hiện Đại',
                category: ['nha-pho', 'phan-tho'],
                categoryName: 'Nhà phố • Thi công phần thô',
                location: 'Khu đô thị Hòa Xuân, TP. Đà Nẵng',
                desc: 'Hạng mục thi công cốt thép sàn dầm, đổ bê tông kết cấu chuẩn kỹ thuật và kiểm định mác bê tông trực tiếp tại công trường.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Xây Dựng Nhà Phố 3 Tầng Trọn Gói',
                category: ['nha-pho', 'hoan-thien'],
                categoryName: 'Nhà phố • Thi công trọn gói',
                location: 'Phường Hòa Xuân, TP. Đà Nẵng',
                desc: 'Công trình nhà phố 3 tầng phong cách tối giản, thi công chuẩn tiến độ với hệ mặt tiền lam chắn nắng và kính cường lực cao cấp.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thiết Kế & Thi Công Biệt Thự Hiện Đại 2 Mặt Tiền',
                category: ['biet-thu', 'hoan-thien'],
                categoryName: 'Biệt thự • Hoàn thiện trọn gói',
                location: 'Quận Ngũ Hành Sơn, TP. Đà Nẵng',
                desc: 'Biệt thự không gian mở sang trọng với hệ mái kiến trúc, đá ốp tự nhiên và cảnh quan sân vườn xanh mát.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Căn Hộ Cho Thuê & Phòng Trọ Cao Cấp',
                category: ['khach-san-can-ho', 'phan-tho'],
                categoryName: 'Khách sạn - Căn hộ - Phòng trọ',
                location: 'Quận Sơn Trà, TP. Đà Nẵng',
                desc: 'Giải pháp tối ưu diện tích khai thác cho thuê, hệ thống PCCC và điện nước âm tường đạt chuẩn vận hành lâu dài.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Hoàn Thiện Mặt Tiền Nhà Phố Thương Mại',
                category: ['nha-pho', 'hoan-thien'],
                categoryName: 'Nhà phố • Thi công hoàn thiện',
                location: 'Quận Hải Châu, TP. Đà Nẵng',
                desc: 'Hoàn thiện ốp lát, sơn nước chống thấm ngoài trời và lắp đặt hệ cửa nhôm Xingfa đồng bộ.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi Công Móng Cọc & Đà Kiềng Kết Cấu Bền Vững',
                category: ['phan-tho', 'biet-thu'],
                categoryName: 'Thi công phần thô • Kết cấu',
                location: 'Nam Hòa Xuân, TP. Đà Nẵng',
                desc: 'Thi công nền móng vững chắc, xử lý chống thấm cổ ống và bảo dưỡng bê tông tiêu chuẩn cho nền đất ven sông.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thiết Kế & Thi Công Khách Sạn Mini Ven Biển',
                category: ['khach-san-can-ho', 'hoan-thien'],
                categoryName: 'Khách sạn - Căn hộ - Phòng trọ',
                location: 'Mỹ Khê, Quận Sơn Trà, TP. Đà Nẵng',
                desc: 'Công trình khách sạn lưu trú hiện đại kết hợp không gian sảnh đón khách sang trọng và hệ thống phòng nghỉ tiện nghi.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công Văn Phòng Làm Việc & Showroom Công Ty',
                category: ['van-phong', 'hoan-thien'],
                categoryName: 'Văn phòng • Hoàn thiện nội thất',
                location: 'Quận Cẩm Lệ, TP. Đà Nẵng',
                desc: 'Không gian văn phòng chuyên nghiệp, bố trí ánh sáng khoa học, vách kính cách âm và nội thất gỗ công nghiệp An Cường.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Giám Sát & Thi Công Hoàn Thiện Nội Ngoại Thất',
                category: ['hoan-thien', 'nha-pho'],
                categoryName: 'Thi công hoàn thiện',
                location: 'TP. Đà Nẵng',
                desc: 'Nghiệm thu kỹ lưỡng từng công đoạn đóng trần thạch cao, sơn bả matit, lắp đặt thiết bị điện và vệ sinh bàn giao.'
            }
        ];

        /* =====================================================================
           2. DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (GOOGLE DRIVE NHÓM 2)
           ===================================================================== */
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Nhà Phố Hiện Đại KĐT Hòa Xuân',
                area: 'hoa-xuan',
                areaLabel: 'Hòa Xuân, Đà Nẵng',
                desc: 'Dự án nhà phố 3 tầng mặt tiền hiện đại do HP HOUSE thiết kế và thi công trọn gói tại khu đô thị sinh thái Hòa Xuân.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Biệt Thự Phố Đường Phạm Hùng',
                area: 'hoa-xuan',
                areaLabel: 'Hòa Xuân, Đà Nẵng',
                desc: 'Biệt thự phố kết hợp không gian sinh hoạt gia đình rộng rãi, thông thoáng với giếng trời trung tâm.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Căn Hộ Dịch Vụ Ven Biển Sơn Trà',
                area: 'son-tra',
                areaLabel: 'Sơn Trà, Đà Nẵng',
                desc: 'Tòa nhà căn hộ cho thuê cao cấp thiết kế hiện đại, tối ưu công suất khai thác du lịch tại quận Sơn Trà.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Nhà Phố Kết Hợp Kinh Doanh Hải Châu',
                area: 'hai-chau',
                areaLabel: 'Hải Châu, Đà Nẵng',
                desc: 'Công trình nhà phố kết hợp mặt bằng kinh doanh trung tâm quận Hải Châu, kết cấu vượt nhịp tối ưu không gian tầng trệt.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Biệt Thự Nghỉ Dưỡng Ngũ Hành Sơn',
                area: 'ngu-hanh-son',
                areaLabel: 'Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Biệt thự sân vườn phong cách nhiệt đới hiện đại, sử dụng vật liệu đá và gỗ tự nhiên chống chịu khí hậu biển.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Nhà Ở Gia Đình 2 Tầng Nam Hòa Xuân',
                area: 'hoa-xuan',
                areaLabel: 'Hòa Xuân, Đà Nẵng',
                desc: 'Thiết kế tinh gọn, chi phí tối ưu nhưng vẫn đảm bảo đầy đủ công năng cho gia đình 3 thế hệ tại Nam Hòa Xuân.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Khách Sạn Boutique Biển Mỹ Khê',
                area: 'son-tra',
                areaLabel: 'Sơn Trà, Đà Nẵng',
                desc: 'Thi công hoàn thiện khách sạn Boutique sang trọng với mặt đứng ấn tượng và nội thất tinh tế.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Tòa Nhà Văn Phòng Trung Tâm Đà Nẵng',
                area: 'hai-chau',
                areaLabel: 'Hải Châu, Đà Nẵng',
                desc: 'Công trình văn phòng làm việc mặt kính cường lực cách nhiệt, tối ưu ánh sáng và diện tích sử dụng.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Nhà Phố Tân Cổ Điển Liên Chiểu',
                area: 'lien-chieu',
                areaLabel: 'Liên Chiểu, Đà Nẵng',
                desc: 'Kiến trúc bán cổ điển thanh lịch, thi công phào chỉ sắc nét và hệ ban công sắt mỹ thuật bền đẹp.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Villa 2 Mặt Tiền Khu Đô Thị FPT Đà Nẵng',
                area: 'ngu-hanh-son',
                areaLabel: 'Ngũ Hành Sơn, Đà Nẵng',
                desc: 'Công trình Villa hiện đại hoàn thiện chìa khóa trao tay với không gian sống đẳng cấp và đầy đủ tiện nghi.'
            }
        ];

        /* =====================================================================
           3. DỮ LIỆU CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ
           ===================================================================== */
        const newsArticles = [
            {
                driveId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                date: '18/11/2026',
                title: 'Hướng dẫn bảo dưỡng bê tông móng đúng kỹ thuật khi xây nhà',
                excerpt: 'Quy trình tưới nước giữ ẩm và che chắn bê tông móng trong 7 ngày đầu giúp tăng cường độ chịu lực, tránh nứt chân chim.',
                content: 'Bảo dưỡng bê tông móng là công đoạn cực kỳ quan trọng quyết định tuổi thọ của toàn bộ ngôi nhà. Sau khi đổ bê tông từ 4–6 giờ (tùy thời tiết Đà Nẵng), cần tiến hành giữ ẩm bề mặt liên tục bằng bao bố ướt hoặc phun sương nhẹ. Tránh đi lại, đặt vật nặng lên bề mặt bê tông trong 48 giờ đầu tiên và duy trì tưới ẩm tối thiểu 7 ngày liên tiếp.'
            },
            {
                driveId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                date: '12/11/2026',
                title: '03 nỗi lo lớn nhất khi xây nhà trọn gói và cách phòng tránh hiệu quả',
                excerpt: 'Làm sao để không phát sinh chi phí, đảm bảo đúng tiến độ và kiểm soát chất lượng vật tư ngay cả khi bạn bận rộn?',
                content: 'Ba nỗi lo phổ biến nhất của chủ đầu tư khi xây nhà là: phát sinh chi phí ngoài dự toán, chậm tiến độ bàn giao và vật tư không đúng cam kết. Tại HP HOUSE, mọi hạng mục vật tư đều được ghi rõ thương hiệu, quy cách trong phụ lục hợp đồng, đi kèm báo cáo ảnh nghiệm thu công trường mỗi ngày để chủ nhà hoàn toàn yên tâm.'
            },
            {
                driveId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                date: '05/11/2026',
                title: 'Tâm lý học không gian: Thiết kế nội thất tác động đến cảm xúc ra sao?',
                excerpt: 'Ánh sáng tự nhiên, tỷ lệ trần nhà và bảng màu hài hòa giúp giảm căng thẳng và nâng cao chất lượng sống mỗi ngày.',
                content: 'Một ngôi nhà đẹp không chỉ nhìn ấn tượng trên phối cảnh mà còn phải mang lại sự thư thái khi sử dụng. Việc bố trí giếng trời, thông gió đối lưu và sử dụng tông màu trung tính kết hợp gỗ ấm áp giúp tối ưu năng lượng tích cực cho cả gia đình.'
            },
            {
                driveId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                date: '29/10/2026',
                title: 'Cập nhật kinh nghiệm dự toán chi phí xây nhà phố tại Hòa Xuân Đà Nẵng',
                excerpt: 'Cách tính diện tích xây dựng theo m² sàn, chi phí phần thô và hoàn thiện giúp gia chủ chủ động kế hoạch tài chính.',
                content: 'Khi chuẩn bị xây nhà tại khu vực Hòa Xuân, Đà Nẵng, chủ đầu tư cần lưu ý đặc điểm địa chất để chọn phương án móng phù hợp (móng băng hoặc móng cọc ép). Việc lập hồ sơ thiết kế chi tiết trước khi thi công giúp bóc tách khối lượng chính xác đến 95%, hạn chế tối đa chi phí phát sinh.'
            }
        ];

        /* =====================================================================
           HÀM HỖ TRỢ TẢI ẢNH GOOGLE DRIVE ỔN ĐỊNH CÓ FALLBACK THÔNG MINH
           ===================================================================== */
        function getDriveThumbUrl(fileId, width = 1000) {
            return `https://drive.google.com/thumbnail?id=${fileId}&sz=w${width}`;
        }

        function handleDriveImgError(imgEl) {
            const fileId = imgEl.getAttribute('data-drive-id');
            const stage = imgEl.getAttribute('data-fallback-stage') || '0';

            if (stage === '0' && fileId) {
                // Thử nguồn Google User Content dự phòng
                imgEl.setAttribute('data-fallback-stage', '1');
                imgEl.src = `https://lh3.googleusercontent.com/d/${fileId}=w1000`;
            } else if (stage === '1') {
                // Nếu tệp Drive chưa mở quyền công khai, hiển thị ảnh giữ chỗ thẩm mỹ
                imgEl.setAttribute('data-fallback-stage', '2');
                imgEl.src = 'https://placehold.co/800x600/0F2942/C89B3C?text=HP+HOUSE+Construction';
            }
        }

        function bindDriveImageFallbacks(scope = document) {
            scope.querySelectorAll('img.hp-drive-img').forEach(img => {
                img.onerror = function() { handleDriveImgError(this); };
            });
        }

        /* =====================================================================
           RENDER DANH SÁCH 9 CÔNG TRÌNH THI CÔNG THỰC TẾ (KHÔNG NHÃN DÁN)
           ===================================================================== */
        function renderConstructionProjects(filterCat = 'all') {
            const container = document.getElementById('construction-grid');
            const filtered = filterCat === 'all'
                ? constructionProjects
                : constructionProjects.filter(item => item.category.includes(filterCat));

            container.innerHTML = filtered.map((item, idx) => `
                <article onclick="openProjectModal('construction', '${item.id}')" class="flatsome-card cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200/90 flex flex-col">
                    <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="${getDriveThumbUrl(item.id, 900)}"
                             data-drive-id="${item.id}"
                             alt="${item.title}"
                             loading="lazy"
                             class="w-full h-full object-cover hp-drive-img">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <h3 class="text-[13px] sm:text-sm font-bold text-hp-navy leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-hp-muted mt-1.5 flex items-start gap-1 leading-snug">
                            <i class="fa-solid fa-location-dot text-hp-gold mt-0.5 shrink-0"></i>
                            <span>${item.location}</span>
                        </p>
                    </div>
                </article>
            `).join('');

            bindDriveImageFallbacks(container);
        }

        function filterConstruction(cat) {
            document.querySelectorAll('.construction-tab').forEach(btn => {
                const isActive = btn.getAttribute('data-cat') === cat;
                btn.classList.toggle('bg-hp-navy', isActive);
                btn.classList.toggle('text-white', isActive);
                btn.classList.toggle('bg-hp-bg', !isActive);
                btn.classList.toggle('text-hp-navy', !isActive);
            });
            renderConstructionProjects(cat);
        }

        function filterConstructionAndScroll(cat) {
            filterConstruction(cat);
            const el = document.getElementById('cong-trinh-thuc-te');
            if (el) el.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }

        /* =====================================================================
           RENDER DANH SÁCH 10 DỰ ÁN TẠI ĐÀ NẴNG (2 CỘT TRÊN MOBILE, KHÔNG NHÃN DÁN)
           ===================================================================== */
        function renderDanangProjects(area = 'all') {
            const container = document.getElementById('danang-grid');
            const filtered = area === 'all'
                ? danangProjects
                : danangProjects.filter(item => item.area === area);

            container.innerHTML = filtered.map(item => `
                <article onclick="openProjectModal('danang', '${item.id}')" class="flatsome-card cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200/90 flex flex-col">
                    <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="${getDriveThumbUrl(item.id, 900)}"
                             data-drive-id="${item.id}"
                             alt="${item.title}"
                             loading="lazy"
                             class="w-full h-full object-cover hp-drive-img">
                    </div>
                    <div class="p-3 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="text-[13px] sm:text-[13.5px] font-bold text-hp-navy leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-hp-muted mt-1.5 flex items-center gap-1">
                            <i class="fa-solid fa-map-pin text-hp-gold shrink-0"></i>
                            <span>${item.areaLabel}</span>
                        </p>
                    </div>
                </article>
            `).join('');

            bindDriveImageFallbacks(container);
        }

        function filterDanang(area) {
            document.querySelectorAll('.danang-tab').forEach(btn => {
                const isActive = btn.getAttribute('data-area') === area;
                btn.classList.toggle('bg-hp-navy', isActive);
                btn.classList.toggle('text-white', isActive);
                btn.classList.toggle('bg-white', !isActive);
                btn.classList.toggle('text-hp-navy', !isActive);
            });
            renderDanangProjects(area);
        }

        /* =====================================================================
           RENDER DANH MỤC BÀI VIẾT / TIN TỨC TRANG CHỦ
           ===================================================================== */
        function renderNewsArticles() {
            const container = document.getElementById('news-grid');
            container.innerHTML = newsArticles.map((art, index) => `
                <article onclick="openNewsModal(${index})" class="flatsome-card cursor-pointer bg-white rounded-xl overflow-hidden border border-slate-200 flex flex-col">
                    <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img src="${getDriveThumbUrl(art.driveId, 800)}"
                             data-drive-id="${art.driveId}"
                             alt="${art.title}"
                             loading="lazy"
                             class="w-full h-full object-cover hp-drive-img">
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-hp-muted mb-1.5">
                                <i class="fa-regular fa-calendar text-hp-gold mr-1"></i>${art.date}
                            </div>
                            <h3 class="text-sm font-bold text-hp-navy leading-snug mb-2">
                                ${art.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-slate-100 text-xs font-bold text-hp-goldDark inline-flex items-center gap-1">
                            <span>Xem chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </div>
                    </div>
                </article>
            `).join('');

            bindDriveImageFallbacks(container);
        }

        /* =====================================================================
           MODAL CHI TIẾT CÔNG TRÌNH & BÀI VIẾT
           ===================================================================== */
        function openProjectModal(source, id) {
            const list = source === 'construction' ? constructionProjects : danangProjects;
            const item = list.find(x => x.id === id);
            if (!item) return;

            const locationText = item.location || item.areaLabel;
            const subtitle = item.categoryName || 'Dự án thực hiện tại Đà Nẵng';

            const modalBody = document.getElementById('modal-body');
            modalBody.innerHTML = `
                <div class="w-full bg-slate-100">
                    <img src="${getDriveThumbUrl(item.id, 1400)}"
                         data-drive-id="${item.id}"
                         alt="${item.title}"
                         class="w-full max-h-[420px] object-cover hp-drive-img">
                </div>
                <div class="p-5 sm:p-6">
                    <p class="text-xs font-bold uppercase tracking-wider text-hp-gold mb-1">${subtitle}</p>
                    <h3 class="text-lg sm:text-xl font-extrabold text-hp-navy mb-2">${item.title}</h3>
                    <p class="text-xs sm:text-sm text-hp-muted mb-3">
                        <i class="fa-solid fa-location-dot text-hp-gold mr-1.5"></i>${locationText}
                    </p>
                    <p class="text-sm text-slate-600 leading-relaxed mb-5">${item.desc}</p>
                    <div class="flex flex-wrap items-center gap-3 pt-3 border-t border-slate-100">
                        <a href="#bao-gia" onclick="closeDetailModal()" class="inline-flex items-center gap-2 bg-hp-gold hover:bg-hp-goldDark text-white text-xs sm:text-sm font-bold px-5 py-2.5 rounded-lg transition">
                            <i class="fa-solid fa-file-signature"></i>
                            <span>Yêu cầu báo giá công trình tương tự</span>
                        </a>
                        <a href="tel:0903578069" class="inline-flex items-center gap-2 bg-hp-navy hover:bg-hp-navyDark text-white text-xs sm:text-sm font-bold px-4 py-2.5 rounded-lg transition">
                            <i class="fa-solid fa-phone"></i>
                            <span>0903.578.069</span>
                        </a>
                    </div>
                </div>
            `;
            bindDriveImageFallbacks(modalBody);
            document.getElementById('detail-modal').classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function openNewsModal(index) {
            const art = newsArticles[index];
            if (!art) return;

            const modalBody = document.getElementById('modal-body');
            modalBody.innerHTML = `
                <div class="w-full bg-slate-100">
                    <img src="${getDriveThumbUrl(art.driveId, 1200)}"
                         data-drive-id="${art.driveId}"
                         alt="${art.title}"
                         class="w-full max-h-[360px] object-cover hp-drive-img">
                </div>
                <div class="p-5 sm:p-6">
                    <p class="text-xs text-hp-muted mb-1.5"><i class="fa-regular fa-calendar text-hp-gold mr-1"></i>${art.date} • HP HOUSE Đà Nẵng</p>
                    <h3 class="text-lg sm:text-xl font-extrabold text-hp-navy mb-3">${art.title}</h3>
                    <p class="text-sm text-slate-700 leading-relaxed mb-5">${art.content}</p>
                    <div class="pt-3 border-t border-slate-100 flex flex-wrap gap-3">
                        <a href="#bao-gia" onclick="closeDetailModal()" class="inline-flex items-center gap-2 bg-hp-gold hover:bg-hp-goldDark text-white text-xs sm:text-sm font-bold px-5 py-2.5 rounded-lg transition">
                            <span>Đăng ký tư vấn miễn phí</span>
                        </a>
                    </div>
                </div>
            `;
            bindDriveImageFallbacks(modalBody);
            document.getElementById('detail-modal').classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeDetailModal() {
            document.getElementById('detail-modal').classList.add('hidden');
            document.body.style.overflow = '';
        }

        document.getElementById('detail-modal').addEventListener('click', function(e) {
            if (e.target === this) closeDetailModal();
        });

        /* =====================================================================
           SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG TRÊN ĐIỆN THOẠI
           ===================================================================== */
        let currentSlide = 0;
        const totalSlides = 2;
        let slideInterval = null;
        const heroTrack = document.getElementById('hero-track');

        function updateSliderUI() {
            heroTrack.style.transform = `translateX(-${currentSlide * 50}%)`;
            for (let i = 0; i < totalSlides; i++) {
                const dot = document.getElementById(`dot-${i}`);
                if (!dot) continue;
                if (i === currentSlide) {
                    dot.className = 'w-7 h-2 rounded-full bg-hp-gold transition-all';
                } else {
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
                }
            }
        }

        function goToSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            updateSliderUI();
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSliderUI();
            }, 5500);
        }

        document.getElementById('prev-slide').addEventListener('click', () => goToSlide(currentSlide - 1));
        document.getElementById('next-slide').addEventListener('click', () => goToSlide(currentSlide + 1));

        // Hỗ trợ vuốt ngang trên điện thoại cho banner
        let touchStartX = 0;
        let touchEndX = 0;
        const heroSection = document.getElementById('trang-chu');
        heroSection.addEventListener('touchstart', e => {
            touchStartX = e.changedTouches[0].screenX;
        }, { passive: true });
        heroSection.addEventListener('touchend', e => {
            touchEndX = e.changedTouches[0].screenX;
            if (touchStartX - touchEndX > 45) goToSlide(currentSlide + 1);
            if (touchEndX - touchStartX > 45) goToSlide(currentSlide - 1);
        }, { passive: true });

        /* =====================================================================
           MENU ĐIỆN THOẠI & XỬ LÝ FORM BÁO GIÁ (KHÔNG DÙNG ALERT)
           ===================================================================== */
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        function closeMobileMenu() {
            mobileMenu.classList.add('hidden');
        }

        document.getElementById('quote-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const type = document.getElementById('q-type').value;
            const feedback = document.getElementById('quote-feedback');

            if (!name || !phone) {
                feedback.className = 'mt-4 p-3.5 rounded-lg bg-red-50 border border-red-200 text-red-700 text-sm font-medium';
                feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để HP HOUSE liên hệ báo giá.';
                return;
            }

            feedback.className = 'mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-sm font-medium';
            feedback.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá hạng mục <strong>${type}</strong> đã được gửi đến HP HOUSE. Kỹ sư của chúng tôi sẽ liên hệ số <strong>${phone}</strong> trong thời gian sớm nhất.`;
            this.reset();
        });

        /* =====================================================================
           KHỞI TẠO TOÀN BỘ GIAO DIỆN KHI TẢI TRANG
           ===================================================================== */
        window.addEventListener('DOMContentLoaded', () => {
            renderConstructionProjects('all');
            renderDanangProjects('all');
            renderNewsArticles();
            bindDriveImageFallbacks(document);
            updateSliderUI();
            resetAutoSlide();
        });
    </script>
</body>
</html>
