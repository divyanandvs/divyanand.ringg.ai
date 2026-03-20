<!-- Design System -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>The Monograph | Home</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Manrope:wght@300;400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-primary": "#ffffff",
              "primary-container": "#e07a5f",
              "surface-dim": "#dadad9",
              "error": "#ba1a1a",
              "outline": "#88726d",
              "on-surface-variant": "#55423e",
              "on-error": "#ffffff",
              "on-tertiary-fixed-variant": "#005144",
              "tertiary-fixed": "#7df7dd",
              "surface-container-highest": "#e3e2e1",
              "on-primary-fixed-variant": "#7c2e19",
              "on-secondary-fixed": "#0e1d25",
              "on-secondary-container": "#55656d",
              "surface": "#faf9f8",
              "on-tertiary-fixed": "#00201a",
              "secondary-fixed-dim": "#b9c9d3",
              "surface-container-high": "#e9e8e7",
              "tertiary-fixed-dim": "#5edbc1",
              "on-error-container": "#93000a",
              "on-primary-container": "#5b1604",
              "secondary": "#516169",
              "on-surface": "#1a1c1c",
              "primary-fixed-dim": "#ffb4a1",
              "error-container": "#ffdad6",
              "inverse-primary": "#ffb4a1",
              "primary": "#9a442d",
              "inverse-surface": "#2f3130",
              "surface-variant": "#e3e2e1",
              "outline-variant": "#dbc1ba",
              "tertiary-container": "#19a992",
              "surface-bright": "#faf9f8",
              "on-primary-fixed": "#3c0800",
              "primary-fixed": "#ffdbd2",
              "secondary-container": "#d2e2ec",
              "on-secondary": "#ffffff",
              "surface-container-lowest": "#ffffff",
              "inverse-on-surface": "#f1f0f0",
              "surface-tint": "#9a442d",
              "on-secondary-fixed-variant": "#3a4951",
              "background": "#faf9f8",
              "tertiary": "#006b5b",
              "secondary-fixed": "#d5e5ef",
              "surface-container-low": "#f4f3f2",
              "on-tertiary-container": "#00362d",
              "surface-container": "#eeeeed",
              "on-background": "#1a1c1c",
              "on-tertiary": "#ffffff"
            },
            fontFamily: {
              "headline": ["Noto Serif"],
              "body": ["Manrope"],
              "label": ["Manrope"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "1rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
            vertical-align: middle;
        }
        body { font-family: 'Manrope', sans-serif; }
        h1, h2, h3 { font-family: 'Noto Serif', serif; }
    </style>
</head>
<body class="bg-surface text-on-surface antialiased">
<!-- TopAppBar Component -->
<nav class="fixed top-0 w-full z-50 bg-[#faf9f8]/80 dark:bg-[#1a1c1c]/80 backdrop-blur-xl shadow-[0_10px_40px_rgba(26,28,28,0.06)]">
<div class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
<div class="text-xl font-bold font-noto-serif text-[#9a442d] dark:text-[#e07a5f]">The Monograph</div>
<div class="hidden md:flex items-center gap-12 font-manrope text-sm tracking-wide uppercase">
<a class="text-[#9a442d] dark:text-[#e07a5f] border-b-2 border-[#9a442d]/30 pb-1" href="#">Home</a>
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors" href="#">Work</a>
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors" href="#">About</a>
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors" href="#">Contact</a>
</div>
<div class="flex items-center gap-4">
<button class="text-[#1a1c1c] dark:text-[#faf9f8] hover:opacity-80 transition-opacity duration-300">
<span class="material-symbols-outlined" data-icon="mail">mail</span>
</button>
</div>
</div>
</nav>
<!-- Main Content Canvas -->
<main class="pt-32">
<!-- Hero Section -->
<section class="max-w-7xl mx-auto px-8 py-20 lg:py-40 flex flex-col lg:flex-row items-center gap-16">
<div class="w-full lg:w-3/5 space-y-8">
<div class="space-y-4">
<span class="font-label text-sm uppercase tracking-[0.2em] text-primary font-semibold">Digital Architect &amp; Curator</span>
<h1 class="text-5xl md:text-7xl lg:text-8xl font-headline font-bold text-on-surface leading-[1.1] tracking-tight">
                        Julian <span class="italic text-primary">Vane</span>
</h1>
</div>
<p class="text-lg md:text-xl text-on-surface-variant max-w-xl font-body leading-relaxed">
                    Crafting digital narratives through intentional asymmetry and tonal depth. A monograph of selective works focusing on high-end identity and architectural interfaces.
                </p>
<div class="pt-6">
<button class="bg-primary text-on-primary px-8 py-4 rounded-lg font-body font-semibold text-lg flex items-center gap-3 hover:bg-primary-container transition-all shadow-sm active:scale-95 duration-200">
                        View My Work
                        <span class="material-symbols-outlined text-xl" data-icon="arrow_forward">arrow_forward</span>
</button>
</div>
</div>
<div class="w-full lg:w-2/5 relative">
<div class="aspect-[4/5] rounded-lg overflow-hidden bg-surface-container-high shadow-2xl">
<img alt="Professional Portrait" class="w-full h-full object-cover" data-alt="Modern professional portrait with dramatic lighting and warm tones" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAXlKaGEQ8jmOqb_l2hkCokbW0QEIoH3QbAZCwi_u8uBx94A6eM3H7uV84WKHWYWsJGcd_jTdIFgm9lvAN6qwkyCZunnqwkLZy5fz_BLWV_BoohXTk1Y8f9OccPygHswIM6YLwXFVKFmgMA-FO8okR3qvpqqtyvKUxDNQ5eBgY3yB9W2kOfxuU2NaBGO6mjcvRZEEJftJAbVG0t-5V0qx4JpLoGiCW8qnzK17j5cPyLyPCKZTr4EEqph-tHgzZ55qhDcsQeZAbQxKs"/>
</div>
<!-- Editorial Accent -->
<div class="absolute -bottom-6 -left-6 bg-surface-container-lowest p-6 rounded-lg shadow-xl hidden md:block">
<p class="font-headline italic text-primary text-xl">"Details define the whole."</p>
<p class="font-label text-[10px] uppercase tracking-widest mt-1 opacity-60">Manifesto No. 04</p>
</div>
</div>
</section>
<!-- Selected Focus / Bento Grid -->
<section class="bg-surface-container-low py-32 mt-20">
<div class="max-w-7xl mx-auto px-8">
<div class="mb-20 space-y-4">
<h2 class="text-3xl md:text-4xl font-headline font-bold">Curated Focus</h2>
<div class="h-1 w-20 bg-primary/30"></div>
</div>
<div class="grid grid-cols-1 md:grid-cols-12 gap-8">
<!-- Feature Card 1 -->
<div class="md:col-span-8 group cursor-pointer">
<div class="relative overflow-hidden rounded-lg aspect-video bg-surface-container-high">
<img alt="Design Project" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="Minimalist interior design shot with soft ambient light" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCFpd5c6Wk49UyVa-EFnop9rNEwUm3Q6GtHeuAGcvZdi-8hVzTfigWNJfQtNauTo2LUigfXs2ny04Gje5Yi2emeiIgXRhKxz4u7MpBn_3vZysSnoz39wZ2fsNmFridDUaGn4C5HB6pRUec3zY60gVn4Bl4SBDxMbGLi-OxfFkzOfI-ULeUcE72GQ8RBFsdez0p4U5avxGdtd8Wdi5Uc7SlF4ME9OuJX83FHwvMZ2sL7TPzLVXCkceTVbvEQxUONoIQxn7KawuH5_iI"/>
<div class="absolute inset-0 bg-gradient-to-t from-on-surface/60 to-transparent flex flex-col justify-end p-8">
<span class="text-white/70 text-xs font-label uppercase tracking-widest mb-2">Editorial Design</span>
<h3 class="text-white text-2xl font-headline font-semibold">The Nordic Archive</h3>
</div>
</div>
</div>
<!-- Feature Card 2 -->
<div class="md:col-span-4 group cursor-pointer">
<div class="relative overflow-hidden rounded-lg aspect-[4/5] md:aspect-auto h-full bg-surface-container-high">
<img alt="Identity Design" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="Abstract golden ratio geometric sketch on paper" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDc-z9Lz_QBfhyNsQS7CwfR9SSImr1-VX3z0IMCsdAzFx5ZaXWGEKMhPUTdvGRSiM5IpyQRHLtt84BaT71nFWS9xxjG-X55O89OZ25WbQPflGaYFJtG0mGYeISBROKBHzppVFUmQ2hckt2zfgwKlH-eKErr-zmsP6ET3gPwMo7Ri2U8heXERK7sU57Lydhr1-ZKmO0J7Nvbj4wx3Wbm3_LOo91eOTxy2TxnlIA7z2m4jRm5J8femF0hy0pL9IpJeDY49nveQ6nVsbo"/>
<div class="absolute inset-0 bg-primary/10 group-hover:bg-primary/0 transition-colors duration-500"></div>
<div class="absolute bottom-0 left-0 p-8">
<span class="text-on-surface text-xs font-label uppercase tracking-widest mb-2 block">Brand Identity</span>
<h3 class="text-on-surface text-2xl font-headline font-semibold">Solace Studio</h3>
</div>
</div>
</div>
<!-- Feature Card 3 -->
<div class="md:col-span-4 group cursor-pointer">
<div class="p-10 rounded-lg bg-surface-container-lowest h-full flex flex-col justify-between border-l-4 border-primary/20">
<div class="space-y-4">
<span class="material-symbols-outlined text-primary text-4xl" data-icon="architecture">architecture</span>
<h3 class="text-xl font-headline font-bold">Systems Thinking</h3>
<p class="text-on-surface-variant font-body text-sm leading-relaxed">Developing scalable design languages that harmonize utility and aesthetic elegance.</p>
</div>
<a class="text-primary font-label text-xs uppercase tracking-widest font-bold mt-8 flex items-center gap-2" href="#">
                                Learn More 
                                <span class="material-symbols-outlined text-sm" data-icon="north_east">north_east</span>
</a>
</div>
</div>
<!-- Feature Card 4 -->
<div class="md:col-span-8 group cursor-pointer">
<div class="relative overflow-hidden rounded-lg aspect-video bg-surface-container-high">
<img alt="Web Experience" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" data-alt="High-end digital interface layout on a laptop screen" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCGdlM5N8vrvyVrgW2Vrfu3RvkV1h8v3Wn8uFcFbiHVx7zWbpVIlkEzA6frq8-YMipVHeGXw1IngUS6fl2lM7qabGAFihLIZoCWyubR-BtVl61S7uL4Al9X1nKv6wx4X1lyO9M2NPYWyTusNwnjUsks6HwcZ05i9wqcZUznpe76NyNHwvNuHlv19tpzCEBM9V0BDPv-M0dq8--1Q2Q43LWfQx1ZGzET2IBNhVcbo_wRWum5Uzw9z9eWLWKDsmnMbpj8hD4nMP6TgsA"/>
<div class="absolute inset-0 bg-gradient-to-r from-on-surface/40 to-transparent flex flex-col justify-center p-12">
<span class="text-white/80 text-xs font-label uppercase tracking-widest mb-2">Digital Experience</span>
<h3 class="text-white text-3xl font-headline font-semibold max-w-xs">Interactive Monographs</h3>
</div>
</div>
</div>
</div>
</div>
</section>
</main>
<!-- Footer Component -->
<footer class="w-full mt-20 bg-[#f4f3f2] dark:bg-[#252727]">
<div class="flex flex-col md:flex-row justify-between items-center px-12 py-16 w-full max-w-7xl mx-auto">
<div class="space-y-4 mb-8 md:mb-0 text-center md:text-left">
<div class="font-noto-serif italic text-lg text-[#9a442d] dark:text-[#e07a5f]">The Curated Monograph</div>
<p class="font-manrope text-sm tracking-wide text-[#1a1c1c] dark:text-[#faf9f8] uppercase opacity-60">© 2024 The Curated Monograph. All rights reserved.</p>
</div>
<div class="flex gap-12 font-manrope text-sm tracking-wide text-[#1a1c1c] dark:text-[#faf9f8] uppercase">
<a class="text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Archive</a>
<a class="text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Journal</a>
<a class="text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Legal</a>
</div>
</div>
</footer>
</body></html>

<!-- Home Screen -->
<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>About | The Monograph</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Manrope:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-primary": "#ffffff",
              "primary-container": "#e07a5f",
              "surface-dim": "#dadad9",
              "error": "#ba1a1a",
              "outline": "#88726d",
              "on-surface-variant": "#55423e",
              "on-error": "#ffffff",
              "on-tertiary-fixed-variant": "#005144",
              "tertiary-fixed": "#7df7dd",
              "surface-container-highest": "#e3e2e1",
              "on-primary-fixed-variant": "#7c2e19",
              "on-secondary-fixed": "#0e1d25",
              "on-secondary-container": "#55656d",
              "surface": "#faf9f8",
              "on-tertiary-fixed": "#00201a",
              "secondary-fixed-dim": "#b9c9d3",
              "surface-container-high": "#e9e8e7",
              "tertiary-fixed-dim": "#5edbc1",
              "on-error-container": "#93000a",
              "on-primary-container": "#5b1604",
              "secondary": "#516169",
              "on-surface": "#1a1c1c",
              "primary-fixed-dim": "#ffb4a1",
              "error-container": "#ffdad6",
              "inverse-primary": "#ffb4a1",
              "primary": "#9a442d",
              "inverse-surface": "#2f3130",
              "surface-variant": "#e3e2e1",
              "outline-variant": "#dbc1ba",
              "tertiary-container": "#19a992",
              "surface-bright": "#faf9f8",
              "on-primary-fixed": "#3c0800",
              "primary-fixed": "#ffdbd2",
              "secondary-container": "#d2e2ec",
              "on-secondary": "#ffffff",
              "surface-container-lowest": "#ffffff",
              "inverse-on-surface": "#f1f0f0",
              "surface-tint": "#9a442d",
              "on-secondary-fixed-variant": "#3a4951",
              "background": "#faf9f8",
              "tertiary": "#006b5b",
              "secondary-fixed": "#d5e5ef",
              "surface-container-low": "#f4f3f2",
              "on-tertiary-container": "#00362d",
              "surface-container": "#eeeeed",
              "on-background": "#1a1c1c",
              "on-tertiary": "#ffffff"
            },
            fontFamily: {
              "noto-serif": ["Noto Serif", "serif"],
              "manrope": ["Manrope", "sans-serif"],
              "headline": ["Noto Serif"],
              "body": ["Manrope"],
              "label": ["Manrope"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      .no-scrollbar::-webkit-scrollbar { display: none; }
      .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="bg-surface text-on-surface font-body selection:bg-primary-container selection:text-on-primary-container">
<!-- TopAppBar -->
<nav class="fixed top-0 w-full z-50 bg-[#faf9f8]/80 dark:bg-[#1a1c1c]/80 backdrop-blur-xl shadow-[0_10px_40px_rgba(26,28,28,0.06)]">
<div class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
<span class="text-xl font-bold font-noto-serif text-[#9a442d] dark:text-[#e07a5f]">The Monograph</span>
<div class="hidden md:flex items-center gap-10">
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors font-manrope text-sm tracking-wide uppercase" href="#">Home</a>
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors font-manrope text-sm tracking-wide uppercase" href="#">Work</a>
<a class="text-[#9a442d] dark:text-[#e07a5f] border-b-2 border-[#9a442d]/30 pb-1 font-manrope text-sm tracking-wide uppercase" href="#">About</a>
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors font-manrope text-sm tracking-wide uppercase" href="#">Contact</a>
</div>
<div class="flex items-center gap-4">
<button class="hover:opacity-80 transition-opacity duration-300 active:scale-95 duration-200">
<span class="material-symbols-outlined text-[#9a442d] dark:text-[#e07a5f]" data-icon="mail">mail</span>
</button>
</div>
</div>
</nav>
<main class="pt-32 pb-20">
<!-- Hero Section: Editorial Intro -->
<section class="max-w-7xl mx-auto px-8 grid grid-cols-1 md:grid-cols-12 gap-12 items-end mb-24">
<div class="md:col-span-7">
<span class="font-label text-sm uppercase tracking-widest text-primary mb-6 block">The Person Behind the Craft</span>
<h1 class="font-headline text-5xl md:text-7xl lg:text-8xl leading-[1.1] mb-8">
                    Design is the <br/> <span class="italic">silent</span> ambassador of your brand.
                </h1>
<p class="font-body text-xl text-on-surface-variant max-w-xl leading-relaxed">
                    I am a designer focused on creating digital experiences that feel as intentional and tactile as a high-end monograph. My philosophy centers on subtraction, hierarchy, and the soul of typography.
                </p>
</div>
<div class="md:col-span-5 relative group">
<div class="aspect-[4/5] rounded-lg overflow-hidden bg-surface-container-low shadow-[0_40px_80px_rgba(26,28,28,0.1)] transition-transform duration-700 hover:scale-[1.02]">
<img alt="Designer portrait" class="w-full h-full object-cover" data-alt="Professional friendly portrait of a designer against a neutral background" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCoVlM_7HT05PgUcJgHJm4hJLym0_LLxnvqf7s42EoU7AKAiSJq4EUt-SJGdYlt4vwmEHhYAByGeenO6K00T--Pr72WjuNlm_cVrZmeCrG_gdtY8d40lT7aEbl9RMLQcXg3fjXtrHupVhBMzwQIAlEV5Hmke2QAFdkZirX7zQqNAQ90_kerZAVLLIjfwU043rahaj-tDBPpqeNblAH8ioLLdeO0tXA241CWRWsESHRpPr93NS50xvTAJLEHvn5LJ11bVL--TQYBRus"/>
</div>
<div class="absolute -bottom-6 -left-6 bg-primary p-6 rounded-lg text-on-primary shadow-xl hidden lg:block">
<span class="font-noto-serif italic text-3xl">12+</span>
<p class="text-xs uppercase tracking-tighter opacity-80 mt-1">Years Experience</p>
</div>
</div>
</section>
<!-- Biography & Philosophy -->
<section class="bg-surface-container-low py-32 mb-24">
<div class="max-w-7xl mx-auto px-8 grid grid-cols-1 md:grid-cols-12 gap-16">
<div class="md:col-start-2 md:col-span-4">
<h2 class="font-headline text-3xl italic mb-6">The Background</h2>
<div class="space-y-6 text-on-surface-variant leading-relaxed">
<p>Starting my career in editorial design for print journals, I learned the importance of whitespace and the rhythm of content. This foundation now guides my digital work.</p>
<p>I believe that every pixel should serve a purpose. If it doesn't aid navigation or enhance meaning, it is noise. My transition to digital was fueled by a desire to combine this classic rigor with the fluidity of interaction.</p>
</div>
</div>
<div class="md:col-span-6 flex flex-col justify-center">
<div class="border-l-2 border-primary/20 pl-12 space-y-12">
<div>
<h3 class="font-label text-xs uppercase tracking-[0.2em] text-primary mb-4">Values</h3>
<p class="font-headline text-2xl">Intentionality over trends. Clarity over decoration. Accessibility over aesthetics.</p>
</div>
<div class="grid grid-cols-2 gap-8">
<div>
<h4 class="font-label text-xs uppercase tracking-widest mb-2 opacity-60">Location</h4>
<p class="font-manrope">Stockholm, SE</p>
</div>
<div>
<h4 class="font-label text-xs uppercase tracking-widest mb-2 opacity-60">Specialty</h4>
<p class="font-manrope">Product Strategy</p>
</div>
</div>
</div>
</div>
</div>
</section>
<!-- Skills Section: Modern Bento Tags -->
<section class="max-w-7xl mx-auto px-8 mb-32">
<div class="mb-12 flex flex-col items-center text-center">
<h2 class="font-headline text-4xl mb-4">Core Competencies</h2>
<p class="text-on-surface-variant max-w-lg">A toolkit refined through years of multidisciplinary projects and collaborative leadership.</p>
</div>
<div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-4">
<!-- Skill Chip -->
<div class="bg-surface-container-high p-6 rounded-xl flex flex-col items-center text-center gap-4 transition-all hover:bg-white hover:shadow-lg">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="architecture">architecture</span>
<span class="font-label text-sm font-semibold">Systems Design</span>
</div>
<div class="bg-surface-container-high p-6 rounded-xl flex flex-col items-center text-center gap-4 transition-all hover:bg-white hover:shadow-lg">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="grid_view">grid_view</span>
<span class="font-label text-sm font-semibold">Bento Layouts</span>
</div>
<div class="bg-surface-container-high p-6 rounded-xl flex flex-col items-center text-center gap-4 transition-all hover:bg-white hover:shadow-lg">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="auto_awesome">auto_awesome</span>
<span class="font-label text-sm font-semibold">Art Direction</span>
</div>
<div class="bg-surface-container-high p-6 rounded-xl flex flex-col items-center text-center gap-4 transition-all hover:bg-white hover:shadow-lg">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="terminal">terminal</span>
<span class="font-label text-sm font-semibold">Front-End</span>
</div>
<div class="bg-surface-container-high p-6 rounded-xl flex flex-col items-center text-center gap-4 transition-all hover:bg-white hover:shadow-lg">
<span class="material-symbols-outlined text-primary text-3xl" data-icon="history_edu">history_edu</span>
<span class="font-label text-sm font-semibold">Typography</span>
</div>
</div>
<div class="mt-8 flex flex-wrap justify-center gap-3">
<span class="px-6 py-2 rounded-full bg-secondary-container text-on-secondary-container text-xs font-bold uppercase tracking-widest">Figma</span>
<span class="px-6 py-2 rounded-full bg-secondary-container text-on-secondary-container text-xs font-bold uppercase tracking-widest">React</span>
<span class="px-6 py-2 rounded-full bg-secondary-container text-on-secondary-container text-xs font-bold uppercase tracking-widest">Tailwind</span>
<span class="px-6 py-2 rounded-full bg-secondary-container text-on-secondary-container text-xs font-bold uppercase tracking-widest">Next.js</span>
<span class="px-6 py-2 rounded-full bg-secondary-container text-on-secondary-container text-xs font-bold uppercase tracking-widest">Python</span>
<span class="px-6 py-2 rounded-full bg-secondary-container text-on-secondary-container text-xs font-bold uppercase tracking-widest">Three.js</span>
</div>
</section>
<!-- Experience Timeline -->
<section class="max-w-4xl mx-auto px-8 mb-32">
<h2 class="font-headline text-3xl mb-16 text-center">Selected Experience</h2>
<div class="space-y-20 relative before:absolute before:left-0 md:before:left-1/2 before:w-[1px] before:h-full before:bg-outline-variant/30">
<!-- Timeline Item 1 -->
<div class="relative flex flex-col md:flex-row md:items-center justify-between gap-8">
<div class="md:w-[45%] md:text-right order-2 md:order-1">
<span class="font-noto-serif text-primary text-lg italic block mb-2">2021 — Present</span>
<h3 class="text-xl font-bold mb-1">Senior Design Lead</h3>
<p class="text-on-surface-variant text-sm">Aesthetic &amp; Co.</p>
</div>
<div class="absolute left-0 md:left-1/2 -translate-x-1/2 w-3 h-3 rounded-full bg-primary border-4 border-surface z-10 hidden md:block"></div>
<div class="md:w-[45%] order-3">
<p class="text-sm text-on-surface-variant leading-relaxed">Directing a multidisciplinary team of 12 designers to reinvent digital commerce for premium lifestyle brands.</p>
</div>
</div>
<!-- Timeline Item 2 -->
<div class="relative flex flex-col md:flex-row md:items-center justify-between gap-8">
<div class="md:w-[45%] order-1 md:order-1">
<p class="text-sm text-on-surface-variant leading-relaxed md:text-right">Specialized in crafting design systems that bridge the gap between marketing and product engineering.</p>
</div>
<div class="absolute left-0 md:left-1/2 -translate-x-1/2 w-3 h-3 rounded-full bg-primary border-4 border-surface z-10 hidden md:block"></div>
<div class="md:w-[45%] order-2 md:order-3">
<span class="font-noto-serif text-primary text-lg italic block mb-2">2018 — 2021</span>
<h3 class="text-xl font-bold mb-1">Product Designer</h3>
<p class="text-on-surface-variant text-sm">Kinfolk Digital</p>
</div>
</div>
<!-- Timeline Item 3 -->
<div class="relative flex flex-col md:flex-row md:items-center justify-between gap-8">
<div class="md:w-[45%] md:text-right order-2 md:order-1">
<span class="font-noto-serif text-primary text-lg italic block mb-2">2015 — 2018</span>
<h3 class="text-xl font-bold mb-1">Visual Designer</h3>
<p class="text-on-surface-variant text-sm">Monograph Studio</p>
</div>
<div class="absolute left-0 md:left-1/2 -translate-x-1/2 w-3 h-3 rounded-full bg-primary border-4 border-surface z-10 hidden md:block"></div>
<div class="md:w-[45%] order-3">
<p class="text-sm text-on-surface-variant leading-relaxed">Foundational years focusing on grid systems, typography selection, and brand identity development.</p>
</div>
</div>
</div>
</section>
<!-- CTA Section -->
<section class="max-w-5xl mx-auto px-8 text-center mb-32">
<div class="bg-primary p-16 rounded-xl text-on-primary">
<h2 class="font-headline text-4xl mb-6">Let's craft something meaningful together.</h2>
<p class="text-lg opacity-90 mb-10 max-w-xl mx-auto">Currently accepting new projects for Q3 2024. Reach out for a consultation on your next digital venture.</p>
<a class="inline-block bg-white text-primary px-10 py-4 rounded-lg font-manrope font-bold uppercase tracking-widest text-sm transition-all hover:bg-primary-container hover:text-on-primary" href="#">Start a Conversation</a>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full mt-20 bg-[#f4f3f2] dark:bg-[#252727]">
<div class="flex flex-col md:flex-row justify-between items-center px-12 py-16 w-full max-w-7xl mx-auto">
<div class="mb-8 md:mb-0">
<span class="font-noto-serif italic text-lg text-[#9a442d] dark:text-[#e07a5f]">The Curated Monograph</span>
<p class="font-manrope text-sm tracking-wide text-[#1a1c1c] dark:text-[#faf9f8] uppercase mt-4">© 2024 The Curated Monograph. All rights reserved.</p>
</div>
<div class="flex gap-12">
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Archive</a>
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Journal</a>
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Legal</a>
</div>
</div>
</footer>
</body></html>

<!-- About Me -->
<!DOCTYPE html>

<html lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Contact — The Monograph</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Manrope:wght@400;500;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-primary": "#ffffff",
              "primary-container": "#e07a5f",
              "surface-dim": "#dadad9",
              "error": "#ba1a1a",
              "outline": "#88726d",
              "on-surface-variant": "#55423e",
              "on-error": "#ffffff",
              "on-tertiary-fixed-variant": "#005144",
              "tertiary-fixed": "#7df7dd",
              "surface-container-highest": "#e3e2e1",
              "on-primary-fixed-variant": "#7c2e19",
              "on-secondary-fixed": "#0e1d25",
              "on-secondary-container": "#55656d",
              "surface": "#faf9f8",
              "on-tertiary-fixed": "#00201a",
              "secondary-fixed-dim": "#b9c9d3",
              "surface-container-high": "#e9e8e7",
              "tertiary-fixed-dim": "#5edbc1",
              "on-error-container": "#93000a",
              "on-primary-container": "#5b1604",
              "secondary": "#516169",
              "on-surface": "#1a1c1c",
              "primary-fixed-dim": "#ffb4a1",
              "error-container": "#ffdad6",
              "inverse-primary": "#ffb4a1",
              "primary": "#9a442d",
              "inverse-surface": "#2f3130",
              "surface-variant": "#e3e2e1",
              "outline-variant": "#dbc1ba",
              "tertiary-container": "#19a992",
              "surface-bright": "#faf9f8",
              "on-primary-fixed": "#3c0800",
              "primary-fixed": "#ffdbd2",
              "secondary-container": "#d2e2ec",
              "on-secondary": "#ffffff",
              "surface-container-lowest": "#ffffff",
              "inverse-on-surface": "#f1f0f0",
              "surface-tint": "#9a442d",
              "on-secondary-fixed-variant": "#3a4951",
              "background": "#faf9f8",
              "tertiary": "#006b5b",
              "secondary-fixed": "#d5e5ef",
              "surface-container-low": "#f4f3f2",
              "on-tertiary-container": "#00362d",
              "surface-container": "#eeeeed",
              "on-background": "#1a1c1c",
              "on-tertiary": "#ffffff"
            },
            fontFamily: {
              "noto-serif": ["Noto Serif", "serif"],
              "manrope": ["Manrope", "sans-serif"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "1rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
        .form-input-focus:focus {
            border-bottom-width: 2px;
            border-bottom-color: #9a442d;
            outline: none;
        }
    </style>
</head>
<body class="bg-surface text-on-surface font-manrope selection:bg-primary-container/30">
<!-- TopAppBar Navigation -->
<header class="fixed top-0 w-full z-50 bg-[#faf9f8]/80 dark:bg-[#1a1c1c]/80 backdrop-blur-xl shadow-[0_10px_40px_rgba(26,28,28,0.06)]">
<nav class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
<div class="text-xl font-bold font-noto-serif text-[#9a442d] dark:text-[#e07a5f]">
                The Monograph
            </div>
<div class="hidden md:flex items-center space-x-12">
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors" href="#">Home</a>
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors" href="#">Work</a>
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors" href="#">About</a>
<a class="text-[#9a442d] dark:text-[#e07a5f] border-b-2 border-[#9a442d]/30 pb-1" href="#">Contact</a>
</div>
<div class="flex items-center space-x-4">
<button class="text-[#9a442d] dark:text-[#e07a5f] hover:opacity-80 transition-opacity duration-300">
<span class="material-symbols-outlined" data-icon="mail">mail</span>
</button>
</div>
</nav>
</header>
<main class="pt-32 pb-20 px-8 max-w-7xl mx-auto min-h-screen">
<!-- Hero Section -->
<section class="mb-20 md:mb-32 max-w-4xl">
<h1 class="font-noto-serif text-5xl md:text-7xl mb-8 tracking-tight text-on-surface">
                Let's start a <span class="italic text-primary">dialogue</span>.
            </h1>
<p class="text-xl text-on-surface-variant leading-relaxed font-manrope max-w-2xl">
                Whether you have a specific project in mind or simply want to discuss the finer points of design and craft, my door is always open.
            </p>
</section>
<!-- Asymmetric Layout Container -->
<div class="grid grid-cols-1 lg:grid-cols-12 gap-16 lg:gap-24">
<!-- Information Column (Marginalia Effect) -->
<div class="lg:col-span-4 space-y-16">
<div>
<h3 class="font-manrope text-xs font-bold tracking-[0.2em] text-on-surface-variant uppercase mb-6">Correspondence</h3>
<div class="space-y-4">
<a class="block text-xl font-noto-serif text-primary hover:opacity-70 transition-opacity" href="mailto:hello@themonograph.com">hello@themonograph.com</a>
<p class="text-on-surface-variant">+1 (555) 0123 4567</p>
</div>
</div>
<div>
<h3 class="font-manrope text-xs font-bold tracking-[0.2em] text-on-surface-variant uppercase mb-6">Archive Office</h3>
<p class="text-on-surface-variant leading-relaxed">
                        128 Curated Way<br/>
                        Creative Quarter, Studio 04<br/>
                        London, E1 6QL
                    </p>
</div>
<div>
<h3 class="font-manrope text-xs font-bold tracking-[0.2em] text-on-surface-variant uppercase mb-6">Digital Presence</h3>
<ul class="space-y-3">
<li><a class="text-on-surface hover:text-primary transition-colors flex items-center gap-2" href="#">Instagram <span class="material-symbols-outlined text-sm" data-icon="north_east">north_east</span></a></li>
<li><a class="text-on-surface hover:text-primary transition-colors flex items-center gap-2" href="#">LinkedIn <span class="material-symbols-outlined text-sm" data-icon="north_east">north_east</span></a></li>
<li><a class="text-on-surface hover:text-primary transition-colors flex items-center gap-2" href="#">Twitter <span class="material-symbols-outlined text-sm" data-icon="north_east">north_east</span></a></li>
</ul>
</div>
</div>
<!-- Contact Form Column -->
<div class="lg:col-span-8">
<div class="bg-surface-container-low p-8 md:p-12 rounded-lg">
<form class="space-y-10">
<div class="grid grid-cols-1 md:grid-cols-2 gap-10">
<!-- Name Field -->
<div class="relative group">
<label class="block font-manrope text-[10px] font-bold tracking-widest text-on-surface-variant uppercase mb-2" for="name">Full Name</label>
<input class="w-full bg-surface-container-highest border-0 border-b border-outline-variant/30 px-0 py-3 text-on-surface font-manrope placeholder:text-on-surface-variant/40 focus:ring-0 focus:border-primary transition-all rounded-t-sm form-input-focus" id="name" name="name" placeholder="Johnathan Doe" type="text"/>
</div>
<!-- Email Field -->
<div class="relative group">
<label class="block font-manrope text-[10px] font-bold tracking-widest text-on-surface-variant uppercase mb-2" for="email">Email Address</label>
<input class="w-full bg-surface-container-highest border-0 border-b border-outline-variant/30 px-0 py-3 text-on-surface font-manrope placeholder:text-on-surface-variant/40 focus:ring-0 focus:border-primary transition-all rounded-t-sm form-input-focus" id="email" name="email" placeholder="j.doe@example.com" type="email"/>
</div>
</div>
<!-- Message Field -->
<div class="relative group">
<label class="block font-manrope text-[10px] font-bold tracking-widest text-on-surface-variant uppercase mb-2" for="message">Your Message</label>
<textarea class="w-full bg-surface-container-highest border-0 border-b border-outline-variant/30 px-0 py-3 text-on-surface font-manrope placeholder:text-on-surface-variant/40 focus:ring-0 focus:border-primary transition-all rounded-t-sm form-input-focus resize-none" id="message" name="message" placeholder="Tell me about your vision..." rows="4"></textarea>
</div>
<!-- Submit Button -->
<div class="pt-4 flex flex-col md:flex-row md:items-center justify-between gap-8">
<p class="text-xs text-on-surface-variant/60 max-w-xs font-manrope">
                                By sending this message, you agree to our privacy policy regarding the handling of your data.
                            </p>
<button class="bg-primary text-on-primary px-10 py-5 rounded-lg font-manrope font-bold text-sm tracking-widest uppercase hover:bg-primary-container transition-all hover:shadow-lg active:scale-95 duration-200 inline-flex items-center justify-center gap-3" type="submit">
                                Send Message
                                <span class="material-symbols-outlined text-sm" data-icon="send">send</span>
</button>
</div>
</form>
</div>
<!-- Ambient Decor Element -->
<div class="mt-12 flex justify-end">
<div class="flex items-baseline gap-2">
<span class="font-noto-serif italic text-on-surface-variant/40 text-4xl">04</span>
<div class="h-[1px] w-24 bg-outline-variant/30"></div>
<span class="font-manrope text-[10px] font-bold tracking-[0.3em] text-on-surface-variant uppercase">The Final Step</span>
</div>
</div>
</div>
</div>
</main>
<!-- Footer Component -->
<footer class="w-full mt-20 bg-[#f4f3f2] dark:bg-[#252727]">
<div class="flex flex-col md:flex-row justify-between items-center px-12 py-16 w-full max-w-7xl mx-auto">
<div class="mb-8 md:mb-0">
<span class="font-noto-serif italic text-lg text-[#1a1c1c] dark:text-[#faf9f8]">The Curated Monograph</span>
</div>
<div class="flex flex-col md:flex-row items-center space-y-4 md:space-y-0 md:space-x-12 mb-8 md:mb-0">
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Archive</a>
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Journal</a>
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Legal</a>
</div>
<div class="text-center md:text-right">
<p class="font-manrope text-xs tracking-widest text-[#1a1c1c]/40 dark:text-[#faf9f8]/40 uppercase">
                    © 2024 The Curated Monograph. All rights reserved.
                </p>
</div>
</div>
</footer>
</body></html>

<!-- Contact Page -->
<!DOCTYPE html>

<html lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Manrope:wght@400;500;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-primary": "#ffffff",
              "primary-container": "#e07a5f",
              "surface-dim": "#dadad9",
              "error": "#ba1a1a",
              "outline": "#88726d",
              "on-surface-variant": "#55423e",
              "on-error": "#ffffff",
              "on-tertiary-fixed-variant": "#005144",
              "tertiary-fixed": "#7df7dd",
              "surface-container-highest": "#e3e2e1",
              "on-primary-fixed-variant": "#7c2e19",
              "on-secondary-fixed": "#0e1d25",
              "on-secondary-container": "#55656d",
              "surface": "#faf9f8",
              "on-tertiary-fixed": "#00201a",
              "secondary-fixed-dim": "#b9c9d3",
              "surface-container-high": "#e9e8e7",
              "tertiary-fixed-dim": "#5edbc1",
              "on-error-container": "#93000a",
              "on-primary-container": "#5b1604",
              "secondary": "#516169",
              "on-surface": "#1a1c1c",
              "primary-fixed-dim": "#ffb4a1",
              "error-container": "#ffdad6",
              "inverse-primary": "#ffb4a1",
              "primary": "#9a442d",
              "inverse-surface": "#2f3130",
              "surface-variant": "#e3e2e1",
              "outline-variant": "#dbc1ba",
              "tertiary-container": "#19a992",
              "surface-bright": "#faf9f8",
              "on-primary-fixed": "#3c0800",
              "primary-fixed": "#ffdbd2",
              "secondary-container": "#d2e2ec",
              "on-secondary": "#ffffff",
              "surface-container-lowest": "#ffffff",
              "inverse-on-surface": "#f1f0f0",
              "surface-tint": "#9a442d",
              "on-secondary-fixed-variant": "#3a4951",
              "background": "#faf9f8",
              "tertiary": "#006b5b",
              "secondary-fixed": "#d5e5ef",
              "surface-container-low": "#f4f3f2",
              "on-tertiary-container": "#00362d",
              "surface-container": "#eeeeed",
              "on-background": "#1a1c1c",
              "on-tertiary": "#ffffff"
            },
            fontFamily: {
              "headline": ["Noto Serif"],
              "body": ["Manrope"],
              "label": ["Manrope"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      .font-noto-serif { font-family: 'Noto Serif', serif; }
      .font-manrope { font-family: 'Manrope', sans-serif; }
    </style>
</head>
<body class="bg-surface text-on-surface font-body selection:bg-primary-container/30">
<!-- TopAppBar -->
<nav class="fixed top-0 w-full z-50 bg-[#faf9f8]/80 dark:bg-[#1a1c1c]/80 backdrop-blur-xl shadow-[0_10px_40px_rgba(26,28,28,0.06)]">
<div class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
<div class="text-xl font-bold font-noto-serif text-[#9a442d] dark:text-[#e07a5f]">The Monograph</div>
<div class="hidden md:flex items-center space-x-10">
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors" href="#">Home</a>
<a class="font-manrope text-sm tracking-wide text-[#9a442d] dark:text-[#e07a5f] border-b-2 border-[#9a442d]/30 pb-1" href="#">Work</a>
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors" href="#">About</a>
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors" href="#">Contact</a>
</div>
<div class="flex items-center space-x-4">
<button class="hover:opacity-80 transition-opacity duration-300 active:scale-95 text-[#9a442d] dark:text-[#e07a5f]">
<span class="material-symbols-outlined" data-icon="mail">mail</span>
</button>
<button class="md:hidden text-[#1a1c1c] dark:text-[#faf9f8]">
<span class="material-symbols-outlined" data-icon="menu">menu</span>
</button>
</div>
</div>
</nav>
<main class="pt-32 pb-20 px-6 max-w-7xl mx-auto">
<!-- Editorial Header Section -->
<header class="mb-20 grid grid-cols-12 gap-8">
<div class="col-span-12 md:col-start-4 md:col-span-8">
<h1 class="text-5xl md:text-7xl font-headline text-on-surface leading-tight mb-6">
                    Selected <span class="italic font-normal">Works</span>
</h1>
<p class="text-lg md:text-xl text-on-surface-variant max-w-2xl font-body leading-relaxed">
                    A collection of digital artifacts and identity systems crafted with a focus on editorial clarity and lasting impact.
                </p>
</div>
</header>
<!-- Filter System -->
<div class="mb-12 flex flex-wrap gap-4 items-center">
<span class="font-label text-xs uppercase tracking-[0.1em] text-outline mr-4">Filter by:</span>
<button class="px-6 py-2 rounded-full bg-primary text-on-primary font-label text-sm font-medium transition-all shadow-sm">All Projects</button>
<button class="px-6 py-2 rounded-full bg-surface-container-highest text-on-surface font-label text-sm font-medium hover:bg-secondary-container transition-all">Web Design</button>
<button class="px-6 py-2 rounded-full bg-surface-container-highest text-on-surface font-label text-sm font-medium hover:bg-secondary-container transition-all">Branding</button>
<button class="px-6 py-2 rounded-full bg-surface-container-highest text-on-surface font-label text-sm font-medium hover:bg-secondary-container transition-all">Illustration</button>
</div>
<!-- Portfolio Grid: Asymmetric Bento-inspired layout -->
<section class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-12">
<!-- Project 1: Large Featured -->
<article class="group lg:col-span-2 relative">
<div class="overflow-hidden rounded-lg bg-surface-container-low aspect-[16/9] mb-6">
<img alt="Minimalist Architecture Website" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-[1.03]" data-alt="Modern minimalist website design showing architectural photography" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDD-9_nDUP3om__9D1hJAPHCRvfqt6yBYTR1UzGYsPSdXcB0fxfOwkdqp1CcgZG31X_PMlKTVTN4dEw2ZuwDNC_kMaBFHBbuEgnKodR28zRuR6OkXFr6Zb9ycnS43REZeKuQWI68nTkO8GvkUP25LqGwxd8RfJOj3Lon0PGKvqHtYVSsnTOCdbynwsV-kuSRidY88a78UxGCfRVV6FEQQNMwj1YRv_WdQpN0oJP0bpLGoxjPwPRvQuLV6e88KY88b3lwfsq4zdvB7w"/>
</div>
<div class="flex flex-col">
<span class="font-label text-xs uppercase tracking-[0.1em] text-primary mb-2">Web Design • 2024</span>
<h3 class="text-3xl font-headline text-on-surface group-hover:text-primary transition-colors">The Solstice Pavilion</h3>
<p class="mt-2 text-on-surface-variant font-body max-w-lg">Digital experience for an avant-garde architectural firm based in Kyoto.</p>
</div>
</article>
<!-- Project 2 -->
<article class="group relative">
<div class="overflow-hidden rounded-lg bg-surface-container-low aspect-square mb-6">
<img alt="Typography Branding" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-[1.03]" data-alt="Close up of high-end typographic brand identity on textured paper" src="https://lh3.googleusercontent.com/aida-public/AB6AXuARcEHFAWajo74s26_3rqJd01p6toCTLWjJWr6xphjlNzGm4dKMAguK7mLBTJeT2riBB5bHcfHmWrRm5HRolknwbaSwCRono7ACkqw9DVOHFugp_Is2gsfgVbn7F87jdlHX7vIXDLlXfL5DpFHBME-FI3Zy6KWcBhK7FutxaHriWKZGxcr13NTkhOvJ1Bfw_kZ0oeAQwq4HHyICoK_sQt4EfSgW22YbmgYr5KFbOYBe-ANCU0hlY2RbDMNLa9L6MrPXRpBHlswNwAk"/>
</div>
<div class="flex flex-col">
<span class="font-label text-xs uppercase tracking-[0.1em] text-primary mb-2">Brand Identity</span>
<h3 class="text-2xl font-headline text-on-surface group-hover:text-primary transition-colors">Æther Press</h3>
<p class="mt-2 text-on-surface-variant font-body">Visual system for an independent publisher of rare manuscripts.</p>
</div>
</article>
<!-- Project 3 -->
<article class="group relative">
<div class="overflow-hidden rounded-lg bg-surface-container-low aspect-[4/5] mb-6">
<img alt="Editorial Illustration" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-[1.03]" data-alt="Abstract colorful editorial illustration with geometric shapes" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBoEDwfYoqCKxa40h1jeHv-Z_ZvmHW7TRfoAjb7TfkuazXrG2z3Z9ot330cZlMsKZPZ-bLO0I4Wa6RF3IlUAne9q4lk2Jo7Ckw8PJgnWtJ1n0l5bdPrmAWfsaRQ5vn1YHh77J3gXkK6KKu3NPBxWd4a8V2fD89Pc1NuQt4Fx_vxqQe2ugakf5t23WnoOENSPJJUUIFhE0ih3y6F-x7W2KHKIGVxg0DRm2-uGO126ifRg5_YxyDxasgJe_6m_oYd5kLOMQIneWMH_ck"/>
</div>
<div class="flex flex-col">
<span class="font-label text-xs uppercase tracking-[0.1em] text-primary mb-2">Illustration</span>
<h3 class="text-2xl font-headline text-on-surface group-hover:text-primary transition-colors">Chromatica Journal</h3>
<p class="mt-2 text-on-surface-variant font-body">A series of digital paintings exploring the theory of light and color.</p>
</div>
</article>
<!-- Project 4: Horizontal Span -->
<article class="group lg:col-span-2 relative">
<div class="overflow-hidden rounded-lg bg-surface-container-low aspect-[21/9] mb-6">
<img alt="E-commerce Interface" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-[1.03]" data-alt="Sleek e-commerce user interface for a luxury furniture brand" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBm2vukZ1qFjkMfpCXVe4H6wTqhfKl6tukt-iw3T5amDblU1OJfGVPHGGIeI7SU8-RFHhXweHKzoV9ZEpvJ5g5GpHU85ha-gsT8RpT-riNDH9d-uyIkG0Uat8J1mSMDjsvKSjJxe0LnLGWMq47n3T8yH87j5XEjAXUhnem6Fl_rnU1RitIe6-PuZ5UwRZYKMh1VfZK_Nzx0Y4JXLlKYj09wyTmcj1osokYhD-lvIMIqpoUlJUp5WMVXt-KqLd3uTsXRHtKu5UCwmeM"/>
</div>
<div class="flex flex-col">
<span class="font-label text-xs uppercase tracking-[0.1em] text-primary mb-2">Web Design</span>
<h3 class="text-3xl font-headline text-on-surface group-hover:text-primary transition-colors">Moderne Atelier</h3>
<p class="mt-2 text-on-surface-variant font-body max-w-xl">Interactive catalog and checkout flow for high-end furniture designers.</p>
</div>
</article>
<!-- Project 5 -->
<article class="group relative">
<div class="overflow-hidden rounded-lg bg-surface-container-low aspect-square mb-6">
<img alt="Logo Design" class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-[1.03]" data-alt="Minimalist logo design displayed on a sleek store front" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAXyEOXGLZNc3ic3WTwmFwyYobOoRhqahpi8Q2OE56cgCpcDALgkMHTJVjMqNzEZVVNqcDZsgK6sNHzk-2v_xYW2OKjO0moRfHp3AZxUp0g9fJ17ZF_dDT_mr6pwF_3A3jTSgwZjruqqbpEorIoHwxV9YG3WFC4aSyGqpdxQDzTR1A0w0MB6RObapm_s5S0VdD9LezDwar8vtDXDzb-9C2xmbkawgrad8osIl2gMgNTHmQMJS_ZQ1GrVdlKdXGod7y3lhXdF5pFxYg"/>
</div>
<div class="flex flex-col">
<span class="font-label text-xs uppercase tracking-[0.1em] text-primary mb-2">Branding</span>
<h3 class="text-2xl font-headline text-on-surface group-hover:text-primary transition-colors">Onyx Studio</h3>
<p class="mt-2 text-on-surface-variant font-body">Identity design for a boutique recording space in Berlin.</p>
</div>
</article>
</section>
<!-- View Archive CTA -->
<div class="mt-24 text-center">
<a class="inline-flex items-center space-x-4 text-primary group" href="#">
<span class="font-label font-bold text-lg uppercase tracking-widest border-b-2 border-primary/30 pb-1 group-hover:border-primary transition-all">Explore the Archive</span>
<span class="material-symbols-outlined group-hover:translate-x-2 transition-transform" data-icon="arrow_forward">arrow_forward</span>
</a>
</div>
</main>
<!-- Footer -->
<footer class="w-full mt-20 bg-[#f4f3f2] dark:bg-[#252727]">
<div class="flex flex-col md:flex-row justify-between items-center px-12 py-16 w-full max-w-7xl mx-auto">
<div class="mb-8 md:mb-0">
<span class="font-noto-serif italic text-lg text-[#9a442d] dark:text-[#e07a5f]">The Curated Monograph</span>
<p class="mt-4 font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase">© 2024 The Curated Monograph. All rights reserved.</p>
</div>
<div class="flex space-x-12">
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Archive</a>
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Journal</a>
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Legal</a>
</div>
</div>
</footer>
</body></html>

<!-- Work Gallery -->
<!DOCTYPE html>

<html class="scroll-smooth" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Project Case Study | The Monograph</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Noto+Serif:ital,wght@0,400;0,700;1,400&amp;family=Manrope:wght@400;500;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-primary": "#ffffff",
              "primary-container": "#e07a5f",
              "surface-dim": "#dadad9",
              "error": "#ba1a1a",
              "outline": "#88726d",
              "on-surface-variant": "#55423e",
              "on-error": "#ffffff",
              "on-tertiary-fixed-variant": "#005144",
              "tertiary-fixed": "#7df7dd",
              "surface-container-highest": "#e3e2e1",
              "on-primary-fixed-variant": "#7c2e19",
              "on-secondary-fixed": "#0e1d25",
              "on-secondary-container": "#55656d",
              "surface": "#faf9f8",
              "on-tertiary-fixed": "#00201a",
              "secondary-fixed-dim": "#b9c9d3",
              "surface-container-high": "#e9e8e7",
              "tertiary-fixed-dim": "#5edbc1",
              "on-error-container": "#93000a",
              "on-primary-container": "#5b1604",
              "secondary": "#516169",
              "on-surface": "#1a1c1c",
              "primary-fixed-dim": "#ffb4a1",
              "error-container": "#ffdad6",
              "inverse-primary": "#ffb4a1",
              "primary": "#9a442d",
              "inverse-surface": "#2f3130",
              "surface-variant": "#e3e2e1",
              "outline-variant": "#dbc1ba",
              "tertiary-container": "#19a992",
              "surface-bright": "#faf9f8",
              "on-primary-fixed": "#3c0800",
              "primary-fixed": "#ffdbd2",
              "secondary-container": "#d2e2ec",
              "on-secondary": "#ffffff",
              "surface-container-lowest": "#ffffff",
              "inverse-on-surface": "#f1f0f0",
              "surface-tint": "#9a442d",
              "on-secondary-fixed-variant": "#3a4951",
              "background": "#faf9f8",
              "tertiary": "#006b5b",
              "secondary-fixed": "#d5e5ef",
              "surface-container-low": "#f4f3f2",
              "on-tertiary-container": "#00362d",
              "surface-container": "#eeeeed",
              "on-background": "#1a1c1c",
              "on-tertiary": "#ffffff"
            },
            fontFamily: {
              "headline": ["Noto Serif"],
              "body": ["Manrope"],
              "label": ["Manrope"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      body {
        font-family: 'Manrope', sans-serif;
      }
      h1, h2, h3, .font-noto-serif {
        font-family: 'Noto Serif', serif;
      }
    </style>
</head>
<body class="bg-surface text-on-surface selection:bg-primary-container/30">
<!-- TopAppBar -->
<header class="fixed top-0 w-full z-50 bg-[#faf9f8]/80 dark:bg-[#1a1c1c]/80 backdrop-blur-xl shadow-[0_10px_40px_rgba(26,28,28,0.06)]">
<nav class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
<div class="text-xl font-bold font-noto-serif text-[#9a442d] dark:text-[#e07a5f]">
                The Monograph
            </div>
<div class="hidden md:flex items-center gap-12">
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors font-label text-sm uppercase tracking-widest" href="#">Home</a>
<a class="text-[#9a442d] dark:text-[#e07a5f] border-b-2 border-[#9a442d]/30 pb-1 font-label text-sm uppercase tracking-widest" href="#">Work</a>
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors font-label text-sm uppercase tracking-widest" href="#">About</a>
<a class="text-[#1a1c1c] dark:text-[#faf9f8] hover:text-[#9a442d] transition-colors font-label text-sm uppercase tracking-widest" href="#">Contact</a>
</div>
<div class="flex items-center gap-4">
<button class="text-[#1a1c1c] dark:text-[#faf9f8] hover:opacity-80 transition-opacity duration-300">
<span class="material-symbols-outlined">mail</span>
</button>
</div>
</nav>
</header>
<main class="pt-32 pb-20">
<!-- Hero Header -->
<section class="max-w-7xl mx-auto px-8 mb-20 md:mb-32">
<div class="grid grid-cols-1 md:grid-cols-12 gap-8">
<div class="md:col-span-8">
<h1 class="text-5xl md:text-7xl font-headline font-bold leading-tight text-on-surface mb-8">
                        The Kinetic Archive: <br/>Redefining Digital Curation
                    </h1>
</div>
<div class="md:col-span-4 flex flex-col justify-end">
<div class="grid grid-cols-2 md:grid-cols-1 gap-6 border-t border-outline-variant/15 pt-8">
<div>
<p class="text-[10px] uppercase tracking-[0.2em] font-label text-on-surface-variant mb-1">Role</p>
<p class="font-body text-on-surface">Creative Direction &amp; UI/UX</p>
</div>
<div>
<p class="text-[10px] uppercase tracking-[0.2em] font-label text-on-surface-variant mb-1">Date</p>
<p class="font-noto-serif italic text-on-surface">Autumn 2023</p>
</div>
</div>
</div>
</div>
</section>
<!-- Hero Image -->
<section class="w-full mb-32 px-4 md:px-0">
<div class="max-w-[1400px] mx-auto aspect-[16/9] bg-surface-container-high overflow-hidden rounded-xl md:rounded-none">
<img class="w-full h-full object-cover" data-alt="Minimalist architectural office space with high contrast shadows" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCUr_mrZLH2p6JLZuybcoKQMa0VxKZ3ubBfS7G1Yzvf3T7OOEGdVfFoHwCRjl58sWkViZNr1-cwT7T4evRSKKH6CwLs-J5QuQO60XFNfsGcFLNZyCYS5A8cjpclzkJrQ9Z6yNN2cIpuHy7BAojbOG-lKH4eHFQ2U0uLkAb_3VeLGc7UIoTjO7wBSZ_8E4EvJfNopjVeNcMMODow4Mn9eygW-s2clU8TImoCjuuV-CdfhlkNuAzpzINy273bXZmc97HU8ymVlfJfx1g"/>
</div>
</section>
<!-- The Challenge -->
<section class="max-w-7xl mx-auto px-8 mb-32">
<div class="grid grid-cols-1 md:grid-cols-12 gap-16 items-start">
<div class="md:col-span-3">
<h2 class="text-2xl font-headline font-bold text-primary">The Challenge</h2>
</div>
<div class="md:col-span-5">
<p class="text-xl font-body leading-relaxed text-on-surface-variant">
                        How do we capture the tactile essence of a physical monograph within a high-performance digital ecosystem? The objective was to create a platform that felt both archival and dynamic, balancing the weight of history with the speed of contemporary interaction.
                    </p>
<div class="mt-12 p-8 bg-surface-container-low rounded-lg">
<p class="font-noto-serif italic text-lg text-on-surface">
                            "The difficulty lay in the 'no-line' philosophy—establishing hierarchy without using traditional UI borders."
                        </p>
</div>
</div>
<div class="md:col-span-4">
<div class="aspect-[4/5] bg-surface-container overflow-hidden rounded-lg">
<img class="w-full h-full object-cover" data-alt="Black and white close up of textured paper" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAw-iMy5s8Ybh34TPBMaz4cdfhdVeqQaQ9ZIbiqoalSYoCpEBiR3upu7mIlEjeE-fqm7awHO85PJmv7K1DHQC8rFTvvh9wvnKeLQPAci7wj7RK-X0U-vA6TLOd-SVEgAeeHgRPxmw-vkEyLYLpoy1poNKSjMjwyLECsthCC1buuuYy1Oqg8-v_at8_8_ArZyr4pFiSitByHicdF5XiWlmPgDnTLgyG8jouqIw2qD_qeiKwwxRi_E68Th-8MUgub9R6IGBfzLZ5W1gE"/>
</div>
</div>
</div>
</section>
<!-- The Solution (Bento Grid Style) -->
<section class="bg-surface-container-low py-32 mb-32">
<div class="max-w-7xl mx-auto px-8">
<div class="mb-16">
<h2 class="text-2xl font-headline font-bold text-primary mb-6">The Solution</h2>
<p class="max-w-2xl text-lg font-body text-on-surface-variant">
                        We developed a design system based on tonal depth and stacking principles. By utilizing Material Design 3's surface roles, we created a natural hierarchy of "elevation" that feels structural rather than cosmetic.
                    </p>
</div>
<!-- Bento Grid Mockups -->
<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
<div class="md:col-span-2 aspect-video bg-white rounded-xl shadow-[0_40px_80px_rgba(26,28,28,0.04)] overflow-hidden">
<img class="w-full h-full object-cover" data-alt="Modern clean web interface showing portfolio grid" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC3UczP2J08DAF_uK82gZFGcFCx9yCsJJtdaDJqhcumLX0aj2NNoQMEfiL9CrOGVx5hxS3M17vJoINDZDJHd1CMRUZUWH7J1jaSm-iVZyEwoV8HD0cfAWHULPcE2QJxbh0v4Nep-kfNWp4V1ShZLV3i5AB0OMd4TIGB2SqihvfPTsoycA2F5DBUhL9nd7AKkBPbqCrCZJxw9nJRrlK-i1pgvpqKWqPKX7EneJbeUHHiqB2l99DfAJOfGHIXZB2CRQyBEYTpKtUEHZc"/>
</div>
<div class="aspect-square bg-primary-container/20 rounded-xl overflow-hidden flex items-center justify-center p-12">
<img class="w-full h-full object-cover rounded-lg shadow-xl" data-alt="Detail of a mobile phone showing sleek typography" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDz03cRKgFEHoNoSexw5Ey5UQ6ZsYXBNi_EXnukYYtNOyTG0U8AJ7SZWfniCv0IkzSWC4xER9_SkLhhkIhR0ftjXvUTisxkfB50IDpDhsnAHFymaUyR4_cGEL2qLEfi5gcHJxjVeoAe_9X4oqIlEh1qDVOE8MNBmeoeTlXQeyMPFmBpC3Ai1Vgw4YmAEESOITsNzVz73MxA611SHJHZ5jOoHyCGu0m804DV1tL8W1lZKQECgjtFq3yZsCcDkeR4piBcIwjCTm8Dlww"/>
</div>
<div class="aspect-square bg-surface-container-highest rounded-xl overflow-hidden">
<img class="w-full h-full object-cover opacity-80" data-alt="Abstract shadow patterns on a wall" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBW-mPYWgvrmkoom-08Ucc3eqav0OuhEhl4VKP4y9c0AwHWRdhG_VRwKN0Zq-3mbva9JxPGRpIMx53Z5vqZhihvxrsJ7Wr_yKcIT1qvGf531qbwvfmCwqi_Zgv2W2mX1TJVRh7cOzbPHWfCirkPyIZTB9IYg7OtW22s_WyZQf3K3sLDyUYAPykff5Q-SZ2Eh4brehCLnZ_669OClYhbTJ2yYEZ1jVcToy9AMufAX3YBHrKbFDcvan6-qUL6v531UHf3FvORMR8ShkY"/>
</div>
<div class="md:col-span-2 bg-on-surface p-12 rounded-xl flex flex-col justify-between text-white">
<p class="text-2xl font-headline italic">Integrated typography and layout systems that prioritize the visual rhythm of the scroll.</p>
<div class="flex gap-4 mt-8">
<span class="px-4 py-2 bg-white/10 rounded-full text-xs font-label tracking-widest uppercase">Responsive</span>
<span class="px-4 py-2 bg-white/10 rounded-full text-xs font-label tracking-widest uppercase">Accessible</span>
<span class="px-4 py-2 bg-white/10 rounded-full text-xs font-label tracking-widest uppercase">Scalable</span>
</div>
</div>
</div>
</div>
</section>
<!-- Outcome Section -->
<section class="max-w-7xl mx-auto px-8 mb-40">
<div class="grid grid-cols-1 md:grid-cols-12 gap-16">
<div class="md:col-span-4">
<h2 class="text-2xl font-headline font-bold text-primary">The Outcome</h2>
</div>
<div class="md:col-span-8">
<div class="grid grid-cols-1 md:grid-cols-2 gap-12">
<div>
<h3 class="text-4xl font-headline text-on-surface mb-4">45%</h3>
<p class="font-body text-on-surface-variant">Increase in session duration as users navigated through the editorial-style project journeys.</p>
</div>
<div>
<h3 class="text-4xl font-headline text-on-surface mb-4">Pure</h3>
<p class="font-body text-on-surface-variant">The final deliverable maintained a 100% borderless interface, achieving the North Star vision of a digital monograph.</p>
</div>
</div>
<div class="mt-16 pt-16 border-t border-outline-variant/15">
<p class="text-xl font-body leading-relaxed text-on-surface">
                            The project successfully transitioned from a collection of images to a curated narrative experience. By leaning into asymmetry and tonal depth, we established a benchmark for how modern archival brands can live digitally without losing their soul.
                        </p>
</div>
</div>
</div>
</section>
<!-- Next Project Navigation -->
<section class="max-w-7xl mx-auto px-8 pt-20">
<div class="group relative py-20 px-12 bg-surface-container-low rounded-2xl overflow-hidden hover:bg-surface-container-high transition-colors duration-500">
<a class="flex flex-col md:flex-row md:items-center justify-between relative z-10" href="#">
<div>
<p class="text-[10px] uppercase tracking-[0.3em] font-label text-primary mb-4">Up Next</p>
<h4 class="text-4xl md:text-6xl font-headline font-bold text-on-surface group-hover:translate-x-4 transition-transform duration-500">Vanguard Studio</h4>
</div>
<div class="mt-8 md:mt-0 flex items-center gap-4 text-primary group-hover:scale-110 transition-transform duration-500">
<span class="font-label uppercase tracking-widest text-sm">View Project</span>
<span class="material-symbols-outlined text-4xl">east</span>
</div>
</a>
<div class="absolute inset-0 bg-gradient-to-r from-primary/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full mt-20 bg-[#f4f3f2] dark:bg-[#252727]">
<div class="flex flex-col md:flex-row justify-between items-center px-12 py-16 w-full max-w-7xl mx-auto">
<div class="mb-8 md:mb-0">
<span class="font-noto-serif italic text-lg text-[#9a442d] dark:text-[#e07a5f]">The Curated Monograph.</span>
</div>
<div class="flex flex-col md:flex-row items-center gap-8 mb-8 md:mb-0">
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Archive</a>
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Journal</a>
<a class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase hover:text-[#9a442d] dark:hover:text-[#e07a5f] transition-all" href="#">Legal</a>
</div>
<div>
<p class="font-manrope text-sm tracking-wide text-[#1a1c1c]/60 dark:text-[#faf9f8]/60 uppercase">
                    © 2024 The Curated Monograph. All rights reserved.
                </p>
</div>
</div>
</footer>
</body></html>
