<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HIMANSHU TIWARI | THE FUTURE OF COMMERCE</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;500;800&family=Space+Grotesk:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --accent: #00f2ff;
            --accent-secondary: #7000ff;
            --bg: #030303;
            --glass: rgba(255, 255, 255, 0.03);
            --border: rgba(255, 255, 255, 0.1);
        }

        * { cursor: none !important; }

        body {
            background-color: var(--bg);
            color: #fff;
            font-family: 'Plus Jakarta Sans', sans-serif;
            overflow-x: hidden;
        }

        h1, h2, h3, .heading-font {
            font-family: 'Space Grotesk', sans-serif;
            text-transform: uppercase;
            font-weight: 800;
        }

        /* Custom Neural Cursor */
        #cursor-neural {
            width: 20px;
            height: 20px;
            border: 2px solid var(--accent);
            border-radius: 50%;
            position: fixed;
            pointer-events: none;
            z-index: 9999;
            transition: transform 0.1s ease;
            mix-blend-mode: difference;
        }

        /* Futuristic Background */
        .grid-system {
            background-image: linear-gradient(var(--border) 1px, transparent 1px), linear-gradient(90deg, var(--border) 1px, transparent 1px);
            background-size: 50px 50px;
            position: fixed;
            inset: 0;
            z-index: -1;
            mask-image: radial-gradient(circle at center, black, transparent 80%);
        }

        /* Glassmorphism Containers */
        .glass-panel {
            background: var(--glass);
            backdrop-filter: blur(15px);
            border: 1px solid var(--border);
            border-radius: 20px;
            transition: all 0.5s cubic-bezier(0.23, 1, 0.32, 1);
        }
        .glass-panel:hover {
            border-color: var(--accent);
            background: rgba(255, 255, 255, 0.08);
            transform: translateY(-8px) scale(1.03);
            box-shadow: 0 15px 30px rgba(0, 242, 255, 0.15);
        }

        /* Tool Logos Styling */
        .tool-logo {
            width: 54px;
            height: 54px;
            transition: all 0.4s ease;
            object-fit: contain;
            filter: grayscale(0.2) brightness(0.9);
        }
        .glass-panel:hover .tool-logo {
            transform: scale(1.15);
            filter: grayscale(0) brightness(1) drop-shadow(0 0 15px rgba(255, 255, 255, 0.4));
        }

        /* Gradient Text */
        .shimmer-text {
            background: linear-gradient(90deg, #fff, var(--accent), #fff);
            background-size: 200% auto;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: shimmer 3s linear infinite;
        }
        @keyframes shimmer {
            to { background-position: 200% center; }
        }

        /* Scroll Progress */
        #progress-bar {
            position: fixed;
            top: 0;
            left: 0;
            height: 4px;
            background: linear-gradient(90deg, var(--accent), var(--accent-secondary));
            z-index: 1000;
        }

        .kinetic-header {
            font-size: clamp(3rem, 15vw, 12rem);
            color: transparent;
            -webkit-text-stroke: 1px rgba(255,255,255,0.1);
            line-height: 0.8;
            pointer-events: none;
        }

        /* Certificate Preview Styling */
        .cert-card {
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }
        .cert-preview {
            width: 100%;
            aspect-ratio: 1.414/1;
            background: #fff;
            border-radius: 8px;
            overflow: hidden;
            position: relative;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }
    </style>
</head>
<body>

    <div id="progress-bar"></div>
    <div id="cursor-neural"></div>
    <div class="grid-system"></div>

    <!-- Nav -->
    <header class="fixed w-full z-50 p-6">
        <nav class="max-w-7xl mx-auto glass-panel px-8 py-4 flex justify-between items-center rounded-full">
            <div class="heading-font text-2xl tracking-tighter shimmer-text">H.TIWARI</div>
            <div class="hidden md:flex gap-8 text-xs font-bold tracking-widest text-gray-400">
                <a href="#about" class="hover:text-cyan-400 transition">01 ABOUT</a>
                <a href="#experience" class="hover:text-cyan-400 transition">02 EXPERIENCE</a>
                <a href="#skills" class="hover:text-cyan-400 transition">03 SKILLS</a>
                <a href="#credentials" class="hover:text-cyan-400 transition">04 CERTIFICATES</a>
                <a href="#contact" class="hover:text-cyan-400 transition">05 CONTACT</a>
            </div>
            <div class="w-12"></div> <!-- Spacer for balance -->
        </nav>
    </header>

    <!-- Hero -->
    <section class="min-h-screen flex items-center px-6 md:px-20 relative">
        <div class="max-w-5xl" data-aos="fade-up">
            <div class="flex items-center gap-3 mb-8">
                <span class="h-[1px] w-12 bg-cyan-400"></span>
                <span class="text-xs font-bold tracking-[0.3em] text-cyan-400">STRATEGIC INNOVATOR</span>
            </div>
            <h1 class="text-6xl md:text-9xl leading-none mb-8">HIMANSHU<br><span class="shimmer-text">TIWARI.</span></h1>
            <p class="text-xl md:text-2xl text-gray-400 max-w-2xl font-light leading-relaxed">
                Commerce Specialist & Audit Lead merging traditional financial integrity with <span class="text-white font-bold">Generative AI workflows</span> and high-impact digital marketing.
            </p>
            <div class="mt-12 flex flex-wrap gap-4">
                <a href="#experience" class="px-10 py-5 bg-white text-black font-black text-sm rounded-xl hover:scale-105 transition uppercase tracking-widest">View Experience</a>
                <div class="flex gap-4">
                    <a href="https://www.linkedin.com/in/himanshu-tiwari-a4a3832a6" target="_blank" class="px-6 py-5 glass-panel text-white font-black text-sm rounded-xl hover:bg-white/10 transition flex items-center gap-2">
                        <i data-lucide="linkedin" class="w-4 h-4 text-cyan-400"></i>
                    </a>
                    <a href="https://www.instagram.com/himanshu_23t?igsh=eHh1YnZtZno4amxu" target="_blank" class="px-6 py-5 glass-panel text-white font-black text-sm rounded-xl hover:bg-white/10 transition flex items-center gap-2">
                        <i data-lucide="instagram" class="w-4 h-4 text-pink-500"></i>
                    </a>
                </div>
            </div>
        </div>
        <div class="absolute right-0 top-1/2 -translate-y-1/2 hidden lg:block">
            <div class="kinetic-header rotate-90 opacity-20">SYSTEMS</div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-32 px-6 bg-[#050505]">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-xs font-black text-cyan-400 mb-20 tracking-[0.5em] text-center">01 // MISSION STATEMENT</h2>
            <div class="glass-panel p-12 md:p-20 relative overflow-hidden">
                <div class="absolute top-0 right-0 p-10 opacity-5">
                    <i data-lucide="quote" class="w-40 h-40"></i>
                </div>
                <p class="text-2xl md:text-4xl font-light leading-tight mb-12">
                    "Dynamic and results-driven commerce graduate with <span class="text-cyan-400 font-bold">1+ year of hands-on experience</span> in Business Development and Audit Assistance. Expert in leveraging emerging technologies to drive <span class="text-purple-500 font-bold">organizational growth</span>."
                </p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-12 border-t border-white/10 pt-12">
                    <div>
                        <h4 class="text-xs font-black text-gray-500 mb-2">EDUCATION</h4>
                        <p class="font-bold">B.Com - GUJARAT UNIVERSITY</p>
                        <p class="text-xs text-gray-400">Gujarat Arts & Commerce College</p>
                    </div>
                    <div>
                        <h4 class="text-xs font-black text-gray-500 mb-2">LOCATION</h4>
                        <p class="font-bold">GANDHIDHAM, GUJARAT</p>
                        <p class="text-xs text-gray-400">Welspun Vidya Mandir (CBSE)</p>
                    </div>
                    <div>
                        <h4 class="text-xs font-black text-gray-500 mb-2">LANGUAGES</h4>
                        <p class="font-bold">ENGLISH • HINDI • GUJARATI</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience -->
    <section id="experience" class="py-32 px-6">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-6xl heading-font mb-20 italic">CAREER RECORDS</h2>
            <div class="space-y-12">
                <div class="glass-panel p-10 border-l-4 border-cyan-400" data-aos="fade-left">
                    <div class="flex flex-col md:flex-row justify-between mb-8">
                        <div>
                            <h3 class="text-3xl font-bold uppercase">Business Development & Auditor</h3>
                            <p class="text-cyan-400 font-bold uppercase">R. R. Tibrewala & Co.</p>
                        </div>
                        <span class="text-xs font-black bg-white/10 px-4 py-2 rounded-full self-start mt-4 md:mt-0">PRESENT</span>
                    </div>
                    <ul class="grid grid-cols-1 md:grid-cols-2 gap-6 text-gray-400 text-sm">
                        <li class="flex gap-3"><i data-lucide="check-circle" class="text-cyan-400 w-5 h-5 shrink-0"></i> Audited Vivan Steels, Bansiwala Fabtex, and Mars Planning.</li>
                        <li class="flex gap-3"><i data-lucide="check-circle" class="text-cyan-400 w-5 h-5 shrink-0"></i> Performed comprehensive auditing procedures for various clients.</li>
                        <li class="flex gap-3"><i data-lucide="check-circle" class="text-cyan-400 w-5 h-5 shrink-0"></i> Implemented Google Ads & SEMrush for firm outreach.</li>
                        <li class="flex gap-3"><i data-lucide="check-circle" class="text-cyan-400 w-5 h-5 shrink-0"></i> Managed professional correspondence and documentation workflows.</li>
                    </ul>
                </div>
                <div class="glass-panel p-10 border-l-4 border-purple-500" data-aos="fade-left" data-aos-delay="100">
                    <div class="flex flex-col md:flex-row justify-between mb-8">
                        <div>
                            <h3 class="text-3xl font-bold uppercase">Graphic Designer & Content Creator</h3>
                            <p class="text-purple-500 font-bold uppercase">R. R. Tibrewala & Co. (Digital Arm)</p>
                        </div>
                    </div>
                    <ul class="grid grid-cols-1 md:grid-cols-2 gap-6 text-gray-400 text-sm">
                        <li class="flex gap-3"><i data-lucide="pen-tool" class="text-purple-500 w-5 h-5 shrink-0"></i> Developed firm digital presence & marketing workflows.</li>
                        <li class="flex gap-3"><i data-lucide="video" class="text-purple-500 w-5 h-5 shrink-0"></i> Used Premiere Pro, Filmora, & CapCut for high-impact content.</li>
                        <li class="flex gap-3"><i data-lucide="layout" class="text-purple-500 w-5 h-5 shrink-0"></i> Designed cross-platform marketing collateral.</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Tools & Software Expertise -->
    <section id="skills" class="py-32 px-6 bg-white/5">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-xs font-black text-cyan-400 mb-4 tracking-[0.5em] text-center uppercase">03 // Tech Ecosystem</h2>
            <h3 class="text-4xl md:text-5xl heading-font text-center mb-20 italic">TOOLS & SOFTWARE EXPERTISE</h3>
            
            <!-- MS Office Grid -->
            <div class="mb-16">
                <h4 class="text-xs font-black text-gray-500 mb-8 tracking-widest border-l-2 border-cyan-400 pl-4 uppercase">Microsoft Office Suite</h4>
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                    <div class="glass-panel p-8 flex flex-col items-center gap-6 group">
                        <img src="https://www.vectorlogo.zone/logos/microsoft_word/microsoft_word-icon.svg" class="tool-logo" alt="Word">
                        <span class="text-[10px] font-black tracking-widest group-hover:text-cyan-400 transition">WORD</span>
                    </div>
                    <div class="glass-panel p-8 flex flex-col items-center gap-6 group">
                        <img src="https://www.vectorlogo.zone/logos/microsoft_excel/microsoft_excel-icon.svg" class="tool-logo" alt="Excel">
                        <span class="text-[10px] font-black tracking-widest group-hover:text-cyan-400 transition">EXCEL</span>
                    </div>
                    <div class="glass-panel p-8 flex flex-col items-center gap-6 group">
                        <img src="https://www.vectorlogo.zone/logos/microsoft_powerpoint/microsoft_powerpoint-icon.svg" class="tool-logo" alt="PowerPoint">
                        <span class="text-[10px] font-black tracking-widest group-hover:text-cyan-400 transition">POWERPOINT</span>
                    </div>
                </div>
            </div>

            <!-- Graphic Design -->
            <div class="mb-16">
                <h4 class="text-xs font-black text-gray-500 mb-8 tracking-widest border-l-2 border-purple-500 pl-4 uppercase">Graphic Design</h4>
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                    <div class="glass-panel p-8 flex flex-col items-center gap-6 group">
                        <img src="https://www.vectorlogo.zone/logos/canva/canva-icon.svg" class="tool-logo" alt="Canva">
                        <span class="text-[10px] font-black tracking-widest group-hover:text-cyan-400 transition">CANVA</span>
                    </div>
                    <div class="glass-panel p-8 flex flex-col items-center gap-6 group">
                        <img src="https://www.vectorlogo.zone/logos/adobe/adobe-icon.svg" class="tool-logo" alt="Adobe">
                        <span class="text-[10px] font-black tracking-widest group-hover:text-cyan-400 transition">ADOBE EXPRESS</span>
                    </div>
                </div>
            </div>

            <!-- Video Editing -->
            <div class="mb-16">
                <h4 class="text-xs font-black text-gray-500 mb-8 tracking-widest border-l-2 border-red-500 pl-4 uppercase">Video Editing</h4>
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                    <div class="glass-panel p-8 flex flex-col items-center gap-6 group">
                        <img src="https://www.vectorlogo.zone/logos/adobe_premiere/adobe_premiere-icon.svg" class="tool-logo" alt="Premiere Pro">
                        <span class="text-[10px] font-black tracking-widest group-hover:text-cyan-400 transition text-center uppercase">Adobe Premiere Pro</span>
                    </div>
                    <div class="glass-panel p-8 flex flex-col items-center gap-6 group">
                        <img src="https://www.vectorlogo.zone/logos/wondershare/wondershare-icon.svg" class="tool-logo" alt="Filmora">
                        <span class="text-[10px] font-black tracking-widest group-hover:text-cyan-400 transition uppercase">Filmora</span>
                    </div>
                    <div class="glass-panel p-8 flex flex-col items-center gap-6 group">
                        <img src="https://www.vectorlogo.zone/logos/capcut/capcut-icon.svg" class="tool-logo" alt="CapCut">
                        <span class="text-[10px] font-black tracking-widest group-hover:text-cyan-400 transition uppercase">CapCut</span>
                    </div>
                </div>
            </div>

            <!-- AI & Development -->
            <div>
                <h4 class="text-xs font-black text-gray-500 mb-8 tracking-widest border-l-2 border-orange-500 pl-4 uppercase">Cloud & AI Integration</h4>
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                    <div class="glass-panel p-8 flex flex-col items-center gap-6 group">
                        <img src="https://www.vectorlogo.zone/logos/amazon_aws/amazon_aws-icon.svg" class="tool-logo" alt="AWS">
                        <span class="text-[10px] font-black tracking-widest group-hover:text-cyan-400 transition">AWS CLOUD</span>
                    </div>
                    <div class="glass-panel p-8 flex flex-col items-center gap-6 group">
                        <img src="https://www.vectorlogo.zone/logos/openai/openai-icon.svg" class="tool-logo" alt="OpenAI">
                        <span class="text-[10px] font-black tracking-widest group-hover:text-cyan-400 transition uppercase">Prompt Engineering</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Certificates -->
    <section id="credentials" class="py-32 px-6">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-xs font-black text-cyan-400 mb-4 tracking-[0.5em] text-right uppercase">04 // Validation</h2>
            <h3 class="text-6xl heading-font mb-20 italic text-right">CERTIFICATES.</h3>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <!-- Google Certification -->
                <div class="cert-card" data-aos="zoom-in">
                    <div class="cert-preview">
                        <svg width="100%" height="100%" viewBox="0 0 800 565" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="800" height="565" fill="white"/>
                            <rect x="20" y="20" width="760" height="525" stroke="#4285F4" stroke-width="2"/>
                            <text fill="#5F6368" font-family="Arial" font-size="14" x="40" y="60">Issue Date: Dec 20, 2025</text>
                            <text fill="#5F6368" font-family="Arial" font-size="14" x="40" y="80">Certificate ID: 169834735</text>
                            <path d="M400 150L415 180H385L400 150Z" fill="#EA4335"/>
                            <text fill="#202124" font-family="Arial" font-weight="bold" font-size="28" text-anchor="middle" x="400" y="220">GOOGLE ADS APPS</text>
                            <text fill="#4285F4" font-family="Arial" font-weight="bold" font-size="18" text-anchor="middle" x="400" y="250">CERTIFIED</text>
                            <text fill="#5F6368" font-family="Arial" font-size="16" text-anchor="middle" x="400" y="300">This acknowledges that</text>
                            <text fill="#202124" font-family="Arial" font-weight="bold" font-size="32" text-anchor="middle" x="400" y="350">HIMANSHU TIWARI</text>
                            <text fill="#5F6368" font-family="Arial" font-size="16" text-anchor="middle" x="400" y="400">Has successfully completed and is certified in</text>
                            <text fill="#202124" font-family="Arial" font-weight="bold" font-size="22" text-anchor="middle" x="400" y="430">Google Ads Apps Certification</text>
                            <rect x="350" y="480" width="100" height="40" fill="#4285F4" rx="4"/>
                            <text fill="white" font-family="Arial" font-weight="bold" font-size="12" text-anchor="middle" x="400" y="505">Google Ads</text>
                        </svg>
                    </div>
                    <div class="glass-panel p-6">
                        <h5 class="text-xl font-bold uppercase">Google Ads Apps</h5>
                        <p class="text-xs text-cyan-400 font-bold mb-4 tracking-widest">ID: 169834735</p>
                        <p class="text-sm text-gray-400">Validated proficiency in creating and optimizing App campaigns to drive business goals.</p>
                    </div>
                </div>

                <!-- AWS Certification -->
                <div class="cert-card" data-aos="zoom-in" data-aos-delay="100">
                    <div class="cert-preview">
                        <svg width="100%" height="100%" viewBox="0 0 800 565" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="800" height="565" fill="#232F3E"/>
                            <text fill="#FF9900" font-family="Arial" font-weight="bold" font-size="16" x="50" y="60">AWS Training & Certification</text>
                            <text fill="white" font-family="Arial" font-size="14" x="50" y="80">Completion Certificate</text>
                            <rect x="50" y="150" width="700" height="2" fill="#FF9900"/>
                            <text fill="white" font-family="Arial" font-weight="bold" font-size="40" x="50" y="220">Foundations of Prompt</text>
                            <text fill="white" font-family="Arial" font-weight="bold" font-size="40" x="50" y="270">Engineering</text>
                            <text fill="#FF9900" font-family="Arial" font-size="16" x="50" y="320">Completed: December 25, 2025</text>
                            <text fill="white" font-family="Arial" font-size="18" x="50" y="380">Awarded to</text>
                            <text fill="white" font-family="Arial" font-weight="bold" font-size="36" x="50" y="430">HIMANSHU TIWARI</text>
                            <path d="M650 450L680 450L680 480L650 480Z" fill="#FF9900"/>
                            <text fill="white" font-family="Arial" font-size="10" x="50" y="515">Michelle Vaz, AWS Training & Certification</text>
                        </svg>
                    </div>
                    <div class="glass-panel p-6">
                        <h5 class="text-xl font-bold uppercase">Prompt Engineering</h5>
                        <p class="text-xs text-orange-400 font-bold mb-4 tracking-widest">AWS TRAINING & CERTIFICATION</p>
                        <p class="text-sm text-gray-400">Mastery of prompt design patterns for LLMs on Amazon Web Services infrastructure.</p>
                    </div>
                </div>

                <!-- Semrush SEO Certification -->
                <div class="cert-card" data-aos="zoom-in" data-aos-delay="200">
                    <div class="cert-preview">
                        <svg width="100%" height="100%" viewBox="0 0 800 565" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="800" height="565" fill="#FF6200"/>
                            <text fill="white" font-family="Arial" font-weight="bold" font-size="24" x="60" y="80">Semrush Academy</text>
                            <text fill="white" font-family="Arial" font-size="18" text-anchor="middle" x="400" y="200">Awarded to</text>
                            <text fill="white" font-family="Arial" font-weight="bold" font-size="42" text-anchor="middle" x="400" y="260">HIMANSHU TIWARI</text>
                            <text fill="white" font-family="Arial" font-weight="bold" font-size="30" text-anchor="middle" x="400" y="360">Getting Started with Semrush</text>
                            <text fill="white" font-family="Arial" font-size="14" x="60" y="480">Expires: 22.12.2026</text>
                            <text fill="white" font-family="Arial" font-size="14" x="60" y="500">ID: f3ae60a97c</text>
                        </svg>
                    </div>
                    <div class="glass-panel p-6">
                        <h5 class="text-xl font-bold uppercase">Semrush Mastery</h5>
                        <p class="text-xs text-orange-500 font-bold mb-4 tracking-widest">ID: F3AE60A97C</p>
                        <p class="text-sm text-gray-400">Expertise in SEO, Competitor Analysis, and Keyword Research.</p>
                    </div>
                </div>

                <!-- Semrush Content Marketing -->
                <div class="cert-card" data-aos="zoom-in" data-aos-delay="300">
                    <div class="cert-preview">
                        <svg width="100%" height="100%" viewBox="0 0 800 565" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="800" height="565" fill="#421390"/>
                            <text fill="white" font-family="Arial" font-weight="bold" font-size="24" x="60" y="80">Semrush Academy</text>
                            <text fill="white" font-family="Arial" font-size="18" text-anchor="middle" x="400" y="200">Awarded to</text>
                            <text fill="#00f2ff" font-family="Arial" font-weight="bold" font-size="42" text-anchor="middle" x="400" y="260">HIMANSHU TIWARI</text>
                            <text fill="white" font-family="Arial" font-weight="bold" font-size="28" text-anchor="middle" x="400" y="360">Content Marketing Principles</text>
                            <text fill="white" font-family="Arial" font-size="14" x="60" y="480">Expires: 22.12.2026</text>
                            <text fill="white" font-family="Arial" font-size="14" x="60" y="500">ID: 71fd1faed1</text>
                        </svg>
                    </div>
                    <div class="glass-panel p-6">
                        <h5 class="text-xl font-bold uppercase">Content Principles</h5>
                        <p class="text-xs text-purple-400 font-bold mb-4 tracking-widest">ID: 71FD1FAED1</p>
                        <p class="text-sm text-gray-400">Advanced strategies for business-driven content marketing and engagement.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact & Map Section -->
    <section id="contact" class="grid grid-cols-1 lg:grid-cols-2 min-h-screen border-t border-white/10">
        <!-- Interactive Map Wrapper -->
        <div class="relative w-full h-[50vh] lg:h-full bg-[#080808] overflow-hidden group">
            <div class="absolute inset-0 z-10 pointer-events-none bg-gradient-to-r from-black via-transparent to-transparent opacity-60"></div>
            <div class="absolute inset-0 z-10 pointer-events-none bg-gradient-to-t from-black via-transparent to-transparent opacity-60"></div>
            <iframe 
                class="w-full h-full border-0 grayscale invert contrast-[1.2] opacity-40 group-hover:opacity-80 transition-all duration-700" 
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d58782.84414631338!2d70.09118029517173!3d23.085121408801452!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3950bf93c9d747a7%3A0x9599540b7914619!2sGandhidham%2C%20Gujarat!5e0!3m2!1sen!2sin!4v1705400000000!5m2!1sen!2sin" 
                allowfullscreen="" 
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade">
            </iframe>
            <!-- UI Overlay for Map -->
            <div class="absolute top-10 left-10 z-20 glass-panel p-4 backdrop-blur-md hidden md:block">
                <div class="flex items-center gap-2">
                    <i data-lucide="map-pin" class="text-cyan-400 w-4 h-4"></i>
                    <span class="text-[10px] font-black tracking-widest uppercase">Base of Operations: Gandhidham</span>
                </div>
            </div>
        </div>

        <!-- Contact Info Wrapper -->
        <div class="p-12 md:p-24 bg-black flex flex-col justify-center border-l border-white/10">
            <h2 class="text-xs font-black text-cyan-400 mb-4 tracking-[0.5em] uppercase">05 // Transmission</h2>
            <h3 class="text-6xl md:text-8xl heading-font mb-12 shimmer-text">CONNECT.</h3>
            
            <div class="space-y-12">
                <div>
                    <h5 class="text-[10px] font-black text-gray-500 mb-2 tracking-[0.5em]">DIRECT LINE</h5>
                    <a href="tel:+919737613740" class="text-3xl md:text-5xl font-bold hover:text-cyan-400 transition tracking-tighter inline-block">+91 9737613740</a>
                </div>
                <div>
                    <h5 class="text-[10px] font-black text-gray-500 mb-2 tracking-[0.5em]">DIGITAL MAIL</h5>
                    <a href="mailto:himanshu0123tiwari@gmail.com" class="text-3xl md:text-5xl font-bold hover:text-cyan-400 transition break-all tracking-tighter inline-block">himanshu0123tiwari@gmail.com</a>
                </div>
                
                <div class="flex flex-wrap gap-8 pt-10 border-t border-white/10">
                    <a href="https://www.linkedin.com/in/himanshu-tiwari-a4a3832a6" target="_blank" class="text-xs font-black hover:text-cyan-400 flex items-center gap-2 tracking-widest transition group">
                        <i data-lucide="linkedin" class="w-4 h-4 group-hover:scale-110 transition"></i> LINKEDIN
                    </a>
                    <a href="https://www.instagram.com/himanshu_23t?igsh=eHh1YnZtZno4amxu" target="_blank" class="text-xs font-black hover:text-pink-500 flex items-center gap-2 tracking-widest transition group">
                        <i data-lucide="instagram" class="w-4 h-4 group-hover:scale-110 transition"></i> INSTAGRAM
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-20 text-center bg-black border-t border-white/10">
        <div class="heading-font text-8xl opacity-10 mb-8">H.TIWARI</div>
        <p class="text-[10px] text-gray-600 font-bold tracking-[0.8em]">V1.0 • PRECISION & INNOVATION • 2026</p>
    </footer>

    <script>
        lucide.createIcons();
        AOS.init({ duration: 1000, once: true });

        const cursor = document.getElementById('cursor-neural');
        window.addEventListener('mousemove', (e) => {
            cursor.style.left = e.clientX + 'px';
            cursor.style.top = e.clientY + 'px';
        });

        document.querySelectorAll('a, .glass-panel, button, iframe').forEach(el => {
            el.addEventListener('mouseenter', () => cursor.style.transform = 'scale(3)');
            el.addEventListener('mouseleave', () => cursor.style.transform = 'scale(1)');
        });

        window.addEventListener('scroll', () => {
            const scrolled = (window.scrollY / (document.documentElement.scrollHeight - window.innerHeight)) * 100;
            document.getElementById("progress-bar").style.width = scrolled + "%";
        });
    </script>
</body>
</html>
