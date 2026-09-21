<!DOCTYPE html>
<html lang="fa" dir="rtl" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover">
    <meta name="theme-color" content="#07080C">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <title>استودیوی تخصصی گوی‌ها | AURA Orb Studio Mobile</title>
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Three.js & OrbitControls -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/three@0.128.0/examples/js/controls/OrbitControls.js"></script>
    
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Vazirmatn Persian Font -->
    <link href="https://cdn.jsdelivr.net/gh/rastikerdar/vazirmatn@v33.003/Vazirmatn-font-face.css" rel="stylesheet" type="text/css" />

    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Vazirmatn', 'sans-serif'],
                    },
                    colors: {
                        aura: {
                            gold: '#D4AF37',
                            goldLight: '#F3E5AB',
                            darkBg: '#07080C',
                            cardBg: 'rgba(15, 18, 28, 0.85)',
                            accent: '#E5C158',
                            cyan: '#00F3FF',
                            purple: '#9D00FF'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        * {
            -webkit-tap-highlight-color: transparent;
        }

        html, body {
            overscroll-behavior: none;
            touch-action: manipulation;
        }

        body {
            font-family: 'Vazirmatn', sans-serif;
            background-color: #07080C;
            color: #f3f4f6;
            overflow: hidden;
            user-select: none;
            padding-top: env(safe-area-inset-top);
            padding-bottom: env(safe-area-inset-bottom);
        }

        /* Glassmorphism styling */
        .glass-panel {
            background: rgba(15, 18, 28, 0.85);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .glass-button {
            background: rgba(255, 255, 255, 0.06);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.12);
            transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .glass-button:hover, .glass-button:active {
            background: rgba(212, 175, 55, 0.2);
            border-color: rgba(212, 175, 55, 0.6);
            color: #D4AF37;
        }
        .glass-button.active {
            background: linear-gradient(135deg, rgba(212, 175, 55, 0.35), rgba(180, 130, 30, 0.25));
            border-color: #D4AF37;
            color: #FFF;
            box-shadow: 0 0 15px rgba(212, 175, 55, 0.3);
        }

        .gold-gradient-text {
            background: linear-gradient(135deg, #FFFFFF 20%, #D4AF37 80%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .gold-glow {
            box-shadow: 0 0 25px rgba(212, 175, 55, 0.25);
        }

        /* 3D Canvas Styling */
        #webgl-canvas {
            width: 100vw;
            height: 100vh;
            display: block;
            outline: none;
            cursor: grab;
            touch-action: none;
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 4px;
        }
        ::-webkit-scrollbar-track {
            background: rgba(0, 0, 0, 0.2);
        }
        ::-webkit-scrollbar-thumb {
            background: rgba(212, 175, 55, 0.3);
            border-radius: 4px;
        }

        /* Range Slider Styling */
        input[type=range] {
            -webkit-appearance: none;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 8px;
            height: 8px;
        }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none;
            height: 22px;
            width: 22px;
            border-radius: 50%;
            background: #D4AF37;
            cursor: pointer;
            box-shadow: 0 0 10px rgba(212, 175, 55, 0.8);
            border: 2px solid #fff;
        }

        /* Mobile Bottom Sheet */
        .bottom-sheet {
            transition: transform 0.35s cubic-bezier(0.4, 0, 0.2, 1);
            transform: translateY(100%);
            max-height: 82vh;
            overflow-y: auto;
            border-top-left-radius: 28px;
            border-top-right-radius: 28px;
        }
        .bottom-sheet.open {
            transform: translateY(0);
        }

        .sheet-handle {
            width: 44px;
            height: 5px;
            background: rgba(255, 255, 255, 0.25);
            border-radius: 999px;
        }

        /* Mobile FAB */
        .fab {
            width: 58px;
            height: 58px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 8px 25px rgba(212, 175, 55, 0.35);
            transition: all 0.25s ease;
        }
        .fab:active {
            transform: scale(0.92);
        }

        /* Hide scrollbar but keep scrolling */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Mode pill scroll */
        .mode-scroll {
            overflow-x: auto;
            scroll-snap-type: x mandatory;
        }
        .mode-scroll > button {
            scroll-snap-align: start;
            white-space: nowrap;
        }

        /* Prevent text selection during drag */
        .dragging {
            cursor: grabbing;
        }

        @media (min-width: 768px) {
            .bottom-sheet {
                display: none !important;
            }
        }
    </style>
</head>
<body class="relative w-screen h-screen overflow-hidden">

    <!-- 3D Canvas -->
    <canvas id="webgl-canvas" class="absolute inset-0 z-0"></canvas>

    <!-- ==================== MOBILE HEADER ==================== -->
    <header class="md:hidden absolute top-0 left-0 right-0 z-30 px-3 pt-3 pointer-events-none">
        <!-- Top Row: Brand + Quick Actions -->
        <div class="flex items-center justify-between gap-2 pointer-events-auto">
            <!-- Brand Mini -->
            <div class="glass-panel px-3 py-2 rounded-2xl flex items-center gap-2 gold-glow">
                <div class="w-8 h-8 rounded-lg bg-gradient-to-tr from-amber-600 via-amber-400 to-amber-200 flex items-center justify-center">
                    <i class="fa-solid fa-circle text-black text-sm"></i>
                </div>
                <div class="leading-tight">
                    <h1 class="text-[11px] font-black gold-gradient-text tracking-wide">AURA STUDIO</h1>
                    <p class="text-[8px] text-gray-400">استودیوی گوی‌های تعاملی</p>
                </div>
            </div>

            <!-- Quick Actions -->
            <div class="flex items-center gap-1.5">
                <button onclick="toggleAudioSynth()" id="audioToggleBtnMobile" class="glass-button w-10 h-10 rounded-xl flex items-center justify-center text-amber-400">
                    <i class="fa-solid fa-volume-high text-sm"></i>
                </button>
                <button onclick="takeSnapshot()" class="glass-button w-10 h-10 rounded-xl flex items-center justify-center text-gray-200">
                    <i class="fa-solid fa-camera text-sm"></i>
                </button>
                <button onclick="openOrderModal()" class="w-10 h-10 rounded-xl bg-gradient-to-r from-amber-500 to-amber-600 text-black flex items-center justify-center shadow-lg shadow-amber-500/20">
                    <i class="fa-solid fa-cart-shopping text-sm"></i>
                </button>
            </div>
        </div>

        <!-- Mode Pills Scroll -->
        <div class="mt-2.5 mode-scroll no-scrollbar flex gap-2 pb-1 pointer-events-auto">
            <button onclick="setStudioMode('lab')" id="modeBtn-lab-mobile" class="glass-button active px-3.5 py-2 rounded-xl text-[11px] font-bold flex items-center gap-1.5 shrink-0">
                <i class="fa-solid fa-flask text-amber-400 text-xs"></i>
                <span>آزمایشگاه</span>
            </button>
            <button onclick="setStudioMode('customizer')" id="modeBtn-customizer-mobile" class="glass-button px-3.5 py-2 rounded-xl text-[11px] font-bold flex items-center gap-1.5 shrink-0">
                <i class="fa-solid fa-wand-magic-sparkles text-amber-400 text-xs"></i>
                <span>دیزاینر</span>
            </button>
            <button onclick="setStudioMode('music')" id="modeBtn-music-mobile" class="glass-button px-3.5 py-2 rounded-xl text-[11px] font-bold flex items-center gap-1.5 shrink-0">
                <i class="fa-solid fa-music text-amber-400 text-xs"></i>
                <span>موزیک</span>
            </button>
            <button onclick="setStudioMode('stack')" id="modeBtn-stack-mobile" class="glass-button px-3.5 py-2 rounded-xl text-[11px] font-bold flex items-center gap-1.5 shrink-0">
                <i class="fa-solid fa-cubes-stacked text-amber-400 text-xs"></i>
                <span>برج</span>
            </button>
        </div>
    </header>

    <!-- ==================== DESKTOP HEADER ==================== -->
    <header class="hidden md:flex absolute top-4 left-4 right-4 z-20 items-center justify-between pointer-events-none">
        <div class="glass-panel px-5 py-3 rounded-2xl flex items-center gap-3.5 pointer-events-auto gold-glow">
            <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-amber-600 via-amber-400 to-amber-200 p-0.5 shadow-lg shadow-amber-500/20 flex items-center justify-center">
                <i class="fa-solid fa-circle text-black text-lg"></i>
            </div>
            <div>
                <h1 class="text-base font-black gold-gradient-text tracking-wide">AURA SPHERE STUDIO</h1>
                <p class="text-[10px] text-gray-400">استودیوی پیشرفته گوی‌ها و کره‌های فیزیکی تعاملی</p>
            </div>
        </div>

        <div class="glass-panel p-1.5 rounded-2xl flex items-center gap-1.5 pointer-events-auto">
            <button onclick="setStudioMode('lab')" id="modeBtn-lab" class="glass-button active px-4 py-2 rounded-xl text-xs font-bold flex items-center gap-2">
                <i class="fa-solid fa-flask text-amber-400"></i>
                <span>آزمایشگاه فیزیک</span>
            </button>
            <button onclick="setStudioMode('customizer')" id="modeBtn-customizer" class="glass-button px-4 py-2 rounded-xl text-xs font-bold flex items-center gap-2">
                <i class="fa-solid fa-wand-magic-sparkles text-amber-400"></i>
                <span>دیزاینر متریال</span>
            </button>
            <button onclick="setStudioMode('music')" id="modeBtn-music" class="glass-button px-4 py-2 rounded-xl text-xs font-bold flex items-center gap-2">
                <i class="fa-solid fa-music text-amber-400"></i>
                <span>موزیک‌باکس گوی‌ها</span>
            </button>
            <button onclick="setStudioMode('stack')" id="modeBtn-stack" class="glass-button px-4 py-2 rounded-xl text-xs font-bold flex items-center gap-2">
                <i class="fa-solid fa-cubes-stacked text-amber-400"></i>
                <span>برج تعادل</span>
            </button>
        </div>

        <div class="flex items-center gap-2 pointer-events-auto">
            <button onclick="toggleAudioSynth()" id="audioToggleBtn" class="glass-button p-3 rounded-2xl text-xs flex items-center justify-center text-amber-400">
                <i class="fa-solid fa-volume-high text-base"></i>
            </button>
            <button onclick="takeSnapshot()" class="glass-button p-3 rounded-2xl text-xs flex items-center justify-center text-gray-200">
                <i class="fa-solid fa-camera text-base"></i>
            </button>
            <button onclick="openOrderModal()" class="px-5 py-3 rounded-2xl bg-gradient-to-r from-amber-500 to-amber-600 text-black font-extrabold text-xs shadow-lg shadow-amber-500/20 hover:brightness-110 transition-all flex items-center gap-2">
                <i class="fa-solid fa-cart-shopping"></i>
                <span>سفارش گوی اختصاصی</span>
            </button>
        </div>
    </header>

    <!-- ==================== DESKTOP LEFT PANEL ==================== -->
    <aside id="leftControlPanel" class="hidden md:flex absolute top-24 left-4 bottom-20 z-20 w-80 glass-panel rounded-3xl p-5 flex-col justify-between overflow-y-auto gap-5">
        <div class="border-b border-white/10 pb-3 flex items-center justify-between">
            <h2 id="panelTitle" class="text-sm font-black text-white flex items-center gap-2">
                <i class="fa-solid fa-sliders text-amber-400"></i>
                <span>تنظیمات گوی فعال</span>
            </h2>
            <span id="activeOrbBadge" class="text-[10px] text-amber-300 bg-amber-500/10 border border-amber-500/30 px-2 py-0.5 rounded-md">گوی اصلی</span>
        </div>

        <div class="space-y-5 flex-1 overflow-y-auto pr-1">
            <div class="space-y-2">
                <label class="text-xs font-bold text-gray-300 block">جنس و متریال گوی:</label>
                <div class="grid grid-cols-2 gap-2 text-xs">
                    <button onclick="setSphereMaterial('walnut')" id="mat-walnut" class="glass-button active p-2.5 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-[#3D2314] border border-amber-500"></span>
                        <span>چوب گردو</span>
                    </button>
                    <button onclick="setSphereMaterial('ebony')" id="mat-ebony" class="glass-button p-2.5 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-[#121212] border border-white/20"></span>
                        <span>آبنوس سیاه</span>
                    </button>
                    <button onclick="setSphereMaterial('rosewood')" id="mat-rosewood" class="glass-button p-2.5 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-[#521C13] border border-white/20"></span>
                        <span>رزوود سرخ</span>
                    </button>
                    <button onclick="setSphereMaterial('crystal')" id="mat-crystal" class="glass-button p-2.5 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-blue-100/60 border border-white"></span>
                        <span>کریستال شفاف</span>
                    </button>
                    <button onclick="setSphereMaterial('emerald')" id="mat-emerald" class="glass-button p-2.5 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-emerald-800 border border-emerald-400"></span>
                        <span>کریستال زمرد</span>
                    </button>
                    <button onclick="setSphereMaterial('gold')" id="mat-gold" class="glass-button p-2.5 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-amber-400 border border-amber-200"></span>
                        <span>طلا ۲۴ عیار</span>
                    </button>
                    <button onclick="setSphereMaterial('obsidian')" id="mat-obsidian" class="glass-button p-2.5 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-zinc-900 border border-zinc-600"></span>
                        <span>مرمر سیاه</span>
                    </button>
                    <button onclick="setSphereMaterial('neon')" id="mat-neon" class="glass-button p-2.5 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-cyan-400 border border-cyan-200 shadow-sm shadow-cyan-400"></span>
                        <span>نئون سایبر</span>
                    </button>
                </div>
            </div>

            <div class="space-y-2">
                <label class="text-xs font-bold text-gray-300 block flex items-center justify-between">
                    <span>حکاکی لیزری روی گوی:</span>
                    <span class="text-[10px] text-amber-400">سفارشی</span>
                </label>
                <input type="text" id="engravingInput" oninput="updateEngravingText()" placeholder="مثلا: AURA 2026" maxlength="20"
                       class="w-full bg-black/50 border border-white/10 rounded-xl px-3 py-2 text-xs text-amber-300 placeholder-gray-500 focus:outline-none focus:border-amber-500 transition-colors">
            </div>

            <div class="space-y-3">
                <div>
                    <div class="flex justify-between text-xs text-gray-300 mb-1">
                        <span>شعاع و اندازه گوی:</span>
                        <span id="radiusVal" class="text-amber-400 font-mono">1.0m</span>
                    </div>
                    <input type="range" id="sliderRadius" min="0.4" max="2.5" step="0.1" value="1.0" oninput="updateSphereRadius(this.value)" class="w-full">
                </div>

                <div>
                    <div class="flex justify-between text-xs text-gray-300 mb-1">
                        <span>پرداخت روغنی / جلا (Gloss):</span>
                        <span id="roughnessVal" class="text-amber-400 font-mono">85%</span>
                    </div>
                    <input type="range" id="sliderRoughness" min="0.05" max="0.95" step="0.05" value="0.25" oninput="updateSphereRoughness(this.value)" class="w-full">
                </div>
            </div>

            <div class="space-y-2">
                <label class="text-xs font-bold text-gray-300 block">محیط استودیو و نورپردازی:</label>
                <div class="grid grid-cols-2 gap-2 text-xs">
                    <button onclick="setEnvironmentPreset('luxury')" id="env-luxury" class="glass-button active p-2 rounded-xl text-center">طلایی لوکس</button>
                    <button onclick="setEnvironmentPreset('cyber')" id="env-cyber" class="glass-button p-2 rounded-xl text-center">سایبر نئون</button>
                    <button onclick="setEnvironmentPreset('studio')" id="env-studio" class="glass-button p-2 rounded-xl text-center">استودیوی سفید</button>
                    <button onclick="setEnvironmentPreset('void')" id="env-void" class="glass-button p-2 rounded-xl text-center">تاریک عمیق</button>
                </div>
            </div>
        </div>

        <div class="pt-3 border-t border-white/10 grid grid-cols-2 gap-2">
            <button onclick="spawnNewSphere()" class="py-2.5 rounded-xl bg-amber-500/20 hover:bg-amber-500 border border-amber-500/40 text-amber-300 hover:text-black font-bold text-xs transition-all flex items-center justify-center gap-1.5">
                <i class="fa-solid fa-plus"></i>
                افزودن گوی جدید
            </button>
            <button onclick="clearExtraSpheres()" class="py-2.5 rounded-xl glass-button text-gray-300 hover:text-red-400 font-bold text-xs transition-all flex items-center justify-center gap-1.5">
                <i class="fa-solid fa-trash"></i>
                پاکسازی محیط
            </button>
        </div>
    </aside>

    <!-- ==================== DESKTOP RIGHT PANEL ==================== -->
    <aside id="rightPhysicsPanel" class="hidden md:block absolute top-24 right-4 z-20 w-72 glass-panel rounded-3xl p-5 space-y-4">
        <div class="border-b border-white/10 pb-2.5 flex items-center justify-between">
            <h3 class="text-xs font-black text-white flex items-center gap-2">
                <i class="fa-solid fa-atom text-amber-400"></i>
                <span>کنترل فیزیک و گرانش</span>
            </h3>
            <span class="text-[10px] text-emerald-400 bg-emerald-500/10 px-2 py-0.5 rounded-full border border-emerald-500/20">60 FPS</span>
        </div>

        <div>
            <div class="flex justify-between text-xs text-gray-300 mb-1">
                <span>شتاب جاذبه (Gravity):</span>
                <span id="gravityVal" class="text-amber-400 font-mono">-9.8 m/s²</span>
            </div>
            <input type="range" id="sliderGravity" min="-25" max="10" step="0.5" value="-9.8" oninput="updateGravity(this.value)" class="w-full">
        </div>

        <div>
            <div class="flex justify-between text-xs text-gray-300 mb-1">
                <span>خاصیت ارتجاعی (Bounce):</span>
                <span id="bounceVal" class="text-amber-400 font-mono">75%</span>
            </div>
            <input type="range" id="sliderBounce" min="0.1" max="0.98" step="0.05" value="0.75" oninput="updateBounce(this.value)" class="w-full">
        </div>

        <button onclick="triggerOrbPulse()" class="w-full py-2.5 rounded-xl bg-gradient-to-r from-amber-500/30 to-amber-600/30 border border-amber-500/50 hover:bg-amber-500 hover:text-black text-amber-300 font-black text-xs transition-all flex items-center justify-center gap-2">
            <i class="fa-solid fa-bolt"></i>
            شلیک موج مغناطیسی (Repel)
        </button>
    </aside>

    <!-- ==================== MOBILE FLOATING ACTION BUTTONS ==================== -->
    <div class="md:hidden fixed bottom-5 left-1/2 -translate-x-1/2 z-30 flex items-center gap-3 pointer-events-auto">
        <button onclick="spawnNewSphere()" class="fab bg-gradient-to-tr from-amber-500 to-amber-600 text-black">
            <i class="fa-solid fa-plus text-xl"></i>
        </button>
        <button onclick="toggleMobileSheet('controlSheet')" class="fab glass-panel text-amber-400 border border-amber-500/40">
            <i class="fa-solid fa-sliders text-xl"></i>
        </button>
        <button onclick="toggleMobileSheet('physicsSheet')" class="fab glass-panel text-amber-400 border border-amber-500/40">
            <i class="fa-solid fa-atom text-xl"></i>
        </button>
        <button onclick="triggerOrbPulse()" class="fab glass-panel text-amber-400 border border-amber-500/40">
            <i class="fa-solid fa-bolt text-xl"></i>
        </button>
    </div>

    <!-- ==================== MOBILE CONTROL BOTTOM SHEET ==================== -->
    <div id="controlSheet" class="md:hidden bottom-sheet fixed bottom-0 left-0 right-0 z-40 glass-panel">
        <div class="sticky top-0 z-10 bg-[rgba(15,18,28,0.95)] backdrop-blur-xl pt-3 pb-2 px-5 border-b border-white/10">
            <div class="flex justify-center mb-2">
                <div class="sheet-handle"></div>
            </div>
            <div class="flex items-center justify-between">
                <h2 class="text-sm font-black text-white flex items-center gap-2">
                    <i class="fa-solid fa-sliders text-amber-400"></i>
                    <span>تنظیمات گوی فعال</span>
                </h2>
                <button onclick="toggleMobileSheet('controlSheet')" class="w-8 h-8 rounded-full glass-button flex items-center justify-center text-gray-300">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
        </div>

        <div class="p-5 space-y-5">
            <!-- Material Selector Mobile -->
            <div class="space-y-2">
                <label class="text-xs font-bold text-gray-300 block">جنس و متریال گوی:</label>
                <div class="grid grid-cols-2 gap-2 text-xs">
                    <button onclick="setSphereMaterial('walnut')" id="mat-walnut-m" class="glass-button active p-3 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-[#3D2314] border border-amber-500"></span>
                        <span>چوب گردو</span>
                    </button>
                    <button onclick="setSphereMaterial('ebony')" id="mat-ebony-m" class="glass-button p-3 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-[#121212] border border-white/20"></span>
                        <span>آبنوس سیاه</span>
                    </button>
                    <button onclick="setSphereMaterial('rosewood')" id="mat-rosewood-m" class="glass-button p-3 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-[#521C13] border border-white/20"></span>
                        <span>رزوود سرخ</span>
                    </button>
                    <button onclick="setSphereMaterial('crystal')" id="mat-crystal-m" class="glass-button p-3 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-blue-100/60 border border-white"></span>
                        <span>کریستال شفاف</span>
                    </button>
                    <button onclick="setSphereMaterial('emerald')" id="mat-emerald-m" class="glass-button p-3 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-emerald-800 border border-emerald-400"></span>
                        <span>کریستال زمرد</span>
                    </button>
                    <button onclick="setSphereMaterial('gold')" id="mat-gold-m" class="glass-button p-3 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-amber-400 border border-amber-200"></span>
                        <span>طلا ۲۴ عیار</span>
                    </button>
                    <button onclick="setSphereMaterial('obsidian')" id="mat-obsidian-m" class="glass-button p-3 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-zinc-900 border border-zinc-600"></span>
                        <span>مرمر سیاه</span>
                    </button>
                    <button onclick="setSphereMaterial('neon')" id="mat-neon-m" class="glass-button p-3 rounded-xl flex items-center gap-2">
                        <span class="w-4 h-4 rounded-full bg-cyan-400 border border-cyan-200 shadow-sm shadow-cyan-400"></span>
                        <span>نئون سایبر</span>
                    </button>
                </div>
            </div>

            <!-- Engraving Mobile -->
            <div class="space-y-2">
                <label class="text-xs font-bold text-gray-300 block flex items-center justify-between">
                    <span>حکاکی لیزری روی گوی:</span>
                    <span class="text-[10px] text-amber-400">سفارشی</span>
                </label>
                <input type="text" id="engravingInputMobile" oninput="updateEngravingTextMobile()" placeholder="مثلا: AURA 2026" maxlength="20"
                       class="w-full bg-black/50 border border-white/10 rounded-xl px-4 py-3 text-sm text-amber-300 placeholder-gray-500 focus:outline-none focus:border-amber-500 transition-colors">
            </div>

            <!-- Sliders Mobile -->
            <div class="space-y-4">
                <div>
                    <div class="flex justify-between text-xs text-gray-300 mb-2">
                        <span>شعاع و اندازه گوی:</span>
                        <span id="radiusValMobile" class="text-amber-400 font-mono">1.0m</span>
                    </div>
                    <input type="range" id="sliderRadiusMobile" min="0.4" max="2.5" step="0.1" value="1.0" oninput="updateSphereRadiusMobile(this.value)" class="w-full">
                </div>

                <div>
                    <div class="flex justify-between text-xs text-gray-300 mb-2">
                        <span>پرداخت روغنی / جلا (Gloss):</span>
                        <span id="roughnessValMobile" class="text-amber-400 font-mono">85%</span>
                    </div>
                    <input type="range" id="sliderRoughnessMobile" min="0.05" max="0.95" step="0.05" value="0.25" oninput="updateSphereRoughnessMobile(this.value)" class="w-full">
                </div>
            </div>

            <!-- Environment Mobile -->
            <div class="space-y-2">
                <label class="text-xs font-bold text-gray-300 block">محیط استودیو و نورپردازی:</label>
                <div class="grid grid-cols-2 gap-2 text-xs">
                    <button onclick="setEnvironmentPreset('luxury')" id="env-luxury-m" class="glass-button active p-2.5 rounded-xl text-center">طلایی لوکس</button>
                    <button onclick="setEnvironmentPreset('cyber')" id="env-cyber-m" class="glass-button p-2.5 rounded-xl text-center">سایبر نئون</button>
                    <button onclick="setEnvironmentPreset('studio')" id="env-studio-m" class="glass-button p-2.5 rounded-xl text-center">استودیوی سفید</button>
                    <button onclick="setEnvironmentPreset('void')" id="env-void-m" class="glass-button p-2.5 rounded-xl text-center">تاریک عمیق</button>
                </div>
            </div>

            <!-- Quick Spawn Mobile -->
            <div class="space-y-2">
                <label class="text-xs font-bold text-gray-300 block">اسپاون سریع:</label>
                <div class="grid grid-cols-2 gap-2 text-xs">
                    <button onclick="spawnPresetSphere('walnut')" class="glass-button p-3 rounded-xl flex items-center gap-2 justify-center">
                        <span class="w-3 h-3 rounded-full bg-[#3D2314]"></span>
                        <span>گوی گردو</span>
                    </button>
                    <button onclick="spawnPresetSphere('crystal')" class="glass-button p-3 rounded-xl flex items-center gap-2 justify-center">
                        <span class="w-3 h-3 rounded-full bg-blue-100"></span>
                        <span>گوی بلور</span>
                    </button>
                    <button onclick="spawnPresetSphere('gold')" class="glass-button p-3 rounded-xl flex items-center gap-2 justify-center">
                        <span class="w-3 h-3 rounded-full bg-amber-400"></span>
                        <span>گوی طلا</span>
                    </button>
                    <button onclick="spawnPresetSphere('neon')" class="glass-button p-3 rounded-xl flex items-center gap-2 justify-center">
                        <span class="w-3 h-3 rounded-full bg-cyan-400"></span>
                        <span>گوی سایبر</span>
                    </button>
                </div>
            </div>

            <!-- Danger Zone Mobile -->
            <div class="pt-3 border-t border-white/10 grid grid-cols-2 gap-2">
                <button onclick="spawnNewSphere()" class="py-3 rounded-xl bg-amber-500/20 hover:bg-amber-500 border border-amber-500/40 text-amber-300 hover:text-black font-bold text-xs transition-all flex items-center justify-center gap-1.5">
                    <i class="fa-solid fa-plus"></i>
                    افزودن گوی جدید
                </button>
                <button onclick="clearExtraSpheres()" class="py-3 rounded-xl glass-button text-gray-300 hover:text-red-400 font-bold text-xs transition-all flex items-center justify-center gap-1.5">
                    <i class="fa-solid fa-trash"></i>
                    پاکسازی محیط
                </button>
            </div>
        </div>
    </div>

    <!-- ==================== MOBILE PHYSICS BOTTOM SHEET ==================== -->
    <div id="physicsSheet" class="md:hidden bottom-sheet fixed bottom-0 left-0 right-0 z-40 glass-panel">
        <div class="sticky top-0 z-10 bg-[rgba(15,18,28,0.95)] backdrop-blur-xl pt-3 pb-2 px-5 border-b border-white/10">
            <div class="flex justify-center mb-2">
                <div class="sheet-handle"></div>
            </div>
            <div class="flex items-center justify-between">
                <h3 class="text-sm font-black text-white flex items-center gap-2">
                    <i class="fa-solid fa-atom text-amber-400"></i>
                    <span>کنترل فیزیک و گرانش</span>
                </h3>
                <button onclick="toggleMobileSheet('physicsSheet')" class="w-8 h-8 rounded-full glass-button flex items-center justify-center text-gray-300">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
        </div>

        <div class="p-5 space-y-5">
            <div>
                <div class="flex justify-between text-xs text-gray-300 mb-2">
                    <span>شتاب جاذبه (Gravity):</span>
                    <span id="gravityValMobile" class="text-amber-400 font-mono">-9.8 m/s²</span>
                </div>
                <input type="range" id="sliderGravityMobile" min="-25" max="10" step="0.5" value="-9.8" oninput="updateGravityMobile(this.value)" class="w-full">
            </div>

            <div>
                <div class="flex justify-between text-xs text-gray-300 mb-2">
                    <span>خاصیت ارتجاعی (Bounce):</span>
                    <span id="bounceValMobile" class="text-amber-400 font-mono">75%</span>
                </div>
                <input type="range" id="sliderBounceMobile" min="0.1" max="0.98" step="0.05" value="0.75" oninput="updateBounceMobile(this.value)" class="w-full">
            </div>

            <button onclick="triggerOrbPulse()" class="w-full py-3.5 rounded-xl bg-gradient-to-r from-amber-500/30 to-amber-600/30 border border-amber-500/50 active:bg-amber-500 active:text-black text-amber-300 font-black text-sm transition-all flex items-center justify-center gap-2">
                <i class="fa-solid fa-bolt"></i>
                شلیک موج مغناطیسی (Repel)
            </button>

            <div class="pt-2 border-t border-white/10">
                <div class="flex items-center justify-between text-xs">
                    <span class="text-gray-400">وضعیت موتور فیزیک:</span>
                    <span class="text-emerald-400 bg-emerald-500/10 px-2 py-0.5 rounded-full border border-emerald-500/20">فعال - 60 FPS</span>
                </div>
            </div>
        </div>
    </div>

    <!-- ==================== DESKTOP BOTTOM TOOLBAR ==================== -->
    <div class="hidden md:flex absolute bottom-4 left-1/2 -translate-x-1/2 z-20 glass-panel px-6 py-3 rounded-full items-center gap-4 gold-glow">
        <span class="text-xs font-bold text-gray-300">اسپاون سریع:</span>
        <button onclick="spawnPresetSphere('walnut')" class="glass-button px-3.5 py-1.5 rounded-full text-xs font-bold flex items-center gap-2">
            <span class="w-3 h-3 rounded-full bg-[#3D2314]"></span>
            <span>گوی گردو</span>
        </button>
        <button onclick="spawnPresetSphere('crystal')" class="glass-button px-3.5 py-1.5 rounded-full text-xs font-bold flex items-center gap-2">
            <span class="w-3 h-3 rounded-full bg-blue-100"></span>
            <span>گوی بلور</span>
        </button>
        <button onclick="spawnPresetSphere('gold')" class="glass-button px-3.5 py-1.5 rounded-full text-xs font-bold flex items-center gap-2">
            <span class="w-3 h-3 rounded-full bg-amber-400"></span>
            <span>گوی طلا</span>
        </button>
        <button onclick="spawnPresetSphere('neon')" class="glass-button px-3.5 py-1.5 rounded-full text-xs font-bold flex items-center gap-2">
            <span class="w-3 h-3 rounded-full bg-cyan-400"></span>
            <span>گوی سایبر</span>
        </button>
    </div>

    <!-- ==================== ORDER MODAL ==================== -->
    <div id="orderModal" class="fixed inset-0 z-50 bg-black/80 backdrop-blur-md hidden flex items-center justify-center p-4">
        <div class="glass-panel max-w-md w-full rounded-3xl p-6 border border-amber-500/40 gold-glow relative max-h-[90vh] overflow-y-auto">
            <button onclick="closeOrderModal()" class="absolute top-4 left-4 w-9 h-9 rounded-full glass-button flex items-center justify-center text-gray-400 hover:text-white text-lg">
                <i class="fa-solid fa-xmark"></i>
            </button>
            
            <h3 class="text-lg font-black gold-gradient-text mb-1 mt-6">ثبت سفارش گوی دست‌ساز اختصاصی</h3>
            <p class="text-xs text-gray-400 mb-4">گوی طراحیشده شما توسط استادکاران خراطی AURA ساخته خواهد شد.</p>

            <div class="space-y-3 text-xs bg-black/40 p-4 rounded-2xl border border-white/10 mb-4">
                <div class="flex justify-between">
                    <span class="text-gray-400">جنس انتخابی:</span>
                    <span id="orderMatName" class="font-bold text-amber-400">چوب گردوی کهنسال</span>
                </div>
                <div class="flex justify-between">
                    <span class="text-gray-400">قطر و سایز:</span>
                    <span id="orderRadiusName" class="font-bold text-amber-400">۱۰ سانتی‌متر</span>
                </div>
                <div class="flex justify-between">
                    <span class="text-gray-400">متن حکاکی:</span>
                    <span id="orderEngravingName" class="font-bold text-amber-400">بدون حکاکی</span>
                </div>
                <div class="flex justify-between pt-2 border-t border-white/10 text-sm font-black text-white">
                    <span>قیمت برآوردی:</span>
                    <span id="orderPriceTotal" class="text-amber-400">۱,۴۵۰,۰۰۰ تومان</span>
                </div>
            </div>

            <form onsubmit="handleOrderSubmit(event)" class="space-y-3 text-xs">
                <div>
                    <label class="block text-gray-400 mb-1">نام و شماره تماس:</label>
                    <input type="text" required placeholder="نام شما و ۰۹۱۲..." class="w-full bg-black/50 border border-white/10 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-amber-500">
                </div>
                <div>
                    <label class="block text-gray-400 mb-1">توضیحات سفارشی‌سازی:</label>
                    <textarea placeholder="توضیحات اضافی برای خراطی..." class="w-full bg-black/50 border border-white/10 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-amber-500 h-20 resize-none"></textarea>
                </div>
                <button type="submit" class="w-full py-3.5 rounded-2xl bg-gradient-to-r from-amber-500 to-amber-600 text-black font-extrabold text-sm shadow-lg shadow-amber-500/20 hover:brightness-110 transition-all">
                    تایید و ارسال به کارگاه خراطی
                </button>
            </form>
        </div>
    </div>

    <!-- ==================== TOAST ==================== -->
    <div id="toast" class="fixed bottom-24 md:bottom-20 right-4 md:right-6 z-50 glass-panel border border-amber-500/40 text-amber-300 text-xs px-5 py-3.5 rounded-2xl shadow-2xl hidden flex items-center gap-3 max-w-[calc(100vw-2rem)]">
        <i class="fa-solid fa-circle-check text-lg text-emerald-400"></i>
        <span id="toastMsg">عملیات انجام شد</span>
    </div>

    <script>
        // ==================== WEB AUDIO SYNTHESIZER ====================
        let audioCtx = null;
        let isAudioEnabled = true;

        function initAudio() {
            if (!audioCtx) {
                const AudioContext = window.AudioContext || window.webkitAudioContext;
                audioCtx = new AudioContext();
            }
        }

        function playSphereImpactSound(velocity, matType = 'walnut') {
            if (!isAudioEnabled) return;
            initAudio();
            if (audioCtx.state === 'suspended') audioCtx.resume();

            const now = audioCtx.currentTime;
            const volume = Math.min(Math.max(velocity / 15, 0.05), 0.8);

            if (matType === 'crystal' || matType === 'emerald') {
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                const freqs = [523.25, 659.25, 783.99, 1046.50, 1318.51];
                const freq = freqs[Math.floor(Math.random() * freqs.length)];
                osc.type = 'sine';
                osc.frequency.setValueAtTime(freq, now);
                gain.gain.setValueAtTime(volume * 0.4, now);
                gain.gain.exponentialRampToValueAtTime(0.0001, now + 1.2);
                osc.connect(gain);
                gain.connect(audioCtx.destination);
                osc.start(now);
                osc.stop(now + 1.2);
            } else if (matType === 'gold' || matType === 'neon') {
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                osc.type = 'triangle';
                osc.frequency.setValueAtTime(300 + Math.random() * 400, now);
                osc.frequency.exponentialRampToValueAtTime(120, now + 0.3);
                gain.gain.setValueAtTime(volume * 0.5, now);
                gain.gain.exponentialRampToValueAtTime(0.001, now + 0.3);
                osc.connect(gain);
                gain.connect(audioCtx.destination);
                osc.start(now);
                osc.stop(now + 0.3);
            } else {
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                osc.type = 'sine';
                osc.frequency.setValueAtTime(140 + Math.random() * 60, now);
                osc.frequency.exponentialRampToValueAtTime(40, now + 0.15);
                gain.gain.setValueAtTime(volume * 0.7, now);
                gain.gain.exponentialRampToValueAtTime(0.001, now + 0.15);
                osc.connect(gain);
                gain.connect(audioCtx.destination);
                osc.start(now);
                osc.stop(now + 0.15);
            }
        }

        function toggleAudioSynth() {
            isAudioEnabled = !isAudioEnabled;
            const btns = [
                document.getElementById('audioToggleBtn'),
                document.getElementById('audioToggleBtnMobile')
            ].filter(Boolean);
            
            btns.forEach(btn => {
                if (isAudioEnabled) {
                    btn.classList.add('text-amber-400');
                    btn.classList.remove('text-gray-500');
                } else {
                    btn.classList.remove('text-amber-400');
                    btn.classList.add('text-gray-500');
                }
            });
            
            showToast(isAudioEnabled ? 'صدای برخورد گوی‌ها فعال شد.' : 'صدا غیرفعال شد.');
        }

        // ==================== THREE.JS SETUP ====================
        let scene, camera, renderer, controls;
        let physicsSpheres = [];
        let activeSphereIndex = 0;
        let gravityY = -9.8;
        let bounceFactor = 0.75;
        let activeStudioMode = 'lab';
        let woodTextures = {};
        let materialsDB = {};
        let engravingCanvas, engravingContext, engravingTexture;
        let raycaster = new THREE.Raycaster();
        let mouse = new THREE.Vector2();
        let isDragging = false;
        let draggedSphere = null;
        let dragPlane = new THREE.Plane();
        let planeIntersection = new THREE.Vector3();
        let clock = new THREE.Clock();

        function createProceduralWoodTexture(colorBase, colorGrain) {
            const canvas = document.createElement('canvas');
            canvas.width = 1024;
            canvas.height = 1024;
            const ctx = canvas.getContext('2d');
            ctx.fillStyle = colorBase;
            ctx.fillRect(0, 0, 1024, 1024);

            for (let i = 0; i < 800; i++) {
                const y = Math.random() * 1024;
                const h = Math.random() * 2.5 + 0.5;
                ctx.fillStyle = colorGrain;
                ctx.globalAlpha = Math.random() * 0.3;
                ctx.beginPath();
                ctx.moveTo(0, y);
                for (let x = 0; x < 1024; x += 30) {
                    const wave = Math.sin(x * 0.015 + y * 0.04) * 6;
                    ctx.lineTo(x, y + wave);
                }
                ctx.lineTo(1024, y + h);
                ctx.lineTo(0, y + h);
                ctx.closePath();
                ctx.fill();
            }

            const texture = new THREE.CanvasTexture(canvas);
            texture.wrapS = THREE.RepeatWrapping;
            texture.wrapT = THREE.RepeatWrapping;
            return texture;
        }

        function createEngravingTexture() {
            engravingCanvas = document.createElement('canvas');
            engravingCanvas.width = 1024;
            engravingCanvas.height = 512;
            engravingContext = engravingCanvas.getContext('2d');
            engravingTexture = new THREE.CanvasTexture(engravingCanvas);
            drawEngravingText('AURA LUXURY');
            return engravingTexture;
        }

        function drawEngravingText(text) {
            if (!engravingContext) return;
            engravingContext.clearRect(0, 0, 1024, 512);
            if (text && text.trim() !== '') {
                engravingContext.fillStyle = '#000000';
                engravingContext.font = 'bold 64px Vazirmatn, sans-serif';
                engravingContext.textAlign = 'center';
                engravingContext.textBaseline = 'middle';
                engravingContext.strokeStyle = '#D4AF37';
                engravingContext.lineWidth = 4;
                engravingContext.strokeText(text, 512, 256);
                engravingContext.fillStyle = '#1A0D00';
                engravingContext.fillText(text, 512, 256);
            }
            if (engravingTexture) engravingTexture.needsUpdate = true;
        }

        function initMaterialsDB() {
            woodTextures.walnut = createProceduralWoodTexture('#2B170B', '#0F0602');
            woodTextures.ebony = createProceduralWoodTexture('#151515', '#000000');
            woodTextures.rosewood = createProceduralWoodTexture('#4A150D', '#200502');
            const engTex = createEngravingTexture();

            materialsDB.walnut = new THREE.MeshStandardMaterial({ map: woodTextures.walnut, bumpMap: engTex, bumpScale: 0.08, roughness: 0.25, metalness: 0.05 });
            materialsDB.ebony = new THREE.MeshStandardMaterial({ map: woodTextures.ebony, bumpMap: engTex, bumpScale: 0.08, roughness: 0.2, metalness: 0.1 });
            materialsDB.rosewood = new THREE.MeshStandardMaterial({ map: woodTextures.rosewood, bumpMap: engTex, bumpScale: 0.08, roughness: 0.22, metalness: 0.05 });
            materialsDB.crystal = new THREE.MeshPhysicalMaterial({ color: 0xffffff, transparent: true, opacity: 0.3, transmission: 0.95, roughness: 0.05, ior: 1.52, thickness: 1.5, clearcoat: 1.0 });
            materialsDB.emerald = new THREE.MeshPhysicalMaterial({ color: 0x054d3b, transparent: true, opacity: 0.5, transmission: 0.88, roughness: 0.08, ior: 1.6, thickness: 2.0 });
            materialsDB.gold = new THREE.MeshStandardMaterial({ color: 0xd4af37, metalness: 0.95, roughness: 0.15 });
            materialsDB.obsidian = new THREE.MeshStandardMaterial({ color: 0x111116, roughness: 0.1, metalness: 0.2 });
            materialsDB.neon = new THREE.MeshStandardMaterial({ color: 0x00f3ff, emissive: 0x00a2ff, emissiveIntensity: 0.6, roughness: 0.2 });
        }

        function initThreeEngine() {
            scene = new THREE.Scene();
            scene.background = new THREE.Color(0x07080c);

            camera = new THREE.PerspectiveCamera(45, window.innerWidth / window.innerHeight, 0.1, 100);
            camera.position.set(0, 4, 10);

            renderer = new THREE.WebGLRenderer({
                canvas: document.getElementById('webgl-canvas'),
                antialias: true,
                alpha: true,
                preserveDrawingBuffer: true
            });
            renderer.setSize(window.innerWidth, window.innerHeight);
            renderer.setPixelRatio(Math.min(window.devicePixelRatio, 2));
            renderer.shadowMap.enabled = true;
            renderer.shadowMap.type = THREE.PCFSoftShadowMap;

            controls = new THREE.OrbitControls(camera, renderer.domElement);
            controls.enableDamping = true;
            controls.dampingFactor = 0.05;
            controls.maxPolarAngle = Math.PI / 2 + 0.05;
            controls.enablePan = false;
            controls.rotateSpeed = 0.8;

            initMaterialsDB();

            const ambientLight = new THREE.AmbientLight(0xffffff, 0.8);
            scene.add(ambientLight);

            const dirLight = new THREE.DirectionalLight(0xfff5ea, 2.5);
            dirLight.position.set(6, 10, 6);
            dirLight.castShadow = true;
            dirLight.shadow.mapSize.width = 2048;
            dirLight.shadow.mapSize.height = 2048;
            scene.add(dirLight);

            const goldPointLight = new THREE.PointLight(0xd4af37, 2, 15);
            goldPointLight.position.set(-5, 3, -4);
            scene.add(goldPointLight);

            const floorGeo = new THREE.PlaneGeometry(30, 30);
            const floorMat = new THREE.MeshStandardMaterial({ color: 0x0b0d14, roughness: 0.3, metalness: 0.5 });
            const floor = new THREE.Mesh(floorGeo, floorMat);
            floor.rotation.x = -Math.PI / 2;
            floor.position.y = -2;
            floor.receiveShadow = true;
            scene.add(floor);

            const ringGeo = new THREE.RingGeometry(3.8, 4.0, 64);
            const ringMat = new THREE.MeshBasicMaterial({ color: 0xd4af37, side: THREE.DoubleSide });
            const ring = new THREE.Mesh(ringGeo, ringMat);
            ring.rotation.x = -Math.PI / 2;
            ring.position.y = -1.99;
            scene.add(ring);

            spawnSphere(0, 0, 0, 1.0, 'walnut', true);

            window.addEventListener('resize', onWindowResize);
            const canvasEl = document.getElementById('webgl-canvas');
            canvasEl.addEventListener('pointerdown', onPointerDown);
            canvasEl.addEventListener('pointermove', onPointerMove);
            canvasEl.addEventListener('pointerup', onPointerUp);
            canvasEl.addEventListener('pointercancel', onPointerUp);

            animateLoop();
        }

        function spawnSphere(x, y, z, radius = 1.0, matKey = 'walnut', isMaster = false) {
            const geo = new THREE.SphereGeometry(radius, 64, 64);
            const mat = materialsDB[matKey] || materialsDB.walnut;
            const mesh = new THREE.Mesh(geo, mat);
            mesh.position.set(x, y, z);
            mesh.castShadow = true;
            mesh.receiveShadow = true;

            const sphereObj = {
                mesh: mesh,
                radius: radius,
                velocity: new THREE.Vector3((Math.random() - 0.5) * 2, Math.random() * 2, (Math.random() - 0.5) * 2),
                materialKey: matKey,
                isMaster: isMaster,
                mass: radius * 2
            };

            scene.add(mesh);
            physicsSpheres.push(sphereObj);
            if (isMaster) activeSphereIndex = physicsSpheres.length - 1;
            return sphereObj;
        }

        function spawnNewSphere() {
            const keys = ['walnut', 'crystal', 'gold', 'emerald', 'neon', 'ebony'];
            const randomMat = keys[Math.floor(Math.random() * keys.length)];
            const r = 0.5 + Math.random() * 0.8;
            spawnSphere((Math.random() - 0.5) * 4, 3 + Math.random() * 2, (Math.random() - 0.5) * 4, r, randomMat);
            showToast('گوی جدید اضافه شد.');
        }

        function spawnPresetSphere(matKey) {
            spawnSphere((Math.random() - 0.5) * 3, 3, (Math.random() - 0.5) * 3, 0.9, matKey);
            showToast(`گوی جدید از جنس ${matKey} ایجاد شد.`);
            closeAllSheets();
        }

        function clearExtraSpheres() {
            for (let i = physicsSpheres.length - 1; i >= 0; i--) {
                if (!physicsSpheres[i].isMaster) {
                    scene.remove(physicsSpheres[i].mesh);
                    physicsSpheres.splice(i, 1);
                }
            }
            activeSphereIndex = 0;
            showToast('گوی‌های فرعی پاکسازی شدند.');
        }

        // ==================== TOUCH / MOUSE DRAG ====================
        function onPointerDown(event) {
            mouse.x = (event.clientX / window.innerWidth) * 2 - 1;
            mouse.y = -(event.clientY / window.innerHeight) * 2 + 1;

            raycaster.setFromCamera(mouse, camera);
            const intersects = raycaster.intersectObjects(physicsSpheres.map(s => s.mesh));

            if (intersects.length > 0) {
                controls.enabled = false;
                isDragging = true;
                const clickedMesh = intersects[0].object;
                draggedSphere = physicsSpheres.find(s => s.mesh === clickedMesh);

                if (draggedSphere) {
                    dragPlane.setFromNormalAndCoplanarPoint(camera.getWorldDirection(dragPlane.normal).negate(), draggedSphere.mesh.position);
                    draggedSphere.velocity.set(0, 0, 0);
                }
            }
        }

        function onPointerMove(event) {
            if (!isDragging || !draggedSphere) return;
            event.preventDefault();

            mouse.x = (event.clientX / window.innerWidth) * 2 - 1;
            mouse.y = -(event.clientY / window.innerHeight) * 2 + 1;

            raycaster.setFromCamera(mouse, camera);
            if (raycaster.ray.intersectPlane(dragPlane, planeIntersection)) {
                draggedSphere.mesh.position.copy(planeIntersection);
                draggedSphere.velocity.set(0, 0, 0);
            }
        }

        function onPointerUp() {
            if (isDragging && draggedSphere) {
                draggedSphere.velocity.set((Math.random() - 0.5) * 3, 2, (Math.random() - 0.5) * 3);
            }
            isDragging = false;
            draggedSphere = null;
            controls.enabled = true;
        }

        // ==================== PHYSICS SIMULATION ====================
        function updatePhysicsSimulation(delta) {
            const floorY = -2.0;

            for (let i = 0; i < physicsSpheres.length; i++) {
                const s = physicsSpheres[i];
                if (isDragging && s === draggedSphere) continue;

                s.velocity.y += gravityY * delta;
                s.mesh.position.addScaledVector(s.velocity, delta);

                if (s.mesh.position.y - s.radius < floorY) {
                    s.mesh.position.y = floorY + s.radius;
                    if (Math.abs(s.velocity.y) > 0.5) playSphereImpactSound(Math.abs(s.velocity.y), s.materialKey);
                    s.velocity.y = -s.velocity.y * bounceFactor;
                    s.velocity.x *= 0.95;
                    s.velocity.z *= 0.95;
                }

                const bound = 6.0;
                if (Math.abs(s.mesh.position.x) > bound) {
                    s.mesh.position.x = Math.sign(s.mesh.position.x) * bound;
                    s.velocity.x = -s.velocity.x * bounceFactor;
                }
                if (Math.abs(s.mesh.position.z) > bound) {
                    s.mesh.position.z = Math.sign(s.mesh.position.z) * bound;
                    s.velocity.z = -s.velocity.z * bounceFactor;
                }

                for (let j = i + 1; j < physicsSpheres.length; j++) {
                    const s2 = physicsSpheres[j];
                    const diff = new THREE.Vector3().subVectors(s2.mesh.position, s.mesh.position);
                    const dist = diff.length();
                    const minDist = s.radius + s2.radius;

                    if (dist < minDist && dist > 0) {
                        const normal = diff.clone().normalize();
                        const overlap = minDist - dist;
                        s.mesh.position.addScaledVector(normal, -overlap * 0.5);
                        s2.mesh.position.addScaledVector(normal, overlap * 0.5);

                        const relativeVelocity = new THREE.Vector3().subVectors(s.velocity, s2.velocity);
                        const velAlongNormal = relativeVelocity.dot(normal);

                        if (velAlongNormal > 0) {
                            const impulse = (2 * velAlongNormal) / (s.mass + s2.mass);
                            s.velocity.subScaledVector(normal, impulse * s2.mass * bounceFactor);
                            s2.velocity.addScaledVector(normal, impulse * s.mass * bounceFactor);
                            playSphereImpactSound(velAlongNormal * 3, s.materialKey);
                        }
                    }
                }
            }
        }

        // ==================== UI FUNCTIONS ====================
        function setSphereMaterial(matKey) {
            if (physicsSpheres[activeSphereIndex]) {
                physicsSpheres[activeSphereIndex].mesh.material = materialsDB[matKey];
                physicsSpheres[activeSphereIndex].materialKey = matKey;

                ['walnut', 'ebony', 'rosewood', 'crystal', 'emerald', 'gold', 'obsidian', 'neon'].forEach(k => {
                    ['', '-m'].forEach(suffix => {
                        const btn = document.getElementById(`mat-${k}${suffix}`);
                        if (btn) {
                            if (k === matKey) btn.classList.add('active');
                            else btn.classList.remove('active');
                        }
                    });
                });
                showToast(`متریال گوی به ${matKey} تغییر یافت.`);
            }
        }

        function updateEngravingText() {
            const txt = document.getElementById('engravingInput').value;
            const txtMobile = document.getElementById('engravingInputMobile');
            if (txtMobile && txtMobile.value !== txt) txtMobile.value = txt;
            drawEngravingText(txt);
        }

        function updateEngravingTextMobile() {
            const txt = document.getElementById('engravingInputMobile').value;
            const txtDesktop = document.getElementById('engravingInput');
            if (txtDesktop && txtDesktop.value !== txt) txtDesktop.value = txt;
            drawEngravingText(txt);
        }

        function updateSphereRadius(val) {
            document.getElementById('radiusVal').innerText = val + 'm';
            const mobileVal = document.getElementById('radiusValMobile');
            if (mobileVal) mobileVal.innerText = val + 'm';
            const mobileSlider = document.getElementById('sliderRadiusMobile');
            if (mobileSlider && mobileSlider.value !== val) mobileSlider.value = val;
            
            if (physicsSpheres[activeSphereIndex]) {
                const r = parseFloat(val);
                physicsSpheres[activeSphereIndex].radius = r;
                physicsSpheres[activeSphereIndex].mesh.geometry.dispose();
                physicsSpheres[activeSphereIndex].mesh.geometry = new THREE.SphereGeometry(r, 64, 64);
            }
        }

        function updateSphereRadiusMobile(val) {
            document.getElementById('radiusValMobile').innerText = val + 'm';
            const desktopVal = document.getElementById('radiusVal');
            if (desktopVal) desktopVal.innerText = val + 'm';
            const desktopSlider = document.getElementById('sliderRadius');
            if (desktopSlider && desktopSlider.value !== val) desktopSlider.value = val;
            
            if (physicsSpheres[activeSphereIndex]) {
                const r = parseFloat(val);
                physicsSpheres[activeSphereIndex].radius = r;
                physicsSpheres[activeSphereIndex].mesh.geometry.dispose();
                physicsSpheres[activeSphereIndex].mesh.geometry = new THREE.SphereGeometry(r, 64, 64);
            }
        }

        function updateSphereRoughness(val) {
            document.getElementById('roughnessVal').innerText = Math.round(val * 100) + '%';
            const mobileVal = document.getElementById('roughnessValMobile');
            if (mobileVal) mobileVal.innerText = Math.round(val * 100) + '%';
            const mobileSlider = document.getElementById('sliderRoughnessMobile');
            if (mobileSlider && mobileSlider.value !== val) mobileSlider.value = val;
            
            if (physicsSpheres[activeSphereIndex] && physicsSpheres[activeSphereIndex].mesh.material) {
                physicsSpheres[activeSphereIndex].mesh.material.roughness = parseFloat(val);
            }
        }

        function updateSphereRoughnessMobile(val) {
            document.getElementById('roughnessValMobile').innerText = Math.round(val * 100) + '%';
            const desktopVal = document.getElementById('roughnessVal');
            if (desktopVal) desktopVal.innerText = Math.round(val * 100) + '%';
            const desktopSlider = document.getElementById('sliderRoughness');
            if (desktopSlider && desktopSlider.value !== val) desktopSlider.value = val;
            
            if (physicsSpheres[activeSphereIndex] && physicsSpheres[activeSphereIndex].mesh.material) {
                physicsSpheres[activeSphereIndex].mesh.material.roughness = parseFloat(val);
            }
        }

        function updateGravity(val) {
            gravityY = parseFloat(val);
            document.getElementById('gravityVal').innerText = val + ' m/s²';
            const mobileVal = document.getElementById('gravityValMobile');
            if (mobileVal) mobileVal.innerText = val + ' m/s²';
            const mobileSlider = document.getElementById('sliderGravityMobile');
            if (mobileSlider && mobileSlider.value !== val) mobileSlider.value = val;
        }

        function updateGravityMobile(val) {
            gravityY = parseFloat(val);
            document.getElementById('gravityValMobile').innerText = val + ' m/s²';
            const desktopVal = document.getElementById('gravityVal');
            if (desktopVal) desktopVal.innerText = val + ' m/s²';
            const desktopSlider = document.getElementById('sliderGravity');
            if (desktopSlider && desktopSlider.value !== val) desktopSlider.value = val;
        }

        function updateBounce(val) {
            bounceFactor = parseFloat(val);
            document.getElementById('bounceVal').innerText = Math.round(val * 100) + '%';
            const mobileVal = document.getElementById('bounceValMobile');
            if (mobileVal) mobileVal.innerText = Math.round(val * 100) + '%';
            const mobileSlider = document.getElementById('sliderBounceMobile');
            if (mobileSlider && mobileSlider.value !== val) mobileSlider.value = val;
        }

        function updateBounceMobile(val) {
            bounceFactor = parseFloat(val);
            document.getElementById('bounceValMobile').innerText = Math.round(val * 100) + '%';
            const desktopVal = document.getElementById('bounceVal');
            if (desktopVal) desktopVal.innerText = Math.round(val * 100) + '%';
            const desktopSlider = document.getElementById('sliderBounce');
            if (desktopSlider && desktopSlider.value !== val) desktopSlider.value = val;
        }

        function triggerOrbPulse() {
            physicsSpheres.forEach(s => {
                s.velocity.set(
                    (Math.random() - 0.5) * 12,
                    5 + Math.random() * 8,
                    (Math.random() - 0.5) * 12
                );
            });
            playSphereImpactSound(10, 'neon');
            showToast('موج مغناطیسی اعمال شد!');
            closeAllSheets();
        }

        function setEnvironmentPreset(preset) {
            ['luxury', 'cyber', 'studio', 'void'].forEach(p => {
                ['', '-m'].forEach(suffix => {
                    const btn = document.getElementById(`env-${p}${suffix}`);
                    if (btn) {
                        if (p === preset) btn.classList.add('active');
                        else btn.classList.remove('active');
                    }
                });
            });

            if (preset === 'luxury') scene.background.setHex(0x07080c);
            else if (preset === 'cyber') scene.background.setHex(0x030814);
            else if (preset === 'studio') scene.background.setHex(0x1a1c23);
            else if (preset === 'void') scene.background.setHex(0x000000);
        }

        function setStudioMode(mode) {
            activeStudioMode = mode;
            ['lab', 'customizer', 'music', 'stack'].forEach(m => {
                ['', '-mobile'].forEach(suffix => {
                    const btn = document.getElementById(`modeBtn-${m}${suffix}`);
                    if (btn) {
                        if (m === mode) btn.classList.add('active');
                        else btn.classList.remove('active');
                    }
                });
            });

            if (mode === 'stack') {
                clearExtraSpheres();
                for (let i = 0; i < 4; i++) {
                    spawnSphere(0, i * 1.8 - 0.5, 0, 0.9 - i * 0.1, i % 2 === 0 ? 'walnut' : 'crystal');
                }
                showToast('حالت برج تعادل آماده شد.');
            } else if (mode === 'music') {
                gravityY = -4;
                document.getElementById('sliderGravity').value = -4;
                document.getElementById('gravityVal').innerText = '-4 m/s²';
                const mg = document.getElementById('sliderGravityMobile');
                if (mg) mg.value = -4;
                const mgv = document.getElementById('gravityValMobile');
                if (mgv) mgv.innerText = '-4 m/s²';
                showToast('حالت موزیک‌باکس با جاذبه نرم فعال شد.');
            }
        }

        function takeSnapshot() {
            renderer.render(scene, camera);
            const dataUrl = renderer.domElement.toDataURL('image/png');
            const link = document.createElement('a');
            link.download = 'AURA-Sphere-3D.png';
            link.href = dataUrl;
            link.click();
            showToast('اسکرین‌شات ۳ بعدی دانلود شد.');
        }

        // ==================== MOBILE SHEET CONTROLS ====================
        function toggleMobileSheet(sheetId) {
            const sheet = document.getElementById(sheetId);
            const otherSheetId = sheetId === 'controlSheet' ? 'physicsSheet' : 'controlSheet';
            const otherSheet = document.getElementById(otherSheetId);
            
            if (otherSheet) otherSheet.classList.remove('open');
            sheet.classList.toggle('open');
        }

        function closeAllSheets() {
            document.getElementById('controlSheet')?.classList.remove('open');
            document.getElementById('physicsSheet')?.classList.remove('open');
        }

        // ==================== MODAL ====================
        function openOrderModal() {
            const master = physicsSpheres[0];
            if (master) {
                document.getElementById('orderMatName').innerText = master.materialKey;
                document.getElementById('orderRadiusName').innerText = Math.round(master.radius * 10) + ' سانتی‌متر';
                const engVal = document.getElementById('engravingInput')?.value || document.getElementById('engravingInputMobile')?.value || '';
                document.getElementById('orderEngravingName').innerText = engVal || 'بدون حکاکی';
            }
            document.getElementById('orderModal').classList.remove('hidden');
        }

        function closeOrderModal() {
            document.getElementById('orderModal').classList.add('hidden');
        }

        function handleOrderSubmit(e) {
            e.preventDefault();
            closeOrderModal();
            showToast('سفارش گوی اختصاصی شما ثبت شد. کارشناسان ما با شما تماس خواهند گرفت.');
        }

        // ==================== TOAST ====================
        function showToast(msg) {
            const toast = document.getElementById('toast');
            document.getElementById('toastMsg').innerText = msg;
            toast.classList.remove('hidden');
            clearTimeout(window.toastTimer);
            window.toastTimer = setTimeout(() => {
                toast.classList.add('hidden');
            }, 3000);
        }

        // ==================== RESIZE & ANIMATE ====================
        function onWindowResize() {
            camera.aspect = window.innerWidth / window.innerHeight;
            camera.updateProjectionMatrix();
            renderer.setSize(window.innerWidth, window.innerHeight);
        }

        function animateLoop() {
            requestAnimationFrame(animateLoop);
            const delta = Math.min(clock.getDelta(), 0.1);
            updatePhysicsSimulation(delta);
            if (controls) controls.update();

            if (physicsSpheres[activeSphereIndex] && !isDragging) {
                physicsSpheres[activeSphereIndex].mesh.rotation.y += 0.005;
            }
            renderer.render(scene, camera);
        }

        // ==================== INIT ====================
        window.addEventListener('DOMContentLoaded', () => {
            initThreeEngine();
            
            // Sync initial values on mobile
            const engInput = document.getElementById('engravingInput');
            const engInputMobile = document.getElementById('engravingInputMobile');
            if (engInput && engInputMobile) {
                engInputMobile.value = engInput.value;
            }
        });

        // Close sheets on outside tap (optional - can be enabled)
        document.getElementById('webgl-canvas')?.addEventListener('touchstart', (e) => {
            if (e.target.id === 'webgl-canvas') {
                // Don't close if user is interacting with 3D
            }
        }, { passive: true });
    </script>
</body>
</html>
