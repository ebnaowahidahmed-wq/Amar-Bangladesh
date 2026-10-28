<!DOCTYPE html>

<html lang="en"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover" name="viewport"/><meta content="mobile_stack" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&amp;family=Plus+Jakarta+Sans:wght@600;700;800&amp;family=Hind+Siliguri:wght@400;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config = { darkMode: "class", theme: { extend: { colors: { "on-tertiary-fixed-variant": "#7f2b00", "secondary-fixed": "#dbe1ff", "on-primary-fixed": "#00164e", "secondary": "#0051d5", "tertiary-container": "#742600", "primary": "#00236f", "on-tertiary": "#ffffff", "primary-container": "#1e3a8a", "inverse-surface": "#283044", "surface-container": "#eaedff", "on-primary-container": "#90a8ff", "on-secondary-container": "#fefcff", "surface-container-high": "#e2e7ff", "on-secondary-fixed-variant": "#003ea8", "on-background": "#131b2e", "surface-tint": "#4059aa", "surface-container-lowest": "#ffffff", "outline": "#757682", "on-error-container": "#93000a", "tertiary": "#4f1700", "on-secondary-fixed": "#00174b", "on-surface-variant": "#444651", "error": "#ba1a1a", "tertiary-fixed-dim": "#ffb599", "on-primary-fixed-variant": "#264191", "on-tertiary-container": "#ff8d5e", "surface-container-highest": "#dae2fd", "surface-variant": "#dae2fd", "on-primary": "#ffffff", "background": "#faf8ff", "surface": "#faf8ff", "primary-fixed": "#dce1ff", "on-secondary": "#ffffff", "tertiary-fixed": "#ffdbce", "inverse-on-surface": "#eef0ff", "primary-fixed-dim": "#b6c4ff", "outline-variant": "#c5c5d3", "secondary-fixed-dim": "#b4c5ff", "inverse-primary": "#b6c4ff", "surface-bright": "#faf8ff", "on-tertiary-fixed": "#370e00", "surface-container-low": "#f2f3ff", "secondary-container": "#316bf3", "on-error": "#ffffff", "error-container": "#ffdad6", "on-surface": "#131b2e", "surface-dim": "#d2d9f4" }, borderRadius: { "DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px" }, spacing: { "gutter-desktop": "1.5rem", "space-sm": "0.5rem", "gutter": "1rem", "space-lg": "1.5rem", "space-2xl": "3rem", "margin": "1rem", "margin-tablet": "1.5rem", "space-xl": "2rem", "space-md": "1rem", "space-xs": "0.25rem", "margin-desktop": "2rem" }, fontFamily: { "label-md": ["Inter"], "headline-lg-mobile": ["Plus Jakarta Sans"], "headline-lg": ["Plus Jakarta Sans"], "headline-md": ["Plus Jakarta Sans"], "body-md": ["Inter"], "display-lg": ["Plus Jakarta Sans"], "headline-sm": ["Plus Jakarta Sans"], "label-sm": ["Inter"], "label-lg": ["Inter"], "display-lg-mobile": ["Plus Jakarta Sans"], "body-sm": ["Inter"], "body-lg": ["Inter"], "title-md": ["Inter"] }, fontSize: { "label-md": ["12px", { lineHeight: "16px", letterSpacing: "0.02em", fontWeight: "600" }], "headline-lg-mobile": ["22px", { lineHeight: "30px", letterSpacing: "-0.015em", fontWeight: "700" }], "headline-lg": ["28px", { lineHeight: "36px", letterSpacing: "-0.015em", fontWeight: "700" }], "headline-md": ["20px", { lineHeight: "28px", letterSpacing: "-0.01em", fontWeight: "600" }], "body-md": ["14px", { lineHeight: "22px", letterSpacing: "0em", fontWeight: "400" }], "display-lg": ["36px", { lineHeight: "44px", letterSpacing: "-0.02em", fontWeight: "800" }], "headline-sm": ["18px", { lineHeight: "26px", letterSpacing: "0em", fontWeight: "600" }], "label-sm": ["10px", { lineHeight: "14px", letterSpacing: "0.04em", fontWeight: "700" }], "label-lg": ["14px", { lineHeight: "20px", letterSpacing: "0.01em", fontWeight: "600" }], "display-lg-mobile": ["28px", { lineHeight: "36px", letterSpacing: "-0.02em", fontWeight: "800" }], "body-sm": ["12px", { lineHeight: "18px", letterSpacing: "0.01em", fontWeight: "400" }], "body-lg": ["16px", { lineHeight: "26px", letterSpacing: "0em", fontWeight: "400" }], "title-md": ["16px", { lineHeight: "24px", letterSpacing: "-0.005em", fontWeight: "600" }] } } } };</script><style>@layer base{html,body{width:100vw;margin:0;padding:0;}body{overscroll-behavior:none;}.pb-safe{padding-bottom:env(safe-area-inset-bottom,0px);}.pt-safe{padding-top:env(safe-area-inset-top,0px);}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head><body class="bg-surface font-body-md text-on-surface antialiased flex flex-col min-h-screen"><header class="fixed top-0 w-full z-50 pt-safe bg-surface/85 backdrop-blur-xl shadow-[0_1px_8px_rgba(0,0,0,0.04)]"><div class="h-16 px-margin flex items-center justify-between gap-space-xs"><div class="flex items-center gap-space-xs min-w-0"><button aria-label="Go Back" class="min-h-[44px] min-w-[44px] flex items-center justify-center text-on-surface active:scale-95 transition-transform" onclick="history.back()"><span class="material-symbols-outlined text-[24px]">arrow_back</span></button><h1 class="font-title-md text-title-md text-on-surface truncate">Course Details</h1></div><div class="flex items-center gap-space-xs shrink-0"><a aria-label="Helpline Hotline" class="min-h-[44px] min-w-[44px] rounded-full bg-surface-container flex items-center justify-center text-primary active:scale-95 transition-transform" href="tel:0185481420"><span class="material-symbols-outlined text-[20px]">call</span></a><div class="w-8 h-8 rounded-full bg-primary flex items-center justify-center shrink-0"><span class="material-symbols-outlined text-on-primary text-[18px]">person</span></div></div></div></header><main class="flex flex-col relative w-full pt-16 bg-surface min-h-screen pb-safe"><div class="flex flex-col w-full pb-10">
<!-- Interactive Toast Notification Element -->
<div class="fixed top-20 left-1/2 -translate-x-1/2 z-50 transition-all duration-300 transform -translate-y-12 opacity-0 pointer-events-none flex items-center gap-space-xs px-margin py-space-sm rounded-full bg-inverse-surface text-inverse-on-surface shadow-xl" id="toastNotification">
<span class="material-symbols-outlined text-[18px] text-tertiary-fixed">check_circle</span>
<span class="font-label-md text-label-md" id="toastText">নম্বর কপি করা হয়েছে!</span>
</div>
<!-- Trust Banner / Security Assurance Strip -->
<div class="px-margin pt-space-sm pb-space-xs">
<div class="flex items-center justify-between bg-surface-container-low px-space-md py-space-sm rounded-xl">
<div class="flex items-center gap-space-xs min-w-0">
<span class="material-symbols-outlined text-secondary text-[20px] shrink-0" style="font-variation-settings: 'FILL' 1;">verified_user</span>
<span class="font-label-md text-label-md text-on-surface truncate">SSL ২৬৬-বিট এনক্রিপ্টেড পেমেন্ট গেটওয়ে</span>
</div>
<div class="flex items-center gap-1 shrink-0 bg-surface-container px-2 py-0.5 rounded-full">
<span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
<span class="font-label-sm text-label-sm text-primary font-bold">লাইভ ভেরিফিকেশন</span>
</div>
</div>
</div>
<!-- Order Summary Card -->
<div class="px-margin my-space-sm">
<div class="bg-surface-container-lowest rounded-xl shadow-md p-space-md flex flex-col gap-space-md">
<!-- Course Title and Badge -->
<div class="flex items-start justify-between gap-space-sm">
<div class="flex flex-col min-w-0">
<div class="flex items-center gap-space-xs mb-1">
<span class="font-label-sm text-label-sm uppercase tracking-wider bg-secondary-fixed text-on-secondary-fixed px-2 py-0.5 rounded-full font-bold">ভর্তি সেশন ২০২৪-২৫</span>
<span class="font-label-sm text-label-sm bg-tertiary-fixed text-on-tertiary-fixed px-2 py-0.5 rounded-full font-bold">৩.২২ স্পেশাল</span>
</div>
<h2 class="font-headline-sm text-headline-sm text-on-surface leading-tight">এইচএসসি মানবিক / ব্যবসায় শিক্ষা পূর্ণাঙ্গ প্যাকেজ</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-0.5">সকল বিষয় + বাংলা, ইংলিশ, আইসিটি (রেকর্ডেড ও লাইভ ম্যারাথন)</p>
</div>
<div class="w-12 h-12 rounded-xl bg-surface-container flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-primary text-[28px]" style="font-variation-settings: 'FILL' 1;">school</span>
</div>
</div>
<!-- Pricing Breakdown Table -->
<div class="bg-surface-container-low rounded-lg p-space-md flex flex-col gap-space-xs">
<div class="flex items-center justify-between">
<span class="font-body-md text-body-md text-on-surface-variant">কোর্সের রেগুলার ফি</span>
<span class="font-label-lg text-label-lg text-on-surface-variant line-through">৳ ৮,৫০০</span>
</div>
<div class="flex items-center justify-between text-on-tertiary-container">
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-[16px]">local_offer</span>
<span class="font-body-md text-body-md font-medium">প্রোমোকোড ছাড় (DISCOUNT1500)</span>
</div>
<span class="font-label-lg text-label-lg font-bold">- ৳ ১,৫০০</span>
</div>
<div class="w-full h-px bg-surface-container my-1"></div>
<div class="flex items-center justify-between pt-1">
<div class="flex flex-col">
<span class="font-title-md text-title-md text-on-surface font-bold">পরিশোধযোগ্য নিট ফি</span>
<span class="font-label-sm text-label-sm text-secondary font-semibold">সকল চার্জ অন্তর্ভুক্ত (No Extra Fee)</span>
</div>
<div class="flex items-baseline gap-1">
<span class="font-headline-lg-mobile text-headline-lg-mobile text-secondary font-extrabold">৳ ৭,০০০</span>
</div>
</div>
</div>
</div>
</div>
<!-- Instruction Banner -->
<div class="px-margin my-space-xs">
<div class="bg-primary text-on-primary rounded-xl p-space-md flex items-center justify-between shadow-sm">
<div class="flex items-center gap-space-sm min-w-0">
<div class="w-9 h-9 rounded-full bg-white/10 flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-white text-[20px]">touch_app</span>
</div>
<div class="flex flex-col min-w-0">
<span class="font-label-lg text-label-lg text-white font-bold leading-snug">পেমেন্ট মেথড নির্বাচন করুন</span>
<span class="font-body-sm text-body-sm text-primary-fixed-dim truncate">নিচের যেকোনো ওয়ালেট থেকে Send Money বা ক্যাশ-ইন করুন</span>
</div>
</div>
</div>
</div>
<!-- Branded MFS Method Selectors (bKash, Nagad, Rocket) -->
<div class="px-margin my-space-sm flex flex-col gap-space-sm">
<!-- bKash Option -->
<div class="payment-method-card bg-surface-container-lowest rounded-xl p-space-md shadow-sm transition-all duration-200 cursor-pointer relative overflow-hidden bg-surface-container-high/60" id="method-bkash" onclick="selectPaymentMethod('bkash', '০১৮৫৪৮১৪২০', '0185481420')">
<div class="flex items-center justify-between">
<div class="flex items-center gap-space-md min-w-0">
<!-- bKash Vector Styled Logo Container -->
<div class="w-12 h-12 rounded-xl flex items-center justify-center shrink-0 bg-[#E2136E] text-white shadow-sm">
<svg class="w-8 h-8 fill-current" viewbox="0 0 100 100">
<path d="M50 10 L88 32 L74 88 L26 88 L12 32 Z" fill-opacity="0.15"></path>
<path d="M50 18 L76 78 L50 62 L24 78 Z" fill="#FFFFFF"></path>
<circle cx="50" cy="46" fill="#E2136E" r="8"></circle>
</svg>
</div>
<div class="flex flex-col min-w-0">
<div class="flex items-center gap-space-xs">
<span class="font-headline-sm text-headline-sm font-bold text-on-surface">বিকাশ (bKash)</span>
<span class="bg-[#E2136E]/10 text-[#E2136E] font-label-sm text-label-sm px-2 py-0.5 rounded-full font-bold">ব্যক্তিগত / মার্চেন্ট</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">Send Money বা Payment: <span class="font-bold text-on-surface">0185481420</span></p>
</div>
</div>
<!-- Radio State Indicator -->
<div class="w-6 h-6 rounded-full bg-secondary flex items-center justify-center shrink-0 radio-indicator shadow-sm" id="radio-bkash">
<div class="w-2.5 h-2.5 rounded-full bg-white"></div>
</div>
</div>
<!-- Instruction Accordion Drop (Default Open for bKash) -->
<div class="method-details mt-space-sm pt-space-sm border-t-0 flex flex-col gap-space-xs" id="instructions-bkash">
<div class="bg-surface-container-low rounded-lg p-space-sm flex items-center justify-between">
<div class="flex flex-col">
<span class="font-label-sm text-label-sm text-on-surface-variant">নির্ধারিত বিকাশ নম্বর (ক্লিক করে কপি করুন):</span>
<span class="font-headline-sm text-headline-sm font-bold text-[#E2136E] tracking-wider">0185481420</span>
</div>
<button class="px-space-md py-1.5 rounded-lg bg-[#E2136E] text-white font-label-md text-label-md flex items-center gap-1 active:scale-95 transition-transform shadow-sm" onclick="copyNumber('0185481420', event)" type="button">
<span class="material-symbols-outlined text-[16px]">content_copy</span>
<span>কপি</span>
</button>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant px-1">
          * বিকাশ অ্যাপে গিয়ে <strong>Send Money</strong> অপশন থেকে <span class="font-bold text-on-surface">৳ ৭,০০০</span> টাকা পাঠিয়ে নিচে ট্রানজেকশন আইডি দিন।
        </p>
</div>
</div>
<!-- Nagad Option -->
<div class="payment-method-card bg-surface-container-lowest rounded-xl p-space-md shadow-sm transition-all duration-200 cursor-pointer relative overflow-hidden" id="method-nagad" onclick="selectPaymentMethod('nagad', '০১৮৫৪৮১৪২০', '0185481420')">
<div class="flex items-center justify-between">
<div class="flex items-center gap-space-md min-w-0">
<!-- Nagad Vector Styled Logo Container -->
<div class="w-12 h-12 rounded-xl flex items-center justify-center shrink-0 bg-[#F7931E] text-white shadow-sm">
<svg class="w-8 h-8 fill-current" viewbox="0 0 100 100">
<circle cx="50" cy="50" fill-opacity="0.2" r="38"></circle>
<path d="M50 22 C34.5 22 22 34.5 22 50 C22 65.5 34.5 78 50 78 C65.5 78 78 65.5 78 50" fill="none" stroke="#FFFFFF" stroke-linecap="round" stroke-width="8"></path>
<polygon fill="#D32F2F" points="50,22 68,36 58,48"></polygon>
</svg>
</div>
<div class="flex flex-col min-w-0">
<div class="flex items-center gap-space-xs">
<span class="font-headline-sm text-headline-sm font-bold text-on-surface">নগদ (Nagad)</span>
<span class="bg-[#F7931E]/10 text-[#D32F2F] font-label-sm text-label-sm px-2 py-0.5 rounded-full font-bold">ব্যক্তিগত</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">Send Money নম্বর: <span class="font-bold text-on-surface">0185481420</span></p>
</div>
</div>
<!-- Radio State Indicator -->
<div class="w-6 h-6 rounded-full bg-surface-container flex items-center justify-center shrink-0 radio-indicator" id="radio-nagad">
<div class="w-2.5 h-2.5 rounded-full bg-transparent"></div>
</div>
</div>
<!-- Instruction Accordion Drop (Nagad) -->
<div class="method-details hidden mt-space-sm pt-space-sm flex flex-col gap-space-xs" id="instructions-nagad">
<div class="bg-surface-container-low rounded-lg p-space-sm flex items-center justify-between">
<div class="flex flex-col">
<span class="font-label-sm text-label-sm text-on-surface-variant">নির্ধারিত নগদ নম্বর (ক্লিক করে কপি করুন):</span>
<span class="font-headline-sm text-headline-sm font-bold text-[#D32F2F] tracking-wider">0185481420</span>
</div>
<button class="px-space-md py-1.5 rounded-lg bg-[#D32F2F] text-white font-label-md text-label-md flex items-center gap-1 active:scale-95 transition-transform shadow-sm" onclick="copyNumber('0185481420', event)" type="button">
<span class="material-symbols-outlined text-[16px]">content_copy</span>
<span>কপি</span>
</button>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant px-1">
          * নগদ অ্যাপ থেকে <strong>Send Money</strong> করে প্রাপ্ত ৮ বা ১০ অক্ষরের TrxID নিচে লিখুন।
        </p>
</div>
</div>
<!-- Rocket Option -->
<div class="payment-method-card bg-surface-container-lowest rounded-xl p-space-md shadow-sm transition-all duration-200 cursor-pointer relative overflow-hidden" id="method-rocket" onclick="selectPaymentMethod('rocket', '০১৮৫৪৮১৪২০', '0185481420')">
<div class="flex items-center justify-between">
<div class="flex items-center gap-space-md min-w-0">
<!-- Rocket Vector Styled Logo Container -->
<div class="w-12 h-12 rounded-xl flex items-center justify-center shrink-0 bg-[#8C3494] text-white shadow-sm">
<svg class="w-8 h-8 fill-current" viewbox="0 0 100 100">
<path d="M50 15 C45 28 35 48 35 65 C35 78 42 85 50 85 C58 85 65 78 65 65 C65 48 55 28 50 15 Z" fill="#FFFFFF"></path>
<circle cx="50" cy="55" fill="#8C3494" r="7"></circle>
<path d="M32 68 L20 78 L26 62 Z" fill="#FFFFFF"></path>
<path d="M68 68 L80 78 L74 62 Z" fill="#FFFFFF"></path>
</svg>
</div>
<div class="flex flex-col min-w-0">
<div class="flex items-center gap-space-xs">
<span class="font-headline-sm text-headline-sm font-bold text-on-surface">রকেট (DBBL Rocket)</span>
<span class="bg-[#8C3494]/10 text-[#8C3494] font-label-sm text-label-sm px-2 py-0.5 rounded-full font-bold">ব্যক্তিগত</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">রকেট ওয়ালেট নম্বর: <span class="font-bold text-on-surface">0185481420</span></p>
</div>
</div>
<!-- Radio State Indicator -->
<div class="w-6 h-6 rounded-full bg-surface-container flex items-center justify-center shrink-0 radio-indicator" id="radio-rocket">
<div class="w-2.5 h-2.5 rounded-full bg-transparent"></div>
</div>
</div>
<!-- Instruction Accordion Drop (Rocket) -->
<div class="method-details hidden mt-space-sm pt-space-sm flex flex-col gap-space-xs" id="instructions-rocket">
<div class="bg-surface-container-low rounded-lg p-space-sm flex items-center justify-between">
<div class="flex flex-col">
<span class="font-label-sm text-label-sm text-on-surface-variant">নির্ধারিত রকেট নম্বর (ক্লিক করে কপি করুন):</span>
<span class="font-headline-sm text-headline-sm font-bold text-[#8C3494] tracking-wider">0185481420</span>
</div>
<button class="px-space-md py-1.5 rounded-lg bg-[#8C3494] text-white font-label-md text-label-md flex items-center gap-1 active:scale-95 transition-transform shadow-sm" onclick="copyNumber('0185481420', event)" type="button">
<span class="material-symbols-outlined text-[16px]">content_copy</span>
<span>কপি</span>
</button>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant px-1">
          * ডাচ-বাংলা রকেট অ্যাপ থেকে Send Money সম্পন্ন করে TrxID সংগ্রহ করুন।
        </p>
</div>
</div>
</div>
<!-- Transaction Verification Submission Form -->
<div class="px-margin my-space-sm">
<div class="bg-surface-container-lowest rounded-xl shadow-md p-space-md flex flex-col gap-space-md">
<div class="flex items-center gap-space-xs">
<span class="material-symbols-outlined text-secondary text-[22px]">assignment_turned_in</span>
<h3 class="font-title-md text-title-md text-on-surface font-bold">পেমেন্ট ভেরিফিকেশন ফর্ম পূরণ করুন</h3>
</div>
<!-- Field 1: Sender Phone Number -->
<div class="flex flex-col gap-1.5">
<label class="font-label-lg text-label-lg text-on-surface flex items-center justify-between" for="senderPhone">
<span>আপনার প্রেরক ফোন নম্বর (Sender Number)</span>
<span class="text-error font-body-sm text-body-sm">*আবশ্যক</span>
</label>
<div class="relative flex items-center">
<span class="absolute left-3 text-on-surface-variant material-symbols-outlined text-[20px]">phone_iphone</span>
<input class="w-full pl-10 pr-4 py-3 rounded-lg bg-surface-container-low text-on-surface font-body-md text-body-md placeholder:text-on-surface-variant/60 focus:bg-surface-container-lowest focus:outline-none transition-colors" id="senderPhone" placeholder="যেমন: 017xxxxxxxx বা 018xxxxxxxx" type="tel"/>
</div>
</div>
<!-- Field 2: Transaction ID -->
<div class="flex flex-col gap-1.5">
<label class="font-label-lg text-label-lg text-on-surface flex items-center justify-between" for="trxId">
<span>ট্র<!DOCTYPE html>

<html lang="en"><head><meta charset="utf-8"/><meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no, viewport-fit=cover" name="viewport"/><meta content="mobile_stack" name="shell-type"/><link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" rel="stylesheet"/><link href="https://fonts.googleapis.com" rel="preconnect"/><link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/><link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&amp;family=Plus+Jakarta+Sans:wght@600;700;800&amp;family=Hind+Siliguri:wght@400;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/><script src="https://cdn.tailwindcss.com"></script><script id="tailwind-config">tailwind.config = { darkMode: "class", theme: { extend: { colors: { "on-tertiary-fixed-variant": "#7f2b00", "secondary-fixed": "#dbe1ff", "on-primary-fixed": "#00164e", "secondary": "#0051d5", "tertiary-container": "#742600", "primary": "#00236f", "on-tertiary": "#ffffff", "primary-container": "#1e3a8a", "inverse-surface": "#283044", "surface-container": "#eaedff", "on-primary-container": "#90a8ff", "on-secondary-container": "#fefcff", "surface-container-high": "#e2e7ff", "on-secondary-fixed-variant": "#003ea8", "on-background": "#131b2e", "surface-tint": "#4059aa", "surface-container-lowest": "#ffffff", "outline": "#757682", "on-error-container": "#93000a", "tertiary": "#4f1700", "on-secondary-fixed": "#00174b", "on-surface-variant": "#444651", "error": "#ba1a1a", "tertiary-fixed-dim": "#ffb599", "on-primary-fixed-variant": "#264191", "on-tertiary-container": "#ff8d5e", "surface-container-highest": "#dae2fd", "surface-variant": "#dae2fd", "on-primary": "#ffffff", "background": "#faf8ff", "surface": "#faf8ff", "primary-fixed": "#dce1ff", "on-secondary": "#ffffff", "tertiary-fixed": "#ffdbce", "inverse-on-surface": "#eef0ff", "primary-fixed-dim": "#b6c4ff", "outline-variant": "#c5c5d3", "secondary-fixed-dim": "#b4c5ff", "inverse-primary": "#b6c4ff", "surface-bright": "#faf8ff", "on-tertiary-fixed": "#370e00", "surface-container-low": "#f2f3ff", "secondary-container": "#316bf3", "on-error": "#ffffff", "error-container": "#ffdad6", "on-surface": "#131b2e", "surface-dim": "#d2d9f4" }, borderRadius: { "DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px" }, spacing: { "gutter-desktop": "1.5rem", "space-sm": "0.5rem", "gutter": "1rem", "space-lg": "1.5rem", "space-2xl": "3rem", "margin": "1rem", "margin-tablet": "1.5rem", "space-xl": "2rem", "space-md": "1rem", "space-xs": "0.25rem", "margin-desktop": "2rem" }, fontFamily: { "label-md": ["Inter"], "headline-lg-mobile": ["Plus Jakarta Sans"], "headline-lg": ["Plus Jakarta Sans"], "headline-md": ["Plus Jakarta Sans"], "body-md": ["Inter"], "display-lg": ["Plus Jakarta Sans"], "headline-sm": ["Plus Jakarta Sans"], "label-sm": ["Inter"], "label-lg": ["Inter"], "display-lg-mobile": ["Plus Jakarta Sans"], "body-sm": ["Inter"], "body-lg": ["Inter"], "title-md": ["Inter"] }, fontSize: { "label-md": ["12px", { lineHeight: "16px", letterSpacing: "0.02em", fontWeight: "600" }], "headline-lg-mobile": ["22px", { lineHeight: "30px", letterSpacing: "-0.015em", fontWeight: "700" }], "headline-lg": ["28px", { lineHeight: "36px", letterSpacing: "-0.015em", fontWeight: "700" }], "headline-md": ["20px", { lineHeight: "28px", letterSpacing: "-0.01em", fontWeight: "600" }], "body-md": ["14px", { lineHeight: "22px", letterSpacing: "0em", fontWeight: "400" }], "display-lg": ["36px", { lineHeight: "44px", letterSpacing: "-0.02em", fontWeight: "800" }], "headline-sm": ["18px", { lineHeight: "26px", letterSpacing: "0em", fontWeight: "600" }], "label-sm": ["10px", { lineHeight: "14px", letterSpacing: "0.04em", fontWeight: "700" }], "label-lg": ["14px", { lineHeight: "20px", letterSpacing: "0.01em", fontWeight: "600" }], "display-lg-mobile": ["28px", { lineHeight: "36px", letterSpacing: "-0.02em", fontWeight: "800" }], "body-sm": ["12px", { lineHeight: "18px", letterSpacing: "0.01em", fontWeight: "400" }], "body-lg": ["16px", { lineHeight: "26px", letterSpacing: "0em", fontWeight: "400" }], "title-md": ["16px", { lineHeight: "24px", letterSpacing: "-0.005em", fontWeight: "600" }] } } } };</script><style>@layer base{html,body{width:100vw;margin:0;padding:0;}body{overscroll-behavior:none;}.pb-safe{padding-bottom:env(safe-area-inset-bottom,0px);}.pt-safe{padding-top:env(safe-area-inset-top,0px);}main>:first-child{margin-top:0!important;}main>:last-child{margin-bottom:0!important;}}::-webkit-scrollbar{display:none;}</style><style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head><body class="bg-surface font-body-md text-on-surface antialiased flex flex-col min-h-screen"><header class="fixed top-0 w-full z-50 pt-safe bg-surface/85 backdrop-blur-xl shadow-[0_1px_8px_rgba(0,0,0,0.04)]"><div class="h-16 px-margin flex items-center justify-between gap-space-xs"><div class="flex items-center gap-space-xs min-w-0"><button aria-label="Go Back" class="min-h-[44px] min-w-[44px] flex items-center justify-center text-on-surface active:scale-95 transition-transform" onclick="history.back()"><span class="material-symbols-outlined text-[24px]">arrow_back</span></button><h1 class="font-title-md text-title-md text-on-surface truncate">Course Details</h1></div><div class="flex items-center gap-space-xs shrink-0"><a aria-label="Helpline Hotline" class="min-h-[44px] min-w-[44px] rounded-full bg-surface-container flex items-center justify-center text-primary active:scale-95 transition-transform" href="tel:0185481420"><span class="material-symbols-outlined text-[20px]">call</span></a><div class="w-8 h-8 rounded-full bg-primary flex items-center justify-center shrink-0"><span class="material-symbols-outlined text-on-primary text-[18px]">person</span></div></div></div></header><main class="flex flex-col relative w-full pt-16 bg-surface min-h-screen pb-safe"><div class="flex flex-col w-full pb-10">
<!-- Interactive Toast Notification Element -->
<div class="fixed top-20 left-1/2 -translate-x-1/2 z-50 transition-all duration-300 transform -translate-y-12 opacity-0 pointer-events-none flex items-center gap-space-xs px-margin py-space-sm rounded-full bg-inverse-surface text-inverse-on-surface shadow-xl" id="toastNotification">
<span class="material-symbols-outlined text-[18px] text-tertiary-fixed">check_circle</span>
<span class="font-label-md text-label-md" id="toastText">নম্বর কপি করা হয়েছে!</span>
</div>
<!-- Trust Banner / Security Assurance Strip -->
<div class="px-margin pt-space-sm pb-space-xs">
<div class="flex items-center justify-between bg-surface-container-low px-space-md py-space-sm rounded-xl">
<div class="flex items-center gap-space-xs min-w-0">
<span class="material-symbols-outlined text-secondary text-[20px] shrink-0" style="font-variation-settings: 'FILL' 1;">verified_user</span>
<span class="font-label-md text-label-md text-on-surface truncate">SSL ২৬৬-বিট এনক্রিপ্টেড পেমেন্ট গেটওয়ে</span>
</div>
<div class="flex items-center gap-1 shrink-0 bg-surface-container px-2 py-0.5 rounded-full">
<span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
<span class="font-label-sm text-label-sm text-primary font-bold">লাইভ ভেরিফিকেশন</span>
</div>
</div>
</div>
<!-- Order Summary Card -->
<div class="px-margin my-space-sm">
<div class="bg-surface-container-lowest rounded-xl shadow-md p-space-md flex flex-col gap-space-md">
<!-- Course Title and Badge -->
<div class="flex items-start justify-between gap-space-sm">
<div class="flex flex-col min-w-0">
<div class="flex items-center gap-space-xs mb-1">
<span class="font-label-sm text-label-sm uppercase tracking-wider bg-secondary-fixed text-on-secondary-fixed px-2 py-0.5 rounded-full font-bold">ভর্তি সেশন ২০২৪-২৫</span>
<span class="font-label-sm text-label-sm bg-tertiary-fixed text-on-tertiary-fixed px-2 py-0.5 rounded-full font-bold">৩.২২ স্পেশাল</span>
</div>
<h2 class="font-headline-sm text-headline-sm text-on-surface leading-tight">এইচএসসি মানবিক / ব্যবসায় শিক্ষা পূর্ণাঙ্গ প্যাকেজ</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant mt-0.5">সকল বিষয় + বাংলা, ইংলিশ, আইসিটি (রেকর্ডেড ও লাইভ ম্যারাথন)</p>
</div>
<div class="w-12 h-12 rounded-xl bg-surface-container flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-primary text-[28px]" style="font-variation-settings: 'FILL' 1;">school</span>
</div>
</div>
<!-- Pricing Breakdown Table -->
<div class="bg-surface-container-low rounded-lg p-space-md flex flex-col gap-space-xs">
<div class="flex items-center justify-between">
<span class="font-body-md text-body-md text-on-surface-variant">কোর্সের রেগুলার ফি</span>
<span class="font-label-lg text-label-lg text-on-surface-variant line-through">৳ ৮,৫০০</span>
</div>
<div class="flex items-center justify-between text-on-tertiary-container">
<div class="flex items-center gap-1.5">
<span class="material-symbols-outlined text-[16px]">local_offer</span>
<span class="font-body-md text-body-md font-medium">প্রোমোকোড ছাড় (DISCOUNT1500)</span>
</div>
<span class="font-label-lg text-label-lg font-bold">- ৳ ১,৫০০</span>
</div>
<div class="w-full h-px bg-surface-container my-1"></div>
<div class="flex items-center justify-between pt-1">
<div class="flex flex-col">
<span class="font-title-md text-title-md text-on-surface font-bold">পরিশোধযোগ্য নিট ফি</span>
<span class="font-label-sm text-label-sm text-secondary font-semibold">সকল চার্জ অন্তর্ভুক্ত (No Extra Fee)</span>
</div>
<div class="flex items-baseline gap-1">
<span class="font-headline-lg-mobile text-headline-lg-mobile text-secondary font-extrabold">৳ ৭,০০০</span>
</div>
</div>
</div>
</div>
</div>
<!-- Instruction Banner -->
<div class="px-margin my-space-xs">
<div class="bg-primary text-on-primary rounded-xl p-space-md flex items-center justify-between shadow-sm">
<div class="flex items-center gap-space-sm min-w-0">
<div class="w-9 h-9 rounded-full bg-white/10 flex items-center justify-center shrink-0">
<span class="material-symbols-outlined text-white text-[20px]">touch_app</span>
</div>
<div class="flex flex-col min-w-0">
<span class="font-label-lg text-label-lg text-white font-bold leading-snug">পেমেন্ট মেথড নির্বাচন করুন</span>
<span class="font-body-sm text-body-sm text-primary-fixed-dim truncate">নিচের যেকোনো ওয়ালেট থেকে Send Money বা ক্যাশ-ইন করুন</span>
</div>
</div>
</div>
</div>
<!-- Branded MFS Method Selectors (bKash, Nagad, Rocket) -->
<div class="px-margin my-space-sm flex flex-col gap-space-sm">
<!-- bKash Option -->
<div class="payment-method-card bg-surface-container-lowest rounded-xl p-space-md shadow-sm transition-all duration-200 cursor-pointer relative overflow-hidden bg-surface-container-high/60" id="method-bkash" onclick="selectPaymentMethod('bkash', '০১৮৫৪৮১৪২০', '0185481420')">
<div class="flex items-center justify-between">
<div class="flex items-center gap-space-md min-w-0">
<!-- bKash Vector Styled Logo Container -->
<div class="w-12 h-12 rounded-xl flex items-center justify-center shrink-0 bg-[#E2136E] text-white shadow-sm">
<svg class="w-8 h-8 fill-current" viewbox="0 0 100 100">
<path d="M50 10 L88 32 L74 88 L26 88 L12 32 Z" fill-opacity="0.15"></path>
<path d="M50 18 L76 78 L50 62 L24 78 Z" fill="#FFFFFF"></path>
<circle cx="50" cy="46" fill="#E2136E" r="8"></circle>
</svg>
</div>
<div class="flex flex-col min-w-0">
<div class="flex items-center gap-space-xs">
<span class="font-headline-sm text-headline-sm font-bold text-on-surface">বিকাশ (bKash)</span>
<span class="bg-[#E2136E]/10 text-[#E2136E] font-label-sm text-label-sm px-2 py-0.5 rounded-full font-bold">ব্যক্তিগত / মার্চেন্ট</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">Send Money বা Payment: <span class="font-bold text-on-surface">0185481420</span></p>
</div>
</div>
<!-- Radio State Indicator -->
<div class="w-6 h-6 rounded-full bg-secondary flex items-center justify-center shrink-0 radio-indicator shadow-sm" id="radio-bkash">
<div class="w-2.5 h-2.5 rounded-full bg-white"></div>
</div>
</div>
<!-- Instruction Accordion Drop (Default Open for bKash) -->
<div class="method-details mt-space-sm pt-space-sm border-t-0 flex flex-col gap-space-xs" id="instructions-bkash">
<div class="bg-surface-container-low rounded-lg p-space-sm flex items-center justify-between">
<div class="flex flex-col">
<span class="font-label-sm text-label-sm text-on-surface-variant">নির্ধারিত বিকাশ নম্বর (ক্লিক করে কপি করুন):</span>
<span class="font-headline-sm text-headline-sm font-bold text-[#E2136E] tracking-wider">0185481420</span>
</div>
<button class="px-space-md py-1.5 rounded-lg bg-[#E2136E] text-white font-label-md text-label-md flex items-center gap-1 active:scale-95 transition-transform shadow-sm" onclick="copyNumber('0185481420', event)" type="button">
<span class="material-symbols-outlined text-[16px]">content_copy</span>
<span>কপি</span>
</button>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant px-1">
          * বিকাশ অ্যাপে গিয়ে <strong>Send Money</strong> অপশন থেকে <span class="font-bold text-on-surface">৳ ৭,০০০</span> টাকা পাঠিয়ে নিচে ট্রানজেকশন আইডি দিন।
        </p>
</div>
</div>
<!-- Nagad Option -->
<div class="payment-method-card bg-surface-container-lowest rounded-xl p-space-md shadow-sm transition-all duration-200 cursor-pointer relative overflow-hidden" id="method-nagad" onclick="selectPaymentMethod('nagad', '০১৮৫৪৮১৪২০', '0185481420')">
<div class="flex items-center justify-between">
<div class="flex items-center gap-space-md min-w-0">
<!-- Nagad Vector Styled Logo Container -->
<div class="w-12 h-12 rounded-xl flex items-center justify-center shrink-0 bg-[#F7931E] text-white shadow-sm">
<svg class="w-8 h-8 fill-current" viewbox="0 0 100 100">
<circle cx="50" cy="50" fill-opacity="0.2" r="38"></circle>
<path d="M50 22 C34.5 22 22 34.5 22 50 C22 65.5 34.5 78 50 78 C65.5 78 78 65.5 78 50" fill="none" stroke="#FFFFFF" stroke-linecap="round" stroke-width="8"></path>
<polygon fill="#D32F2F" points="50,22 68,36 58,48"></polygon>
</svg>
</div>
<div class="flex flex-col min-w-0">
<div class="flex items-center gap-space-xs">
<span class="font-headline-sm text-headline-sm font-bold text-on-surface">নগদ (Nagad)</span>
<span class="bg-[#F7931E]/10 text-[#D32F2F] font-label-sm text-label-sm px-2 py-0.5 rounded-full font-bold">ব্যক্তিগত</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">Send Money নম্বর: <span class="font-bold text-on-surface">0185481420</span></p>
</div>
</div>
<!-- Radio State Indicator -->
<div class="w-6 h-6 rounded-full bg-surface-container flex items-center justify-center shrink-0 radio-indicator" id="radio-nagad">
<div class="w-2.5 h-2.5 rounded-full bg-transparent"></div>
</div>
</div>
<!-- Instruction Accordion Drop (Nagad) -->
<div class="method-details hidden mt-space-sm pt-space-sm flex flex-col gap-space-xs" id="instructions-nagad">
<div class="bg-surface-container-low rounded-lg p-space-sm flex items-center justify-between">
<div class="flex flex-col">
<span class="font-label-sm text-label-sm text-on-surface-variant">নির্ধারিত নগদ নম্বর (ক্লিক করে কপি করুন):</span>
<span class="font-headline-sm text-headline-sm font-bold text-[#D32F2F] tracking-wider">0185481420</span>
</div>
<button class="px-space-md py-1.5 rounded-lg bg-[#D32F2F] text-white font-label-md text-label-md flex items-center gap-1 active:scale-95 transition-transform shadow-sm" onclick="copyNumber('0185481420', event)" type="button">
<span class="material-symbols-outlined text-[16px]">content_copy</span>
<span>কপি</span>
</button>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant px-1">
          * নগদ অ্যাপ থেকে <strong>Send Money</strong> করে প্রাপ্ত ৮ বা ১০ অক্ষরের TrxID নিচে লিখুন।
        </p>
</div>
</div>
<!-- Rocket Option -->
<div class="payment-method-card bg-surface-container-lowest rounded-xl p-space-md shadow-sm transition-all duration-200 cursor-pointer relative overflow-hidden" id="method-rocket" onclick="selectPaymentMethod('rocket', '০১৮৫৪৮১৪২০', '0185481420')">
<div class="flex items-center justify-between">
<div class="flex items-center gap-space-md min-w-0">
<!-- Rocket Vector Styled Logo Container -->
<div class="w-12 h-12 rounded-xl flex items-center justify-center shrink-0 bg-[#8C3494] text-white shadow-sm">
<svg class="w-8 h-8 fill-current" viewbox="0 0 100 100">
<path d="M50 15 C45 28 35 48 35 65 C35 78 42 85 50 85 C58 85 65 78 65 65 C65 48 55 28 50 15 Z" fill="#FFFFFF"></path>
<circle cx="50" cy="55" fill="#8C3494" r="7"></circle>
<path d="M32 68 L20 78 L26 62 Z" fill="#FFFFFF"></path>
<path d="M68 68 L80 78 L74 62 Z" fill="#FFFFFF"></path>
</svg>
</div>
<div class="flex flex-col min-w-0">
<div class="flex items-center gap-space-xs">
<span class="font-headline-sm text-headline-sm font-bold text-on-surface">রকেট (DBBL Rocket)</span>
<span class="bg-[#8C3494]/10 text-[#8C3494] font-label-sm text-label-sm px-2 py-0.5 rounded-full font-bold">ব্যক্তিগত</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">রকেট ওয়ালেট নম্বর: <span class="font-bold text-on-surface">0185481420</span></p>
</div>
</div>
<!-- Radio State Indicator -->
<div class="w-6 h-6 rounded-full bg-surface-container flex items-center justify-center shrink-0 radio-indicator" id="radio-rocket">
<div class="w-2.5 h-2.5 rounded-full bg-transparent"></div>
</div>
</div>
<!-- Instruction Accordion Drop (Rocket) -->
<div class="method-details hidden mt-space-sm pt-space-sm flex flex-col gap-space-xs" id="instructions-rocket">
<div class="bg-surface-container-low rounded-lg p-space-sm flex items-center justify-between">
<div class="flex flex-col">
<span class="font-label-sm text-label-sm text-on-surface-variant">নির্ধারিত রকেট নম্বর (ক্লিক করে কপি করুন):</span>
<span class="font-headline-sm text-headline-sm font-bold text-[#8C3494] tracking-wider">0185481420</span>
</div>
<button class="px-space-md py-1.5 rounded-lg bg-[#8C3494] text-white font-label-md text-label-md flex items-center gap-1 active:scale-95 transition-transform shadow-sm" onclick="copyNumber('0185481420', event)" type="button">
<span class="material-symbols-outlined text-[16px]">content_copy</span>
<span>কপি</span>
</button>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant px-1">
          * ডাচ-বাংলা রকেট অ্যাপ থেকে Send Money সম্পন্ন করে TrxID সংগ্রহ করুন।
        </p>
</div>
</div>
</div>
<!-- Transaction Verification Submission Form -->
<div class="px-margin my-space-sm">
<div class="bg-surface-container-lowest rounded-xl shadow-md p-space-md flex flex-col gap-space-md">
<div class="flex items-center gap-space-xs">
<span class="material-symbols-outlined text-secondary text-[22px]">assignment_turned_in</span>
<h3 class="font-title-md text-title-md text-on-surface font-bold">পেমেন্ট ভেরিফিকেশন ফর্ম পূরণ করুন</h3>
</div>
<!-- Field 1: Sender Phone Number -->
<div class="flex flex-col gap-1.5">
<label class="font-label-lg text-label-lg text-on-surface flex items-center justify-between" for="senderPhone">
<span>আপনার প্রেরক ফোন নম্বর (Sender Number)</span>
<span class="text-error font-body-sm text-body-sm">*আবশ্যক</span>
</label>
<div class="relative flex items-center">
<span class="absolute left-3 text-on-surface-variant material-symbols-outlined text-[20px]">phone_iphone</span>
<input class="w-full pl-10 pr-4 py-3 rounded-lg bg-surface-container-low text-on-surface font-body-md text-body-md placeholder:text-on-surface-variant/60 focus:bg-surface-container-lowest focus:outline-none transition-colors" id="senderPhone" placeholder="যেমন: 017xxxxxxxx বা 018xxxxxxxx" type="tel"/>
</div>
</div>
<!-- Field 2: Transaction ID -->
<div class="flex flex-col gap-1.5">
<label class="font-label-lg text-label-lg text-on-surface flex items-center justify-between" for="trxId">
<span>ট্র
