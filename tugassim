<!-- Eksplor Jasa Mahasiswa - SWALIS -->
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="shell-type" content="web_standard">
  <title>SWALIS - Marketplace Jasa Mahasiswa UIN Walisongo Semarang</title>
  
  <!-- Google Fonts & Material Symbols -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&display=swap" rel="stylesheet">
  
  <style>
    @layer base {
      html, body {
        margin: 0;
        padding: 0;
      }
      body {
        overscroll-behavior: none;
      }
      main > :first-child {
        margin-top: 0 !important;
      }
      main > :last-child {
        margin-bottom: 0 !important;
      }
    }
    ::-webkit-scrollbar {
      display: none;
    }
  </style>

  <!-- Tailwind CSS CDN & Config -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script id="tailwind-config">
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "surface-bright": "#f9f9ff",
            "on-primary-fixed-variant": "#0f5132",
            "background": "#f9f9ff",
            "secondary-fixed-dim": "#e9c349",
            "on-tertiary-fixed": "#001d35",
            "primary": "#003820",
            "surface-dim": "#cfdaf2",
            "primary-container": "#0f5132",
            "outline": "#707971",
            "amber-highlight": "#E5A93C",
            "on-primary-fixed": "#002111",
            "error": "#ba1a1a",
            "ktm-verified": "#0D9488",
            "secondary-container": "#fed65b",
            "on-tertiary-container": "#8eb8e9",
            "error-container": "#ffdad6",
            "on-error-container": "#93000a",
            "secondary-fixed": "#ffe088",
            "on-background": "#111c2d",
            "emerald-accent": "#198754",
            "outline-variant": "#c0c9c0",
            "on-secondary": "#ffffff",
            "inverse-on-surface": "#ecf1ff",
            "tertiary-fixed-dim": "#a0cafc",
            "surface-container-highest": "#d8e3fb",
            "on-secondary-fixed-variant": "#574500",
            "on-primary-container": "#84c39b",
            "surface-ice": "#F2F6FA",
            "tertiary": "#003257",
            "secondary": "#735c00",
            "tertiary-fixed": "#d1e4ff",
            "surface-container-low": "#f0f3ff",
            "surface-container-lowest": "#ffffff",
            "surface-variant": "#d8e3fb",
            "surface-container": "#e7eeff",
            "surface": "#f9f9ff",
            "surface-container-high": "#dee8ff",
            "surface-tint": "#2d6a48",
            "inverse-surface": "#263143",
            "on-secondary-fixed": "#241a00",
            "primary-fixed": "#b0f1c7",
            "inverse-primary": "#95d4ac",
            "on-surface-variant": "#404942",
            "on-surface": "#111c2d",
            "on-tertiary": "#ffffff",
            "on-tertiary-fixed-variant": "#184974",
            "anti-joki-badge": "#991B1B",
            "tertiary-container": "#184974",
            "on-secondary-container": "#745c00",
            "on-primary": "#ffffff",
            "surface-subtle": "#F8FAFC",
            "on-error": "#ffffff",
            "primary-fixed-dim": "#95d4ac"
          },
          borderRadius: {
            DEFAULT: "0.25rem",
            lg: "0.5rem",
            xl: "0.75rem",
            full: "9999px"
          },
          spacing: {
            "space-md": "1rem",
            "space-sm": "0.5rem",
            "margin": "2rem",
            "gutter-sm": "1rem",
            "space-lg": "1.5rem",
            "gutter": "1.5rem",
            "space-xl": "2.5rem",
            "space-xs": "0.25rem",
            "margin-mobile": "1rem"
          },
          fontFamily: {
            "label-lg": ["Space Grotesk"],
            "headline-lg": ["Plus Jakarta Sans"],
            "headline-md": ["Plus Jakarta Sans"],
            "body-md": ["Plus Jakarta Sans"],
            "headline-lg-mobile": ["Plus Jakarta Sans"],
            "body-sm": ["Plus Jakarta Sans"],
            "body-lg": ["Plus Jakarta Sans"],
            "label-sm": ["Space Grotesk"],
            "label-md": ["Space Grotesk"],
            "headline-xl-mobile": ["Plus Jakarta Sans"],
            "headline-xl": ["Plus Jakarta Sans"],
            "headline-sm": ["Plus Jakarta Sans"]
          },
          fontSize: {
            "label-lg": ["14px", { lineHeight: "20px", letterSpacing: "0.02em", fontWeight: "600" }],
            "headline-lg": ["32px", { lineHeight: "40px", letterSpacing: "-0.015em", fontWeight: "700" }],
            "headline-md": ["22px", { lineHeight: "28px", fontWeight: "700" }],
            "body-md": ["14px", { lineHeight: "22px", fontWeight: "400" }],
            "headline-lg-mobile": ["24px", { lineHeight: "32px", letterSpacing: "-0.015em", fontWeight: "700" }],
            "body-sm": ["12px", { lineHeight: "18px", fontWeight: "400" }],
            "body-lg": ["16px", { lineHeight: "26px", fontWeight: "400" }],
            "label-sm": ["10px", { lineHeight: "14px", letterSpacing: "0.05em", fontWeight: "700" }],
            "label-md": ["12px", { lineHeight: "16px", letterSpacing: "0.03em", fontWeight: "600" }],
            "headline-xl-mobile": ["30px", { lineHeight: "36px", letterSpacing: "-0.02em", fontWeight: "800" }],
            "headline-xl": ["40px", { lineHeight: "48px", letterSpacing: "-0.02em", fontWeight: "800" }],
            "headline-sm": ["18px", { lineHeight: "24px", fontWeight: "600" }]
          }
        }
      }
    };
  </script>
</head>
<body class="bg-surface font-body-md text-on-surface antialiased">

  <!-- HEADER NAVBAR -->
  <header class="fixed top-0 w-full z-50 bg-surface/90 backdrop-blur-xl shadow-[0_1px_8px_rgba(0,0,0,0.04)]">
    <div class="w-full px-margin">
      <div class="h-20 flex items-center justify-between gap-gutter">
        
        <!-- Brand Logo & Info -->
        <div class="flex items-center gap-gutter flex-shrink-0">
          <div class="flex items-center gap-space-sm">
            <img alt="SWALIS Brand Logo" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA6b6th2SN9GPHxA9enH585sssukKu7ggTJiBazrSt4jo06QUlysbU0p_hwsrc3Hz_6yIsD9W1CsrmJUUc0fDG06B1Ysl1n1pPh42QKgcZrKzcdR6RSsYlpy2BvYsrW0ZVhaEHQ0jxAOhHs174J93XAaMA6_qdKluR1cYR7kh5zagYES4w5mMhf7yRx68FT_8tmQnclQrE1hYzXAVSrG_6cy7J1_B0RnWcs3TTyqU6rUKKUywMgO-M">
            <div class="flex flex-col">
              <div class="flex items-center gap-space-xs">
                <span class="font-headline-sm text-headline-sm text-primary tracking-tight font-bold">SWALIS</span>
                <span class="bg-primary/10 text-primary font-label-sm text-label-sm px-space-xs py-0.5 rounded">UIN Walisongo</span>
              </div>
              <span class="font-body-sm text-body-sm text-on-surface-variant hidden lg:inline">Skill Walisongo Marketplace</span>
            </div>
          </div>
          <div class="hidden xl:flex items-center gap-space-xs bg-error-container/60 text-anti-joki-badge px-space-sm py-1 rounded-full text-label-sm font-label-sm border border-error-container">
            <span class="material-symbols-outlined text-[16px]">gavel</span>
            <span>Bebas Joki Akademik</span>
          </div>
        </div>

        <!-- Search Bar Header -->
        <div class="hidden md:flex flex-1 max-w-xl items-center relative">
          <div class="w-full flex items-center bg-surface-container-lowest rounded-lg shadow-[0_2px_10px_rgba(15,81,50,0.06)] px-space-sm py-1.5">
            <div class="flex items-center gap-space-xs border-r border-outline-variant pr-space-sm mr-space-sm text-on-surface-variant font-label-md text-label-md">
              <span class="material-symbols-outlined text-primary text-[18px]">category</span>
              <select class="bg-transparent text-on-surface text-body-sm font-body-sm focus:outline-none cursor-pointer">
                <option>Semua Kategori</option>
                <option>Teknologi &amp; Coding</option>
                <option>Desain Grafis &amp; Video</option>
                <option>Terjemah &amp; Bahasa</option>
                <option>Tutor Non-Joki</option>
                <option>Riset Data &amp; Statistik</option>
              </select>
            </div>
            <input class="w-full bg-transparent text-body-sm font-body-sm text-on-surface placeholder:text-outline focus:outline-none" placeholder="Cari jasa mahasiswa (contoh: Website Next.js, Desain Poster)..." type="text">
            <button class="bg-primary text-on-primary p-1.5 rounded-lg hover:bg-emerald-accent transition-colors flex items-center justify-center" type="button">
              <span class="material-symbols-outlined text-[18px]">search</span>
            </button>
          </div>
        </div>

        <!-- Navigation Links -->
        <nav class="hidden 2xl:flex items-center gap-space-md">
          <a aria-current="page" class="px-space-sm py-1.5 transition-colors text-primary font-label-md bg-surface-container-high rounded-lg" href="#">Eksplor Jasa</a>
          <a class="text-on-surface-variant hover:text-on-surface font-label-md text-label-md px-space-sm py-1.5 transition-colors" href="#">Request Jasa (Bidding)</a>
          <a class="text-on-surface-variant hover:text-on-surface font-label-md text-label-md px-space-sm py-1.5 transition-colors" href="#">Cara Kerja</a>
          <a class="text-on-surface-variant hover:text-on-surface font-label-md text-label-md px-space-sm py-1.5 transition-colors" href="#">Tentang SWALIS</a>
        </nav>

        <!-- User Controls & Profile -->
        <div class="flex items-center gap-space-md flex-shrink-0">
          <div class="hidden lg:flex items-center bg-surface-container-high p-1 rounded-full">
            <button class="px-space-sm py-1 rounded-full text-label-sm font-label-sm bg-surface-container-lowest text-primary shadow-sm font-bold" type="button">Mode: Pelanggan</button>
            <button class="px-space-sm py-1 rounded-full text-label-sm font-label-sm text-on-surface-variant hover:text-on-surface flex items-center gap-1 transition-colors" type="button">
              <span class="w-1.5 h-1.5 rounded-full bg-ktm-verified"></span>Freelancer (KTM)
            </button>
          </div>
          <a class="hidden sm:inline-flex items-center gap-1 bg-primary text-on-primary font-label-md text-label-md px-space-md py-2 rounded-lg hover:bg-emerald-accent transition-all" href="#">
            <span class="material-symbols-outlined text-[18px]">post_add</span>
            <span>Pasang Request</span>
          </a>
          <div class="relative">
            <button class="p-2 rounded-full text-on-surface-variant hover:bg-surface-container-high hover:text-on-surface transition-colors flex items-center relative" type="button">
              <span class="material-symbols-outlined text-[22px]">notifications</span>
              <span class="absolute top-1.5 right-1.5 w-2.5 h-2.5 bg-amber-highlight rounded-full"></span>
            </button>
          </div>
          <div class="flex items-center gap-space-sm pl-space-xs">
            <div class="relative flex items-center gap-space-xs cursor-pointer">
              <div class="relative">
                <img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDMru77qTsFBMrnhr3wRzk5Qr6oA0afd8F1J94LFjgcBWQktxUdegcdZ5VxhxB_-sH_F-BV0DLfhFajlFwIhH9S6pQrQe_IXr7u7upDhUZ4r9syEMt6sg78M4y6DE8kp6Yv2HoW8qg03fxhpp3K-sZtPCbIoSca-rd0I9UXId-DBm6sk-aoBWy1FBhQrEgmX7SDfO1J7CPIoUoqkXlRbRWBSzIjUeup5ceJvJu2ySs5Yfw9G9lB4C0">
                <span class="absolute -bottom-1 -right-1 w-3.5 h-3.5 bg-ktm-verified text-on-primary rounded-full flex items-center justify-center text-[9px] font-bold ring-2 ring-surface" title="KTM Terverifikasi UIN WS">
                  <span class="material-symbols-outlined text-[10px]">verified</span>
                </span>
              </div>
              <div class="hidden xl:flex flex-col text-left">
                <span class="font-label-sm text-label-sm text-on-surface truncate max-w-[140px]">M. Hanif Ladzuardi</span>
                <span class="text-[10px] text-ktm-verified font-bold">KTM Terverifikasi • TI FST</span>
              </div>
              <span class="material-symbols-outlined text-on-surface-variant text-[18px]">expand_more</span>
            </div>
          </div>
        </div>

      </div>
    </div>
  </header>

  <!-- MAIN CONTAINER -->
  <main class="w-full pt-20 bg-surface min-h-[calc(100vh-20rem)]">
    <div class="flex flex-col w-full">
      
      <!-- Top Academic Integrity Banner -->
      <section class="w-full bg-error-container/80 text-on-error-container py-3 px-margin">
        <div class="w-full flex flex-col md:flex-row items-center justify-between gap-space-sm">
          <div class="flex items-center gap-space-sm">
            <div class="w-8 h-8 rounded-full bg-anti-joki-badge text-on-primary flex items-center justify-center flex-shrink-0 shadow-sm">
              <span class="material-symbols-outlined text-[18px]">verified_user</span>
            </div>
            <div>
              <span class="font-headline-sm text-sm font-bold tracking-tight text-anti-joki-badge uppercase block md:inline md:mr-2">Prinsip Integritas Akademik:</span>
              <span class="font-body-md text-xs md:text-sm text-on-error-container font-medium">
                Melarang keras joki skripsi, tugas akhir utuh, ujian, dan kuis. Hanya melayani jasa pendukung kreatif, pemrograman, bimbingan belajar/tutoring, dan pengetikan administratif.
              </span>
            </div>
          </div>
          <a class="inline-flex items-center gap-1 font-label-md text-xs text-anti-joki-badge hover:underline whitespace-nowrap font-bold" href="#">
            <span>Baca Pakta Etika SIM FST</span>
            <span class="material-symbols-outlined text-[14px]">arrow_forward</span>
          </a>
        </div>
      </section>

      <!-- Hero Section -->
      <section class="w-full px-margin pt-space-lg pb-space-xl relative overflow-hidden bg-gradient-to-b from-surface to-surface-container-low/50">
        <div class="max-w-7xl mx-auto flex flex-col items-center text-center relative z-10">
          
          <!-- Institutional Pill / Badge -->
          <div class="inline-flex items-center gap-2 px-space-md py-1.5 rounded-full bg-surface-container-lowest shadow-sm mb-space-md">
            <span class="w-2 h-2 rounded-full bg-emerald-accent"></span>
            <span class="font-label-md text-label-md text-primary font-bold tracking-wider uppercase">Inisiatif SIM TI FST UIN Walisongo Semarang</span>
            <span class="bg-primary/10 text-primary text-label-sm font-label-sm px-2 py-0.5 rounded-full font-bold">Versi 2026</span>
          </div>

          <!-- Main Headline -->
          <h1 class="font-headline-xl text-3xl sm:text-4xl lg:text-[44px] lg:leading-[52px] text-on-background font-extrabold max-w-4xl tracking-tight mb-space-sm">
            Marketplace Jasa Mahasiswa <br class="hidden sm:block">
            <span class="text-primary-container relative inline-block">
              UIN Walisongo Semarang
              <svg class="absolute -bottom-2 left-0 w-full" fill="none" height="8" viewBox="0 0 200 8" xmlns="http://www.w3.org/2000/svg">
                <path d="M1 5.5C40 2 160 2 199 5.5" stroke="#E5A93C" stroke-linecap="round" stroke-width="3"></path>
              </svg>
            </span>
          </h1>
          <p class="font-body-lg text-body-lg text-on-surface-variant max-w-2xl mt-space-xs mb-space-lg font-normal">
            Solusi terpercaya menghubungkan mahasiswa bertalenta dengan kebutuhan jasa kampus, UMKM, dan masyarakat. 100% Mahasiswa Terverifikasi KTM &amp; Beretika Bebas Joki.
          </p>

          <!-- Smart Search Box Component -->
          <div class="w-full max-w-4xl bg-surface-container-lowest p-3 sm:p-4 rounded-xl shadow-xl mb-space-lg">
            <form class="grid grid-cols-1 sm:grid-cols-12 gap-2 sm:gap-3 items-center" id="search-form">
              <div class="sm:col-span-5 relative flex items-center bg-surface-container-low/60 rounded-lg px-3 py-2.5">
                <span class="material-symbols-outlined text-outline text-[20px] mr-2">search</span>
                <input class="w-full bg-transparent text-body-md font-body-md text-on-surface placeholder:text-outline focus:outline-none" id="keyword-input" placeholder="Cari contoh: Web Dev, Logo, Tutor..." type="text">
              </div>
              <div class="sm:col-span-3 relative flex items-center bg-surface-container-low/60 rounded-lg px-3 py-2.5">
                <span class="material-symbols-outlined text-primary text-[18px] mr-2">category</span>
                <select class="w-full bg-transparent text-body-sm font-body-sm text-on-surface focus:outline-none cursor-pointer" id="kategori-filter">
                  <option value="all">Semua Kategori</option>
                  <option value="desain">Desain Grafis</option>
                  <option value="web">Web &amp; Pemrograman</option>
                  <option value="video">Video &amp; Animasi</option>
                  <option value="bahasa">Penerjemahan &amp; Bahasa</option>
                  <option value="tutor">Tutor &amp; Belajar Bareng</option>
                  <option value="ketik">Pengetikan &amp; Dokumen</option>
                </select>
              </div>
              <div class="sm:col-span-2 relative flex items-center bg-surface-container-low/60 rounded-lg px-3 py-2.5">
                <span class="material-symbols-outlined text-secondary text-[18px] mr-1.5">payments</span>
                <select class="w-full bg-transparent text-body-sm font-body-sm text-on-surface focus:outline-none cursor-pointer" id="harga-filter">
                  <option value="all">Kisaran Harga</option>
                  <option value="under50">&lt; Rp 50.000</option>
                  <option value="50-100">Rp 50k - 100k</option>
                  <option value="over100">&gt; Rp 100.000</option>
                </select>
              </div>
              <div class="sm:col-span-2">
                <button class="w-full bg-primary text-on-primary hover:bg-emerald-accent font-label-lg text-label-lg py-2.5 px-4 rounded-lg flex items-center justify-center gap-1.5 transition-colors shadow-sm" id="btn-search-trigger" type="button">
                  <span>Temukan</span>
                  <span class="material-symbols-outlined text-[18px]">arrow_forward</span>
                </button>
              </div>
            </form>
            
            <!-- Quick Category Chips -->
            <div class="flex items-center gap-2 pt-3 flex-wrap text-left border-t border-surface-container-high/40 mt-3">
              <span class="font-label-sm text-label-sm text-on-surface-variant font-bold uppercase tracking-wider">Kategori Cepat:</span>
              <button class="chip-btn px-2.5 py-1 rounded-full text-xs font-label-md bg-surface-container hover:bg-primary-container hover:text-on-primary transition-all text-on-surface-variant" type="button">Desain Grafis</button>
              <button class="chip-btn px-2.5 py-1 rounded-full text-xs font-label-md bg-surface-container hover:bg-primary-container hover:text-on-primary transition-all text-on-surface-variant" type="button">Video &amp; Animasi</button>
              <button class="chip-btn px-2.5 py-1 rounded-full text-xs font-label-md bg-surface-container hover:bg-primary-container hover:text-on-primary transition-all text-on-surface-variant" type="button">Web &amp; Pemrograman</button>
              <button class="chip-btn px-2.5 py-1 rounded-full text-xs font-label-md bg-surface-container hover:bg-primary-container hover:text-on-primary transition-all text-on-surface-variant" type="button">Penerjemahan &amp; Bahasa</button>
              <button class="chip-btn px-2.5 py-1 rounded-full text-xs font-label-md bg-surface-container hover:bg-primary-container hover:text-on-primary transition-all text-on-surface-variant" type="button">Tutor Non-Joki</button>
              <button class="chip-btn px-2.5 py-1 rounded-full text-xs font-label-md bg-surface-container hover:bg-primary-container hover:text-on-primary transition-all text-on-surface-variant" type="button">Format Dokumen</button>
            </div>
          </div>

          <!-- Live Stat Counter Badges -->
          <div class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-4 w-full max-w-4xl">
            <div class="bg-surface-container-lowest p-3.5 rounded-lg shadow-sm flex items-center gap-3 text-left">
              <div class="w-10 h-10 rounded-lg bg-primary/10 text-primary flex items-center justify-center flex-shrink-0">
                <span class="material-symbols-outlined text-[24px]">verified</span>
              </div>
              <div>
                <div class="font-headline-sm text-lg font-bold text-primary">450+</div>
                <div class="font-body-sm text-xs text-on-surface-variant leading-tight">Mahasiswa KTM Terverifikasi</div>
              </div>
            </div>
            <div class="bg-surface-container-lowest p-3.5 rounded-lg shadow-sm flex items-center gap-3 text-left">
              <div class="w-10 h-10 rounded-lg bg-emerald-accent/10 text-emerald-accent flex items-center justify-center flex-shrink-0">
                <span class="material-symbols-outlined text-[24px]">task_alt</span>
              </div>
              <div>
                <div class="font-headline-sm text-lg font-bold text-on-surface">1.280+</div>
                <div class="font-body-sm text-xs text-on-surface-variant leading-tight">Proyek Kampus Selesai</div>
              </div>
            </div>
            <div class="bg-surface-container-lowest p-3.5 rounded-lg shadow-sm flex items-center gap-3 text-left">
              <div class="w-10 h-10 rounded-lg bg-amber-highlight/15 text-amber-highlight flex items-center justify-center flex-shrink-0">
                <span class="material-symbols-outlined text-[24px]">star</span>
              </div>
              <div>
                <div class="font-headline-sm text-lg font-bold text-on-surface">4.9 / 5.0</div>
                <div class="font-body-sm text-xs text-on-surface-variant leading-tight">Kepuasan Klien Kampus</div>
              </div>
            </div>
            <div class="bg-surface-container-lowest p-3.5 rounded-lg shadow-sm flex items-center gap-3 text-left">
              <div class="w-10 h-10 rounded-lg bg-error/10 text-anti-joki-badge flex items-center justify-center flex-shrink-0">
                <span class="material-symbols-outlined text-[24px]">gavel</span>
              </div>
              <div>
                <div class="font-headline-sm text-lg font-bold text-anti-joki-badge">100%</div>
                <div class="font-body-sm text-xs text-on-surface-variant leading-tight">Etika Anti-Joki Akademik</div>
              </div>
            </div>
          </div>

        </div>
      </section>

      <!-- Service Catalog Section -->
      <section class="w-full px-margin py-space-xl">
        <div class="max-w-7xl mx-auto flex flex-col gap-space-lg">
          
          <div class="flex flex-col md:flex-row md:items-end justify-between gap-space-md">
            <div>
              <div class="flex items-center gap-2 mb-1">
                <span class="w-2.5 h-2.5 bg-primary rounded-full"></span>
                <span class="font-label-sm text-label-sm font-bold tracking-widest text-primary uppercase">Eksplorasi Jasa Pilihan</span>
              </div>
              <h2 class="font-headline-lg text-2xl sm:text-3xl text-on-background font-bold tracking-tight">
                Katalog Talenta Mahasiswa Terverifikasi
              </h2>
              <p class="font-body-md text-body-md text-on-surface-variant">
                Pilih jasa langsung atau gunakan penawaran kompetitif dengan garansi 2x revisi gratis dan arsip Google Drive.
              </p>
            </div>
            
            <div class="flex items-center flex-wrap gap-2">
              <div class="flex items-center bg-surface-container-lowest rounded-lg p-1 shadow-sm">
                <button class="px-3 py-1.5 rounded text-xs font-label-md bg-primary text-on-primary font-bold" type="button">Semua</button>
                <button class="px-3 py-1.5 rounded text-xs font-label-md text-on-surface-variant hover:text-on-surface" type="button">Terpopuler</button>
                <button class="px-3 py-1.5 rounded text-xs font-label-md text-on-surface-variant hover:text-on-surface" type="button">Rating 5.0</button>
                <button class="px-3 py-1.5 rounded text-xs font-label-md text-on-surface-variant hover:text-on-surface" type="button">Harga Terendah</button>
              </div>
              <div class="inline-flex items-center gap-1.5 px-3 py-2 bg-surface-container-lowest rounded-lg text-xs font-label-md text-primary font-bold shadow-sm">
                <span class="material-symbols-outlined text-[16px] text-ktm-verified">replay</span>
                <span>2x Revisi Gratis</span>
              </div>
            </div>
          </div>

          <!-- Service Cards Grid -->
          <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-gutter" id="service-catalog-grid">
            
            <!-- Card 1: Ahmad Marsel -->
            <div class="group bg-surface-container-lowest rounded-xl shadow-sm hover:shadow-xl transition-all duration-300 flex flex-col overflow-hidden relative" data-category="desain" data-price="75000">
              <div class="relative w-full h-48 bg-surface-container overflow-hidden">
                <img alt="Presentasi Sidang" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBI3oAUUlm8CxGOr9qE44ftpamAR7tchI1shEALGMDK6ab_AvCmfkHmuMm7TlD-0ft2WBVwj9EQzwwErdkTODAgLdJwKkJlwhhdx8SjoB7Ev1MbmNISpO87PMKZOMnDC3ezgb27Myggq0JMfCD5AaqqB0kvZnAcWjuohoSwqUu4BwPaWPkJfThzuh79tHXQUKlzUupNDZeaBtrbkRIDXxrsI9V7l-40CH0oCsLUegiSZU-zo7TlgO8">
                <div class="absolute top-3 left-3 bg-primary text-on-primary text-[10px] font-label-sm font-bold uppercase tracking-wider px-2 py-1 rounded">Desain Grafis</div>
                <div class="absolute top-3 right-3 bg-surface-container-lowest/90 backdrop-blur text-primary text-[11px] font-label-md font-bold px-2 py-0.5 rounded shadow-sm flex items-center gap-1">
                  <span class="material-symbols-outlined text-[14px] text-amber-highlight" style="font-variation-settings: 'FILL' 1;">star</span>
                  <span>4.9</span> <span class="text-on-surface-variant font-normal">(42)</span>
                </div>
                <div class="absolute bottom-2 right-2 bg-surface-container-lowest/95 backdrop-blur text-ktm-verified text-[10px] font-label-sm font-bold px-2 py-1 rounded shadow-sm flex items-center gap-1">
                  <span class="material-symbols-outlined text-[13px]">cloud</span> <span>Preview GDrive</span>
                </div>
              </div>
              <div class="p-space-md flex-1 flex flex-col justify-between">
                <div>
                  <div class="flex items-center gap-2 mb-2">
                    <img alt="Ahmad Marsel" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuACAUqUo982WnZnOZ5y67-4KFcz4I4YXybIk3RrqKWTfK1fcZDjVuFQKKPwvFsezcAfXFVc4kCf6Hpp4L3j2GZLbzqGsg96F2ixmS6QT7IGcYrwR_HmULBcDz9DbU0MqWGbLdUhMVNdH2_WEbPHobLbZ4ZJlG-KFRgKsm5cfW_wUEOO17v_wUEAhUKgp3edXwBWAfczc7wa5zQ9VhlOilP8Y2eyIX5F8CGAl47o6OgmYg8qtEPI-QY">
                    <div class="flex flex-col">
                      <div class="flex items-center gap-1">
                        <span class="font-label-md text-xs font-bold text-on-surface truncate max-w-[130px]">Ahmad Marsel</span>
                        <span class="inline-flex items-center text-[10px] text-ktm-verified font-bold"><span class="material-symbols-outlined text-[14px]">verified</span></span>
                      </div>
                      <span class="font-body-sm text-[11px] text-on-surface-variant">TI • FST UIN WS</span>
                    </div>
                  </div>
                  <h3 class="font-headline-sm text-base font-bold text-on-surface line-clamp-2 hover:text-primary transition-colors mb-2">
                    Jasa Desain Presentasi Sidang &amp; Pitch Deck Interaktif
                  </h3>
                  <div class="flex items-center gap-2 flex-wrap mb-3">
                    <span class="inline-flex items-center gap-1 px-2 py-0.5 rounded bg-surface-ice text-primary font-label-sm text-[10px] font-semibold"><span class="material-symbols-outlined text-[12px]">replay</span> 2x Revisi Gratis</span>
                    <span class="inline-flex items-center gap-1 px-2 py-0.5 rounded bg-surface-container-high text-on-surface-variant font-label-sm text-[10px]"><span class="material-symbols-outlined text-[12px]">schedule</span> 1 Hari Jadi</span>
                  </div>
                </div>
                <div class="pt-3 border-t border-surface-container-high/60 flex items-center justify-between">
                  <div>
                    <span class="text-[11px] text-on-surface-variant font-body-sm block">Mulai dari</span>
                    <span class="font-label-lg text-lg font-bold text-primary">Rp 75.000</span>
                  </div>
                  <div class="flex items-center gap-1.5">
                    <button class="px-2.5 py-1.5 rounded-lg text-xs font-label-md text-on-surface hover:bg-surface-container-high transition-colors" type="button">Detail</button>
                    <button class="px-3 py-1.5 rounded-lg text-xs font-label-md bg-primary text-on-primary hover:bg-emerald-accent transition-colors font-bold shadow-sm" type="button">Pesan</button>
                  </div>
                </div>
              </div>
            </div>

            <!-- Card 2: M. Hanif Ladzuardi -->
            <div class="group bg-surface-container-lowest rounded-xl shadow-sm hover:shadow-xl transition-all duration-300 flex flex-col overflow-hidden relative" data-category="web" data-price="250000">
              <div class="relative w-full h-48 bg-surface-container overflow-hidden">
                <img alt="Web Coding" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC7kuRw3C-j6Hks0Typ1TKOtmN4yDspazVzcCPAakglYg_He6K0h3estBy6pFPnAhFcxi6GbnjjqWZi7piKEzFtUA79dEoSzbLmOGKL1veolSENsFWyqDISkmZGGzrRHTicKlfF_2t5kPxWPJQLPwoW4YfQw-Bp45aQPcz5Vi-RQOIUT1rFCgRr-0nnH8OsnFT8k6vkddMI7EhZ5kgeBbdtvq3ubEUl80ISkYY8rtY2Dgy0DSw9ClE">
                <div class="absolute top-3 left-3 bg-tertiary-container text-on-primary text-[10px] font-label-sm font-bold uppercase tracking-wider px-2 py-1 rounded">Web &amp; Coding</div>
                <div class="absolute top-3 right-3 bg-surface-container-lowest/90 backdrop-blur text-primary text-[11px] font-label-md font-bold px-2 py-0.5 rounded shadow-sm flex items-center gap-1">
                  <span class="material-symbols-outlined text-[14px] text-amber-highlight" style="font-variation-settings: 'FILL' 1;">star</span>
                  <span>5.0</span> <span class="text-on-surface-variant font-normal">(68)</span>
                </div>
                <div class="absolute bottom-2 right-2 bg-surface-container-lowest/95 backdrop-blur text-ktm-verified text-[10px] font-label-sm font-bold px-2 py-1 rounded shadow-sm flex items-center gap-1">
                  <span class="material-symbols-outlined text-[13px]">cloud</span> <span>Source GDrive</span>
                </div>
              </div>
              <div class="p-space-md flex-1 flex flex-col justify-between">
                <div>
                  <div class="flex items-center gap-2 mb-2">
                    <img alt="M. Hanif Ladzuardi" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA4CNbvqxsSVl-6mR73oBSJY7JrX-5uffPM9NX1TFMjhO7Y7NqqmyaCFCNVeJ6jOYSeJK1rlAao4_eNe4VMhxOND-PbfuOOIuU8r2Gxis2LtBfdKF2q0mAUPhGnjATteBnfb42myOrjc3sQFKWPQT0Vu0pZqCahRMODOAkJ3CFH2uf2G67H9p4Cy-MJKNwjubJMh-Q5W6_o4psuii5qeoPH8U99c6pmJQNYURNo_E908Lk7zX5sCfg">
                    <div class="flex flex-col">
                      <div class="flex items-center gap-1">
                        <span class="font-label-md text-xs font-bold text-on-surface truncate max-w-[130px]">M. Hanif Ladzuardi</span>
                        <span class="inline-flex items-center text-[10px] text-ktm-verified font-bold"><span class="material-symbols-outlined text-[14px]">verified</span></span>
                      </div>
                      <span class="font-body-sm text-[11px] text-on-surface-variant">TI • FST UIN WS (2026)</span>
                    </div>
                  </div>
                  <h3 class="font-headline-sm text-base font-bold text-on-surface line-clamp-2 hover:text-primary transition-colors mb-2">
                    Pembuatan Website Portofolio &amp; Landing Page Responsif (Tailwind/PHP)
                  </h3>
                  <div class="flex items-center gap-2 flex-wrap mb-3">
                    <span class="inline-flex items-center gap-1 px-2 py-0.5 rounded bg-surface-ice text-primary font-label-sm text-[10px] font-semibold"><span class="material-symbols-outlined text-[12px]">replay</span> 2x Revisi Gratis</span>
                    <span class="inline-flex items-center gap-1 px-2 py-0.5 rounded bg-secondary-fixed/50 text-on-secondary-fixed-variant font-label-sm text-[10px] font-bold"><span class="material-symbols-outlined text-[12px]">bolt</span> Prioritas</span>
                  </div>
                </div>
                <div class="pt-3 border-t border-surface-container-high/60 flex items-center justify-between">
                  <div>
                    <span class="text-[11px] text-on-surface-variant font-body-sm block">Mulai dari</span>
                    <span class="font-label-lg text-lg font-bold text-primary">Rp 250.000</span>
                  </div>
                  <div class="flex items-center gap-1.5">
                    <button class="px-2.5 py-1.5 rounded-lg text-xs font-label-md text-on-surface hover:bg-surface-container-high transition-colors" type="button">Detail</button>
                    <button class="px-3 py-1.5 rounded-lg text-xs font-label-md bg-primary text-on-primary hover:bg-emerald-accent transition-colors font-bold shadow-sm" type="button">Pesan</button>
                  </div>
                </div>
              </div>
            </div>

            <!-- Card 3: M. Rizky Novendra -->
            <div class="group bg-surface-container-lowest rounded-xl shadow-sm hover:shadow-xl transition-all duration-300 flex flex-col overflow-hidden relative" data-category="video" data-price="90000">
              <div class="relative w-full h-48 bg-surface-container overflow-hidden">
                <img alt="Video Editing" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCgwzqQ-oSADI0lZhCcQ6gapAiptUBblfhrZF8Wpup2FcrqVd6sDAe9il1fi1IczvvuNDAX5rpgjXuOVaIVhXqr0YbBtU72xDQlrHngbBNc0tXBX0oXZneS_RVrBt8Qz-uHQHAc031LLxdH2lZI-T5GJ2sSvtPnz--zlAWbbGph5B-jDDO-oJOArVLPc-bqEP7mfwlUw7YzeSRwANu-ME8fF7Wqh0vYMPityozR6CUHzSG_W-Ydt-U">
                <div class="absolute top-3 left-3 bg-secondary text-on-secondary text-[10px] font-label-sm font-bold uppercase tracking-wider px-2 py-1 rounded">Video &amp; Animasi</div>
                <div class="absolute top-3 right-3 bg-surface-container-lowest/90 backdrop-blur text-primary text-[11px] font-label-md font-bold px-2 py-0.5 rounded shadow-sm flex items-center gap-1">
                  <span class="material-symbols-outlined text-[14px] text-amber-highlight" style="font-variation-settings: 'FILL' 1;">star</span>
                  <span>4.8</span> <span class="text-on-surface-variant font-normal">(35)</span>
                </div>
                <div class="absolute bottom-2 right-2 bg-surface-container-lowest/95 backdrop-blur text-ktm-verified text-[10px] font-label-sm font-bold px-2 py-1 rounded shadow-sm flex items-center gap-1">
                  <span class="material-symbols-outlined text-[13px]">cloud</span> <span>Preview GDrive</span>
                </div>
              </div>
              <div class="p-space-md flex-1 flex flex-col justify-between">
                <div>
                  <div class="flex items-center gap-2 mb-2">
                    <img alt="M. Rizky Novendra" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDMru77qTsFBMrnhr3wRzk5Qr6oA0afd8F1J94LFjgcBWQktxUdegcdZ5VxhxB_-sH_F-BV0DLfhFajlFwIhH9S6pQrQe_IXr7u7upDhUZ4r9syEMt6sg78M4y6DE8kp6Yv2HoW8qg03fxhpp3K-sZtPCbIoSca-rd0I9UXId-DBm6sk-aoBWy1FBhQrEgmX7SDfO1J7CPIoUoqkXlRbRWBSzIjUeup5ceJvJu2ySs5Yfw9G9lB4C0">
                    <div class="flex flex-col">
                      <div class="flex items-center gap-1">
                        <span class="font-label-md text-xs font-bold text-on-surface truncate max-w-[130px]">M. Rizky Novendra</span>
                        <span class="inline-flex items-center text-[10px] text-ktm-verified font-bold"><span class="material-symbols-outlined text-[14px]">verified</span></span>
                      </div>
                      <span class="font-body-sm text-[11px] text-on-surface-variant">FDK UIN Walisongo</span>
                    </div>
                  </div>
                  <h3 class="font-headline-sm text-base font-bold text-on-surface line-clamp-2 hover:text-primary transition-colors mb-2">
                    Editing Video Reels &amp; Aftermovie Kegiatan Kampus / Ormawa
                  </h3>
                  <div class="flex items-center gap-2 flex-wrap mb-3">
                    <span class="inline-flex items-center gap-1 px-2 py-0.5 rounded bg-surface-ice text-primary font-label-sm text-[10px] font-semibold"><span class="material-symbols-outlined text-[12px]">replay</span> 2x Revisi Gratis</span>
                  </div>
                </div>
                <div class="pt-3 border-t border-surface-container-high/60 flex items-center justify-between">
                  <div>
                    <span class="text-[11px] text-on-surface-variant font-body-sm block">Mulai dari</span>
                    <span class="font-label-lg text-lg font-bold text-primary">Rp 90.000</span>
                  </div>
                  <div class="flex items-center gap-1.5">
                    <button class="px-2.5 py-1.5 rounded-lg text-xs font-label-md text-on-surface hover:bg-surface-container-high transition-colors" type="button">Detail</button>
                    <button class="px-3 py-1.5 rounded-lg text-xs font-label-md bg-primary text-on-primary hover:bg-emerald-accent transition-colors font-bold shadow-sm" type="button">Pesan</button>
                  </div>
                </div>
              </div>
            </div>

          </div>
        </div>
      </section>

    </div>
  </main>

  <!-- FOOTER -->
  <footer class="w-full bg-[#0c2238] text-[#e7f1f5] py-12 px-margin">
    <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-start gap-8">
      <div>
        <div class="flex items-center gap-2 text-white font-bold text-lg mb-2">
          <div class="h-8 w-8 rounded-lg bg-primary flex items-center justify-center text-white">S</div>
          <span>SWALIS — Skill Walisongo</span>
        </div>
        <p class="text-xs text-[#b9cbd5] max-w-sm">Marketplace resmi jasa mahasiswa UIN Walisongo Semarang. Mendukung ekonomi kreatif kampus secara aman, transparan, dan berintegritas.</p>
      </div>
      <div class="text-xs text-[#b9cbd5] space-y-1">
        <p class="font-semibold text-white">Prototipe Sistem Informasi Manajemen</p>
        <p>Program Studi Teknologi Informasi · Fakultas Sains dan Teknologi</p>
        <p>© 2026 SWALIS UIN Walisongo Semarang</p>
      </div>
    </div>
  </footer>

</body>
</html>
