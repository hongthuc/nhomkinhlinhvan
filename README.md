<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nhôm Kính Linh Vấn - Thi Công Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng | nhomkinhlinhvan.com</title>
    <meta name="description" content="Nhôm Kính Linh Vấn chuyên tư vấn, thiết kế và thi công Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cầu thang kính, Kính ốp bếp, Phòng tắm kính uy tín tại Đà Nẵng. Hotline: 0333.838.181.">

    <!-- Ảnh Thumbnail (Open Graph / Zalo / Facebook Share) sử dụng Logo Nhôm Kính Linh Vấn -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Nhôm Kính Linh Vấn">
    <meta property="og:url" content="https://nhomkinhlinhvan.com">
    <meta property="og:title" content="Nhôm Kính Linh Vấn - Cửa Nhôm Xingfa & Nhôm Kính Cao Cấp Đà Nẵng">
    <meta property="og:description" content="Tư vấn, thiết kế & thi công Cửa nhôm Xingfa từ 1.550.000đ/m², Cửa kính cường lực, Cầu thang kính, Kính ốp bếp, Phòng tắm kính tại Đà Nẵng. Hotline: 0333.838.181.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/15GiKIwELeh8eLdTThQXJWgPMMMXrpCVu">
    <meta property="og:image:alt" content="Logo Nhôm Kính Linh Vấn">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Nhôm Kính Linh Vấn - nhomkinhlinhvan.com">
    <meta name="twitter:description" content="Chuyên Cửa nhôm Xingfa, Cửa kính cường lực, Cầu thang kính, Kính ốp bếp tại Đà Nẵng. Hotline: 0333.838.181.">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/15GiKIwELeh8eLdTThQXJWgPMMMXrpCVu">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/15GiKIwELeh8eLdTThQXJWgPMMMXrpCVu">

    <!-- Font Inter & Font Awesome Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
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
                        brand: {
                            DEFAULT: '#0B3C68',
                            dark: '#072948',
                            light: '#145896',
                            soft: '#EEF5FC',
                            accent: '#D97706',
                            sale: '#DC2626'
                        }
                    }
                }
            }
        }
    </script>

    <!-- Custom CSS tối ưu chuẩn Flatsome, chiều ngang 95% trên máy tính và chống tràn viền tuyệt đối -->
    <style>
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background-color: #F8FAFC;
            color: #1E293B;
        }

        /* Khung chuẩn 95% màn hình trên máy tính, cân giữa và không lệch phải */
        .ux-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .ux-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu thanh menu trên máy tính: nằm gọn trên 1 hàng, không xuống dòng từng tên danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 2px;
        }
        .desktop-nav-item {
            position: relative;
            flex-shrink: 0;
        }
        .desktop-nav-link {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            white-space: nowrap;
            font-size: 12px;
            font-weight: 600;
            letter-spacing: 0.01em;
            padding: 11px 9px;
            color: #FFFFFF;
            transition: background-color 0.2s ease, color 0.2s ease;
            border-radius: 6px;
        }
        @media (min-width: 1280px) {
            .desktop-nav-link {
                font-size: 13px;
                padding: 12px 13px;
            }
        }
        .desktop-nav-link:hover,
        .desktop-nav-item:hover > .desktop-nav-link {
            background-color: rgba(255, 255, 255, 0.14);
            color: #FDE68A;
        }

        /* Menu thả xuống (Dropdown) Flatsome */
        .desktop-dropdown {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 225px;
            background: #FFFFFF;
            border-radius: 10px;
            box-shadow: 0 12px 30px rgba(11, 60, 104, 0.16);
            border: 1px solid #E2E8F0;
            padding: 6px;
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            z-index: 60;
        }
        .desktop-nav-item:hover .desktop-dropdown,
        .desktop-nav-item:focus-within .desktop-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .desktop-dropdown a {
            display: block;
            padding: 8px 12px;
            font-size: 13px;
            font-weight: 500;
            color: #1E293B;
            border-radius: 6px;
            white-space: nowrap;
            transition: background-color 0.15s ease, color 0.15s ease;
        }
        .desktop-dropdown a:hover {
            background-color: #EEF5FC;
            color: #0B3C68;
        }

        /* Banner tự trượt kích thước bằng nhau tuyệt đối, chữ nằm gọn trong khung và cách xa viền */
        .banner-viewport {
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 14px;
        }
        .banner-track {
            display: flex;
            width: 100%;
            transition: transform 0.6s cubic-bezier(0.22, 1, 0.36, 1);
        }
        .banner-slide {
            flex: 0 0 100%;
            width: 100%;
            min-width: 100%;
        }

        /* Tiêu đề mục chuẩn Flatsome */
        .ux-section-title {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .ux-section-title::after {
            content: "";
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 64px;
            height: 3px;
            background-color: #0B3C68;
            border-radius: 999px;
        }

        /* Hiệu ứng nhịp nhẹ cho nút liên hệ nổi */
        @keyframes softPulse {
            0%, 100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(11, 60, 104, 0.4); }
            50% { transform: scale(1.05); box-shadow: 0 0 0 8px rgba(11, 60, 104, 0); }
        }
        .float-pulse {
            animation: softPulse 2.4s infinite;
        }
    </style>
</head>
<body class="antialiased">

    <!-- ===================================================================== -->
    <!-- TOP BAR: THÔNG TIN NHANH (CHUẨN FLATSOME - KHÔNG CÓ TÙY CHỌN UXBUILDER) -->
    <!-- ===================================================================== -->
    <div class="bg-brand-dark text-slate-200 text-[11px] sm:text-xs py-2 border-b border-white/10">
        <div class="ux-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 min-w-0">
                <i class="fa-solid fa-location-dot text-amber-400 shrink-0"></i>
                <span class="truncate">Khu Tái Định Cư Lệ Sơn - Hòa Tiến - Hòa Vang - TP Đà Nẵng</span>
            </div>
            <div class="hidden sm:flex items-center gap-4 shrink-0">
                <span><i class="fa-regular fa-clock text-amber-400 mr-1"></i>Làm việc: 24/7</span>
                <span><i class="fa-solid fa-globe text-amber-400 mr-1"></i>nhomkinhlinhvan.com</span>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- HEADER CHÍNH: LOGO GỌN NHỎ + TÌM KIẾM (KHÔNG CÓ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) -->
    <!-- ===================================================================== -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="ux-container py-2.5 sm:py-3">
            <div class="flex items-center justify-between gap-3">
                <!-- Nút mở menu trên điện thoại -->
                <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục"
                    class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand hover:bg-brand-soft transition shrink-0">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ + Tên thương hiệu -->
                <a href="#trang-chu" class="flex items-center gap-2.5 min-w-0 shrink-0">
                    <img
                        src="https://lh3.googleusercontent.com/d/15GiKIwELeh8eLdTThQXJWgPMMMXrpCVu"
                        data-gdrive-id="15GiKIwELeh8eLdTThQXJWgPMMMXrpCVu"
                        data-fallback-text="LINH VAN"
                        onerror="handleGDriveError(this)"
                        alt="Logo Nhôm Kính Linh Vấn"
                        class="h-10 sm:h-12 w-auto max-w-[110px] sm:max-w-[130px] object-contain rounded-lg"
                    >
                    <div class="leading-tight min-w-0">
                        <div class="text-sm sm:text-base md:text-lg font-extrabold text-brand tracking-tight whitespace-nowrap">NHÔM KÍNH LINH VẤN</div>
                        <div class="text-[10px] sm:text-xs text-slate-500 font-medium truncate">nhomkinhlinhvan.com</div>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm (hiển thị gọn gàng trên máy tính & máy tính bảng) -->
                <div class="hidden md:flex flex-1 max-w-md mx-4">
                    <div class="relative w-full">
                        <input id="desktopSearchInput" type="text" placeholder="Tìm cửa nhôm Xingfa, kính cường lực, cầu thang..."
                            class="w-full pl-4 pr-10 py-2 text-sm bg-slate-50 border border-slate-200 rounded-full focus:outline-none focus:border-brand focus:bg-white transition">
                        <button type="button" onclick="triggerProductSearch()" aria-label="Tìm kiếm"
                            class="absolute right-1.5 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-brand text-white flex items-center justify-center hover:bg-brand-light transition">
                            <i class="fa-solid fa-magnifying-glass text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Thông tin địa bàn ngắn gọn trên desktop (không đặt nút gọi ngay) -->
                <div class="hidden xl:flex items-center gap-2 text-xs text-slate-600 shrink-0">
                    <i class="fa-solid fa-shield-halved text-brand text-base"></i>
                    <div>
                        <div class="font-semibold text-slate-800">Tư vấn - Thiết kế - Thi công</div>
                        <div class="text-slate-500">Uy tín - Chất lượng - Thẩm mỹ</div>
                    </div>
                </div>

                <!-- Nút tìm kiếm nhanh trên điện thoại -->
                <button id="mobileSearchToggle" type="button" aria-label="Tìm kiếm sản phẩm"
                    class="md:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand hover:bg-brand-soft transition shrink-0">
                    <i class="fa-solid fa-magnifying-glass text-base"></i>
                </button>
            </div>

            <!-- Thanh tìm kiếm thả xuống cho điện thoại -->
            <div id="mobileSearchBar" class="hidden md:hidden mt-2.5">
                <div class="relative w-full">
                    <input id="mobileSearchInput" type="text" placeholder="Tìm sản phẩm nhôm kính..."
                        class="w-full pl-4 pr-10 py-2 text-sm bg-slate-50 border border-slate-200 rounded-full focus:outline-none focus:border-brand">
                    <button type="button" onclick="triggerProductSearch(true)" aria-label="Tìm"
                        class="absolute right-1.5 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-brand text-white flex items-center justify-center">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- =================================================================== -->
        <!-- THANH DANH MỤC MÁY TÍNH: CHỮ NHỎ GỌN, VIẾT LIỀN 1 HÀNG, KHÔNG XUỐNG DÒNG TÊN DANH MỤC -->
        <!-- =================================================================== -->
        <nav class="hidden lg:block bg-brand border-t border-white/10" aria-label="Danh mục chính">
            <div class="ux-container py-0.5">
                <ul class="desktop-nav-list">
                    <li class="desktop-nav-item">
                        <a href="#trang-chu" class="desktop-nav-link">Trang chủ</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#san-pham-xingfa" class="desktop-nav-link">
                            <span>Cửa nhôm xingfa</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
                        </a>
                        <div class="desktop-dropdown">
                            <a href="#san-pham-xingfa" onclick="filterProducts('1-canh')">+ Cửa nhôm xingfa 1 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('2-canh')">+ Cửa nhôm xingfa 2 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('3-canh')">+ Cửa nhôm xingfa 3 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('4-canh')">+ Cửa nhôm xingfa 4 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('xep-truot')">+ Cửa nhôm xingfa 5 cánh</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" class="desktop-nav-link">Cửa kính cường lực</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" class="desktop-nav-link">
                            <span>Sản phẩm</span>
                            <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
                        </a>
                        <div class="desktop-dropdown">
                            <a href="#san-pham-xingfa" onclick="filterProducts('all')">+ Cửa nhôm xingfa</a>
                            <a href="#danh-muc-san-pham">+ Cửa nhựa lõi thép</a>
                            <a href="#danh-muc-san-pham">+ Cửa kính tự động</a>
                            <a href="#danh-muc-san-pham">+ Cầu thang kính</a>
                            <a href="#danh-muc-san-pham">+ Kính ốp bếp</a>
                            <a href="#danh-muc-san-pham">+ Phòng tắm kính</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#cong-trinh" class="desktop-nav-link">Công trình</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#bao-gia" class="desktop-nav-link">Báo giá</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- ===================================================================== -->
    <!-- MENU NGĂN KÉO ĐIỆN THOẠI (MOBILE DRAWER - FLATSOME STYLE) -->
    <!-- ===================================================================== -->
    <div id="mobileDrawerBackdrop" class="fixed inset-0 bg-slate-900/50 z-50 hidden transition-opacity"></div>
    <aside id="mobileDrawer" class="fixed top-0 left-0 h-full w-[82%] max-w-[320px] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="flex items-center justify-between px-4 py-3.5 bg-brand text-white">
            <span class="font-bold text-sm tracking-wide">DANH MỤC WEBSITE</span>
            <button id="closeMobileDrawer" type="button" aria-label="Đóng menu" class="w-8 h-8 rounded-lg bg-white/15 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>
        <div class="flex-1 overflow-y-auto p-3 space-y-1 text-sm">
            <a href="#trang-chu" onclick="closeDrawer()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-soft hover:text-brand">Trang chủ</a>
            <a href="#gioi-thieu" onclick="closeDrawer()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-soft hover:text-brand">Giới thiệu</a>

            <!-- Accordion: Cửa nhôm xingfa -->
            <div class="rounded-lg border border-slate-100 overflow-hidden">
                <button type="button" onclick="toggleMobileSub('subXingfa', this)" class="w-full flex items-center justify-between px-3 py-2.5 font-semibold text-slate-800 hover:bg-brand-soft">
                    <span>Cửa nhôm xingfa</span>
                    <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
                </button>
                <div id="subXingfa" class="hidden bg-slate-50 px-3 py-1.5 space-y-1 text-xs font-medium text-slate-700">
                    <a href="#san-pham-xingfa" onclick="filterProducts('1-canh'); closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Cửa nhôm xingfa 1 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('2-canh'); closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Cửa nhôm xingfa 2 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('3-canh'); closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Cửa nhôm xingfa 3 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('4-canh'); closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Cửa nhôm xingfa 4 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('xep-truot'); closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Cửa nhôm xingfa 5 cánh</a>
                </div>
            </div>

            <a href="#danh-muc-san-pham" onclick="closeDrawer()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-soft hover:text-brand">Cửa kính cường lực</a>

            <!-- Accordion: Sản phẩm -->
            <div class="rounded-lg border border-slate-100 overflow-hidden">
                <button type="button" onclick="toggleMobileSub('subSanPham', this)" class="w-full flex items-center justify-between px-3 py-2.5 font-semibold text-slate-800 hover:bg-brand-soft">
                    <span>Sản phẩm</span>
                    <i class="fa-solid fa-chevron-down text-xs transition-transform"></i>
                </button>
                <div id="subSanPham" class="hidden bg-slate-50 px-3 py-1.5 space-y-1 text-xs font-medium text-slate-700">
                    <a href="#san-pham-xingfa" onclick="filterProducts('all'); closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Cửa nhôm xingfa</a>
                    <a href="#danh-muc-san-pham" onclick="closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Cửa nhựa lõi thép</a>
                    <a href="#danh-muc-san-pham" onclick="closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Cửa kính tự động</a>
                    <a href="#danh-muc-san-pham" onclick="closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Cầu thang kính</a>
                    <a href="#danh-muc-san-pham" onclick="closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Kính ốp bếp</a>
                    <a href="#danh-muc-san-pham" onclick="closeDrawer()" class="block py-2 pl-2 rounded hover:text-brand">+ Phòng tắm kính</a>
                </div>
            </div>

            <a href="#cong-trinh" onclick="closeDrawer()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-soft hover:text-brand">Công trình</a>
            <a href="#bao-gia" onclick="closeDrawer()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-soft hover:text-brand">Báo giá</a>
            <a href="#tin-tuc" onclick="closeDrawer()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-soft hover:text-brand">Tin tức</a>
            <a href="#lien-he" onclick="closeDrawer()" class="block px-3 py-2.5 rounded-lg font-semibold text-slate-800 hover:bg-brand-soft hover:text-brand">Liên hệ</a>
        </div>
        <div class="p-4 border-t border-slate-100 bg-slate-50 text-xs text-slate-600 space-y-1">
            <div class="font-bold text-brand">NHÔM KÍNH LINH VẤN</div>
            <div>Hotline / Zalo: <a href="tel:0333838181" class="font-bold text-slate-900">0333.838.181</a></div>
            <div>Khu TĐC Lệ Sơn - Hòa Tiến - Hòa Vang - Đà Nẵng</div>
        </div>
    </aside>

    <!-- ===================================================================== -->
    <!-- MAIN CONTENT (UX BUILDER FLATSOME STRUCTURE: DỄ DÀNG TÁI TẠO TỪNG SECTION) -->
    <!-- ===================================================================== -->
    <main id="trang-chu">

        <!-- ================================================================= -->
        <!-- SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU    -->
        <!-- Hình ảnh và chữ nằm gọn hoàn toàn bên trong, chữ cách xa viền ảnh  -->
        <!-- ================================================================= -->
        <section class="pt-3 pb-4 sm:pt-5 sm:pb-6">
            <div class="ux-container">
                <div id="heroBannerViewport" class="banner-viewport shadow-md border border-slate-200 bg-brand-dark">
                    <div id="heroBannerTrack" class="banner-track">

                        <!-- BANNER 1 -->
                        <div class="banner-slide">
                            <div class="w-full h-[380px] sm:h-[400px] lg:h-[440px] bg-gradient-to-br from-[#072948] via-[#0B3C68] to-[#13538A] px-7 py-6 sm:px-14 sm:py-10 lg:px-20 lg:py-12 flex items-center">
                                <div class="w-full grid grid-cols-1 md:grid-cols-12 gap-4 sm:gap-8 items-center">
                                    <!-- Khối chữ cách xa viền, không bao giờ thiếu chữ -->
                                    <div class="md:col-span-7 text-white space-y-2.5 sm:space-y-4">
                                        <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-amber-300">
                                            Nhôm Kính Linh Vấn • Đà Nẵng
                                        </p>
                                        <h1 class="text-lg sm:text-2xl lg:text-4xl font-extrabold leading-snug tracking-tight">
                                            Thi Công Cửa Nhôm Xingfa Nhập Khẩu Chính Hãng
                                        </h1>
                                        <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl">
                                            Giá ưu đãi chỉ từ <strong class="text-amber-300">1.550.000đ/m²</strong> • Hệ vát cạnh từ <strong class="text-amber-300">1.350.000đ/m²</strong>. Cam kết phụ kiện chính hãng, bảo hành dài hạn, lắp đặt chuẩn thẩm mỹ.
                                        </p>
                                        <div class="pt-1 flex flex-wrap gap-2.5 sm:gap-3">
                                            <a href="#form-bao-gia" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2 sm:py-2.5 rounded-lg bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs sm:text-sm transition">
                                                <span>Nhận Báo Giá Ngay</span>
                                                <i class="fa-solid fa-arrow-right text-xs"></i>
                                            </a>
                                            <a href="#san-pham-xingfa" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs sm:text-sm border border-white/25 transition">
                                                <span>Xem Sản Phẩm</span>
                                            </a>
                                        </div>
                                    </div>
                                    <!-- Hình ảnh minh họa nằm gọn bên trong khung banner -->
                                    <div class="hidden md:flex md:col-span-5 justify-end">
                                        <div class="w-full max-w-[380px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-xl bg-white/10">
                                            <img
                                                src="https://lh3.googleusercontent.com/d/1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                                                data-gdrive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                                                data-fallback-text="Cua Nhom Xingfa"
                                                onerror="handleGDriveError(this)"
                                                alt="Cửa nhôm Xingfa Linh Vấn Đà Nẵng"
                                                class="w-full h-full object-cover"
                                            >
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- BANNER 2 (Cùng kích thước chiều cao và padding với Banner 1) -->
                        <div class="banner-slide">
                            <div class="w-full h-[380px] sm:h-[400px] lg:h-[440px] bg-gradient-to-br from-[#0F2C4C] via-[#124570] to-[#0B3C68] px-7 py-6 sm:px-14 sm:py-10 lg:px-20 lg:py-12 flex items-center">
                                <div class="w-full grid grid-cols-1 md:grid-cols-12 gap-4 sm:gap-8 items-center">
                                    <!-- Khối chữ cách xa viền, không bao giờ thiếu chữ -->
                                    <div class="md:col-span-7 text-white space-y-2.5 sm:space-y-4">
                                        <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-amber-300">
                                            Uy Tín • Chất Lượng • Thẩm Mỹ
                                        </p>
                                        <h2 class="text-lg sm:text-2xl lg:text-4xl font-extrabold leading-snug tracking-tight">
                                            Giải Pháp Nhôm Kính & Nội Thất Toàn Diện Cho Mọi Công Trình
                                        </h2>
                                        <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-xl">
                                            Chuyên thi công Cửa kính cường lực, Cầu thang kính, Phòng tắm kính, Kính ốp bếp, Cửa nhựa Composite & Tủ bếp nhôm cao cấp tại TP. Đà Nẵng.
                                        </p>
                                        <div class="pt-1 flex flex-wrap gap-2.5 sm:gap-3">
                                            <a href="#cong-trinh" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2 sm:py-2.5 rounded-lg bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs sm:text-sm transition">
                                                <span>Xem Dự Án Thực Tế</span>
                                                <i class="fa-solid fa-building text-xs"></i>
                                            </a>
                                            <a href="tel:0333838181" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs sm:text-sm border border-white/25 transition">
                                                <i class="fa-solid fa-phone text-xs"></i>
                                                <span>0333.838.181</span>
                                            </a>
                                        </div>
                                    </div>
                                    <!-- Hình ảnh minh họa nằm gọn bên trong khung banner -->
                                    <div class="hidden md:flex md:col-span-5 justify-end">
                                        <div class="w-full max-w-[380px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-xl bg-white/10">
                                            <img
                                                src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                                                data-gdrive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                                                data-fallback-text="Du An Nhom Kinh"
                                                onerror="handleGDriveError(this)"
                                                alt="Dự án thi công Nhôm Kính Linh Vấn"
                                                class="w-full h-full object-cover"
                                            >
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <!-- Nút chuyển trái/phải gọn gàng -->
                    <button id="bannerPrev" type="button" aria-label="Banner trước"
                        class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-left text-xs"></i>
                    </button>
                    <button id="bannerNext" type="button" aria-label="Banner sau"
                        class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-right text-xs"></i>
                    </button>

                    <!-- Chấm chỉ báo 2 banner -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 flex items-center gap-2">
                        <button type="button" onclick="goToBanner(0)" id="bannerDot0" aria-label="Banner 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                        <button type="button" onclick="goToBanner(1)" id="bannerDot1" aria-label="Banner 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 2: DANH MỤC SẢN PHẨM NỔI BẬT (CHỮ NHỎ GỌN - THEO WEB MẪU)  -->
        <!-- ================================================================= -->
        <section id="danh-muc-san-pham" class="py-6 sm:py-8">
            <div class="ux-container">
                <div class="text-center mb-5 sm:mb-6">
                    <h2 class="ux-section-title text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase">
                        Danh Mục Sản Phẩm
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2">Giải pháp cửa & nhôm kính đồng bộ cho nhà phố, biệt thự, khách sạn tại Đà Nẵng</p>
                </div>

                <!-- 6 Danh mục sản phẩm chuẩn web mẫu -->
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                    <!-- Danh mục 1: Cửa nhôm Xingfa -->
                    <a href="#san-pham-xingfa" onclick="filterProducts('all')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                                 data-gdrive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                                 data-fallback-text="Cua Nhom Xingfa"
                                 onerror="handleGDriveError(this)"
                                 alt="Cửa nhôm Xingfa"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center">
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-tight">Cửa nhôm Xingfa</h3>
                        </div>
                    </a>

                    <!-- Danh mục 2: Cửa nhựa lõi thép -->
                    <a href="#form-bao-gia" onclick="prefillQuote('Cửa nhựa lõi thép / Composite')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
                                 data-gdrive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
                                 data-fallback-text="Cua Nhua Loi Thep"
                                 onerror="handleGDriveError(this)"
                                 alt="Cửa nhựa lõi thép"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center">
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-tight">Cửa nhựa lõi thép</h3>
                        </div>
                    </a>

                    <!-- Danh mục 3: Cửa kính tự động -->
                    <a href="#form-bao-gia" onclick="prefillQuote('Cửa kính tự động')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
                                 data-gdrive-id="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
                                 data-fallback-text="Cua Kinh Tu Dong"
                                 onerror="handleGDriveError(this)"
                                 alt="Cửa kính tự động"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center">
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-tight">Cửa kính tự động</h3>
                        </div>
                    </a>

                    <!-- Danh mục 4: Cầu thang kính -->
                    <a href="#form-bao-gia" onclick="prefillQuote('Cầu thang kính')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
                                 data-gdrive-id="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
                                 data-fallback-text="Cau Thang Kinh"
                                 onerror="handleGDriveError(this)"
                                 alt="Cầu thang kính"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center">
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-tight">Cầu thang kính</h3>
                        </div>
                    </a>

                    <!-- Danh mục 5: Kính ốp bếp -->
                    <a href="#form-bao-gia" onclick="prefillQuote('Kính ốp bếp')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
                                 data-gdrive-id="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
                                 data-fallback-text="Kinh Op Bep"
                                 onerror="handleGDriveError(this)"
                                 alt="Kính ốp bếp"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center">
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-tight">Kính ốp bếp</h3>
                        </div>
                    </a>

                    <!-- Danh mục 6: Phòng tắm kính -->
                    <a href="#form-bao-gia" onclick="prefillQuote('Phòng tắm kính')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                                 data-gdrive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                                 data-fallback-text="Phong Tam Kinh"
                                 onerror="handleGDriveError(this)"
                                 alt="Phòng tắm kính"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 text-center flex-1 flex items-center justify-center">
                            <h3 class="text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-brand uppercase leading-tight">Phòng tắm kính</h3>
                        </div>
                    </a>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 3: SẢN PHẨM CỬA NHÔM XINGFA (2 CỘT TRÊN MOBILE, GIÁ & -% GÓC TRÊN TRÁI) -->
        <!-- ================================================================= -->
        <section id="san-pham-xingfa" class="py-8 sm:py-10 bg-white border-y border-slate-200">
            <div class="ux-container">
                <div class="text-center mb-5">
                    <h2 class="ux-section-title text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase">
                        Báo Giá Cửa Nhôm Xingfa Đà Nẵng
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2">Sản phẩm gia công trực tiếp tại xưởng Nhôm Kính Linh Vấn — Miễn phí đo đạc & tư vấn tại nhà</p>
                </div>

                <!-- Bộ lọc nhanh danh mục Xingfa -->
                <div id="productFilterTabs" class="flex flex-wrap items-center justify-center gap-2 mb-6">
                    <button type="button" data-filter="all" onclick="filterProducts('all')" class="filter-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-brand text-white transition">Tất cả</button>
                    <button type="button" data-filter="1-canh" onclick="filterProducts('1-canh')" class="filter-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition">1 cánh</button>
                    <button type="button" data-filter="2-canh" onclick="filterProducts('2-canh')" class="filter-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition">2 cánh</button>
                    <button type="button" data-filter="3-canh" onclick="filterProducts('3-canh')" class="filter-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition">3 cánh</button>
                    <button type="button" data-filter="4-canh" onclick="filterProducts('4-canh')" class="filter-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition">4 cánh</button>
                    <button type="button" data-filter="xep-truot" onclick="filterProducts('xep-truot')" class="filter-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition">Xếp trượt</button>
                    <button type="button" data-filter="cua-so" onclick="filterProducts('cua-so')" class="filter-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition">Cửa sổ</button>
                </div>

                <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột trên máy tính bảng & máy tính -->
                <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                    <!-- Được render bằng JavaScript từ dữ liệu chuẩn Google Drive -->
                </div>

                <!-- Thông báo nếu tìm kiếm không thấy kết quả -->
                <div id="noProductMessage" class="hidden text-center py-8 text-sm text-slate-500">
                    Không tìm thấy sản phẩm phù hợp. <button type="button" onclick="resetSearch()" class="text-brand font-bold underline">Xem lại tất cả sản phẩm</button>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 4: GIỚI THIỆU NHÔM KÍNH LINH VẤN (THEO NỘI DUNG FANPAGE)   -->
        <!-- ================================================================= -->
        <section id="gioi-thieu" class="py-8 sm:py-12">
            <div class="ux-container">
                <div class="bg-white rounded-2xl border border-slate-200 shadow-sm p-5 sm:p-8 lg:p-10">
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                        <div class="lg:col-span-7 space-y-4">
                            <h2 class="text-lg sm:text-2xl font-extrabold text-brand uppercase">
                                Nhôm Kính Linh Vấn – Tư Vấn, Thiết Kế & Thi Công Tại Đà Nẵng
                            </h2>
                            <p class="text-sm text-slate-600 leading-relaxed">
                                <strong>Nhôm Kính Linh Vấn</strong> là đơn vị trực tiếp sản xuất, gia công và thi công lắp đặt trọn gói các hạng mục nhôm kính cao cấp tại TP. Đà Nẵng và khu vực Miền Trung. Với phương châm <strong>“Uy tín – Chất lượng – Thẩm mỹ”</strong>, chúng tôi <strong>nói không với hàng kém chất lượng</strong>, cam kết sử dụng nhôm Xingfa chính hãng kết hợp phụ kiện đồng bộ Draho, Kinlong, Candy, Hasmet.
                            </p>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs sm:text-sm text-slate-700 pt-1">
                                <div class="flex items-start gap-2"><i class="fa-solid fa-check-circle text-brand mt-0.5"></i><span>Cửa nhôm Xingfa nhập khẩu & hệ vát cạnh</span></div>
                                <div class="flex items-start gap-2"><i class="fa-solid fa-check-circle text-brand mt-0.5"></i><span>Cửa nhựa Composite & cửa nhựa lõi thép</span></div>
                                <div class="flex items-start gap-2"><i class="fa-solid fa-check-circle text-brand mt-0.5"></i><span>Cửa kính cường lực & cửa kính tự động</span></div>
                                <div class="flex items-start gap-2"><i class="fa-solid fa-check-circle text-brand mt-0.5"></i><span>Cầu thang kính, lan can kính, phòng tắm kính</span></div>
                                <div class="flex items-start gap-2"><i class="fa-solid fa-check-circle text-brand mt-0.5"></i><span>Tủ bếp nhôm nội thất & tủ bếp nhựa cao cấp</span></div>
                                <div class="flex items-start gap-2"><i class="fa-solid fa-check-circle text-brand mt-0.5"></i><span>Kính sơn màu ốp bếp sang trọng, dễ vệ sinh</span></div>
                            </div>
                        </div>

                        <!-- 4 Chỉ số năng lực Flatsome -->
                        <div class="lg:col-span-5 grid grid-cols-2 gap-3 sm:gap-4">
                            <div class="bg-brand-soft rounded-xl p-4 sm:p-5 text-center border border-brand/10">
                                <div class="text-2xl sm:text-3xl font-extrabold text-brand">150+</div>
                                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Dự án hoàn thành</div>
                            </div>
                            <div class="bg-brand-soft rounded-xl p-4 sm:p-5 text-center border border-brand/10">
                                <div class="text-2xl sm:text-3xl font-extrabold text-brand">50+</div>
                                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Thợ kỹ thuật lành nghề</div>
                            </div>
                            <div class="bg-brand-soft rounded-xl p-4 sm:p-5 text-center border border-brand/10">
                                <div class="text-2xl sm:text-3xl font-extrabold text-brand">100+</div>
                                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Mẫu mã chính hãng</div>
                            </div>
                            <div class="bg-brand-soft rounded-xl p-4 sm:p-5 text-center border border-brand/10">
                                <div class="text-2xl sm:text-3xl font-extrabold text-brand">100%</div>
                                <div class="text-xs sm:text-sm font-semibold text-slate-700 mt-1">Khách hàng hài lòng</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 5: BẢNG GIÁ THAM KHẢO NHANH (CHUẨN GIÁ FANPAGE LINH VẤN)  -->
        <!-- ================================================================= -->
        <section id="bao-gia" class="py-8 sm:py-10 bg-white border-y border-slate-200">
            <div class="ux-container">
                <div class="text-center mb-6">
                    <h2 class="ux-section-title text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase">
                        Bảng Báo Giá Thi Công Tham Khảo
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2">Đơn giá trực tiếp tại xưởng — Chiết khấu hấp dẫn cho công trình khối lượng lớn</p>
                </div>

                <div class="overflow-x-auto rounded-xl border border-slate-200 shadow-sm">
                    <table class="w-full text-left border-collapse text-xs sm:text-sm">
                        <thead>
                            <tr class="bg-brand text-white">
                                <th class="py-3 px-3 sm:px-5 font-semibold">Hạng Mục Thi Công</th>
                                <th class="py-3 px-3 sm:px-5 font-semibold">Quy Cách / Phụ Kiện</th>
                                <th class="py-3 px-3 sm:px-5 font-semibold text-right whitespace-nowrap">Đơn Giá Tham Khảo</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-200 bg-white">
                            <tr class="hover:bg-slate-50">
                                <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Cửa nhôm Xingfa nhập khẩu</td>
                                <td class="py-3 px-3 sm:px-5 text-slate-600">Nhôm Xingfa tem đỏ, kính cường lực 8mm, phụ kiện Kinlong / Draho</td>
                                <td class="py-3 px-3 sm:px-5 text-right font-bold text-brand-sale whitespace-nowrap">1.550.000đ / m²</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Cửa nhôm Xingfa hệ vát cạnh</td>
                                <td class="py-3 px-3 sm:px-5 text-slate-600">Bản cánh trơn/vát cạnh thẩm mỹ, phụ kiện đồng bộ</td>
                                <td class="py-3 px-3 sm:px-5 text-right font-bold text-brand-sale whitespace-nowrap">1.350.000đ / m²</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Cửa kính cường lực 10mm - 12mm</td>
                                <td class="py-3 px-3 sm:px-5 text-slate-600">Kính tôi nhiệt an toàn, bản lề sàn & tay nắm inox cao cấp</td>
                                <td class="py-3 px-3 sm:px-5 text-right font-bold text-brand-sale whitespace-nowrap">750.000đ / m²</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Cầu thang kính & Lan can kính</td>
                                <td class="py-3 px-3 sm:px-5 text-slate-600">Kính cường lực 10mm - 12mm, trụ inox 304 / tay vịn gỗ 3D</td>
                                <td class="py-3 px-3 sm:px-5 text-right font-bold text-brand-sale whitespace-nowrap">1.150.000đ / md</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Kính sơn màu ốp bếp cường lực</td>
                                <td class="py-3 px-3 sm:px-5 text-slate-600">Kính 8mm sơn hấp nhiệt đa dạng màu sắc, chống bám dầu mỡ</td>
                                <td class="py-3 px-3 sm:px-5 text-right font-bold text-brand-sale whitespace-nowrap">720.000đ / md</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-3 px-3 sm:px-5 font-semibold text-slate-800">Phòng tắm kính / Cabin tắm</td>
                                <td class="py-3 px-3 sm:px-5 text-slate-600">Kính 10mm cường lực, phụ kiện inox 304 chống gỉ tuyệt đối</td>
                                <td class="py-3 px-3 sm:px-5 text-right font-bold text-brand-sale whitespace-nowrap">1.250.000đ / m²</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 6: CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG (6 DỰ ÁN THỰC TẾ)       -->
        <!-- ================================================================= -->
        <section id="cong-trinh" class="py-8 sm:py-12">
            <div class="ux-container">
                <div class="text-center mb-6">
                    <h2 class="ux-section-title text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase">
                        Các Dự Án Nổi Bật Tại Đà Nẵng
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2">Công trình khách sạn, resort, căn hộ và nhà phố tiêu biểu đã hoàn thiện</p>
                </div>

                <div id="projectGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                    <!-- Render 6 dự án với đúng link Google Drive từ người dùng -->
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 7: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC NỔI BẬT)      -->
        <!-- ================================================================= -->
        <section id="tin-tuc" class="py-8 sm:py-12 bg-white border-y border-slate-200">
            <div class="ux-container">
                <div class="text-center mb-5">
                    <h2 class="ux-section-title text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase">
                        Tin Tức & Cẩm Nang Nhôm Kính
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2">Kiến thức lựa chọn cửa nhôm Xingfa, kính cường lực và kinh nghiệm thi công thực tế</p>
                </div>

                <!-- Danh mục lọc bài viết ngay tại trang chủ -->
                <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
                    <button type="button" data-news-cat="all" onclick="filterNews('all')" class="news-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-brand text-white transition">Tất cả bài viết</button>
                    <button type="button" data-news-cat="tu-van" onclick="filterNews('tu-van')" class="news-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition">Tư vấn chọn cửa</button>
                    <button type="button" data-news-cat="ky-thuat" onclick="filterNews('ky-thuat')" class="news-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition">Kinh nghiệm thi công</button>
                    <button type="button" data-news-cat="bao-gia" onclick="filterNews('bao-gia')" class="news-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition">Báo giá & Phụ kiện</button>
                </div>

                <div id="newsGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                    <!-- Render danh sách bài viết bằng JS -->
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 8: FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ                       -->
        <!-- ================================================================= -->
        <section id="form-bao-gia" class="py-8 sm:py-12">
            <div class="ux-container">
                <div class="bg-gradient-to-br from-[#072948] to-[#0B3C68] rounded-2xl shadow-lg overflow-hidden">
                    <div class="grid grid-cols-1 lg:grid-cols-12">
                        <!-- Thông tin cam kết bên trái -->
                        <div class="lg:col-span-5 p-6 sm:p-8 lg:p-10 text-white flex flex-col justify-center space-y-4">
                            <h2 class="text-xl sm:text-2xl font-extrabold uppercase leading-snug">
                                Đăng Ký Nhận Tư Vấn & Báo Giá Miễn Phí
                            </h2>
                            <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                                Để lại thông tin hạng mục cần thi công, đội ngũ kỹ thuật <strong>Nhôm Kính Linh Vấn</strong> sẽ liên hệ khảo sát tận nơi tại Đà Nẵng và gửi bảng dự toán chi tiết trong vòng 15 phút.
                            </p>
                            <div class="space-y-2.5 pt-2 text-xs sm:text-sm">
                                <div class="flex items-center gap-3">
                                    <span class="w-8 h-8 rounded-lg bg-white/15 flex items-center justify-center shrink-0"><i class="fa-solid fa-phone text-amber-400"></i></span>
                                    <span>Hotline / Zalo: <a href="tel:0333838181" class="font-bold text-amber-300">0333.838.181</a></span>
                                </div>
                                <div class="flex items-center gap-3">
                                    <span class="w-8 h-8 rounded-lg bg-white/15 flex items-center justify-center shrink-0"><i class="fa-solid fa-location-dot text-amber-400"></i></span>
                                    <span>Khu TĐC Lệ Sơn - Hòa Tiến - Hòa Vang - TP Đà Nẵng</span>
                                </div>
                                <div class="flex items-center gap-3">
                                    <span class="w-8 h-8 rounded-lg bg-white/15 flex items-center justify-center shrink-0"><i class="fa-solid fa-ruler-combined text-amber-400"></i></span>
                                    <span>Miễn phí đo đạc, lên bản vẽ & vận chuyển lắp đặt</span>
                                </div>
                            </div>
                        </div>

                        <!-- Biểu mẫu yêu cầu bên phải -->
                        <div class="lg:col-span-7 bg-white p-6 sm:p-8 lg:p-10">
                            <form id="quoteForm" class="space-y-4">
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                    <div>
                                        <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                                        <input id="qName" type="text" required placeholder="Nhập họ tên của bạn"
                                            class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15">
                                    </div>
                                    <div>
                                        <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                                        <input id="qPhone" type="tel" required placeholder="VD: 0905 xxx xxx"
                                            class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15">
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                    <div>
                                        <label for="qCategory" class="block text-xs font-semibold text-slate-700 mb-1.5">Hạng mục quan tâm</label>
                                        <select id="qCategory"
                                            class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg bg-white focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15">
                                            <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                                            <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                                            <option value="Cửa nhựa lõi thép / Composite">Cửa nhựa lõi thép / Composite</option>
                                            <option value="Cửa kính tự động">Cửa kính tự động</option>
                                            <option value="Cầu thang kính">Cầu thang kính</option>
                                            <option value="Kính ốp bếp">Kính ốp bếp</option>
                                            <option value="Phòng tắm kính">Phòng tắm kính</option>
                                            <option value="Tủ bếp nhôm / nội thất cao cấp">Tủ bếp nhôm / nội thất cao cấp</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label for="qArea" class="block text-xs font-semibold text-slate-700 mb-1.5">Diện tích dự kiến (m²)</label>
                                        <input id="qArea" type="text" placeholder="VD: 35 m² hoặc 4 bộ cửa"
                                            class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15">
                                    </div>
                                </div>

                                <div>
                                    <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Địa chỉ công trình & ghi chú yêu cầu</label>
                                    <textarea id="qNote" rows="3" placeholder="Nhập địa chỉ công trình tại Đà Nẵng, loại cửa, màu sắc mong muốn..."
                                        class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15"></textarea>
                                </div>

                                <button type="submit"
                                    class="w-full sm:w-auto px-7 py-3 rounded-lg bg-brand hover:bg-brand-light text-white font-bold text-sm transition inline-flex items-center justify-center gap-2 shadow-sm">
                                    <i class="fa-solid fa-paper-plane"></i>
                                    <span>Gửi Yêu Cầu Báo Giá</span>
                                </button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 9: FANPAGE FACEBOOK & BẢN ĐỒ GOOGLE MAP NGOÀI TRANG CHỦ    -->
        <!-- ================================================================= -->
        <section id="lien-he" class="py-8 sm:py-12 bg-white border-y border-slate-200">
            <div class="ux-container">
                <div class="text-center mb-6">
                    <h2 class="ux-section-title text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase">
                        Kết Nối Fanpage & Bản Đồ Chỉ Đường
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-500 mt-2">Theo dõi công trình bàn giao mới nhất mỗi ngày và xem vị trí xưởng sản xuất tại Hòa Tiến, Đà Nẵng</p>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
                    <!-- Cột trái: Fanpage Facebook Nhôm Kính Linh Vấn -->
                    <div class="lg:col-span-5 bg-slate-50 rounded-2xl border border-slate-200 p-4 sm:p-5 flex flex-col justify-between">
                        <div>
                            <div class="flex items-center justify-between gap-3 mb-3">
                                <div class="flex items-center gap-2.5">
                                    <span class="w-9 h-9 rounded-full bg-[#1877F2] text-white flex items-center justify-center shrink-0">
                                        <i class="fa-brands fa-facebook-f text-base"></i>
                                    </span>
                                    <div>
                                        <h3 class="text-sm font-bold text-slate-900">Fanpage Nhôm Kính Linh Vấn</h3>
                                        <p class="text-xs text-slate-500">facebook.com/nhomkinhlinhvan</p>
                                    </div>
                                </div>
                                <a href="https://www.facebook.com/nhomkinhlinhvan" target="_blank" rel="noopener noreferrer"
                                   class="px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold whitespace-nowrap transition">
                                    Theo dõi
                                </a>
                            </div>

                            <!-- Nhúng Facebook Page Plugin chính thức -->
                            <div class="w-full rounded-xl overflow-hidden bg-white border border-slate-200 mb-3">
                                <iframe
                                    title="Fanpage Nhôm Kính Linh Vấn"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fnhomkinhlinhvan&tabs=timeline&width=500&height=300&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                    width="100%"
                                    height="300"
                                    style="border:none;overflow:hidden;display:block;"
                                    scrolling="no"
                                    frameborder="0"
                                    allowfullscreen="true"
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                </iframe>
                            </div>
                        </div>

                        <!-- Khung tóm tắt liên kết trực tiếp Fanpage (luôn hiển thị đẹp kể cả khi trình duyệt chặn iframe) -->
                        <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-between gap-3">
                            <div class="flex items-center gap-2.5 min-w-0">
                                <img src="https://lh3.googleusercontent.com/d/15GiKIwELeh8eLdTThQXJWgPMMMXrpCVu"
                                     data-gdrive-id="15GiKIwELeh8eLdTThQXJWgPMMMXrpCVu"
                                     data-fallback-text="LV"
                                     onerror="handleGDriveError(this)"
                                     alt="Nhôm Kính Linh Vấn"
                                     class="w-10 h-10 rounded-lg object-contain border border-slate-200 p-0.5 shrink-0">
                                <div class="min-w-0">
                                    <div class="text-xs font-bold text-slate-800 truncate">Nhôm Kính Linh Vấn - Đà Nẵng</div>
                                    <div class="text-[11px] text-slate-500 truncate">Cập nhật ảnh thực tế công trình bàn giao</div>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/nhomkinhlinhvan" target="_blank" rel="noopener noreferrer"
                               class="px-3 py-1.5 rounded-lg border border-brand text-brand hover:bg-brand hover:text-white text-xs font-semibold whitespace-nowrap transition">
                                Mở Facebook
                            </a>
                        </div>
                    </div>

                    <!-- Cột phải: Bản đồ Google Maps ngoài trang chủ -->
                    <div class="lg:col-span-7 bg-slate-50 rounded-2xl border border-slate-200 p-4 sm:p-5 flex flex-col justify-between">
                        <div>
                            <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                                <div class="flex items-center gap-2.5">
                                    <span class="w-9 h-9 rounded-full bg-brand text-white flex items-center justify-center shrink-0">
                                        <i class="fa-solid fa-map-location-dot text-sm"></i>
                                    </span>
                                    <div>
                                        <h3 class="text-sm font-bold text-slate-900">Bản Đồ Xưởng Nhôm Kính Linh Vấn</h3>
                                        <p class="text-xs text-slate-500">Khu Tái Định Cư Lệ Sơn - Hòa Tiến - Hòa Vang - TP Đà Nẵng</p>
                                    </div>
                                </div>
                                <a href="https://www.google.com/maps/search/?api=1&query=Khu+T%C3%A1i+%C4%90%E1%BB%8Bnh+C%C6%B0+L%E1%BB%87+S%C6%A1n+H%C3%B2a+Ti%E1%BA%BFn+H%C3%B2a+Vang+%C4%90%C3%A0+N%E1%BA%B5ng"
                                   target="_blank" rel="noopener noreferrer"
                                   class="px-3 py-1.5 rounded-lg bg-brand hover:bg-brand-light text-white text-xs font-semibold whitespace-nowrap transition">
                                    <i class="fa-solid fa-diamond-turn-right mr-1"></i>Chỉ đường
                                </a>
                            </div>

                            <!-- Bản đồ Google Maps trực tiếp -->
                            <div class="w-full h-[300px] sm:h-[365px] rounded-xl overflow-hidden border border-slate-200 bg-white">
                                <iframe
                                    title="Bản đồ Nhôm Kính Linh Vấn - Khu TĐC Lệ Sơn, Hòa Tiến, Hòa Vang, Đà Nẵng"
                                    src="https://maps.google.com/maps?q=Khu+T%C3%A1i+%C4%90%E1%BB%8Bnh+C%C6%B0+L%E1%BB%87+S%C6%A1n,+H%C3%B2a+Ti%E1%BA%BFn,+H%C3%B2a+Vang,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                                    width="100%"
                                    height="100%"
                                    style="border:0;display:block;"
                                    allowfullscreen=""
                                    loading="lazy"
                                    referrerpolicy="no-referrer-when-downgrade">
                                </iframe>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 10: ĐỐI TÁC CỦA CHÚNG TÔI (6 ẢNH ĐỐI TÁC GOOGLE DRIVE)     -->
        <!-- ================================================================= -->
        <section class="py-8 sm:py-10">
            <div class="ux-container">
                <div class="text-center mb-5">
                    <h2 class="ux-section-title text-lg sm:text-xl md:text-2xl font-extrabold text-brand uppercase">
                        Đối Tác Của Chúng Tôi
                    </h2>
                </div>

                <div class="grid grid-cols-3 md:grid-cols-6 gap-3 sm:gap-4">
                    <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" data-gdrive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" data-fallback-text="Doi Tac 1" onerror="handleGDriveError(this)" alt="Đối tác Nhôm Kính Linh Vấn 1" class="max-h-14 w-auto object-contain">
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" data-gdrive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" data-fallback-text="Doi Tac 2" onerror="handleGDriveError(this)" alt="Đối tác Nhôm Kính Linh Vấn 2" class="max-h-14 w-auto object-contain">
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" data-gdrive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" data-fallback-text="Doi Tac 3" onerror="handleGDriveError(this)" alt="Đối tác Nhôm Kính Linh Vấn 3" class="max-h-14 w-auto object-contain">
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" data-gdrive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" data-fallback-text="Doi Tac 4" onerror="handleGDriveError(this)" alt="Đối tác Nhôm Kính Linh Vấn 4" class="max-h-14 w-auto object-contain">
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-" data-gdrive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" data-fallback-text="Doi Tac 5" onerror="handleGDriveError(this)" alt="Đối tác Nhôm Kính Linh Vấn 5" class="max-h-14 w-auto object-contain">
                    </div>
                    <div class="bg-white rounded-xl border border-slate-200 p-3 flex items-center justify-center h-20 sm:h-24 shadow-sm hover:shadow transition">
                        <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" data-gdrive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" data-fallback-text="Doi Tac 6" onerror="handleGDriveError(this)" alt="Đối tác Nhôm Kính Linh Vấn 6" class="max-h-14 w-auto object-contain">
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ===================================================================== -->
    <!-- FOOTER (CHUẨN FLATSOME 4 CỘT)                                          -->
    <!-- ===================================================================== -->
    <footer class="bg-brand-dark text-slate-300 pt-10 pb-20 sm:pb-10">
        <div class="ux-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin liên hệ -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/15GiKIwELeh8eLdTThQXJWgPMMMXrpCVu"
                             data-gdrive-id="15GiKIwELeh8eLdTThQXJWgPMMMXrpCVu"
                             data-fallback-text="LINH VAN"
                             onerror="handleGDriveError(this)"
                             alt="Logo Nhôm Kính Linh Vấn"
                             class="h-10 w-auto bg-white rounded-lg p-1 object-contain">
                        <div class="font-extrabold text-white text-base">NHÔM KÍNH LINH VẤN</div>
                    </div>
                    <p class="text-xs leading-relaxed text-slate-300">
                        Chuyên tư vấn, thiết kế, gia công và thi công Cửa nhôm Xingfa, Cửa kính cường lực, Cầu thang kính, Phòng tắm kính, Kính ốp bếp uy tín hàng đầu tại Đà Nẵng.
                    </p>
                    <ul class="space-y-2 text-xs">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-0.5"></i>
                            <span>Khu Tái Định Cư Lệ Sơn - Hòa Tiến - Hòa Vang - TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-amber-400"></i>
                            <a href="tel:0333838181" class="font-bold text-white hover:text-amber-300">0333.838.181</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-amber-400"></i>
                            <a href="https://nhomkinhlinhvan.com" class="hover:text-amber-300">nhomkinhlinhvan.com</a>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Cửa nhôm Xingfa -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3">Cửa Nhôm Xingfa</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('1-canh')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa 1 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('2-canh')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa 2 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('3-canh')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa 3 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('4-canh')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa 4 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('xep-truot')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa 5 cánh / Xếp trượt</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3">Danh Mục Sản Phẩm</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham-xingfa" class="hover:text-amber-300 transition">Cửa nhôm Xingfa</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa nhựa lõi thép</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cửa kính tự động</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Cầu thang kính</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Kính ốp bếp</a></li>
                        <li><a href="#danh-muc-san-pham" class="hover:text-amber-300 transition">Phòng tắm kính</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên kết nhanh -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3">Hỗ Trợ Khách Hàng</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#gioi-thieu" class="hover:text-amber-300 transition">Giới thiệu Nhôm Kính Linh Vấn</a></li>
                        <li><a href="#cong-trinh" class="hover:text-amber-300 transition">Dự án đã thi công tại Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-300 transition">Bảng báo giá thi công mới nhất</a></li>
                        <li><a href="#tin-tuc" class="hover:text-amber-300 transition">Tin tức & Kinh nghiệm chọn cửa</a></li>
                        <li><a href="https://www.facebook.com/nhomkinhlinhvan" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition">Fanpage Facebook Chính Thức</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <div>Copyright © 2026 <strong class="text-white">Nhôm Kính Linh Vấn</strong> (nhomkinhlinhvan.com).</div>
                <div>Thiết kế chuẩn giao diện Flatsome UX Builder.</div>
            </div>
        </div>
    </footer>

    <!-- ===================================================================== -->
    <!-- BỘ NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH MOBILE & PC) -->
    <!-- ===================================================================== -->
    <!-- Dạng cột nổi gọn gàng bên phải trên máy tính & máy tính bảng -->
    <div class="hidden sm:flex fixed right-4 bottom-5 z-40 flex-col gap-2.5 items-end">
        <a href="https://zalo.me/0333838181" target="_blank" rel="noopener noreferrer"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white px-3.5 py-2.5 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center">Zalo</span>
            <span class="text-xs font-bold pr-1">Chat Zalo</span>
        </a>
        <a href="https://www.facebook.com/nhomkinhlinhvan" target="_blank" rel="noopener noreferrer"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3.5 py-2.5 rounded-full shadow-lg transition">
            <i class="fa-brands fa-facebook-f w-6 h-6 rounded-full bg-white text-[#1877F2] text-xs flex items-center justify-center"></i>
            <span class="text-xs font-bold pr-1">Facebook</span>
        </a>
        <a href="tel:0333838181"
           class="float-pulse flex items-center gap-2 bg-[#DC2626] hover:bg-red-700 text-white px-4 py-2.5 rounded-full shadow-lg transition">
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs font-extrabold">0333.838.181</span>
        </a>
    </div>

    <!-- Thanh liên hệ nổi cố định đáy màn hình trên điện thoại (không che nội dung, dễ bấm 1 chạm) -->
    <div class="sm:hidden fixed bottom-0 left-0 right-0 z-40 bg-white/95 backdrop-blur border-t border-slate-200 px-2 py-2 shadow-[0_-4px_15px_rgba(0,0,0,0.08)]">
        <div class="grid grid-cols-3 gap-2">
            <a href="https://zalo.me/0333838181" target="_blank" rel="noopener noreferrer"
               class="flex items-center justify-center gap-1.5 py-2 rounded-lg bg-[#0068FF] text-white font-bold text-xs shadow-sm">
                <span class="bg-white text-[#0068FF] px-1 rounded text-[10px] font-extrabold">Zalo</span>
                <span>Chat Zalo</span>
            </a>
            <a href="https://www.facebook.com/nhomkinhlinhvan" target="_blank" rel="noopener noreferrer"
               class="flex items-center justify-center gap-1.5 py-2 rounded-lg bg-[#1877F2] text-white font-bold text-xs shadow-sm">
                <i class="fa-brands fa-facebook-f text-xs"></i>
                <span>Facebook</span>
            </a>
            <a href="tel:0333838181"
               class="flex items-center justify-center gap-1.5 py-2 rounded-lg bg-[#DC2626] text-white font-bold text-xs shadow-sm">
                <i class="fa-solid fa-phone-volume text-xs"></i>
                <span>Hotline</span>
            </a>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- MODAL XEM NHANH SẢN PHẨM / BÀI VIẾT / THÔNG BÁO (KHÔNG DÙNG ALERT)    -->
    <!-- ===================================================================== -->
    <div id="appModal" class="fixed inset-0 z-50 hidden items-center justify-center bg-slate-900/60 p-4">
        <div class="bg-white rounded-2xl max-w-lg w-full max-h-[88vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="flex items-center justify-between px-5 py-3.5 border-b border-slate-100 sticky top-0 bg-white">
                <h3 id="modalTitle" class="text-sm sm:text-base font-extrabold text-brand pr-4">Thông tin chi tiết</h3>
                <button type="button" onclick="closeModal()" aria-label="Đóng cửa sổ"
                    class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="modalBody" class="p-5 text-sm text-slate-700 space-y-3"></div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- JAVASCRIPT: DỮ LIỆU SẢN PHẨM, DỰ ÁN, BÀI VIẾT, BANNER & TƯƠNG TÁC     -->
    <!-- ===================================================================== -->
    <script>
        /* -------------------------------------------------------------------
         * 1. HÀM XỬ LÝ DỰ PHÒNG ẢNH GOOGLE DRIVE (CHỐNG LỖI ẢNH VỠ)
         * ------------------------------------------------------------------- */
        function handleGDriveError(img) {
            try {
                const fileId = img.getAttribute('data-gdrive-id');
                const fallbackText = encodeURIComponent(img.getAttribute('data-fallback-text') || 'Nhom Kinh Linh Van');
                const step = parseInt(img.getAttribute('data-retry-step') || '0', 10);

                if (step === 0 && fileId) {
                    img.setAttribute('data-retry-step', '1');
                    img.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
                } else {
                    img.onerror = null;
                    img.src = 'https://placehold.co/600x450/0B3C68/FFFFFF?text=' + fallbackText;
                }
            } catch (err) {
                img.onerror = null;
            }
        }

        function gdriveUrl(id) {
            return 'https://lh3.googleusercontent.com/d/' + id;
        }

        /* -------------------------------------------------------------------
         * 2. DỮ LIỆU SẢN PHẨM CỬA NHÔM XINGFA (ĐÚNG ẢNH DRIVE + GIÁ & GIẢM %)
         * ------------------------------------------------------------------- */
        const productsData = [
            {
                id: 'xingfa-1-canh',
                name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
                category: '1-canh',
                imageId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
                oldPrice: '1.950.000 ₫',
                salePrice: '1.550.000 ₫/m²',
                discount: '-21%',
                spec: 'Nhôm Xingfa hệ 55 dày 2.0mm, kính cường lực 8mm, phụ kiện Kinlong/Draho chính hãng, kín khít cách âm cao.'
            },
            {
                id: 'xingfa-2-canh',
                name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
                category: '2-canh',
                imageId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                oldPrice: '2.100.000 ₫',
                salePrice: '1.650.000 ₫/m²',
                discount: '-21%',
                spec: 'Thiết kế mở quay 2 cánh rộng thoáng cho cửa chính, ban công, sơn tĩnh điện bền màu chịu khí hậu biển Đà Nẵng.'
            },
            {
                id: 'xingfa-3-canh',
                name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
                category: '3-canh',
                imageId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
                oldPrice: '2.200.000 ₫',
                salePrice: '1.750.000 ₫/m²',
                discount: '-20%',
                spec: 'Kết cấu khung nhôm Xingfa nhập khẩu chắc chắn, gioăng EPDM kép chống nước tuyệt đối, vận hành êm ái.'
            },
            {
                id: 'xingfa-4-canh',
                name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
                category: '4-canh',
                imageId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                oldPrice: '2.350.000 ₫',
                salePrice: '1.850.000 ₫/m²',
                discount: '-21%',
                spec: 'Lựa chọn hàng đầu cho cửa mặt tiền nhà phố, biệt thự; tăng tối đa độ mở thông thủy và vẻ sang trọng hiện đại.'
            },
            {
                id: 'xingfa-xep-truot',
                name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
                category: 'xep-truot',
                imageId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                oldPrice: '2.500.000 ₫',
                salePrice: '1.950.000 ₫/m²',
                discount: '-22%',
                spec: 'Hệ nhôm xếp trượt 5 cánh – 6 cánh chuyên dụng cho không gian mở, resort, khách sạn, tiết kiệm diện tích tối đa.'
            },
            {
                id: 'xingfa-so-hat-2-canh',
                name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
                category: 'cua-so',
                imageId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                oldPrice: '1.750.000 ₫',
                salePrice: '1.350.000 ₫/m²',
                discount: '-23%',
                spec: 'Cửa sổ mở hất chống hắt mưa hiệu quả, thanh định vị chống gió đập, phù hợp nhà cao tầng và khí hậu miền Trung.'
            }
        ];

        /* -------------------------------------------------------------------
         * 3. DỮ LIỆU 6 DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
         * ------------------------------------------------------------------- */
        const projectsData = [
            {
                title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
                imageId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
                location: 'TP. Đà Nẵng',
                scope: 'Thi công toàn bộ hệ cửa nhôm Xingfa, vách kính mặt dựng và phòng tắm kính.'
            },
            {
                title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
                imageId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
                location: 'Quảng Nam - Đà Nẵng',
                scope: 'Gia công & lắp đặt hệ cửa đi xếp trượt nhôm Xingfa, lan can kính khu nghỉ dưỡng 4 sao.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
                imageId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
                location: 'TP. Đà Nẵng',
                scope: 'Hạng mục cửa nhôm kính cách âm chống gió biển, cửa kính cường lực sảnh chính.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
                imageId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
                location: 'TP. Đà Nẵng',
                scope: 'Thi công cửa sổ mở hất Xingfa, vách kính cường lực và cabin phòng tắm kính.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
                imageId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
                location: 'TP. Đà Nẵng',
                scope: 'Lắp đặt đồng bộ cửa nhôm Xingfa cao cấp, kính cường lực chịu lực tiêu chuẩn khách sạn.'
            },
            {
                title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
                imageId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
                location: 'Ven biển TP. Đà Nẵng',
                scope: 'Cung cấp & thi công hệ nhôm Xingfa sơn tĩnh điện chống ăn mòn muối biển, phụ kiện đồng bộ.'
            }
        ];

        /* -------------------------------------------------------------------
         * 4. DỮ LIỆU BÀI VIẾT TRANG CHỦ
         * ------------------------------------------------------------------- */
        const newsData = [
            {
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu mưa bão tại Đà Nẵng không?',
                category: 'tu-van',
                date: '18/11/2026',
                imageId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                excerpt: 'Tìm hiểu khả năng chống gió bão, chống thấm nước và chống ăn mòn hơi biển của nhôm Xingfa nhập khẩu.',
                content: 'Nhôm Xingfa hệ 55 và hệ 93 sở hữu cấu trúc khoang rỗng có gân gia cường chịu lực cực tốt, kết hợp hệ gioăng cao su EPDM kín khít và keo silicone chuyên dụng giúp ngăn nước mưa tạt hiệu quả. Bề mặt sơn tĩnh điện cao cấp giúp cửa giữ màu bền bỉ trên 15 năm ngay cả tại các khu vực ven biển Đà Nẵng.'
            },
            {
                title: 'Cách phân biệt cửa nhôm Xingfa nhập khẩu và hệ nhôm vát cạnh',
                category: 'bao-gia',
                date: '12/11/2026',
                imageId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                excerpt: 'So sánh chi tiết độ dày thanh nhôm, mức giá từ 1.350.000đ - 1.550.000đ/m² để chọn đúng nhu cầu.',
                content: 'Nhôm Xingfa nhập khẩu có độ dày từ 1.4mm đến 2.0mm, giá tham khảo tại Nhôm Kính Linh Vấn chỉ từ 1.550.000đ/m², phù hợp cửa mặt tiền và công trình yêu cầu độ chắc chắn cao. Hệ vát cạnh giá chỉ từ 1.350.000đ/m², đường nét thanh mảnh hiện đại, tiết kiệm chi phí cho nhà ở dân dụng.'
            },
            {
                title: 'Kinh nghiệm lắp đặt cầu thang kính và kính ốp bếp bền đẹp theo thời gian',
                category: 'ky-thuat',
                date: '05/11/2026',
                imageId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
                excerpt: 'Những lưu ý quan trọng về độ dày kính cường lực, phụ kiện inox 304 và kỹ thuật đi keo chống ố.',
                content: 'Khi thi công cầu thang kính và phòng tắm kính, nên ưu tiên kính cường lực dày 10mm - 12mm cùng bộ trụ, kẹp inox 304 chống gỉ tuyệt đối. Đối với kính ốp bếp, sử dụng kính tôi 8mm sơn hấp nhiệt giúp bề mặt sáng bóng, chịu nhiệt bếp nấu tốt và lau chùi dầu mỡ chỉ trong vài giây.'
            },
            {
                title: 'Nên chọn phụ kiện Draho, Kinlong hay Candy cho cửa nhôm Xingfa?',
                category: 'bao-gia',
                date: '28/10/2026',
                imageId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                excerpt: 'Đánh giá ưu nhược điểm các dòng phụ kiện đồng bộ phổ biến nhất hiện nay tại Đà Nẵng.',
                content: 'Phụ kiện chiếm vai trò quyết định đến độ êm ái và tuổi thọ bộ cửa. Kinlong nổi tiếng ổn định, Draho có thiết kế sắc sảo chống gỉ tốt, còn dòng Candy mang lại vẻ đẹp hiện đại với tay nắm màu bạc/đen sang trọng. Tại Nhôm Kính Linh Vấn, khách hàng được xem mẫu thực tế trước khi thi công.'
            }
        ];

        /* -------------------------------------------------------------------
         * 5. RENDER SẢN PHẨM (2 CỘT TRÊN MOBILE, KHÔNG TRÀN CHỮ, CÓ GIÁ & -% GÓC TRÊN TRÁI)
         * ------------------------------------------------------------------- */
        let currentCategoryFilter = 'all';
        let currentSearchKeyword = '';

        function renderProducts() {
            const grid = document.getElementById('productGrid');
            const noMsg = document.getElementById('noProductMessage');
            if (!grid) return;

            const filtered = productsData.filter(item => {
                const matchCat = currentCategoryFilter === 'all' || item.category === currentCategoryFilter;
                const matchKey = !currentSearchKeyword || item.name.toLowerCase().includes(currentSearchKeyword.toLowerCase());
                return matchCat && matchKey;
            });

            if (filtered.length === 0) {
                grid.innerHTML = '';
                noMsg.classList.remove('hidden');
                return;
            }

            noMsg.classList.add('hidden');
            grid.innerHTML = filtered.map(item => `
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand/40 transition flex flex-col">
                    <!-- Ảnh sản phẩm + Giảm giá % ở góc trên bên trái -->
                    <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <span class="absolute top-2 left-2 z-10 bg-brand-sale text-white text-[11px] sm:text-xs font-extrabold px-2 py-0.5 rounded-md shadow-sm">
                            ${item.discount}
                        </span>
                        <img
                            src="${gdriveUrl(item.imageId)}"
                            data-gdrive-id="${item.imageId}"
                            data-fallback-text="${item.name}"
                            onerror="handleGDriveError(this)"
                            alt="${item.name}"
                            class="w-full h-full object-cover hover:scale-105 transition duration-300 cursor-pointer"
                            onclick="openProductModal('${item.id}')"
                        >
                    </div>

                    <!-- Thông tin sản phẩm: Tên đầy đủ không bị cắt hay tràn ra ngoài -->
                    <div class="p-2.5 sm:p-4 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <h3 onclick="openProductModal('${item.id}')"
                                class="text-[12.5px] sm:text-sm font-bold text-slate-800 hover:text-brand leading-snug break-words cursor-pointer">
                                ${item.name}
                            </h3>
                        </div>

                        <div class="space-y-2 pt-1">
                            <!-- Giá gốc gạch ngang & Giá khuyến mãi -->
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-[13px] sm:text-base font-extrabold text-brand-sale">${item.salePrice}</span>
                                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${item.oldPrice}</span>
                            </div>

                            <!-- Nút hành động gọn gàng cho cả 2 cột mobile -->
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-1.5">
                                <button type="button" onclick="openProductModal('${item.id}')"
                                    class="w-full py-1.5 px-2 rounded-lg border border-brand/30 text-brand hover:bg-brand-soft text-[11px] sm:text-xs font-semibold transition">
                                    Xem nhanh
                                </button>
                                <button type="button" onclick="prefillQuote('${item.name.replace(/'/g, "\\'")}')"
                                    class="w-full py-1.5 px-2 rounded-lg bg-brand hover:bg-brand-light text-white text-[11px] sm:text-xs font-semibold transition">
                                    Báo giá
                                </button>
                            </div>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterProducts(cat) {
            currentCategoryFilter = cat;
            document.querySelectorAll('.filter-tab').forEach(btn => {
                if (btn.getAttribute('data-filter') === cat) {
                    btn.className = 'filter-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-brand text-white transition';
                } else {
                    btn.className = 'filter-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition';
                }
            });
            renderProducts();
        }

        function triggerProductSearch(isMobile) {
            const input = document.getElementById(isMobile ? 'mobileSearchInput' : 'desktopSearchInput');
            currentSearchKeyword = (input ? input.value : '').trim();
            currentCategoryFilter = 'all';
            filterProducts('all');
            const target = document.getElementById('san-pham-xingfa');
            if (target) target.scrollIntoView({ behavior: 'smooth' });
        }

        function resetSearch() {
            currentSearchKeyword = '';
            const dInput = document.getElementById('desktopSearchInput');
            const mInput = document.getElementById('mobileSearchInput');
            if (dInput) dInput.value = '';
            if (mInput) mInput.value = '';
            filterProducts('all');
        }

        /* -------------------------------------------------------------------
         * 6. RENDER DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
         * ------------------------------------------------------------------- */
        function renderProjects() {
            const grid = document.getElementById('projectGrid');
            if (!grid) return;

            grid.innerHTML = projectsData.map((proj, index) => `
                <article onclick="openProjectModal(${index})"
                    class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition cursor-pointer flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${gdriveUrl(proj.imageId)}"
                            data-gdrive-id="${proj.imageId}"
                            data-fallback-text="Du An Da Nang"
                            onerror="handleGDriveError(this)"
                            alt="${proj.title}"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between gap-2">
                        <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand leading-snug">
                            ${proj.title}
                        </h3>
                        <div class="flex items-center justify-between text-[11px] sm:text-xs text-slate-500 pt-1 border-t border-slate-100">
                            <span><i class="fa-solid fa-location-dot text-brand mr-1"></i>${proj.location}</span>
                            <span class="text-brand font-semibold">Xem chi tiết</span>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /* -------------------------------------------------------------------
         * 7. RENDER DANH MỤC BÀI VIẾT TRANG CHỦ
         * ------------------------------------------------------------------- */
        function renderNews(cat = 'all') {
            const grid = document.getElementById('newsGrid');
            if (!grid) return;

            const filtered = cat === 'all' ? newsData : newsData.filter(n => n.category === cat);
            grid.innerHTML = filtered.map((post, idx) => {
                const realIdx = newsData.indexOf(post);
                return `
                <article onclick="openNewsModal(${realIdx})"
                    class="group bg-slate-50 rounded-xl border border-slate-200 overflow-hidden hover:shadow-md hover:bg-white transition cursor-pointer flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-200">
                        <img
                            src="${gdriveUrl(post.imageId)}"
                            data-gdrive-id="${post.imageId}"
                            data-fallback-text="Tin Tuc"
                            onerror="handleGDriveError(this)"
                            alt="${post.title}"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <div class="text-[11px] text-slate-400 mb-1"><i class="fa-regular fa-calendar mr-1"></i>${post.date}</div>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand leading-snug mb-1.5">
                                ${post.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">${post.excerpt}</p>
                        </div>
                        <div class="text-xs font-semibold text-brand pt-2">
                            Đọc tiếp <i class="fa-solid fa-arrow-right text-[10px] ml-1"></i>
                        </div>
                    </div>
                </article>
                `;
            }).join('');
        }

        function filterNews(cat) {
            document.querySelectorAll('.news-tab').forEach(btn => {
                if (btn.getAttribute('data-news-cat') === cat) {
                    btn.className = 'news-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-brand text-white transition';
                } else {
                    btn.className = 'news-tab px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-semibold bg-slate-100 text-slate-700 hover:bg-brand-soft transition';
                }
            });
            renderNews(cat);
        }

        /* -------------------------------------------------------------------
         * 8. HỆ THỐNG MODAL CHI TIẾT (SẢN PHẨM, DỰ ÁN, BÀI VIẾT, XÁC NHẬN FORM)
         * ------------------------------------------------------------------- */
        function openModal(title, htmlContent) {
            document.getElementById('modalTitle').textContent = title;
            document.getElementById('modalBody').innerHTML = htmlContent;
            const modal = document.getElementById('appModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeModal() {
            const modal = document.getElementById('appModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function openProductModal(productId) {
            const item = productsData.find(p => p.id === productId);
            if (!item) return;
            openModal(item.name, `
                <div class="relative rounded-xl overflow-hidden bg-slate-100 aspect-[4/3]">
                    <span class="absolute top-2.5 left-2.5 bg-brand-sale text-white text-xs font-extrabold px-2.5 py-1 rounded-md">${item.discount}</span>
                    <img src="${gdriveUrl(item.imageId)}" data-gdrive-id="${item.imageId}" data-fallback-text="${item.name}" onerror="handleGDriveError(this)" alt="${item.name}" class="w-full h-full object-cover">
                </div>
                <div class="flex items-baseline gap-3">
                    <span class="text-xl font-extrabold text-brand-sale">${item.salePrice}</span>
                    <span class="text-sm text-slate-400 line-through">${item.oldPrice}</span>
                </div>
                <p class="text-sm text-slate-600 leading-relaxed">${item.spec}</p>
                <div class="bg-brand-soft rounded-xl p-3 text-xs text-slate-700 space-y-1">
                    <div><strong>Đơn vị thi công:</strong> Nhôm Kính Linh Vấn - Đà Nẵng</div>
                    <div><strong>Hotline / Zalo:</strong> <a href="tel:0333838181" class="font-bold text-brand">0333.838.181</a></div>
                    <div><strong>Ưu đãi:</strong> Miễn phí khảo sát đo đạc & tư vấn tại công trình</div>
                </div>
                <div class="grid grid-cols-2 gap-2.5 pt-1">
                    <a href="tel:0333838181" class="py-2.5 rounded-lg bg-brand-sale text-white text-center text-xs sm:text-sm font-bold hover:bg-red-700 transition">Gọi 0333.838.181</a>
                    <button type="button" onclick="closeModal(); prefillQuote('${item.name.replace(/'/g, "\\'")}')" class="py-2.5 rounded-lg bg-brand text-white text-xs sm:text-sm font-bold hover:bg-brand-light transition">Đăng ký báo giá</button>
                </div>
            `);
        }

        function openProjectModal(index) {
            const proj = projectsData[index];
            if (!proj) return;
            openModal(proj.title, `
                <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
                    <img src="${gdriveUrl(proj.imageId)}" data-gdrive-id="${proj.imageId}" data-fallback-text="Du An" onerror="handleGDriveError(this)" alt="${proj.title}" class="w-full h-full object-cover">
                </div>
                <div class="text-xs text-slate-500"><i class="fa-solid fa-location-dot text-brand mr-1"></i>Khu vực: <strong>${proj.location}</strong></div>
                <p class="text-sm text-slate-700 leading-relaxed">${proj.scope}</p>
                <div class="pt-2 flex justify-end">
                    <button type="button" onclick="closeModal(); prefillQuote('Tư vấn công trình tương tự: ${proj.title.replace(/'/g, "\\'")}')" class="px-4 py-2 rounded-lg bg-brand text-white text-xs font-bold hover:bg-brand-light transition">
                        Liên hệ tư vấn công trình
                    </button>
                </div>
            `);
        }

        function openNewsModal(index) {
            const post = newsData[index];
            if (!post) return;
            openModal(post.title, `
                <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/10]">
                    <img src="${gdriveUrl(post.imageId)}" data-gdrive-id="${post.imageId}" data-fallback-text="Bai Viet" onerror="handleGDriveError(this)" alt="${post.title}" class="w-full h-full object-cover">
                </div>
                <div class="text-xs text-slate-400">Đăng ngày ${post.date} • Nhôm Kính Linh Vấn</div>
                <p class="text-sm text-slate-700 leading-relaxed">${post.content}</p>
                <div class="bg-slate-50 border border-slate-200 rounded-xl p-3 text-xs text-slate-600">
                    Cần tư vấn chi tiết hơn cho công trình nhà bạn tại Đà Nẵng? Gọi ngay <a href="tel:0333838181" class="font-bold text-brand">0333.838.181</a> để được hỗ trợ miễn phí.
                </div>
            `);
        }

        /* -------------------------------------------------------------------
         * 9. ĐIỀN SẴN FORM BÁO GIÁ & XỬ LÝ GỬI YÊU CẦU
         * ------------------------------------------------------------------- */
        function prefillQuote(itemName) {
            const note = document.getElementById('qNote');
            const cat = document.getElementById('qCategory');
            if (cat) {
                for (let i = 0; i < cat.options.length; i++) {
                    if (itemName.toLowerCase().includes(cat.options[i].value.toLowerCase().split(' ')[0])) {
                        cat.selectedIndex = i;
                        break;
                    }
                }
            }
            if (note) {
                note.value = 'Tôi muốn nhận báo giá chi tiết cho: ' + itemName;
            }
            const formSec = document.getElementById('form-bao-gia');
            if (formSec) formSec.scrollIntoView({ behavior: 'smooth' });
        }

        document.getElementById('quoteForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const category = document.getElementById('qCategory').value;
            const area = document.getElementById('qArea').value.trim() || 'Chưa xác định';

            openModal('Gửi Yêu Cầu Báo Giá Thành Công', `
                <div class="text-center py-2 space-y-3">
                    <div class="w-12 h-12 rounded-full bg-green-100 text-green-600 flex items-center justify-center mx-auto text-xl">
                        <i class="fa-solid fa-check"></i>
                    </div>
                    <p class="text-sm text-slate-700">
                        Cảm ơn <strong>${name}</strong>! Nhôm Kính Linh Vấn đã tiếp nhận yêu cầu báo giá hạng mục <strong>${category}</strong> (${area}).
                    </p>
                    <p class="text-xs text-slate-500">
                        Kỹ thuật viên sẽ gọi lại qua số <strong>${phone}</strong> trong thời gian sớm nhất. Bạn cũng có thể nhắn trực tiếp qua Zalo <strong>0333.838.181</strong>.
                    </p>
                    <div class="pt-2 flex justify-center gap-2">
                        <a href="https://zalo.me/0333838181" target="_blank" rel="noopener noreferrer" class="px-4 py-2 rounded-lg bg-[#0068FF] text-white text-xs font-bold">Nhắn Zalo ngay</a>
                        <button type="button" onclick="closeModal()" class="px-4 py-2 rounded-lg bg-slate-100 text-slate-700 text-xs font-bold">Đóng</button>
                    </div>
                </div>
            `);
            this.reset();
        });

        /* -------------------------------------------------------------------
         * 10. BANNER TỰ TRƯỢT (2 SLIDE BẰNG NHAU + VUỐT CẢM ỨNG MOBILE)
         * ------------------------------------------------------------------- */
        let currentBanner = 0;
        const totalBanners = 2;
        let bannerInterval = null;

        function updateBannerUI() {
            const track = document.getElementById('heroBannerTrack');
            if (track) {
                track.style.transform = `translateX(-${currentBanner * 100}%)`;
            }
            for (let i = 0; i < totalBanners; i++) {
                const dot = document.getElementById('bannerDot' + i);
                if (!dot) continue;
                if (i === currentBanner) {
                    dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                } else {
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
                }
            }
        }

        function goToBanner(idx) {
            currentBanner = (idx + totalBanners) % totalBanners;
            updateBannerUI();
            restartBannerTimer();
        }

        function restartBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                currentBanner = (currentBanner + 1) % totalBanners;
                updateBannerUI();
            }, 5000);
        }

        document.getElementById('bannerPrev').addEventListener('click', () => goToBanner(currentBanner - 1));
        document.getElementById('bannerNext').addEventListener('click', () => goToBanner(currentBanner + 1));

        // Hỗ trợ vuốt trái/phải banner trên điện thoại
        let touchStartX = 0;
        const viewportEl = document.getElementById('heroBannerViewport');
        viewportEl.addEventListener('touchstart', (e) => {
            touchStartX = e.changedTouches[0].screenX;
        }, { passive: true });
        viewportEl.addEventListener('touchend', (e) => {
            const diff = e.changedTouches[0].screenX - touchStartX;
            if (Math.abs(diff) > 45) {
                goToBanner(diff < 0 ? currentBanner + 1 : currentBanner - 1);
            }
        }, { passive: true });

        /* -------------------------------------------------------------------
         * 11. MENU NGĂN KÉO ĐIỆN THOẠI & TÌM KIẾM NHANH
         * ------------------------------------------------------------------- */
        const mobileDrawer = document.getElementById('mobileDrawer');
        const mobileBackdrop = document.getElementById('mobileDrawerBackdrop');

        function openDrawer() {
            mobileBackdrop.classList.remove('hidden');
            mobileDrawer.classList.remove('-translate-x-full');
        }
        function closeDrawer() {
            mobileBackdrop.classList.add('hidden');
            mobileDrawer.classList.add('-translate-x-full');
        }
        function toggleMobileSub(id, btn) {
            const sub = document.getElementById(id);
            const icon = btn.querySelector('i');
            if (sub) sub.classList.toggle('hidden');
            if (icon) icon.classList.toggle('rotate-180');
        }

        document.getElementById('mobileMenuBtn').addEventListener('click', openDrawer);
        document.getElementById('closeMobileDrawer').addEventListener('click', closeDrawer);
        mobileBackdrop.addEventListener('click', closeDrawer);

        document.getElementById('mobileSearchToggle').addEventListener('click', () => {
            document.getElementById('mobileSearchBar').classList.toggle('hidden');
        });

        document.getElementById('desktopSearchInput').addEventListener('keydown', (e) => {
            if (e.key === 'Enter') triggerProductSearch(false);
        });
        document.getElementById('mobileSearchInput').addEventListener('keydown', (e) => {
            if (e.key === 'Enter') triggerProductSearch(true);
        });

        // Đóng modal khi bấm ra ngoài nền tối
        document.getElementById('appModal').addEventListener('click', (e) => {
            if (e.target === e.currentTarget) closeModal();
        });

        /* -------------------------------------------------------------------
         * 12. KHỞI TẠO TRANG KHI TẢI XONG
         * ------------------------------------------------------------------- */
        window.addEventListener('DOMContentLoaded', () => {
            renderProducts();
            renderProjects();
            renderNews('all');
            updateBannerUI();
            restartBannerTimer();
        });
    </script>
</body>
</html>
