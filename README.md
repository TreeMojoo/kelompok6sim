<!-- Katalog Jasa & Beranda SWALIS -->
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="shell-type" content="web_standard"/>
  <title>SWALIS - Skill Walisongo Marketplace</title>
  
  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com"/>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin=""/>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&display=swap" rel="stylesheet"/>
  
  <!-- Base Style & Tailwind CSS -->
  <style>
    @layer base {
      html, body { margin: 0; padding: 0; }
      body { overscroll-behavior: none; }
      main > :first-child { margin-top: 0 !important; }
      main > :last-child { margin-bottom: 0 !important; }
    }
    ::-webkit-scrollbar { display: none; }
  </style>
  <script src="https://cdn.tailwindcss.com"></script>
  <script id="tailwind-config">
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "inverse-surface": "#283044",
            "outline": "#717970",
            "secondary-fixed-dim": "#bcc7de",
            "on-error-container": "#93000a",
            "surface-container-highest": "#dae2fd",
            "tertiary-fixed": "#ffdcc3",
            "on-error": "#ffffff",
            "surface-container-high": "#e2e7ff",
            "tertiary-fixed-dim": "#ffb77d",
            "surface-variant": "#dae2fd",
            "on-secondary-container": "#586377",
            "surface-container-lowest": "#ffffff",
            "primary-container": "#14532d",
            "on-tertiary-container": "#ffa14e",
            "on-primary-container": "#87c695",
            "secondary": "#545f73",
            "tertiary": "#4f2700",
            "inverse-primary": "#96d5a3",
            "on-secondary": "#ffffff",
            "on-primary-fixed-variant": "#12512c",
            "surface-container-low": "#f2f3ff",
            "on-background": "#131b2e",
            "error": "#ba1a1a",
            "surface-dim": "#d2d9f4",
            "on-primary-fixed": "#00210d",
            "inverse-on-surface": "#eef0ff",
            "surface-tint": "#2e6a41",
            "on-secondary-fixed": "#111c2d",
            "background": "#faf8ff",
            "primary-fixed": "#b1f2be",
            "surface": "#faf8ff",
            "outline-variant": "#c0c9be",
            "on-tertiary-fixed-variant": "#6e3900",
            "surface-container": "#eaedff",
            "on-surface-variant": "#404941",
            "primary": "#003b1b",
            "on-surface": "#131b2e",
            "on-tertiary": "#ffffff",
            "secondary-container": "#d5e0f8",
            "primary-fixed-dim": "#96d5a3",
            "on-primary": "#ffffff",
            "on-tertiary-fixed": "#2f1500",
            "surface-bright": "#faf8ff",
            "error-container": "#ffdad6",
            "secondary-fixed": "#d8e3fb",
            "on-secondary-fixed-variant": "#3c475a",
            "tertiary-container": "#703a00"
          },
          borderRadius: { DEFAULT: "0.25rem", lg: "0.5rem", xl: "0.75rem", full: "9999px" },
          spacing: {
            "gutter": "1.5rem", "margin": "2rem", "space-lg": "1.5rem", "space-xl": "2.5rem",
            "space-xs": "0.25rem", "gutter-mobile": "1rem", "space-md": "1rem", "margin-mobile": "1rem", "space-sm": "0.5rem"
          },
          fontFamily: {
            "headline-lg": ["Plus Jakarta Sans"], "headline-sm": ["Plus Jakarta Sans"], "label-lg": ["Plus Jakarta Sans"],
            "title-md": ["Plus Jakarta Sans"], "headline-xl": ["Plus Jakarta Sans"], "headline-lg-mobile": ["Plus Jakarta Sans"],
            "label-md": ["Plus Jakarta Sans"], "title-sm": ["Plus Jakarta Sans"], "label-sm": ["Plus Jakarta Sans"],
            "headline-xl-mobile": ["Plus Jakarta Sans"], "headline-md": ["Plus Jakarta Sans"], "body-lg": ["Plus Jakarta Sans"],
            "body-sm": ["Plus Jakarta Sans"], "body-md": ["Plus Jakarta Sans"]
          },
          fontSize: {
            "headline-lg": ["32px", { lineHeight: "40px", letterSpacing: "-0.015em", fontWeight: "700" }],
            "headline-sm": ["20px", { lineHeight: "28px", fontWeight: "600" }],
            "label-lg": ["14px", { lineHeight: "20px", letterSpacing: "0.01em", fontWeight: "600" }],
            "title-md": ["16px", { lineHeight: "24px", fontWeight: "600" }],
            "headline-xl": ["40px", { lineHeight: "48px", letterSpacing: "-0.02em", fontWeight: "800" }],
            "headline-lg-mobile": ["24px", { lineHeight: "32px", letterSpacing: "-0.01em", fontWeight: "700" }],
            "label-md": ["12px", { lineHeight: "16px", letterSpacing: "0.02em", fontWeight: "600" }],
            "title-sm": ["14px", { lineHeight: "20px", fontWeight: "600" }],
            "label-sm": ["11px", { lineHeight: "14px", letterSpacing: "0.03em", fontWeight: "700" }],
            "headline-xl-mobile": ["30px", { lineHeight: "38px", letterSpacing: "-0.015em", fontWeight: "800" }],
            "headline-md": ["24px", { lineHeight: "32px", letterSpacing: "-0.01em", fontWeight: "700" }],
            "body-lg": ["18px", { lineHeight: "28px", fontWeight: "400" }],
            "body-sm": ["13px", { lineHeight: "20px", fontWeight: "400" }],
            "body-md": ["15px", { lineHeight: "24px", fontWeight: "400" }]
          }
        }
      }
    };
  </script>
</head>
<body class="bg-surface font-body-md text-on-surface antialiased">

  <!-- HEADER -->
  <header class="fixed top-0 left-0 right-0 z-50 bg-surface/90 backdrop-blur-xl shadow-[0_1px_8px_rgba(0,0,0,0.04)]">
    <div class="h-20 max-w-7xl mx-auto px-margin flex items-center justify-between gap-space-md">
      <div class="flex items-center gap-space-md">
        <a class="flex items-center gap-space-sm" data-path="katalog-jasa" href="#">
          <img alt="SWALIS Brand Logo" class="h-8 w-auto object-contain" src="https://lh3.googleusercontent.com/aida/AEtjO1Xgx22oY5UQO2flf-x-PjEOs4Jgefo4-xVOuVlTExulXn4wvRPB89tyHd1tlLakAdNUT5bbRLkXBMZRGXfAYGM1ztNSoQ8wRhNLkZz5_3tPp6pGJv-eMEhxQ8eVt1K0SHlT9lyWnkm95Df7YIkJH79lfTCV2zVdT07kxIfih3BYPXKklKOzBCw8e2vVgPzwuvQM6u_HWiUA1tByTaiwvAWf7-f9KxrSaatnaHQDwjfP3i6wclTQldLGjkHZ"/>
          <div class="flex flex-col">
            <span class="font-title-md text-title-md text-primary font-bold tracking-tight">SWALIS</span>
            <span class="font-label-sm text-label-sm text-secondary">UIN Walisongo</span>
          </div>
        </a>
        <div class="hidden xl:flex items-center gap-space-xs px-space-sm py-space-xs rounded-full bg-primary-fixed text-on-primary-fixed">
          <span class="material-symbols-outlined text-title-sm">verified</span>
          <span class="font-label-sm text-label-sm">Anti-Joki Akademik Terverifikasi</span>
        </div>
      </div>
      <div class="hidden md:flex flex-1 max-w-md mx-space-sm">
        <div class="w-full flex items-center bg-surface-container-low rounded-lg px-space-md py-space-xs gap-space-sm">
          <span class="material-symbols-outlined text-secondary text-title-md">search</span>
          <input class="w-full bg-transparent font-body-sm text-body-sm text-on-surface placeholder-secondary focus:outline-none" placeholder="Cari jasa: Desain, UI/UX, Bimbingan Belajar, Pengetikan..." type="text"/>
        </div>
      </div>
      <nav class="hidden lg:flex items-center gap-space-xs">
        <a aria-current="page" class="bg-primary-container text-on-primary font-title-sm px-space-md py-space-xs rounded-lg transition-all" data-path="katalog-jasa" href="#">Katalog Jasa</a>
        <a class="font-title-sm text-title-sm text-on-surface-variant hover:text-on-surface hover:bg-surface-container-high px-space-md py-space-xs rounded-lg transition-all" data-path="request-jasa" href="#">Request Jasa</a>
        <a class="font-title-sm text-title-sm text-on-surface-variant hover:text-on-surface hover:bg-surface-container-high px-space-md py-space-xs rounded-lg transition-all" data-path="dashboard-freelancer" href="#">Dashboard Freelancer</a>
        <a class="font-title-sm text-title-sm text-on-surface-variant hover:text-on-surface hover:bg-surface-container-high px-space-md py-space-xs rounded-lg transition-all" data-path="panel-admin" href="#">Panel Admin</a>
      </nav>
      <div class="flex items-center gap-space-sm">
        <div class="hidden sm:flex items-center bg-surface-container rounded-full p-space-xs gap-space-xs">
          <button class="px-space-sm py-space-xs rounded-full font-label-sm text-label-sm bg-surface-container-lowest text-on-surface font-semibold shadow-[0_1px_4px_rgba(0,0,0,0.06)]" type="button">Client</button>
          <button class="px-space-sm py-space-xs rounded-full font-label-sm text-label-sm text-on-surface-variant hover:text-on-surface flex items-center gap-space-xs" type="button">
            <span class="material-symbols-outlined text-label-sm text-primary">verified_user</span>
            <span>Freelancer KTM</span>
          </button>
        </div>
        <a class="hidden sm:inline-flex items-center gap-space-xs bg-primary text-on-primary px-space-md py-space-sm rounded-lg font-label-lg text-label-lg hover:bg-primary-container transition-all" data-path="pasang-request" href="#">
          <span class="material-symbols-outlined text-title-sm">add_circle</span>
          <span>Pasang Request</span>
        </a>
        <div class="flex items-center gap-space-xs pl-space-xs">
          <div class="relative">
            <img alt="Profile" class="w-8 h-8 rounded-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDDCXedUsYpQMfIRvK7lHZ1K0Q2s0Dkyl4AipTokx0lPkSgz2O2E3v88LFPFj8dFzX6hYld5Uyoh_ewIthc1VhudkIY4Op505eb2nV5o-ibWJMMpOKlodkthLZ7USEmV0PokyRefkIDHBde3dCabeBoCfk-KaYGzOXAvX1se_Bdh2qyGtEJOtaTNJB62ZuXeo9_shG6e_PKsXpG1Z6JEfcaAqICK4Xh2zyfcO7zlDfeIZ_yWHKdvUPW9w"/>
            <div class="absolute -bottom-1 -right-1 w-3.5 h-3.5 rounded-full bg-primary flex items-center justify-center">
              <span class="material-symbols-outlined text-[10px] text-on-primary font-bold">check</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>

  <!-- MAIN CONTENT -->
  <main class="w-full pt-20 bg-surface min-h-screen">
    <div class="flex flex-col w-full">
      
      <!-- HERO SECTION -->
      <section class="relative w-full overflow-hidden bg-surface-container-low px-margin py-space-xl">
        <div class="absolute -top-32 -right-32 w-96 h-96 rounded-full bg-primary-fixed/20 blur-3xl pointer-events-none"></div>
        <div class="absolute -bottom-24 -left-24 w-80 h-80 rounded-full bg-surface-container-highest/60 blur-2xl pointer-events-none"></div>
        
        <div class="max-w-7xl mx-auto flex flex-col gap-space-lg relative z-10">
          <div class="flex flex-wrap items-center justify-between gap-space-sm">
            <div class="inline-flex items-center gap-space-xs px-space-sm py-space-xs rounded-full bg-surface-container text-on-surface-variant shadow-sm">
              <span class="w-2 h-2 rounded-full bg-primary animate-pulse"></span>
              <span class="font-label-sm text-label-sm uppercase tracking-wider text-primary font-bold">Portal Ekosistem Kreatif Resmi</span>
              <span class="text-outline">/</span>
              <span class="font-label-sm text-label-sm text-secondary">FST UIN Walisongo</span>
            </div>
            <div class="flex items-center gap-space-sm text-secondary font-label-sm text-label-sm">
              <span class="flex items-center gap-1"><span class="material-symbols-outlined text-title-sm text-primary">verified_user</span> Integrasi SIAKAD & KTM</span>
              <span class="hidden md:inline text-outline-variant">•</span>
              <span class="hidden md:inline">Kampus Bebas Joki 2025</span>
            </div>
          </div>

          <div class="grid grid-cols-1 lg:grid-cols-12 gap-space-lg items-center">
            <div class="lg:col-span-8 space-y-space-md">
              <h1 class="font-headline-xl text-headline-xl text-primary font-extrabold tracking-tight">
                Marketplace Jasa & Keahlian Mahasiswa UIN Walisongo
              </h1>
              <p class="font-body-lg text-body-lg text-on-surface-variant max-w-3xl leading-relaxed">
                Berdayakan mahasiswa bertalenta dengan layanan terpercaya, transparan, dan beretika akademik tanpa praktik perjokian. Kolaborasi sehat berbasis portofolio otentik.
              </p>
            </div>
            <div class="lg:col-span-4 flex flex-col gap-space-sm bg-surface-container-lowest p-space-md rounded-xl shadow-md border-l-4 border-primary">
              <div class="flex items-center gap-space-sm">
                <span class="p-space-xs rounded-lg bg-primary-fixed text-primary flex items-center justify-center">
                  <span class="material-symbols-outlined text-title-md">shield</span>
                </span>
                <span class="font-title-sm text-title-sm text-primary font-bold">Gerakan Kampus Bermartabat</span>
              </div>
              <p class="font-body-sm text-body-sm text-on-surface-variant">
                Platform kami menggunakan verifikasi ganda via kartu mahasiswa aktif demi menjaga orisinalitas riset dan karya intelektual civitas akademika.
              </p>
              <div class="flex items-center justify-between text-secondary pt-space-xs">
                <span class="font-label-sm text-label-sm font-semibold">SK Rektorat UIN Walisongo</span>
                <span class="material-symbols-outlined text-title-sm text-primary">arrow_forward</span>
              </div>
            </div>
          </div>

          <!-- Search Input & Chips -->
          <div class="bg-surface-container-lowest rounded-xl p-space-md shadow-xl flex flex-col gap-space-md">
            <div class="flex flex-col md:flex-row items-center gap-space-sm">
              <div class="w-full flex items-center bg-surface-container-low rounded-lg px-space-md py-space-sm gap-space-sm focus-within:ring-2 focus-within:ring-primary/20 transition-all">
                <span class="material-symbols-outlined text-primary text-title-md">search</span>
                <input class="w-full bg-transparent font-body-md text-body-md text-on-surface placeholder-secondary focus:outline-none" id="mainSearchInput" placeholder="Cari keahlian: Tutor Figma, Editing Makalah, Translasi Jurnal, Web App..." type="text"/>
                <button class="text-secondary hover:text-on-surface hidden" id="clearSearchBtn">
                  <span class="material-symbols-outlined text-title-sm">close</span>
                </button>
              </div>
              <div class="flex items-center gap-space-xs w-full md:w-auto">
                <button class="w-full md:w-auto bg-primary text-on-primary font-label-lg text-label-lg px-space-lg py-space-sm rounded-lg hover:bg-primary-container transition-all flex items-center justify-center gap-space-xs whitespace-nowrap shadow-sm">
                  <span class="material-symbols-outlined text-title-sm">tune</span>
                  <span>Temukan Jasa</span>
                </button>
              </div>
            </div>

            <!-- Filter Chips -->
            <div class="flex flex-col gap-space-xs">
              <div class="flex items-center justify-between">
                <span class="font-label-sm text-label-sm text-secondary font-bold uppercase tracking-wider">Kategori Unggulan Mahasiswa:</span>
                <span class="font-label-sm text-label-sm text-primary cursor-pointer hover:underline">Reset Filter</span>
              </div>
              <div class="flex flex-wrap items-center gap-space-xs">
                <button class="category-chip bg-primary text-on-primary font-label-sm text-label-sm px-space-sm py-space-xs rounded-full transition-all">Semua Kategori</button>
                <button class="category-chip bg-surface-container text-on-surface-variant hover:bg-surface-container-high font-label-sm text-label-sm px-space-sm py-space-xs rounded-full transition-all">Desain Grafis</button>
                <button class="category-chip bg-surface-container text-on-surface-variant hover:bg-surface-container-high font-label-sm text-label-sm px-space-sm py-space-xs rounded-full transition-all">UI/UX Design</button>
                <button class="category-chip bg-surface-container text-on-surface-variant hover:bg-surface-container-high font-label-sm text-label-sm px-space-sm py-space-xs rounded-full transition-all">Bimbingan Belajar & Tutor</button>
                <button class="category-chip bg-surface-container text-on-surface-variant hover:bg-surface-container-high font-label-sm text-label-sm px-space-sm py-space-xs rounded-full transition-all">Video Editing</button>
                <button class="category-chip bg-surface-container text-on-surface-variant hover:bg-surface-container-high font-label-sm text-label-sm px-space-sm py-space-xs rounded-full transition-all">Pemrograman & Web</button>
                <button class="category-chip bg-surface-container text-on-surface-variant hover:bg-surface-container-high font-label-sm text-label-sm px-space-sm py-space-xs rounded-full transition-all">Pengetikan & Tata Dokumen</button>
                <button class="category-chip bg-surface-container text-on-surface-variant hover:bg-surface-container-high font-label-sm text-label-sm px-space-sm py-space-xs rounded-full transition-all">Translasi & Voice Over</button>
              </div>
            </div>
          </div>

          <!-- Advisory Strip -->
          <div class="bg-gradient-to-r from-primary-fixed/40 via-surface-container-low to-surface-container-lowest rounded-xl p-space-md shadow-sm flex flex-col md:flex-row items-start md:items-center justify-between gap-space-md">
            <div class="flex items-center gap-space-md">
              <div class="w-12 h-12 rounded-xl bg-primary text-on-primary flex items-center justify-center shrink-0 shadow-md">
                <span class="material-symbols-outlined text-headline-sm">gavel</span>
              </div>
              <div class="space-y-0.5">
                <div class="flex items-center gap-space-xs">
                  <span class="font-title-sm text-title-sm text-primary font-bold">Zona Integritas Bebas Joki Akademik</span>
                  <span class="px-1.5 py-0.5 text-[10px] rounded bg-error-container text-on-error-container font-extrabold uppercase">Dilarang Keras</span>
                </div>
                <p class="font-body-sm text-body-sm text-on-surface-variant">
                  SWALIS secara tegas melarang pembuatan skripsi utuh, joki ujian, kuis, dan pemalsuan data riset. Melanggar berakibat sanksi pembekuan akun & laporan ke dekanat terkait.
                </p>
              </div>
            </div>
            <a class="shrink-0 inline-flex items-center gap-space-xs text-primary font-label-md text-label-md font-bold hover:underline" data-path="panduan-etika-akademik" href="#">
              <span>Baca Regulasi Etika</span>
              <span class="material-symbols-outlined text-title-sm">arrow_forward</span>
            </a>
          </div>

        </div>
      </section>

      <!-- METRIC STRIP -->
      <section class="w-full bg-surface-container-lowest py-space-lg shadow-sm">
        <div class="max-w-7xl mx-auto px-margin">
          <div class="grid grid-cols-2 md:grid-cols-4 gap-space-md">
            <div class="flex flex-col p-space-sm bg-surface-container-low rounded-lg transition-transform hover:-translate-y-1 duration-200">
              <div class="flex items-center justify-between">
                <span class="font-label-sm text-label-sm text-secondary uppercase font-bold">Mahasiswa Terdaftar</span>
                <span class="material-symbols-outlined text-primary text-title-md">badge</span>
              </div>
              <div class="mt-space-xs flex items-baseline gap-space-xs">
                <span class="font-headline-lg text-headline-lg text-primary font-extrabold">280+</span>
                <span class="font-label-sm text-label-sm text-on-surface-variant">Freelancer</span>
              </div>
              <p class="font-label-sm text-label-sm text-secondary mt-1">KTM UIN Valid & Aktif</p>
            </div>
            <div class="flex flex-col p-space-sm bg-surface-container-low rounded-lg transition-transform hover:-translate-y-1 duration-200">
              <div class="flex items-center justify-between">
                <span class="font-label-sm text-label-sm text-secondary uppercase font-bold">Pesanan Sukses</span>
                <span class="material-symbols-outlined text-primary text-title-md">task_alt</span>
              </div>
              <div class="mt-space-xs flex items-baseline gap-space-xs">
                <span class="font-headline-lg text-headline-lg text-primary font-extrabold">1.450+</span>
                <span class="font-label-sm text-label-sm text-on-surface-variant">Proyek</span>
              </div>
              <p class="font-label-sm text-label-sm text-secondary mt-1">Selesai Bergaransi</p>
            </div>
            <div class="flex flex-col p-space-sm bg-surface-container-low rounded-lg transition-transform hover:-translate-y-1 duration-200">
              <div class="flex items-center justify-between">
                <span class="font-label-sm text-label-sm text-secondary uppercase font-bold">Tingkat Kepuasan</span>
                <span class="material-symbols-outlined text-tertiary-container text-title-md">star</span>
              </div>
              <div class="mt-space-xs flex items-baseline gap-space-xs">
                <span class="font-headline-lg text-headline-lg text-primary font-extrabold">4.9</span>
                <span class="font-label-sm text-label-sm text-on-surface-variant">/ 5.0</span>
              </div>
              <p class="font-label-sm text-label-sm text-secondary mt-1">Dari 890+ Review Kampus</p>
            </div>
            <div class="flex flex-col p-space-sm bg-primary-fixed/30 rounded-lg transition-transform hover:-translate-y-1 duration-200">
              <div class="flex items-center justify-between">
                <span class="font-label-sm text-label-sm text-primary font-bold uppercase">Integritas Kampus</span>
                <span class="material-symbols-outlined text-primary text-title-md">verified</span>
              </div>
              <div class="mt-space-xs flex items-baseline gap-space-xs">
                <span class="font-headline-lg text-headline-lg text-primary font-extrabold">100%</span>
                <span class="font-label-sm text-label-sm text-on-primary-fixed-variant font-bold">Kepatuhan</span>
              </div>
              <p class="font-label-sm text-label-sm text-on-surface-variant mt-1">Bebas Joki & Plagiasi</p>
            </div>
          </div>
        </div>
      </section>

      <!-- CATALOG SECTION -->
      <section class="max-w-7xl mx-auto px-margin py-space-xl w-full">
        <div class="flex flex-col gap-space-md mb-space-lg">
          <div class="flex flex-col md:flex-row md:items-end justify-between gap-space-sm">
            <div>
              <span class="font-label-sm text-label-sm uppercase tracking-wider text-primary font-bold">Eksplorasi Layanan</span>
              <h2 class="font-headline-md text-headline-md text-on-surface font-extrabold">Katalog Jasa Mahasiswa Terverifikasi</h2>
              <p class="font-body-sm text-body-sm text-on-surface-variant mt-0.5">Pilih layanan resmi, konsultasi langsung, dan dapatkan jaminan revisi transparan.</p>
            </div>
            <div class="flex items-center gap-space-xs text-secondary font-label-sm text-label-sm bg-surface-container px-space-sm py-1.5 rounded-full">
              <span class="w-2 h-2 rounded-full bg-primary"></span>
              <span>Menampilkan 6 Rekomendasi Unggulan</span>
            </div>
          </div>

          <div class="bg-surface-container-lowest p-space-md rounded-xl shadow-md flex flex-wrap items-center justify-between gap-space-md">
            <div class="flex flex-wrap items-center gap-space-md">
              <div class="flex items-center gap-space-xs bg-surface-container-low px-space-sm py-1.5 rounded-lg">
                <span class="material-symbols-outlined text-title-sm text-secondary">payments</span>
                <span class="font-label-sm text-label-sm text-secondary">Harga:</span>
                <span class="font-label-sm text-label-sm font-bold text-on-surface">Rp15.000 - Rp500.000</span>
              </div>
              <label class="flex items-center gap-space-xs cursor-pointer select-none">
                <input checked class="w-4 h-4 accent-primary rounded cursor-pointer" type="checkbox"/>
                <span class="font-label-sm text-label-sm font-semibold text-primary flex items-center gap-1">
                  <span class="material-symbols-outlined text-title-sm">verified_user</span>
                  Hanya Verified Mahasiswa Aktif
                </span>
              </label>
            </div>
            <div class="flex items-center gap-space-sm">
              <span class="font-label-sm text-label-sm text-secondary">Urutkan:</span>
              <select class="bg-surface-container-low text-on-surface font-label-sm text-label-sm px-space-sm py-1.5 rounded-lg focus:outline-none focus:ring-1 focus:ring-primary cursor-pointer">
                <option>Paling Relevan & Populer</option>
                <option>Rating Tertinggi (5.0 - 4.5)</option>
                <option>Harga Terendah ke Tinggi</option>
                <option>Paling Cepat Selesai (1 Hari)</option>
              </select>
            </div>
          </div>
        </div>

        <!-- CARDS GRID -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-space-lg">
          
          <!-- Card 1 -->
          <div class="bg-surface-container-lowest rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-all duration-200 flex flex-col justify-between group">
            <div>
              <div class="relative w-full aspect-video overflow-hidden bg-surface-container">
                <img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCKM1eRQSalkN3Niexxv_jmrahNsfsbbvTmCy-YPXMNT8_l4-XBrgKxuCx3GWQQSKpTTyy8u7YXEWxuNsWIIH3IULOtRXWYuL328IAi5VZFmD5lt9hiK9-b9KfT62s78479kph-txzQOnJMJTAy9UNPIlYNxvtbVmLH0hMEw5U60RqHZ92pwP_sjuxBOcxrhTKuyjoUO4dr0Zk6MS-Vu26kRSwhhQg6FSvEixRow90C4m2nc_z4m-ugRQ" alt="Slide Presentasi"/>
                <div class="absolute top-3 left-3 bg-primary text-on-primary font-label-sm text-label-sm px-space-sm py-0.5 rounded-full shadow-md flex items-center gap-1">
                  <span class="material-symbols-outlined text-label-sm">slideshow</span>
                  <span>Desain Presentasi</span>
                </div>
                <div class="absolute bottom-3 right-3 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-label-sm px-space-sm py-0.5 rounded-md shadow-sm font-bold">
                  2x Revisi Gratis
                </div>
              </div>
              <div class="p-space-md space-y-space-sm">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-space-xs">
                    <img class="w-9 h-9 rounded-full object-cover shadow-sm" src="https://lh3.googleusercontent.com/aida-public/AB6AXuB3ncR0Rk9lZ4E69h1ImRassAMG81EYvaXe8DNsqCa8TP0EW3mptpmvtYgv5KnNhrSOcgQxxEcxAWZXsY1aX6kbFlZeVEyhWCSv3iNpOQxQBmPuWyNCoCLkIQBMVw8BL2bY7spdUkCzFLVDwqlXuuJnM9jkW5dVCTgswu2tXLoH76ql3casQMghbvaF19M1yJm2YTcW2P8mwzeS-Xrb93hjzrXWUAsbI-UqAUmFLKHJDz5S9V4ijsSEww" alt="Muhammad Hanif"/>
                    <div class="flex flex-col">
                      <span class="font-title-sm text-title-sm text-on-surface font-bold leading-tight">Muhammad Hanif</span>
                      <span class="font-label-sm text-label-sm text-secondary">Prodi TI (FST)</span>
                    </div>
                  </div>
                  <div class="inline-flex items-center gap-1 px-2 py-0.5 rounded-full bg-primary-fixed text-primary font-label-sm text-label-sm font-bold shadow-xs">
                    <span class="material-symbols-outlined text-[13px]">verified</span>
                    <span>KTM Valid</span>
                  </div>
                </div>
                <h3 class="font-title-md text-title-md text-on-surface font-bold leading-snug group-hover:text-primary transition-colors">
                  Desain Slide Presentasi Skripsi & Seminar Hasil Modern Clean
                </h3>
                <p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Bantu visualisasikan konsep riset, bagan metode, dan temuan data menjadi slide interaktif Canva / PowerPoint siap sidang.
                </p>
                <div class="pt-space-xs">
                  <a class="inline-flex items-center gap-1 font-label-sm text-label-sm text-primary bg-primary-fixed/30 hover:bg-primary-fixed/60 px-space-sm py-1 rounded-md transition-colors" href="#">
                    <span class="material-symbols-outlined text-title-sm">folder_shared</span>
                    <span>Lihat Portofolio GDrive (18 Contoh)</span>
                  </a>
                </div>
              </div>
            </div>
            <div class="p-space-md pt-0">
              <div class="border-t border-surface-container-high pt-space-sm flex items-center justify-between">
                <div>
                  <span class="font-label-sm text-label-sm text-secondary block">Mulai dari</span>
                  <span class="font-title-md text-title-md text-primary font-extrabold">Rp35.000</span>
                </div>
                <div class="flex items-center gap-space-sm">
                  <div class="flex items-center gap-1 text-tertiary-container font-label-sm text-label-sm font-bold">
                    <span class="material-symbols-outlined text-title-sm" style="font-variation-settings: 'FILL' 1;">star</span>
                    <span>4.9</span>
                    <span class="text-secondary font-normal">(42)</span>
                  </div>
                  <button class="bg-primary text-on-primary hover:bg-primary-container px-space-md py-1.5 rounded-lg font-label-sm text-label-sm font-semibold transition-all shadow-sm">
                    Pesan
                  </button>
                </div>
              </div>
            </div>
          </div>

          <!-- Card 2 -->
          <div class="bg-surface-container-lowest rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-all duration-200 flex flex-col justify-between group">
            <div>
              <div class="relative w-full aspect-video overflow-hidden bg-surface-container">
                <img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCcnL-rlHOuHAxzxtOeB45f9zHquMGjvXDQskxo9lkVH5AW7rQgkvXakd5vJfB8QdR5o8ChF_ODrZgAyTpQEEOxbImKsuPOr3nKbbhRzdBTAfUFa5jMUUROSpF1gUIIHpdiOigI8ruL366sX9yKvoQfpQM35SkeskFu9UBPW5hZ5OnWH3w_4wsNvDtYgKlV9FeahOPkPzKg5cekttCn-J3B8yqn7v87SfMZJpx8i2ETkWD3j2Rx9H30GA" alt="Video Editing"/>
                <div class="absolute top-3 left-3 bg-secondary text-on-secondary font-label-sm text-label-sm px-space-sm py-0.5 rounded-full shadow-md flex items-center gap-1">
                  <span class="material-symbols-outlined text-label-sm">movie</span>
                  <span>Video Editing</span>
                </div>
                <div class="absolute bottom-3 right-3 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-label-sm px-space-sm py-0.5 rounded-md shadow-sm font-bold">
                  2x Revisi Gratis
                </div>
              </div>
              <div class="p-space-md space-y-space-sm">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-space-xs">
                    <img class="w-9 h-9 rounded-full object-cover shadow-sm" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCPaF9fJqTgBAl80eMIGjpTfAHJd3zV8C3E6vjYLJgC6SmR9y_QLYWGnpbgqW9YOr67X05ePyM3EEO7L9m6h5GC4YXIRUOw9PCAWEuXqbBNCRvJQlxz6OSGfoasffnPnEWcX1-3v6nfFyHwCjLC3oYwLeuy-Qwi-Ksp9dqKqVPJajuo30c6V4p4W9mzxPUy3Hm4tUqewcCuUTPb_Tew1Da82awY_3HcpZQkKFH5kFcO_Zjc_9dNy7in4Q" alt="Siti Masitoh"/>
                    <div class="flex flex-col">
                      <span class="font-title-sm text-title-sm text-on-surface font-bold leading-tight">Siti Masitoh</span>
                      <span class="font-label-sm text-label-sm text-secondary">Ilmu Komunikasi (FDK)</span>
                    </div>
                  </div>
                  <div class="inline-flex items-center gap-1 px-2 py-0.5 rounded-full bg-primary-fixed text-primary font-label-sm text-label-sm font-bold shadow-xs">
                    <span class="material-symbols-outlined text-[13px]">verified</span>
                    <span>KTM Valid</span>
                  </div>
                </div>
                <h3 class="font-title-md text-title-md text-on-surface font-bold leading-snug group-hover:text-primary transition-colors">
                  Video Editing Reels & TikTok Promosi Organisasi / UMKM Kampus
                </h3>
                <p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Editing dinamis pakai CapCut Pro / Premiere, subtitle karaoke kekinian, sound effect viral, siap naikin engagement event atau jualan.
                </p>
                <div class="pt-space-xs">
                  <a class="inline-flex items-center gap-1 font-label-sm text-label-sm text-primary bg-primary-fixed/30 hover:bg-primary-fixed/60 px-space-sm py-1 rounded-md transition-colors" href="#">
                    <span class="material-symbols-outlined text-title-sm">folder_shared</span>
                    <span>Portofolio Video GDrive (Link Terbuka)</span>
                  </a>
                </div>
              </div>
            </div>
            <div class="p-space-md pt-0">
              <div class="border-t border-surface-container-high pt-space-sm flex items-center justify-between">
                <div>
                  <span class="font-label-sm text-label-sm text-secondary block">Mulai dari</span>
                  <span class="font-title-md text-title-md text-primary font-extrabold">Rp50.000</span>
                </div>
                <div class="flex items-center gap-space-sm">
                  <div class="flex items-center gap-1 text-tertiary-container font-label-sm text-label-sm font-bold">
                    <span class="material-symbols-outlined text-title-sm" style="font-variation-settings: 'FILL' 1;">star</span>
                    <span>5.0</span>
                    <span class="text-secondary font-normal">(29)</span>
                  </div>
                  <button class="bg-primary text-on-primary hover:bg-primary-container px-space-md py-1.5 rounded-lg font-label-sm text-label-sm font-semibold transition-all shadow-sm">
                    Pesan
                  </button>
                </div>
              </div>
            </div>
          </div>

          <!-- Card 3 -->
          <div class="bg-surface-container-lowest rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-all duration-200 flex flex-col justify-between group">
            <div>
              <div class="relative w-full aspect-video overflow-hidden bg-surface-container">
                <img class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300" src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?auto=format&fit=crop&q=80&w=800" alt="Pemrograman Web"/>
                <div class="absolute top-3 left-3 bg-primary text-on-primary font-label-sm text-label-sm px-space-sm py-0.5 rounded-full shadow-md flex items-center gap-1">
                  <span class="material-symbols-outlined text-label-sm">code</span>
                  <span>Pemrograman Web</span>
                </div>
                <div class="absolute bottom-3 right-3 bg-surface-container-lowest/90 backdrop-blur-sm text-on-surface font-label-sm text-label-sm px-space-sm py-0.5 rounded-md shadow-sm font-bold">
                  Konsultasi Live
                </div>
              </div>
              <div class="p-space-md space-y-space-sm">
                <div class="flex items-center justify-between">
                  <div class="flex items-center gap-space-xs">
                    <img class="w-9 h-9 rounded-full object-cover shadow-sm" src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&q=80&w=200" alt="Ahmad Fauzi"/>
                    <div class="flex flex-col">
                      <span class="font-title-sm text-title-sm text-on-surface font-bold leading-tight">Ahmad Fauzi</span>
                      <span class="font-label-sm text-label-sm text-secondary">Teknik Informatika</span>
                    </div>
                  </div>
                  <div class="inline-flex items-center gap-1 px-2 py-0.5 rounded-full bg-primary-fixed text-primary font-label-sm text-label-sm font-bold shadow-xs">
                    <span class="material-symbols-outlined text-[13px]">verified</span>
                    <span>KTM Valid</span>
                  </div>
                </div>
                <h3 class="font-title-md text-title-md text-on-surface font-bold leading-snug group-hover:text-primary transition-colors">
                  Bimbingan Privat Pemrograman Web PHP, MySQL & HTML/CSS Dasar
                </h3>
                <p class="font-body-sm text-body-sm text-on-surface-variant line-clamp-2">
                  Solusi belajar coding tugas kuliah tanpa joki. Dibimbing step-by-step sampai paham logika pemrograman dan database dengan benar.
                </p>
                <div class="pt-space-xs">
                  <a class="inline-flex items-center gap-1 font-label-sm text-label-sm text-primary bg-primary-fixed/30 hover:bg-primary-fixed/60 px-space-sm py-1 rounded-md transition-colors" href="#">
                    <span class="material-symbols-outlined text-title-sm">folder_shared</span>
                    <span>Lihat Modul Belajar</span>
                  </a>
                </div>
              </div>
            </div>
            <div class="p-space-md pt-0">
              <div class="border-t border-surface-container-high pt-space-sm flex items-center justify-between">
                <div>
                  <span class="font-label-sm text-label-sm text-secondary block">Mulai dari</span>
                  <span class="font-title-md text-title-md text-primary font-extrabold">Rp45.000</span>
                </div>
                <div class="flex items-center gap-space-sm">
                  <div class="flex items-center gap-1 text-tertiary-container font-label-sm text-label-sm font-bold">
                    <span class="material-symbols-outlined text-title-sm" style="font-variation-settings: 'FILL' 1;">star</span>
                    <span>4.8</span>
                    <span class="text-secondary font-normal">(35)</span>
                  </div>
                  <button class="bg-primary text-on-primary hover:bg-primary-container px-space-md py-1.5 rounded-lg font-label-sm text-label-sm font-semibold transition-all shadow-sm">
                    Pesan
                  </button>
                </div>
              </div>
            </div>
          </div>

        </div>
      </section>

    </div>
  </main>

</body>
</html>
