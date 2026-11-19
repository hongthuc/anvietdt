<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG AN VIỆT DT | anvietdt.com</title>
  <meta name="description" content="CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG AN VIỆT DT chuyên thiết kế kiến trúc, thi công xây dựng trọn gói nhà phố, biệt thự, căn hộ, khách sạn, nội thất tại Đà Nẵng. Hotline: 0982.212.347.">
  <meta name="keywords" content="An Việt DT, anvietdt.com, thiết kế xây dựng Đà Nẵng, xây nhà trọn gói Đà Nẵng, thi công phần thô, thi công nội thất Đà Nẵng">

  <!-- Open Graph / Thumbnail chia sẻ liên kết dùng ảnh Logo chính thức -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="AN VIỆT DT - anvietdt.com">
  <meta property="og:title" content="CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG AN VIỆT DT | anvietdt.com">
  <meta property="og:description" content="Chuyên Thiết Kế Kiến Trúc – Thi Công Xây Dựng Trọn Gói – Nội Thất tại Đà Nẵng. Địa chỉ: Tổ 3, Thôn Đồng Trì, Xã Thăng Trường, TP Đà Nẵng. Hotline: 0982.212.347.">
  <meta property="og:url" content="https://anvietdt.com">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX">
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX">
  <meta property="og:image:alt" content="Logo CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG AN VIỆT DT">

  <!-- Twitter / Zalo Share Card -->
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG AN VIỆT DT">
  <meta name="twitter:description" content="Thiết kế & Thi công xây dựng trọn gói uy tín tại Đà Nẵng - Hotline: 0982.212.347">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX">

  <!-- Favicon dùng ảnh Logo -->
  <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX">
  <link rel="apple-touch-icon" href="https://lh3.googleusercontent.com/d/1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX">

  <!-- Font Inter hiện đại, dễ đọc và chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

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
              primary: '#0F3057',   /* Xanh kiến trúc chủ đạo hài hòa logo */
              dark: '#091E38',
              light: '#1B497A',
              accent: '#C98A2B',    /* Vàng đồng sang trọng phong cách xây dựng */
              accentDark: '#A66F1E',
              soft: '#F5F7FA'
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Thiết lập chống tràn viền ngang và lệch sang phải tuyệt đối */
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
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
    }

    img, iframe, svg, video {
      max-width: 100%;
    }

    /* Chiều ngang chuẩn Flatsome: Mobile vừa khít lề an toàn, Desktop đúng 95% màn hình */
    .av-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 640px) {
      .av-container {
        padding-left: 18px;
        padding-right: 18px;
      }
    }

    @media (min-width: 1024px) {
      .av-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Banner tự trượt 2 ảnh bằng kích thước, đảm bảo chữ nằm trọn bên trong, cách xa viền */
    .hero-slider-wrapper {
      position: relative;
      width: 100%;
      overflow: hidden;
      background-color: #091E38;
    }

    .hero-slides-grid {
      display: grid;
      grid-template-columns: 1fr;
      width: 100%;
    }

    .hero-slide {
      grid-area: 1 / 1;
      position: relative;
      width: 100%;
      min-height: 330px;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    @media (min-width: 640px) {
      .hero-slide {
        min-height: 400px;
      }
    }

    @media (min-width: 1024px) {
      .hero-slide {
        min-height: 490px;
      }
    }

    .hero-slide.active {
      opacity: 1;
      visibility: visible;
      z-index: 2;
    }

    /* Gạch chân tiêu đề chuẩn phong cách Flatsome */
    .flatsome-heading {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }

    .flatsome-heading::after {
      content: '';
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background-color: #C98A2B;
      border-radius: 999px;
    }

    .flatsome-heading-left::after {
      left: 0;
      transform: none;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes pulseRing {
      0% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.55); }
      70% { box-shadow: 0 0 0 12px rgba(220, 38, 38, 0); }
      100% { box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
    }

    .hotline-pulse {
      animation: pulseRing 2s infinite;
    }

    /* Dropdown menu mượt mà trên máy tính */
    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
    }

    .nav-item:hover .nav-dropdown,
    .nav-item:focus-within .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ==================== TOP BAR THÔNG TIN GỌN GÀNG ==================== -->
  <div class="bg-brand-primary text-white text-xs border-b border-white/10">
    <div class="av-container py-2 flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <a href="tel:0982212347" class="inline-flex items-center gap-1.5 hover:text-brand-accent transition-colors font-medium">
          <svg class="w-3.5 h-3.5 text-brand-accent shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
          <span>Hotline: 0982.212.347</span>
        </a>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="hidden sm:inline-flex items-center gap-1.5 text-slate-200">
          <svg class="w-3.5 h-3.5 text-brand-accent shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          <span>Tổ 3, Thôn Đồng Trì, Xã Thăng Trường, TP Đà Nẵng</span>
        </span>
      </div>
      <div class="hidden md:flex items-center gap-4 text-slate-200">
        <span>Website: <strong class="text-white font-semibold">anvietdt.com</strong></span>
        <a href="https://www.facebook.com/profile.php?id=100088883929336&locale=vi_VN" target="_blank" rel="noopener noreferrer" class="hover:text-brand-accent transition-colors font-medium">
          Fanpage Facebook
        </a>
      </div>
    </div>
  </div>

  <!-- ==================== HEADER CHÍNH (KHÔNG CÓ NÚT GỌI NGAY, MENU 1 HÀNG GỌN) ==================== -->
  <header class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm w-full">
    <div class="av-container py-2.5 flex items-center justify-between gap-3">
      <!-- Logo chỉnh gọn nhỏ lại -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0">
        <img
          src="https://lh3.googleusercontent.com/d/1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX"
          data-fallback="https://drive.google.com/thumbnail?id=1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX&sz=w600"
          onerror="handleImgError(this, 'AN VIET DT')"
          alt="Logo Công ty TNHH Thiết Kế và Xây Dựng An Việt DT"
          class="h-10 sm:h-11 lg:h-12 w-auto max-w-[140px] object-contain rounded"
        >
        <div class="leading-tight">
          <div class="text-xs sm:text-sm font-extrabold text-brand-primary tracking-tight uppercase">AN VIỆT DT</div>
          <div class="text-[10px] sm:text-[11px] font-medium text-slate-500">Thiết Kế &amp; Xây Dựng</div>
        </div>
      </a>

      <!-- Menu máy tính viết liền trên 1 hàng, chữ nhỏ gọn, không xuống dòng -->
      <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-3 xl:gap-5" aria-label="Menu chính">
        <a href="#trang-chu" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-wide text-brand-primary hover:text-brand-accent transition-colors py-2">
          Trang chủ
        </a>
        <a href="#gioi-thieu" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-wide text-slate-700 hover:text-brand-accent transition-colors py-2">
          Giới thiệu
        </a>

        <!-- Dropdown Lĩnh vực hoạt động (theo web mẫu tintruongthinh.com) -->
        <div class="relative nav-item">
          <a href="#linh-vuc" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-wide text-slate-700 hover:text-brand-accent transition-colors py-2 inline-flex items-center gap-1">
            <span>Lĩnh vực hoạt động</span>
            <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 9l-7 7-7-7"/></svg>
          </a>
          <div class="nav-dropdown absolute left-0 top-full w-60 bg-white border border-slate-200 rounded-lg shadow-lg py-1.5 z-50">
            <a href="#linh-vuc" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-soft hover:text-brand-primary font-medium">Thiết kế Kiến trúc – Nội thất</a>
            <a href="#linh-vuc" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-soft hover:text-brand-primary font-medium">Thi công phần thô</a>
            <a href="#linh-vuc" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-soft hover:text-brand-primary font-medium">Thi công hoàn thiện</a>
            <a href="#linh-vuc" class="block px-4 py-2 text-[13px] text-slate-700 hover:bg-brand-soft hover:text-brand-primary font-medium">Thi công nội thất</a>
          </div>
        </div>

        <a href="#cong-trinh-thuc-te" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-wide text-slate-700 hover:text-brand-accent transition-colors py-2">
          Công trình thực tế
        </a>
        <a href="#du-an-da-nang" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-wide text-slate-700 hover:text-brand-accent transition-colors py-2">
          Dự án Đà Nẵng
        </a>
        <a href="#bao-gia" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-wide text-slate-700 hover:text-brand-accent transition-colors py-2">
          Báo giá
        </a>
        <a href="#doi-tac" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-wide text-slate-700 hover:text-brand-accent transition-colors py-2">
          Đối tác
        </a>
        <a href="#tin-tuc" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-wide text-slate-700 hover:text-brand-accent transition-colors py-2">
          Tin tức
        </a>
        <a href="#lien-he" class="whitespace-nowrap text-[12px] xl:text-[13px] font-semibold uppercase tracking-wide text-slate-700 hover:text-brand-accent transition-colors py-2">
          Liên hệ
        </a>
      </nav>

      <!-- Nút mở menu trên điện thoại / máy tính bảng -->
      <button
        id="mobileMenuBtn"
        type="button"
        aria-label="Mở danh mục điều hướng"
        class="lg:hidden inline-flex items-center justify-center p-2.5 rounded-lg border border-slate-200 text-brand-primary hover:bg-brand-soft transition-colors"
      >
        <svg id="menuIconOpen" class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/></svg>
        <svg id="menuIconClose" class="w-5 h-5 hidden" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
      </button>
    </div>

    <!-- Menu trượt xuống trên điện thoại -->
    <div id="mobileMenuPanel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="av-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-slate-700">
        <a href="#trang-chu" class="mobile-nav-link py-2.5 px-2 hover:text-brand-accent">Trang chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-link py-2.5 px-2 hover:text-brand-accent">Giới thiệu</a>
        <a href="#linh-vuc" class="mobile-nav-link py-2.5 px-2 hover:text-brand-accent">Lĩnh vực hoạt động</a>
        <a href="#cong-trinh-thuc-te" class="mobile-nav-link py-2.5 px-2 hover:text-brand-accent">Công trình thực tế</a>
        <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 px-2 hover:text-brand-accent">Dự án Đà Nẵng</a>
        <a href="#bao-gia" class="mobile-nav-link py-2.5 px-2 hover:text-brand-accent">Báo giá xây dựng</a>
        <a href="#doi-tac" class="mobile-nav-link py-2.5 px-2 hover:text-brand-accent">Đối tác</a>
        <a href="#tin-tuc" class="mobile-nav-link py-2.5 px-2 hover:text-brand-accent">Tin tức &amp; Kinh nghiệm</a>
        <a href="#lien-he" class="mobile-nav-link py-2.5 px-2 hover:text-brand-accent">Liên hệ &amp; Báo giá</a>
      </div>
    </div>
  </header>

  <!-- ==================== 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP BẰNG KÍCH THƯỚC ==================== -->
  <section id="trang-chu" class="hero-slider-wrapper">
    <div class="hero-slides-grid" id="heroSlider">
      <!-- Banner 1 -->
      <div class="hero-slide active">
        <img
          src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
          data-fallback="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
          onerror="handleImgError(this, 'AN VIET DT - THIET KE & XAY DUNG')"
          alt="Công trình thiết kế và thi công xây dựng An Việt DT"
          class="absolute inset-0 w-full h-full object-cover object-center"
        >
        <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/85 via-brand-primary/70 to-brand-dark/55"></div>
        <!-- Vùng nội dung cách xa viền ảnh trên cả mobile và máy tính, đảm bảo không thiếu chữ -->
        <div class="relative z-10 w-full max-w-5xl mx-auto px-10 sm:px-16 lg:px-20 py-10 sm:py-14 lg:py-16 text-center">
          <p class="text-[11px] sm:text-xs lg:text-sm uppercase tracking-[0.2em] text-amber-300 font-semibold mb-2.5">
            ANVIETDT.COM • ĐÀ NẴNG
          </p>
          <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3">
            CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG AN VIỆT DT
          </h1>
          <p class="text-xs sm:text-sm lg:text-base text-slate-100 max-w-2xl mx-auto leading-relaxed mb-6">
            Chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện và xây nhà trọn gói nhà phố, biệt thự, căn hộ, khách sạn với tiêu chuẩn kỹ thuật vững chắc và tiến độ chuẩn xác.
          </p>
          <div class="flex flex-wrap items-center justify-center gap-3">
            <a href="#lien-he" class="px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white text-xs sm:text-sm font-bold shadow-md transition-colors">
              Nhận Báo Giá Miễn Phí
            </a>
            <a href="#cong-trinh-thuc-te" class="px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition-colors">
              Xem Công Trình Thực Tế
            </a>
          </div>
        </div>
      </div>

      <!-- Banner 2 -->
      <div class="hero-slide">
        <img
          src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
          data-fallback="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
          onerror="handleImgError(this, 'DU AN XAY DUNG TAI DA NANG')"
          alt="Dự án thi công xây dựng tại Đà Nẵng của An Việt DT"
          class="absolute inset-0 w-full h-full object-cover object-center"
        >
        <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/85 via-brand-primary/70 to-brand-dark/55"></div>
        <!-- Vùng nội dung cùng khoảng đệm an toàn, bằng kích thước banner 1 -->
        <div class="relative z-10 w-full max-w-5xl mx-auto px-10 sm:px-16 lg:px-20 py-10 sm:py-14 lg:py-16 text-center">
          <p class="text-[11px] sm:text-xs lg:text-sm uppercase tracking-[0.2em] text-amber-300 font-semibold mb-2.5">
            AN TOÀN • CHẤT LƯỢNG • TIẾN ĐỘ • TẬN TÂM
          </p>
          <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3">
            KIẾN TẠO KHÔNG GIAN SỐNG BỀN VỮNG TẠI ĐÀ NẴNG
          </h2>
          <p class="text-xs sm:text-sm lg:text-base text-slate-100 max-w-2xl mx-auto leading-relaxed mb-6">
            Đội ngũ kiến trúc sư và kỹ sư giàu kinh nghiệm trực tiếp giám sát công trình từ bản vẽ 3D đến bàn giao chìa khóa trao tay, tối ưu chi phí cho mọi chủ đầu tư.
          </p>
          <div class="flex flex-wrap items-center justify-center gap-3">
            <a href="#du-an-da-nang" class="px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white text-xs sm:text-sm font-bold shadow-md transition-colors">
              Khám Phá Dự Án Đà Nẵng
            </a>
            <a href="#bao-gia" class="px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition-colors">
              Tham Khảo Bảng Báo Giá
            </a>
          </div>
        </div>
      </div>
    </div>

    <!-- Nút chuyển slide trái / phải đặt gọn ở hai mép ngoài -->
    <button
      id="prevSlideBtn"
      type="button"
      aria-label="Banner trước"
      class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors"
    >
      <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
    </button>
    <button
      id="nextSlideBtn"
      type="button"
      aria-label="Banner tiếp theo"
      class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition-colors"
    >
      <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
    </button>

    <!-- Dấu chấm chỉ báo slide -->
    <div class="absolute bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
      <button type="button" data-slide-index="0" aria-label="Chuyển tới banner 1" class="slide-dot w-7 h-2 rounded-full bg-brand-accent transition-all"></button>
      <button type="button" data-slide-index="1" aria-label="Chuyển tới banner 2" class="slide-dot w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all"></button>
    </div>
  </section>

  <!-- ==================== DỊCH VỤ TIÊU BIỂU & LĨNH VỰC HOẠT ĐỘNG (THEO WEB MẪU TINTRUONGTHINH) ==================== -->
  <section id="linh-vuc" class="py-10 sm:py-14 bg-white">
    <div class="av-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-brand-primary uppercase">
          Dịch Vụ Tiêu Biểu
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Giải pháp toàn diện từ ý tưởng thiết kế đến thi công hoàn thiện và nội thất công trình.
        </p>
      </div>

      <!-- 3 Khối Dịch vụ chính giống trang mẫu (Thiết kế - Thi công - Nội thất) -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6 mb-8">
        <a href="#bao-gia" class="group bg-brand-soft border border-slate-200 rounded-xl p-5 sm:p-6 text-center hover:border-brand-accent hover:shadow-md transition-all">
          <div class="w-12 h-12 mx-auto mb-3.5 rounded-xl bg-brand-primary text-white flex items-center justify-center group-hover:bg-brand-accent transition-colors">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M11 5H6a2 2 0 00-2 2v11a2 2 0 002 2h11a2 2 0 002-2v-5m-1.414-9.414a2 2 0 112.828 2.828L11.828 15H9v-2.828l8.586-8.586z"/></svg>
          </div>
          <h3 class="text-base sm:text-lg font-bold text-brand-primary uppercase mb-2">Thiết Kế Kiến Trúc</h3>
          <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
            Thiết kế hồ sơ kiến trúc, kết cấu, điện nước và phối cảnh 3D tối ưu công năng, thẩm mỹ và phong thủy.
          </p>
        </a>

        <a href="#bao-gia" class="group bg-brand-soft border border-slate-200 rounded-xl p-5 sm:p-6 text-center hover:border-brand-accent hover:shadow-md transition-all">
          <div class="w-12 h-12 mx-auto mb-3.5 rounded-xl bg-brand-primary text-white flex items-center justify-center group-hover:bg-brand-accent transition-colors">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/></svg>
          </div>
          <h3 class="text-base sm:text-lg font-bold text-brand-primary uppercase mb-2">Thi Công Xây Dựng</h3>
          <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
            Thi công phần thô, thi công hoàn thiện và xây nhà trọn gói đảm bảo vật tư chuẩn hãng, kết cấu bền vững.
          </p>
        </a>

        <a href="#bao-gia" class="group bg-brand-soft border border-slate-200 rounded-xl p-5 sm:p-6 text-center hover:border-brand-accent hover:shadow-md transition-all">
          <div class="w-12 h-12 mx-auto mb-3.5 rounded-xl bg-brand-primary text-white flex items-center justify-center group-hover:bg-brand-accent transition-colors">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/></svg>
          </div>
          <h3 class="text-base sm:text-lg font-bold text-brand-primary uppercase mb-2">Thi Công Nội Thất</h3>
          <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
            Sản xuất và lắp đặt nội thất nhà phố, biệt thự, căn hộ, văn phòng tinh tế, đồng bộ đúng bản vẽ thiết kế.
          </p>
        </a>
      </div>

      <!-- 4 Danh mục lĩnh vực chi tiết (Chia 2 cột trên điện thoại, 4 cột trên máy tính) -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <div class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition-shadow">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
              data-fallback="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800"
              onerror="handleImgError(this, 'Thiet Ke Kien Truc')"
              alt="Thiết kế Kiến trúc - Nội thất"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-500"
            >
          </div>
          <div class="p-3 sm:p-4 text-center">
            <h3 class="text-[13px] sm:text-sm font-bold text-brand-primary leading-snug break-words">
              Thiết Kế Kiến Trúc – Nội Thất
            </h3>
          </div>
        </div>

        <div class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition-shadow">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
              data-fallback="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800"
              onerror="handleImgError(this, 'Thi Cong Phan Tho')"
              alt="Thi công phần thô"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-500"
            >
          </div>
          <div class="p-3 sm:p-4 text-center">
            <h3 class="text-[13px] sm:text-sm font-bold text-brand-primary leading-snug break-words">
              Thi Công Phần Thô &amp; Nhân Công
            </h3>
          </div>
        </div>

        <div class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition-shadow">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
              data-fallback="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800"
              onerror="handleImgError(this, 'Thi Cong Hoan Thien')"
              alt="Thi công hoàn thiện"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-500"
            >
          </div>
          <div class="p-3 sm:p-4 text-center">
            <h3 class="text-[13px] sm:text-sm font-bold text-brand-primary leading-snug break-words">
              Thi Công Hoàn Thiện Trọn Gói
            </h3>
          </div>
        </div>

        <div class="bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition-shadow">
          <div class="aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn"
              data-fallback="https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w800"
              onerror="handleImgError(this, 'Thi Cong Noi That')"
              alt="Thi công nội thất"
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-500"
            >
          </div>
          <div class="p-3 sm:p-4 text-center">
            <h3 class="text-[13px] sm:text-sm font-bold text-brand-primary leading-snug break-words">
              Thi Công Nội Thất &amp; Cải Tạo
            </h3>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== GIỚI THIỆU & THẾ MẠNH CỦA AN VIỆT DT ==================== -->
  <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-soft border-y border-slate-200">
    <div class="av-container">
      <!-- Giới thiệu công ty -->
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-12">
        <div class="lg:col-span-5">
          <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
            <img
              src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
              data-fallback="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
              onerror="handleImgError(this, 'AN VIET DT')"
              alt="Công trình thi công bởi Công ty TNHH Thiết Kế và Xây Dựng An Việt DT"
              class="w-full aspect-[4/3] object-cover"
            >
          </div>
        </div>
        <div class="lg:col-span-7">
          <h2 class="flatsome-heading flatsome-heading-left text-xl sm:text-2xl lg:text-[26px] font-extrabold text-brand-primary uppercase mb-4">
            CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG AN VIỆT DT
          </h2>
          <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-3.5">
            <strong>AN VIỆT DT</strong> chuyên Thiết kế – Xây dựng – Nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại khu vực <strong>TP Đà Nẵng</strong> và các tỉnh miền Trung.
          </p>
          <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-5">
            Với phương châm đặt chữ <strong>“TÂM”</strong> và chất lượng kết cấu lên hàng đầu, mỗi công trình do An Việt DT thực hiện đều cam kết đạt tiêu chuẩn <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – TỐI ƯU CHI PHÍ”</strong>, mang lại sự an tâm tuyệt đối cho Quý khách hàng.
          </p>
          <div class="grid grid-cols-2 sm:grid-cols-3 gap-3">
            <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-accent">100%</div>
              <div class="text-xs font-semibold text-slate-600 mt-0.5">Vật Tư Chính Hãng</div>
            </div>
            <div class="bg-white rounded-lg border border-slate-200 p-3.5 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-accent">Đúng Hẹn</div>
              <div class="text-xs font-semibold text-slate-600 mt-0.5">Cam Kết Tiến Độ</div>
            </div>
            <div class="col-span-2 sm:col-span-1 bg-white rounded-lg border border-slate-200 p-3.5 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-accent">Tận Tâm</div>
              <div class="text-xs font-semibold text-slate-600 mt-0.5">Bảo Hành Dài Hạn</div>
            </div>
          </div>
        </div>
      </div>

      <!-- 6 Thế mạnh của chúng tôi (chuẩn Flatsome Icon Box) -->
      <div class="text-center mb-7">
        <h3 class="flatsome-heading text-lg sm:text-xl lg:text-2xl font-extrabold text-brand-primary uppercase">
          Thế Mạnh Của Chúng Tôi
        </h3>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <div class="bg-white rounded-xl border border-slate-200 p-5 flex items-start gap-3.5 shadow-sm">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Đội ngũ kiến trúc sư sáng tạo cùng kỹ sư giám sát và thợ thi công tay nghề cao, tận tâm tại công trường.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-slate-200 p-5 flex items-start gap-3.5 shadow-sm">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Cập nhật xu hướng hiện đại</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Ứng dụng giải pháp thiết kế thông thoáng, vật liệu mới và biện pháp thi công tiên tiến cho ngôi nhà bền đẹp.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-slate-200 p-5 flex items-start gap-3.5 shadow-sm">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Giám sát tiến độ chuẩn xác</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Báo cáo tiến độ và hình ảnh thực tế từng hạng mục thường xuyên giúp gia chủ dễ dàng theo dõi từ xa.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-slate-200 p-5 flex items-start gap-3.5 shadow-sm">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Bảo hành công trình lâu dài</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Chính sách bảo hành kết cấu và hoàn thiện rõ ràng bằng hợp đồng, hỗ trợ bảo trì nhanh chóng sau bàn giao.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-slate-200 p-5 flex items-start gap-3.5 shadow-sm">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Chi phí minh bạch, không phát sinh</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục và chủng loại vật tư ngay từ đầu, cân đối ngân sách hợp lý nhất cho gia chủ.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-slate-200 p-5 flex items-start gap-3.5 shadow-sm">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Tư vấn &amp; Khảo sát miễn phí 24/7</h4>
            <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Luôn sẵn sàng lắng nghe nhu cầu, khảo sát thực tế hiện trạng đất và lập phương án sơ bộ hoàn toàn miễn phí.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== CÔNG TRÌNH THỰC TẾ (9 ẢNH THI CÔNG THỰC TẾ + BỘ LỌC DANH MỤC GỌN) ==================== -->
  <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
    <div class="av-container">
      <div class="text-center mb-6">
        <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-brand-primary uppercase">
          Công Trình Thực Tế
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Hình ảnh thực tế thi công xây dựng và hoàn thiện công trình do An Việt DT trực tiếp thực hiện.
        </p>
      </div>

      <!-- Danh mục lọc sản phẩm / công trình: chữ nhỏ gọn, tên danh mục không xuống dòng, tối ưu 1-2 hàng đẹp mắt -->
      <div id="projectFilterBar" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
        <button type="button" data-filter="all" class="filter-btn active whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold border transition-colors bg-brand-primary text-white border-brand-primary">
          Tất cả
        </button>
        <button type="button" data-filter="nha-pho" class="filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold border transition-colors bg-white text-slate-700 border-slate-200 hover:border-brand-primary hover:text-brand-primary">
          Nhà phố
        </button>
        <button type="button" data-filter="biet-thu" class="filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold border transition-colors bg-white text-slate-700 border-slate-200 hover:border-brand-primary hover:text-brand-primary">
          Biệt thự
        </button>
        <button type="button" data-filter="khach-san-can-ho" class="filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold border transition-colors bg-white text-slate-700 border-slate-200 hover:border-brand-primary hover:text-brand-primary">
          Khách sạn – Căn hộ
        </button>
        <button type="button" data-filter="van-phong" class="filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold border transition-colors bg-white text-slate-700 border-slate-200 hover:border-brand-primary hover:text-brand-primary">
          Văn phòng
        </button>
        <button type="button" data-filter="phan-tho" class="filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold border transition-colors bg-white text-slate-700 border-slate-200 hover:border-brand-primary hover:text-brand-primary">
          Thi công phần thô
        </button>
        <button type="button" data-filter="hoan-thien" class="filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold border transition-colors bg-white text-slate-700 border-slate-200 hover:border-brand-primary hover:text-brand-primary">
          Thi công hoàn thiện
        </button>
        <button type="button" data-filter="noi-that" class="filter-btn whitespace-nowrap px-3 py-1.5 rounded-lg text-[11px] sm:text-xs font-semibold border transition-colors bg-white text-slate-700 border-slate-200 hover:border-brand-primary hover:text-brand-primary">
          Thi công nội thất
        </button>
      </div>

      <!-- Lưới 9 ảnh thực tế thi công: 2 cột trên điện thoại, 3 cột trên máy tính, KHÔNG nhãn dán đè lên ảnh -->
      <div id="realProjectsGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
        <!-- Dữ liệu được render tự động từ JS để dễ lọc danh mục và xem ảnh phóng to -->
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH DỰ ÁN TẠI ĐÀ NẴNG) ==================== -->
  <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-soft border-y border-slate-200">
    <div class="av-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-brand-primary uppercase">
          Các Dự Án Tại Đà Nẵng
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Tổng hợp các dự án nhà ở, biệt thự, căn hộ và công trình dân dụng tiêu biểu An Việt DT triển khai tại TP Đà Nẵng.
        </p>
      </div>

      <!-- 2 cột trên điện thoại, 3 cột trên tablet, 5 cột trên desktop (2 hàng x 5 ảnh cân đối tuyệt đẹp) -->
      <div id="danangProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
        <!-- Dữ liệu được render tự động từ JS -->
      </div>
    </div>
  </section>

  <!-- ==================== BẢNG BÁO GIÁ DỊCH VỤ (THEO DANH MỤC WEB MẪU) ==================== -->
  <section id="bao-gia" class="py-10 sm:py-14 bg-white">
    <div class="av-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-brand-primary uppercase">
          Báo Giá Thiết Kế &amp; Thi Công
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Đơn giá tham khảo minh bạch theo m² xây dựng. Liên hệ trực tiếp 0982.212.347 để nhận bảng dự toán chi tiết miễn phí.
        </p>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <div class="bg-white border border-slate-200 rounded-xl p-4 sm:p-5 flex flex-col justify-between hover:border-brand-accent hover:shadow-md transition-all">
          <div>
            <h3 class="text-[13px] sm:text-base font-bold text-brand-primary leading-snug mb-2">
              Báo Giá Thiết Kế Kiến Trúc
            </h3>
            <div class="text-base sm:text-xl font-extrabold text-brand-accent mb-3">
              Từ 120.000đ/m²
            </div>
            <ul class="space-y-1.5 text-xs sm:text-[13px] text-slate-600 mb-4">
              <li>• Hồ sơ kiến trúc &amp; kết cấu chi tiết</li>
              <li>• Hồ sơ hệ thống điện nước M&amp;E</li>
              <li>• Phối cảnh 3D mặt tiền hiện đại</li>
              <li>• Hỗ trợ hồ sơ xin phép xây dựng</li>
            </ul>
          </div>
          <button type="button" onclick="selectQuoteService('Thiết kế Kiến trúc – Nội thất')" class="w-full py-2 px-3 rounded-lg bg-brand-primary hover:bg-brand-accent text-white text-xs sm:text-sm font-semibold transition-colors">
            Nhận Báo Giá Chi Tiết
          </button>
        </div>

        <div class="bg-white border border-slate-200 rounded-xl p-4 sm:p-5 flex flex-col justify-between hover:border-brand-accent hover:shadow-md transition-all">
          <div>
            <h3 class="text-[13px] sm:text-base font-bold text-brand-primary leading-snug mb-2">
              Báo Giá Thi Công Phần Thô
            </h3>
            <div class="text-base sm:text-xl font-extrabold text-brand-accent mb-3">
              Từ 3.400.000đ/m²
            </div>
            <ul class="space-y-1.5 text-xs sm:text-[13px] text-slate-600 mb-4">
              <li>• Vật tư phần thô chính hãng chuẩn</li>
              <li>• Nhân công xây tô và hoàn thiện</li>
              <li>• Kỹ sư giám sát trực tiếp tại công trình</li>
              <li>• Bảo hành kết cấu khung chịu lực</li>
            </ul>
          </div>
          <button type="button" onclick="selectQuoteService('Thi công phần thô')" class="w-full py-2 px-3 rounded-lg bg-brand-primary hover:bg-brand-accent text-white text-xs sm:text-sm font-semibold transition-colors">
            Nhận Báo Giá Chi Tiết
          </button>
        </div>

        <div class="bg-white border border-slate-200 rounded-xl p-4 sm:p-5 flex flex-col justify-between hover:border-brand-accent hover:shadow-md transition-all">
          <div>
            <h3 class="text-[13px] sm:text-base font-bold text-brand-primary leading-snug mb-2">
              Báo Giá Thi Công Hoàn Thiện
            </h3>
            <div class="text-base sm:text-xl font-extrabold text-brand-accent mb-3">
              Từ 2.500.000đ/m²
            </div>
            <ul class="space-y-1.5 text-xs sm:text-[13px] text-slate-600 mb-4">
              <li>• Ốp lát gạch, đá cầu thang, mặt tiền</li>
              <li>• Sơn nước, trần thạch cao hoàn chỉnh</li>
              <li>• Lắp đặt cửa nhôm kính &amp; thiết bị</li>
              <li>• Nghiệm thu sắc nét từng chi tiết</li>
            </ul>
          </div>
          <button type="button" onclick="selectQuoteService('Thi công hoàn thiện')" class="w-full py-2 px-3 rounded-lg bg-brand-primary hover:bg-brand-accent text-white text-xs sm:text-sm font-semibold transition-colors">
            Nhận Báo Giá Chi Tiết
          </button>
        </div>

        <div class="bg-white border border-slate-200 rounded-xl p-4 sm:p-5 flex flex-col justify-between hover:border-brand-accent hover:shadow-md transition-all">
          <div>
            <h3 class="text-[13px] sm:text-base font-bold text-brand-primary leading-snug mb-2">
              Báo Giá Thi Công Trọn Gói
            </h3>
            <div class="text-base sm:text-xl font-extrabold text-brand-accent mb-3">
              Từ 5.500.000đ/m²
            </div>
            <ul class="space-y-1.5 text-xs sm:text-[13px] text-slate-600 mb-4">
              <li>• Miễn phí tư vấn &amp; thiết kế cơ bản</li>
              <li>• Chìa khóa trao tay từ móng đến mái</li>
              <li>• Không phát sinh chi phí ngoài hợp đồng</li>
              <li>• Bàn giao sạch đẹp đúng tiến độ</li>
            </ul>
          </div>
          <button type="button" onclick="selectQuoteService('Thi công xây dựng trọn gói')" class="w-full py-2 px-3 rounded-lg bg-brand-primary hover:bg-brand-accent text-white text-xs sm:text-sm font-semibold transition-colors">
            Nhận Báo Giá Chi Tiết
          </button>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC CÁC ĐỐI TÁC ==================== -->
  <section id="doi-tac" class="py-10 sm:py-12 bg-brand-soft border-y border-slate-200">
    <div class="av-container">
      <div class="text-center mb-7">
        <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-brand-primary uppercase">
          Đối Tác Cung Ứng Vật Tư
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          An Việt DT hợp tác cùng các thương hiệu vật liệu xây dựng hàng đầu để bảo chứng chất lượng mọi công trình.
        </p>
      </div>

      <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-4">
        <div class="bg-white border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
          <div class="text-sm sm:text-base font-extrabold tracking-wider text-brand-primary">THÉP HÒA PHÁT</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Kết cấu thép xây dựng</div>
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
          <div class="text-sm sm:text-base font-extrabold tracking-wider text-brand-primary">XI MĂNG SÔNG GIANH</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Xi măng PCB40 chuẩn chất lượng</div>
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
          <div class="text-sm sm:text-base font-extrabold tracking-wider text-brand-primary">SƠN DULUX</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Sơn nội ngoại thất cao cấp</div>
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
          <div class="text-sm sm:text-base font-extrabold tracking-wider text-brand-primary">CADIVI</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Dây cáp điện an toàn</div>
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
          <div class="text-sm sm:text-base font-extrabold tracking-wider text-brand-primary">NHỰA BÌNH MINH</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Hệ thống cấp thoát nước</div>
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
          <div class="text-sm sm:text-base font-extrabold tracking-wider text-brand-primary">NHÔM XINGFA</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Cửa nhôm kính cách âm</div>
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
          <div class="text-sm sm:text-base font-extrabold tracking-wider text-brand-primary">INAX VIỆT NAM</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh cao cấp</div>
        </div>
        <div class="bg-white border border-slate-200 rounded-xl p-4 flex flex-col items-center justify-center text-center hover:border-brand-accent transition-colors">
          <div class="text-sm sm:text-base font-extrabold tracking-wider text-brand-primary">GỖ AN CƯỜNG</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Vật liệu gỗ nội thất</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC BÀI VIẾT / TIN TỨC TRANG CHỦ ==================== -->
  <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
    <div class="av-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-brand-primary uppercase">
          Tin Tức &amp; Kinh Nghiệm Xây Dựng
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Chia sẻ kiến thức thực tế về thiết kế, kỹ thuật thi công và kinh nghiệm xây nhà tiết kiệm chi phí.
        </p>
      </div>

      <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Render tự động từ JS -->
      </div>
    </div>
  </section>

  <!-- ==================== FORM YÊU CẦU BÁO GIÁ + GOOGLE MAP + FANPAGE TRÊN TRANG CHỦ ==================== -->
  <section id="lien-he" class="py-10 sm:py-14 bg-brand-soft border-t border-slate-200">
    <div class="av-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-xl sm:text-2xl lg:text-[26px] font-extrabold text-brand-primary uppercase">
          Yêu Cầu Tư Vấn &amp; Báo Giá Miễn Phí
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
          Để lại thông tin công trình dự kiến, kỹ sư của An Việt DT sẽ liên hệ tư vấn và gửi bảng dự toán chi tiết nhanh nhất.
        </p>
      </div>

      <!-- Khối 1: Form Yêu Cầu Báo Giá + Thông Tin Liên Hệ -->
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 mb-8">
        <!-- Form Yêu Cầu Báo Giá -->
        <div class="lg:col-span-7 bg-white border border-slate-200 rounded-xl p-5 sm:p-7 shadow-sm">
          <h3 class="text-base sm:text-lg font-bold text-brand-primary mb-4">
            Gửi Yêu Cầu Tư Vấn &amp; Báo Giá
          </h3>

          <form id="quoteForm" class="space-y-3.5" novalidate>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
              <div>
                <label for="customerName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                <input
                  id="customerName"
                  name="customerName"
                  type="text"
                  required
                  placeholder="Nhập họ tên của bạn"
                  class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"
                >
              </div>
              <div>
                <label for="customerPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại *</label>
                <input
                  id="customerPhone"
                  name="customerPhone"
                  type="tel"
                  required
                  placeholder="Nhập số điện thoại liên hệ"
                  class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"
                >
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
              <div>
                <label for="projectType" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình / Dịch vụ</label>
                <select
                  id="projectType"
                  name="projectType"
                  class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"
                >
                  <option value="Thi công xây dựng trọn gói">Thi công xây dựng trọn gói</option>
                  <option value="Thiết kế Kiến trúc – Nội thất">Thiết kế Kiến trúc – Nội thất</option>
                  <option value="Thi công phần thô">Thi công phần thô</option>
                  <option value="Thi công hoàn thiện">Thi công hoàn thiện</option>
                  <option value="Nhà phố">Xây dựng Nhà phố</option>
                  <option value="Biệt thự">Xây dựng Biệt thự</option>
                  <option value="Khách sạn – Căn hộ – Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                  <option value="Văn phòng">Văn phòng / Cải tạo sửa chữa</option>
                </select>
              </div>
              <div>
                <label for="budgetRange" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                <select
                  id="budgetRange"
                  name="budgetRange"
                  class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"
                >
                  <option value="Chưa xác định">Chưa xác định</option>
                  <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                  <option value="500 triệu – 1 tỷ">500 triệu – 1 tỷ</option>
                  <option value="1 tỷ – 2 tỷ">1 tỷ – 2 tỷ</option>
                  <option value="2 tỷ – 3 tỷ">2 tỷ – 3 tỷ</option>
                  <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                </select>
              </div>
            </div>

            <div>
              <label for="customerNote" class="block text-xs font-semibold text-slate-700 mb-1">Yêu cầu chi tiết (diện tích đất, số tầng, địa điểm...)</label>
              <textarea
                id="customerNote"
                name="customerNote"
                rows="3"
                placeholder="Ví dụ: Xây nhà phố 2 tầng diện tích 5x20m tại Đà Nẵng..."
                class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"
              ></textarea>
            </div>

            <!-- Hộp thông báo trạng thái gửi form (không dùng alert) -->
            <div id="formFeedback" class="hidden rounded-lg p-3.5 text-xs sm:text-sm font-medium"></div>

            <button
              type="submit"
              class="w-full sm:w-auto px-7 py-3 rounded-lg bg-brand-primary hover:bg-brand-accent text-white text-sm font-bold shadow-sm transition-colors"
            >
              Gửi Yêu Cầu Báo Giá Ngay
            </button>
          </form>
        </div>

        <!-- Fanpage Facebook đưa trực tiếp ra ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white border border-slate-200 rounded-xl p-5 sm:p-6 shadow-sm flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between gap-2 mb-3">
              <h3 class="text-base sm:text-lg font-bold text-brand-primary">
                Fanpage Chính Thức
              </h3>
              <a
                href="https://www.facebook.com/profile.php?id=100088883929336&locale=vi_VN"
                target="_blank"
                rel="noopener noreferrer"
                class="text-xs font-semibold text-blue-600 hover:underline"
              >
                Mở trên Facebook →
              </a>
            </div>

            <!-- Khung thẻ Fanpage đồng bộ thương hiệu + Plugin nhúng Facebook -->
            <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50 mb-3">
              <div class="p-3.5 bg-white border-b border-slate-200 flex items-center gap-3">
                <img
                  src="https://lh3.googleusercontent.com/d/1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX"
                  data-fallback="https://drive.google.com/thumbnail?id=1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX&sz=w400"
                  onerror="handleImgError(this, 'AV')"
                  alt="Avatar Fanpage An Việt DT"
                  class="w-11 h-11 rounded-lg object-contain border border-slate-200 bg-white p-1 shrink-0"
                >
                <div class="min-w-0">
                  <div class="text-sm font-bold text-brand-primary leading-snug">
                    CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG AN VIỆT DT
                  </div>
                  <div class="text-xs text-slate-500">
                    Thiết kế &amp; Xây dựng tại Đà Nẵng • 0982.212.347
                  </div>
                </div>
              </div>
              <div class="w-full overflow-hidden bg-white">
                <iframe
                  title="Fanpage Facebook Công ty TNHH Thiết Kế và Xây Dựng An Việt DT"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100088883929336&tabs=timeline&width=500&height=260&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                  class="w-full h-[260px] border-0 block"
                  scrolling="no"
                  frameborder="0"
                  allowfullscreen="true"
                  loading="lazy"
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                ></iframe>
              </div>
            </div>
          </div>

          <a
            href="https://www.facebook.com/profile.php?id=100088883929336&locale=vi_VN"
            target="_blank"
            rel="noopener noreferrer"
            class="w-full py-2.5 px-4 rounded-lg bg-[#1877F2] hover:bg-[#1465CC] text-white text-xs sm:text-sm font-semibold text-center inline-flex items-center justify-center gap-2 transition-colors"
          >
            <svg class="w-4 h-4 fill-current" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116C23.403 24 24 23.403 24 22.674V1.326C24 .597 23.403 0 22.675 0z"/></svg>
            <span>Theo Dõi &amp; Nhắn Tin Fanpage AN VIỆT DT</span>
          </a>
        </div>
      </div>

      <!-- Khối 2: Bản đồ Google Map đưa trực tiếp ra ngoài trang chủ -->
      <div class="bg-white border border-slate-200 rounded-xl p-4 sm:p-6 shadow-sm">
        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-4">
          <div>
            <h3 class="text-base sm:text-lg font-bold text-brand-primary">
              Bản Đồ Chỉ Đường Trụ Sở AN VIỆT DT
            </h3>
            <p class="text-xs sm:text-sm text-slate-600">
              Địa chỉ: Tổ 3, Thôn Đồng Trì, Xã Thăng Trường, TP Đà Nẵng
            </p>
          </div>
          <a
            href="https://www.google.com/maps/search/?api=1&query=T%E1%BB%95+3%2C+Th%C3%B4n+%C4%90%E1%BB%93ng+Tr%C3%AC%2C+X%C3%A3+Th%C4%83ng+Tr%C6%B0%E1%BB%9Dng%2C+%C4%90%C3%A0+N%E1%BA%B5ng"
            target="_blank"
            rel="noopener noreferrer"
            class="inline-flex items-center gap-1.5 text-xs sm:text-sm font-semibold text-brand-primary hover:text-brand-accent transition-colors shrink-0"
          >
            <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
            <span>Mở trên Google Maps</span>
          </a>
        </div>
        <div class="w-full rounded-lg overflow-hidden border border-slate-200">
          <iframe
            title="Google Map - Công ty TNHH Thiết Kế và Xây Dựng An Việt DT"
            src="https://maps.google.com/maps?q=X%C3%A3%20Th%C4%83ng%20Tr%C6%B0%E1%BB%9Dng%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=14&ie=UTF8&iwloc=&output=embed"
            class="w-full h-[280px] sm:h-[340px] border-0 block"
            loading="lazy"
            referrerpolicy="no-referrer-when-downgrade"
          ></iframe>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FOOTER CHUẨN FLATSOME ==================== -->
  <footer class="bg-brand-dark text-slate-200 pt-10 pb-6 border-t-4 border-brand-accent">
    <div class="av-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">
        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="sm:col-span-2 lg:col-span-1">
          <div class="flex items-center gap-2.5 mb-3">
            <img
              src="https://lh3.googleusercontent.com/d/1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX"
              data-fallback="https://drive.google.com/thumbnail?id=1PsEKXWCPq_jil2XVB6ZIZ1a0bn4djsHX&sz=w400"
              onerror="handleImgError(this, 'AN VIET DT')"
              alt="Logo An Việt DT"
              class="h-10 w-auto bg-white rounded p-1 object-contain"
            >
            <div class="text-sm font-extrabold text-white leading-tight uppercase">
              AN VIỆT DT
            </div>
          </div>
          <p class="text-xs font-bold text-amber-300 uppercase mb-2">
            CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG AN VIỆT DT
          </p>
          <ul class="space-y-1.5 text-xs text-slate-300 leading-relaxed">
            <li><strong class="text-white">Địa chỉ:</strong> Tổ 3, Thôn Đồng Trì, Xã Thăng Trường, TP Đà Nẵng</li>
            <li><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0982212347" class="hover:text-brand-accent">0982.212.347</a></li>
            <li><strong class="text-white">Website:</strong> <a href="https://anvietdt.com" class="hover:text-brand-accent">anvietdt.com</a></li>
            <li><strong class="text-white">Mã số thuế:</strong> 4001262051</li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
            Lĩnh Vực Hoạt Động
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#linh-vuc" class="hover:text-brand-accent transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#linh-vuc" class="hover:text-brand-accent transition-colors">Thi công phần thô</a></li>
            <li><a href="#linh-vuc" class="hover:text-brand-accent transition-colors">Thi công hoàn thiện</a></li>
            <li><a href="#linh-vuc" class="hover:text-brand-accent transition-colors">Thi công nội thất trọn gói</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-accent transition-colors">Báo giá xây nhà trọn gói</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục công trình -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
            Danh Mục Công Trình
          </h4>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-accent transition-colors">Nhà phố hiện đại</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-accent transition-colors">Biệt thự sân vườn &amp; Biệt thự phố</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-accent transition-colors">Khách sạn – Căn hộ – Phòng trọ</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-accent transition-colors">Văn phòng &amp; Showroom</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-brand-accent transition-colors">Các dự án tại Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 4: Kết nối nhanh -->
        <div>
          <h4 class="text-sm font-bold text-white uppercase mb-3 pb-2 border-b border-white/15">
            Hỗ Trợ Khách Hàng
          </h4>
          <p class="text-xs text-slate-300 leading-relaxed mb-3">
            Tư vấn thiết kế, khảo sát mặt bằng và lập dự toán chi tiết miễn phí các ngày trong tuần.
          </p>
          <div class="flex flex-wrap gap-2">
            <a href="https://www.facebook.com/profile.php?id=100088883929336&locale=vi_VN" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-[#1877F2] hover:opacity-90 text-white text-xs font-semibold">
              Facebook
            </a>
            <a href="https://zalo.me/0982212347" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-[#0068FF] hover:opacity-90 text-white text-xs font-semibold">
              Zalo
            </a>
            <a href="tel:0982212347" class="px-3 py-1.5 rounded-lg bg-brand-accent hover:bg-brand-accentDark text-white text-xs font-semibold">
              0982.212.347
            </a>
          </div>
        </div>
      </div>

      <div class="pt-5 text-center text-xs text-slate-400">
        Copyright 2026 © CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG AN VIỆT DT – anvietdt.com. All rights reserved.
      </div>
    </div>
  </footer>

  <!-- ==================== CỤM NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE ==================== -->
  <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0982212347"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Liên hệ Zalo An Việt DT"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0054CC] text-white rounded-full shadow-lg px-3 py-2.5 sm:px-4 sm:py-2.5 transition-all"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] text-[10px] font-extrabold flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Facebook -->
    <a
      href="https://www.facebook.com/profile.php?id=100088883929336&locale=vi_VN"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Fanpage Facebook An Việt DT"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1362C7] text-white rounded-full shadow-lg px-3 py-2.5 sm:px-4 sm:py-2.5 transition-all"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <svg class="w-3.5 h-3.5 fill-current" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24H12.82v-9.294H9.692v-3.622h3.128V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116C23.403 24 24 23.403 24 22.674V1.326C24 .597 23.403 0 22.675 0z"/></svg>
      </span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a
      href="tel:0982212347"
      aria-label="Gọi Hotline 0982.212.347"
      class="hotline-pulse flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full shadow-xl px-3.5 py-2.5 sm:px-4 sm:py-2.5 transition-all"
    >
      <span class="w-6 h-6 rounded-full bg-white text-red-600 flex items-center justify-center shrink-0">
        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="2.4" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      </span>
      <span class="text-xs font-extrabold whitespace-nowrap">0982.212.347</span>
    </a>
  </div>

  <!-- ==================== MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH & BÀI VIẾT ==================== -->
  <div id="detailModal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-xs p-3 sm:p-6 flex items-center justify-center" role="dialog" aria-modal="true">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between gap-3 px-5 py-3.5 border-b border-slate-200 sticky top-0 bg-white z-10">
        <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-brand-primary leading-snug">Chi tiết</h3>
        <button id="closeModalBtn" type="button" aria-label="Đóng cửa sổ" class="p-1.5 rounded-lg text-slate-500 hover:bg-slate-100 hover:text-slate-800">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div class="p-4 sm:p-5">
        <div class="rounded-xl overflow-hidden bg-slate-100 mb-4">
          <img id="modalImage" src="" alt="" class="w-full max-h-[380px] object-cover">
        </div>
        <p id="modalCategory" class="text-xs font-semibold text-brand-accent uppercase mb-2"></p>
        <div id="modalBody" class="text-sm text-slate-700 leading-relaxed space-y-2.5 mb-5"></div>
        <div class="flex flex-wrap items-center gap-3 pt-3 border-t border-slate-200">
          <a href="#lien-he" onclick="closeDetailModal()" class="px-4 py-2 rounded-lg bg-brand-primary hover:bg-brand-accent text-white text-xs sm:text-sm font-semibold transition-colors">
            Nhận Báo Giá Công Trình Tương Tự
          </a>
          <a href="tel:0982212347" class="px-4 py-2 rounded-lg border border-brand-primary text-brand-primary hover:bg-brand-soft text-xs sm:text-sm font-semibold transition-colors">
            Hotline: 0982.212.347
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ==================== JAVASCRIPT ĐIỀU KHIỂN DỮ LIỆU & TƯƠNG TÁC ==================== -->
  <script>
    /**
     * Hàm xử lý fallback khi tải ảnh Google Drive gặp sự cố
     * Bước 1: Thử đường dẫn thumbnail của Google Drive
     * Bước 2: Nếu vẫn lỗi, hiển thị ảnh giữ chỗ đẹp theo màu thương hiệu
     */
    function handleImgError(imgEl, labelText) {
      try {
        if (!imgEl.dataset.triedFallback && imgEl.dataset.fallback) {
          imgEl.dataset.triedFallback = 'true';
          imgEl.src = imgEl.dataset.fallback;
        } else {
          imgEl.onerror = null;
          const safeText = encodeURIComponent(labelText || 'AN VIET DT');
          imgEl.src = 'https://placehold.co/800x600/0F3057/FFFFFF?text=' + safeText;
        }
      } catch (err) {
        console.error('Lỗi tải hình ảnh:', err);
      }
    }

    /**
     * Dữ liệu 9 ảnh thực tế thi công xây dựng do khách hàng cung cấp
     */
    const realProjects = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi Công Trọn Gói Nhà Phố Hiện Đại 3 Tầng',
        categoryKey: 'nha-pho',
        categoryLabel: 'Nhà phố',
        description: 'Công trình nhà phố hiện đại được An Việt DT trực tiếp thiết kế kiến trúc và thi công trọn gói từ phần móng, khung bê tông cốt thép đến hoàn thiện mặt tiền thẩm mỹ.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thi Công Phần Thô Kết Cấu Bê Tông Cốt Thép',
        categoryKey: 'phan-tho',
        categoryLabel: 'Thi công phần thô',
        description: 'Hạng mục thi công phần thô tuân thủ nghiêm ngặt quy trình kỹ thuật cốt thép, cốp pha, bảo dưỡng bê tông tiêu chuẩn đảm bảo tuổi thọ vững bền cho công trình.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Thiết Kế & Thi Công Biệt Thự Phố Hiện Đại',
        categoryKey: 'biet-thu',
        categoryLabel: 'Biệt thự',
        description: 'Công trình biệt thự phố thiết kế sang trọng, bố trí không gian đón sáng tự nhiên tối ưu và vật liệu hoàn thiện cao cấp do đội ngũ kỹ sư An Việt DT giám sát.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thi Công Xây Dựng Căn Hộ Cho Thuê Hiện Đại',
        categoryKey: 'khach-san-can-ho',
        categoryLabel: 'Khách sạn – Căn hộ',
        description: 'Giải pháp thiết kế và thi công căn hộ dịch vụ tối ưu số phòng, hệ thống M&E đồng bộ, đáp ứng tiêu chuẩn vận hành khai thác lưu trú lâu dài.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thi Công Hoàn Thiện Mặt Tiền & Ngoại Thất',
        categoryKey: 'hoan-thien',
        categoryLabel: 'Thi công hoàn thiện',
        description: 'Công tác hoàn thiện xây tô, chống thấm, ốp lát đá mặt tiền và lắp đặt hệ cửa nhôm kính sắc nét, đúng bản vẽ phối cảnh 3D.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thiết Kế & Thi Công Biệt Thự Sân Vườn 2 Tầng',
        categoryKey: 'biet-thu',
        categoryLabel: 'Biệt thự',
        description: 'Biệt thự sân vườn thoáng mát với tỷ lệ hình khối cân đối, sân vườn tiểu cảnh hài hòa và công năng tiện nghi cho gia đình nhiều thế hệ.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thi Công Văn Phòng & Không Gian Kinh Doanh',
        categoryKey: 'van-phong',
        categoryLabel: 'Văn phòng',
        description: 'Thi công xây dựng và hoàn thiện văn phòng làm việc hiện đại, tối ưu diện tích sử dụng, ánh sáng và hệ thống kỹ thuật tiêu chuẩn.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi Công Nhà Phố 2 Mặt Tiền Kết Hợp Ở & Kinh Doanh',
        categoryKey: 'nha-pho',
        categoryLabel: 'Nhà phố',
        description: 'Mẫu nhà phố 2 mặt tiền thông thoáng, mặt bằng tầng trệt linh hoạt kinh doanh kết hợp không gian sinh hoạt riêng tư ở các tầng trên.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Thi Công Hoàn Thiện Nội Thất Trọn Gói',
        categoryKey: 'noi-that',
        categoryLabel: 'Thi công nội thất',
        description: 'Hạng mục hoàn thiện và lắp đặt nội thất phòng khách, bếp, phòng ngủ đồng bộ vật liệu cao cấp, bàn giao sạch sẽ sẵn sàng vào ở.'
      }
    ];

    /**
     * Dữ liệu 10 ảnh dự án tại Đà Nẵng do khách hàng cung cấp
     */
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Nhà Phố Hiện Đại Khu Đô Thị Hòa Xuân – Đà Nẵng',
        location: 'Hòa Xuân, TP Đà Nẵng'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Biệt Thự Phố Khu Nam Việt Á – Đà Nẵng',
        location: 'Ngũ Hành Sơn, TP Đà Nẵng'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Căn Hộ Dịch Vụ Cho Thuê An Thượng – Đà Nẵng',
        location: 'Sơn Trà, TP Đà Nẵng'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Nhà Phố 3 Tầng Khu Đô Thị Phước Lý – Đà Nẵng',
        location: 'Liên Chiểu, TP Đà Nẵng'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Công Trình Nhà Ở Gia Đình Xã Thăng Trường – Đà Nẵng',
        location: 'Thăng Trường, TP Đà Nẵng'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Khách Sạn Mini Ven Biển Mỹ Khê – Đà Nẵng',
        location: 'Sơn Trà, TP Đà Nẵng'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Biệt Thự Sân Vườn Mái Nhật Hòa Vang – Đà Nẵng',
        location: 'Hòa Vang, TP Đà Nẵng'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Thi Công Văn Phòng Làm Việc Quận Hải Châu – Đà Nẵng',
        location: 'Hải Châu, TP Đà Nẵng'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Nhà Phố Tân Cổ Điển Quận Thanh Khê – Đà Nẵng',
        location: 'Thanh Khê, TP Đà Nẵng'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Hoàn Thiện Nội Thất Căn Hộ Cao Cấp – Đà Nẵng',
        location: 'TP Đà Nẵng'
      }
    ];

    /**
     * Dữ liệu 4 bài viết kinh nghiệm xây dựng hiển thị trên trang chủ
     */
    const articles = [
      {
        title: 'Hướng Dẫn Bảo Dưỡng Bê Tông Móng Đúng Kỹ Thuật Khi Xây Nhà',
        date: 'Kinh nghiệm thi công',
        imageId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        excerpt: 'Bảo dưỡng bê tông móng đúng chuẩn trong 7 ngày đầu giúp tăng cường độ chịu lực, hạn chế nứt chân chim và kéo dài tuổi thọ công trình.',
        content: [
          'Bê tông móng là bộ phận chịu toàn bộ tải trọng của ngôi nhà. Sau khi đổ bê tông, việc giữ ẩm liên tục trong 7 ngày đầu tiên đóng vai trò quyết định đến cường độ nén của bê tông.',
          'Trong điều kiện thời tiết nắng nóng tại Đà Nẵng, đội ngũ kỹ sư An Việt DT luôn che phủ bao bố ẩm và tưới nước định kỳ giúp bê tông thủy hóa hoàn toàn, tránh hiện tượng co ngót gây nứt bề mặt.',
          'Chủ đầu tư cũng cần lưu ý không chất tải vật liệu nặng lên sàn/móng khi bê tông chưa đạt cường độ tháo dỡ cốp pha theo tiêu chuẩn.'
        ]
      },
      {
        title: '3 Lưu Ý Quan Trọng Giúp Xây Nhà Trọn Gói Không Phát Sinh Chi Phí',
        date: 'Tư vấn xây nhà',
        imageId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        excerpt: 'Chuẩn bị hồ sơ thiết kế chi tiết, thống nhất chủng loại vật tư và chọn nhà thầu uy tín là chìa khóa kiểm soát ngân sách hiệu quả.',
        content: [
          'Thứ nhất, hoàn thiện hồ sơ thiết kế kiến trúc, kết cấu và điện nước chi tiết trước khi khởi công giúp hạn chế tối đa việc đập phá, chỉnh sửa giữa chừng.',
          'Thứ hai, lập bảng phụ lục vật tư rõ ràng từng thương hiệu (thép, xi măng, dây điện, gạch ốp lát, sơn nước) trong hợp đồng thi công trọn gói.',
          'Thứ ba, lựa chọn đơn vị thi công có năng lực thực tế, quy trình giám sát chặt chẽ như An Việt DT để đảm bảo đúng tiến độ và không phát sinh chi phí ngoài dự toán.'
        ]
      },
      {
        title: 'Thiết Kế Nội Thất Tối Ưu Ánh Sáng Và Thông Gió Cho Nhà Phố',
        date: 'Thiết kế nội thất',
        imageId: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        excerpt: 'Giải pháp giếng trời, khoảng lùi ban công và lựa chọn gam màu sáng giúp nhà phố diện tích hẹp luôn thoáng đãng, mát mẻ.',
        content: [
          'Đặc trưng của nhà phố thường bị hạn chế mặt thoáng hai bên hông. Vì vậy bố trí giếng trời kết hợp cầu thang thông tầng giúp đối lưu không khí tự nhiên cực kỳ hiệu quả.',
          'Sử dụng vật liệu nội thất đồng bộ, ưu tiên gam màu trung tính ấm áp cùng ánh sáng phân tầng sẽ mang lại cảm giác rộng rãi và sang trọng cho từng phòng chức năng.'
        ]
      },
      {
        title: 'Kinh Nghiệm Chọn Vật Liệu Xây Dựng Bền Bỉ Với Khí Hậu Ven Biển Đà Nẵng',
        date: 'Vật liệu xây dựng',
        imageId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        excerpt: 'Lựa chọn sơn chống kiềm, hệ nhôm kính chuẩn độ dày và giải pháp chống thấm toàn diện giúp ngôi nhà bền đẹp qua nhiều mùa mưa bão.',
        content: [
          'Khí hậu miền Trung – Đà Nẵng có đặc thù nắng gắt vào mùa hè và mưa bão kéo dài vào cuối năm, đặc biệt các khu vực gần biển có hơi muối dễ ăn mòn kim loại.',
          'An Việt DT khuyến nghị sử dụng hệ cửa nhôm kính sơn tĩnh điện chất lượng cao, phụ kiện inox 304, quy trình chống thấm 2 thành phần cho sân thượng, nhà vệ sinh và tường ngoại thất.'
        ]
      }
    ];

    /**
     * Render danh sách Công trình thực tế (2 cột mobile, 3 cột desktop, KHÔNG nhãn dán)
     */
    function renderRealProjects(filterKey) {
      const container = document.getElementById('realProjectsGrid');
      if (!container) return;

      const filtered = filterKey === 'all'
        ? realProjects
        : realProjects.filter(item => item.categoryKey === filterKey);

      container.innerHTML = filtered.map((item) => {
        const imgSrc = 'https://lh3.googleusercontent.com/d/' + item.id;
        const fallbackSrc = 'https://drive.google.com/thumbnail?id=' + item.id + '&sz=w1000';
        const safeTitle = item.title.replace(/'/g, "\\'");
        const safeCat = item.categoryLabel.replace(/'/g, "\\'");
        const safeDesc = item.description.replace(/'/g, "\\'");

        return `
          <article
            onclick="openDetailModal('${safeTitle}', '${safeCat}', '${imgSrc}', '${fallbackSrc}', '${safeDesc}')"
            class="cursor-pointer group bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md hover:border-brand-accent transition-all flex flex-col"
          >
            <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
              <img
                src="${imgSrc}"
                data-fallback="${fallbackSrc}"
                onerror="handleImgError(this, 'An Viet DT')"
                alt="${item.title}"
                loading="lazy"
                class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
              >
            </div>
            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
              <h3 class="text-[12.5px] sm:text-sm md:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition-colors leading-snug break-words">
                ${item.title}
              </h3>
              <p class="mt-1.5 text-[11px] sm:text-xs text-slate-500 font-medium">
                ${item.categoryLabel}
              </p>
            </div>
          </article>
        `;
      }).join('');
    }

    /**
     * Render danh sách 10 Dự án tại Đà Nẵng (2 cột mobile, 5 cột desktop, KHÔNG nhãn dán)
     */
    function renderDanangProjects() {
      const container = document.getElementById('danangProjectsGrid');
      if (!container) return;

      container.innerHTML = danangProjects.map((item) => {
        const imgSrc = 'https://lh3.googleusercontent.com/d/' + item.id;
        const fallbackSrc = 'https://drive.google.com/thumbnail?id=' + item.id + '&sz=w1000';
        const safeTitle = item.title.replace(/'/g, "\\'");
        const safeLoc = item.location.replace(/'/g, "\\'");
        const desc = 'Dự án được Công ty TNHH Thiết Kế và Xây Dựng An Việt DT thiết kế và thi công tại ' + item.location + '. Cam kết chất lượng kết cấu vững chắc, thẩm mỹ hiện đại và bảo hành dài hạn.';

        return `
          <article
            onclick="openDetailModal('${safeTitle}', '${safeLoc}', '${imgSrc}', '${fallbackSrc}', '${desc}')"
            class="cursor-pointer group bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md hover:border-brand-accent transition-all flex flex-col"
          >
            <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
              <img
                src="${imgSrc}"
                data-fallback="${fallbackSrc}"
                onerror="handleImgError(this, 'Du An Da Nang')"
                alt="${item.title}"
                loading="lazy"
                class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
              >
            </div>
            <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
              <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-primary group-hover:text-brand-accent transition-colors leading-snug break-words">
                ${item.title}
              </h3>
              <p class="mt-1.5 text-[11px] text-slate-500">
                ${item.location}
              </p>
            </div>
          </article>
        `;
      }).join('');
    }

    /**
     * Render 4 bài viết tin tức trang chủ (2 cột mobile, 4 cột desktop)
     */
    function renderArticles() {
      const container = document.getElementById('articlesGrid');
      if (!container) return;

      container.innerHTML = articles.map((article, idx) => {
        const imgSrc = 'https://lh3.googleusercontent.com/d/' + article.imageId;
        const fallbackSrc = 'https://drive.google.com/thumbnail?id=' + article.imageId + '&sz=w800';
        return `
          <article
            onclick="openArticleModal(${idx})"
            class="cursor-pointer group bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm hover:shadow-md hover:border-brand-accent transition-all flex flex-col"
          >
            <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
              <img
                src="${imgSrc}"
                data-fallback="${fallbackSrc}"
                onerror="handleImgError(this, 'Tin Tuc Xay Dung')"
                alt="${article.title}"
                loading="lazy"
                class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
              >
            </div>
            <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
              <div>
                <div class="text-[11px] font-semibold text-brand-accent mb-1">${article.date}</div>
                <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-primary group-hover:text-brand-accent transition-colors leading-snug break-words mb-1.5">
                  ${article.title}
                </h3>
                <p class="hidden sm:block text-xs text-slate-600 leading-relaxed">
                  ${article.excerpt}
                </p>
              </div>
              <div class="mt-2.5 text-xs font-semibold text-brand-primary group-hover:text-brand-accent">
                Xem chi tiết →
              </div>
            </div>
          </article>
        `;
      }).join('');
    }

    /**
     * Modal hiển thị chi tiết công trình / bài viết
     */
    function openDetailModal(title, category, imgSrc, fallbackSrc, description) {
      const modal = document.getElementById('detailModal');
      const modalImg = document.getElementById('modalImage');
      document.getElementById('modalTitle').textContent = title;
      document.getElementById('modalCategory').textContent = category;
      document.getElementById('modalBody').innerHTML = '<p>' + description + '</p>';

      modalImg.dataset.triedFallback = '';
      modalImg.dataset.fallback = fallbackSrc;
      modalImg.onerror = function () { handleImgError(modalImg, title); };
      modalImg.src = imgSrc;
      modalImg.alt = title;

      modal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function openArticleModal(index) {
      const article = articles[index];
      if (!article) return;
      const imgSrc = 'https://lh3.googleusercontent.com/d/' + article.imageId;
      const fallbackSrc = 'https://drive.google.com/thumbnail?id=' + article.imageId + '&sz=w1000';

      const modal = document.getElementById('detailModal');
      const modalImg = document.getElementById('modalImage');
      document.getElementById('modalTitle').textContent = article.title;
      document.getElementById('modalCategory').textContent = article.date;
      document.getElementById('modalBody').innerHTML = article.content.map(p => '<p>' + p + '</p>').join('');

      modalImg.dataset.triedFallback = '';
      modalImg.dataset.fallback = fallbackSrc;
      modalImg.onerror = function () { handleImgError(modalImg, article.title); };
      modalImg.src = imgSrc;
      modalImg.alt = article.title;

      modal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      document.body.style.overflow = '';
    }

    /**
     * Chọn nhanh gói báo giá và cuộn mượt xuống Form yêu cầu báo giá
     */
    function selectQuoteService(serviceName) {
      const selectEl = document.getElementById('projectType');
      if (selectEl) {
        selectEl.value = serviceName;
      }
      const contactSection = document.getElementById('lien-he');
      if (contactSection) {
        contactSection.scrollIntoView({ behavior: 'smooth' });
      }
      setTimeout(() => {
        const nameInput = document.getElementById('customerName');
        if (nameInput) nameInput.focus();
      }, 500);
    }

    /**
     * Khởi tạo toàn bộ tính năng sau khi trang tải xong
     */
    document.addEventListener('DOMContentLoaded', function () {
      // 1. Render các lưới nội dung
      renderRealProjects('all');
      renderDanangProjects();
      renderArticles();

      // 2. Xử lý bộ lọc danh mục công trình thực tế
      const filterButtons = document.querySelectorAll('.filter-btn');
      filterButtons.forEach((btn) => {
        btn.addEventListener('click', function () {
          filterButtons.forEach((b) => {
            b.classList.remove('bg-brand-primary', 'text-white', 'border-brand-primary', 'active');
            b.classList.add('bg-white', 'text-slate-700', 'border-slate-200');
          });
          this.classList.remove('bg-white', 'text-slate-700', 'border-slate-200');
          this.classList.add('bg-brand-primary', 'text-white', 'border-brand-primary', 'active');

          const filterKey = this.getAttribute('data-filter');
          renderRealProjects(filterKey);
        });
      });

      // 3. Xử lý 2 Banner tự trượt chuyên nghiệp + vuốt cảm ứng trên điện thoại
      const slides = document.querySelectorAll('.hero-slide');
      const dots = document.querySelectorAll('.slide-dot');
      let currentSlide = 0;
      let sliderTimer = null;

      function showSlide(index) {
        currentSlide = (index + slides.length) % slides.length;
        slides.forEach((s, i) => {
          s.classList.toggle('active', i === currentSlide);
        });
        dots.forEach((d, i) => {
          if (i === currentSlide) {
            d.classList.remove('w-2.5', 'bg-white/60');
            d.classList.add('w-7', 'bg-brand-accent');
          } else {
            d.classList.remove('w-7', 'bg-brand-accent');
            d.classList.add('w-2.5', 'bg-white/60');
          }
        });
      }

      function startAutoSlide() {
        stopAutoSlide();
        sliderTimer = setInterval(() => {
          showSlide(currentSlide + 1);
        }, 5500);
      }

      function stopAutoSlide() {
        if (sliderTimer) clearInterval(sliderTimer);
      }

      document.getElementById('prevSlideBtn').addEventListener('click', function () {
        showSlide(currentSlide - 1);
        startAutoSlide();
      });

      document.getElementById('nextSlideBtn').addEventListener('click', function () {
        showSlide(currentSlide + 1);
        startAutoSlide();
      });

      dots.forEach((dot) => {
        dot.addEventListener('click', function () {
          const idx = parseInt(this.getAttribute('data-slide-index'), 10);
          showSlide(idx);
          startAutoSlide();
        });
      });

      // Hỗ trợ vuốt trái/phải banner trên điện thoại
      const heroSlider = document.getElementById('heroSlider');
      let touchStartX = 0;
      heroSlider.addEventListener('touchstart', function (e) {
        touchStartX = e.changedTouches[0].screenX;
      }, { passive: true });
      heroSlider.addEventListener('touchend', function (e) {
        const diffX = e.changedTouches[0].screenX - touchStartX;
        if (Math.abs(diffX) > 45) {
          showSlide(diffX < 0 ? currentSlide + 1 : currentSlide - 1);
          startAutoSlide();
        }
      }, { passive: true });

      startAutoSlide();

      // 4. Xử lý Menu điện thoại
      const mobileMenuBtn = document.getElementById('mobileMenuBtn');
      const mobileMenuPanel = document.getElementById('mobileMenuPanel');
      const menuIconOpen = document.getElementById('menuIconOpen');
      const menuIconClose = document.getElementById('menuIconClose');

      function toggleMobileMenu(forceClose) {
        const willHide = forceClose === true ? true : !mobileMenuPanel.classList.contains('hidden');
        mobileMenuPanel.classList.toggle('hidden', willHide);
        menuIconOpen.classList.toggle('hidden', !willHide);
        menuIconClose.classList.toggle('hidden', willHide);
      }

      mobileMenuBtn.addEventListener('click', () => toggleMobileMenu());
      document.querySelectorAll('.mobile-nav-link').forEach((link) => {
        link.addEventListener('click', () => toggleMobileMenu(true));
      });

      // 5. Đóng Modal khi bấm nút đóng, bấm ra ngoài hoặc nhấn phím ESC
      document.getElementById('closeModalBtn').addEventListener('click', closeDetailModal);
      document.getElementById('detailModal').addEventListener('click', function (e) {
        if (e.target === this) closeDetailModal();
      });
      document.addEventListener('keydown', function (e) {
        if (e.key === 'Escape') closeDetailModal();
      });

      // 6. Xử lý gửi Form yêu cầu tư vấn & báo giá (thông báo ngay trong trang)
      const quoteForm = document.getElementById('quoteForm');
      const formFeedback = document.getElementById('formFeedback');

      quoteForm.addEventListener('submit', function (e) {
        e.preventDefault();
        const name = document.getElementById('customerName').value.trim();
        const phone = document.getElementById('customerPhone').value.trim();
        const projectType = document.getElementById('projectType').value;

        formFeedback.classList.remove('hidden', 'bg-red-50', 'text-red-700', 'border-red-200', 'bg-emerald-50', 'text-emerald-800', 'border-emerald-200');

        if (!name || !phone) {
          formFeedback.classList.add('bg-red-50', 'text-red-700', 'border', 'border-red-200');
          formFeedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để kỹ sư An Việt DT liên hệ tư vấn.';
          return;
        }

        const phoneClean = phone.replace(/[\s.-]/g, '');
        if (!/^[0-9]{9,12}$/.test(phoneClean)) {
          formFeedback.classList.add('bg-red-50', 'text-red-700', 'border', 'border-red-200');
          formFeedback.textContent = 'Số điện thoại chưa đúng định dạng. Vui lòng kiểm tra lại.';
          return;
        }

        formFeedback.classList.add('bg-emerald-50', 'text-emerald-800', 'border', 'border-emerald-200');
        formFeedback.innerHTML = 'Cảm ơn <strong>' + name + '</strong>! Yêu cầu tư vấn hạng mục <strong>' + projectType + '</strong> đã được ghi nhận. Kỹ sư An Việt DT sẽ liên hệ qua số <strong>' + phone + '</strong> trong thời gian sớm nhất (Hotline hỗ trợ nhanh: 0982.212.347).';
        quoteForm.reset();
      });
    });
  </script>
</body>
</html>
