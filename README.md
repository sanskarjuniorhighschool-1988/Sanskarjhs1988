<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanskar Junior High School | Shastrinagar, Ballia</title>
    <meta name="description" content="Sanskar Junior High School, Ballia - English Medium, NCERT Pattern, Est. 1988. Admissions Open 2026-27.">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!-- AOS Animation Library -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <!-- Tailwind Config for Custom Colors -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            blue: '#1e3a8a', // Deep Blue
                            gold: '#d97706', // Gold
                            light: '#eff6ff',
                        }
                    },
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif'],
                        serif: ['Playfair Display', 'serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Custom Styles & Overrides */
        body {
            font-family: 'Poppins', sans-serif;
            overflow-x: hidden;
        }
        
        .hero-pattern {
            background-color: #1e3a8a;
            background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23ffffff' fill-opacity='0.05'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }

        .glass-nav {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(0,0,0,0.05);
        }

        .text-gradient {
            background: linear-gradient(to right, #1e3a8a, #d97706);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .blob {
            position: absolute;
            filter: blur(40px);
            z-index: -1;
            opacity: 0.4;
        }

        /* Stats Counter Animation Helper */
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        
        .floating {
            animation: float 4s ease-in-out infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- Top Bar -->
    <div class="bg-brand-blue text-white text-xs md:text-sm py-2 px-4">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-2">
            <div class="flex items-center gap-4">
                <span><i class="fas fa-phone-alt mr-2"></i>9838528470, 9721760309</span>
                <span class="hidden md:inline">|</span>
                <a href="mailto:srivastavavinod@gmail.com" class="hover:text-brand-gold transition"><i class="fas fa-envelope mr-2"></i>srivastavavinod@gmail.com</a>
            </div>
            <div class="flex items-center gap-4">
                <span class="bg-brand-gold text-white px-2 py-0.5 rounded font-bold text-xs">RTE APPROVED</span>
                <span class="bg-green-600 text-white px-2 py-0.5 rounded font-bold text-xs">EST. 1988</span>
            </div>
        </div>
    </div>

    <!-- Navigation -->
    <nav class="glass-nav sticky top-0 z-50 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20">
                <!-- Logo Section -->
                <div class="flex-shrink-0 flex items-center gap-3">
                    <!-- SVG Logo Generation -->
                    <svg width="50" height="50" viewBox="0 0 100 100" class="drop-shadow-md">
                        <circle cx="50" cy="50" r="48" fill="#1e3a8a" stroke="#d97706" stroke-width="4"/>
                        <path d="M50 10 L85 30 L85 70 L50 90 L15 70 L15 30 Z" fill="none" stroke="white" stroke-width="2" opacity="0.5"/>
                        <text x="50" y="65" font-family="serif" font-size="40" font-weight="bold" fill="white" text-anchor="middle">S</text>
                        <text x="50" y="30" font-family="sans-serif" font-size="10" fill="#d97706" text-anchor="middle">EST 1988</text>
                    </svg>
                    <div class="flex flex-col">
                        <span class="font-serif font-bold text-xl md:text-2xl text-brand-blue leading-tight">SANSKAR</span>
                        <span class="text-xs md:text-sm font-medium text-slate-600 tracking-wider">JUNIOR HIGH SCHOOL</span>
                    </div>
                </div>

                <!-- Desktop Menu -->
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="text-slate-700 hover:text-brand-blue font-medium transition">Home</a>
                    <a href="#about" class="text-slate-700 hover:text-brand-blue font-medium transition">About</a>
                    <a href="#academics" class="text-slate-700 hover:text-brand-blue font-medium transition">Academics</a>
                    <a href="#achievements" class="text-slate-700 hover:text-brand-blue font-medium transition">Achievements</a>
                    <a href="#admission" class="px-5 py-2.5 bg-brand-blue text-white rounded-full font-medium hover:bg-blue-800 transition shadow-lg hover:shadow-xl transform hover:-translate-y-0.5">Admissions Open</a>
                </div>

                <!-- Mobile Menu Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-700 hover:text-brand-blue focus:outline-none">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Panel -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-gray-100 absolute w-full shadow-lg">
            <div class="px-4 pt-2 pb-4 space-y-1">
                <a href="#home" class="block px-3 py-2 text-base font-medium text-slate-700 hover:text-brand-blue hover:bg-blue-50 rounded-md">Home</a>
                <a href="#about" class="block px-3 py-2 text-base font-medium text-slate-700 hover:text-brand-blue hover:bg-blue-50 rounded-md">About</a>
                <a href="#academics" class="block px-3 py-2 text-base font-medium text-slate-700 hover:text-brand-blue hover:bg-blue-50 rounded-md">Academics</a>
                <a href="#achievements" class="block px-3 py-2 text-base font-medium text-slate-700 hover:text-brand-blue hover:bg-blue-50 rounded-md">Achievements</a>
                <a href="#admission" class="block px-3 py-2 text-base font-medium text-brand-blue font-bold hover:bg-blue-50 rounded-md">Apply for Admission</a>
            </div>
        </div>
    </nav>

    <!-- News Ticker -->
    <div class="bg-brand-gold text-white overflow-hidden py-2 relative z-10">
        <div class="whitespace-nowrap animate-marquee flex gap-10">
            <span class="inline-block px-4"><i class="fas fa-bullhorn mr-2"></i>ADMISSION OPEN FOR SESSION 2026-27</span>
            <span class="inline-block px-4"><i class="fas fa-trophy mr-2"></i>Awarded by Viksit Bharat Buildathon 2025</span>
            <span class="inline-block px-4"><i class="fas fa-star mr-2"></i>RTE Approved Institution</span>
            <span class="inline-block px-4"><i class="fas fa-book-reader mr-2"></i>NCERT (SEAS) Paper Host 2023</span>
        </div>
        <style>
            .animate-marquee {
                display: inline-block;
                animation: marquee 20s linear infinite;
                padding-left: 100%;
            }
            @keyframes marquee {
                0% { transform: translate(0, 0); }
                100% { transform: translate(-100%, 0); }
            }
        </style>
    </div>

    <!-- Hero Section -->
    <section id="home" class="relative hero-pattern text-white pt-20 pb-32 overflow-hidden">
        <!-- Abstract Shapes -->
        <div class="absolute top-0 right-0 w-96 h-96 bg-blue-500 rounded-full mix-blend-multiply filter blur-3xl opacity-20 animate-blob"></div>
        <div class="absolute -bottom-32 -left-32 w-96 h-96 bg-brand-gold rounded-full mix-blend-multiply filter blur-3xl opacity-20 animate-blob animation-delay-2000"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 flex flex-col md:flex-row items-center">
            <div class="w-full md:w-1/2 text-center md:text-left mb-12 md:mb-0" data-aos="fade-right">
                <span class="inline-block py-1 px-3 rounded-full bg-blue-800 bg-opacity-50 border border-blue-400 text-blue-100 text-sm font-semibold mb-4 backdrop-blur-sm">
                    Excellence in Education
                </span>
                <h1 class="text-4xl md:text-6xl font-serif font-bold leading-tight mb-6">
                    Shaping Futures at <br>
                    <span class="text-brand-gold">Sanskar</span> Junior High School
                </h1>
                <p class="text-lg md:text-xl text-blue-100 mb-8 leading-relaxed max-w-lg mx-auto md:mx-0">
                    Located in Shastrinagar, Ballia. Providing quality English Medium education with NCERT pattern since 1988.
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center md:justify-start">
                    <a href="#admission" class="px-8 py-4 bg-brand-gold text-white rounded-lg font-bold hover:bg-amber-600 transition shadow-lg transform hover:-translate-y-1">
                        Enroll Now (2026-27)
                    </a>
                    <a href="#about" class="px-8 py-4 bg-white bg-opacity-10 border border-white text-white rounded-lg font-bold hover:bg-opacity-20 transition backdrop-blur-md">
                        Learn More
                    </a>
                </div>
            </div>
            
            <!-- Hero Illustration/Card -->
            <div class="w-full md:w-1/2 flex justify-center relative" data-aos="fade-left">
                <div class="relative w-80 h-96 md:w-96 md:h-[28rem] bg-white rounded-2xl shadow-2xl p-6 transform rotate-3 hover:rotate-0 transition duration-500 text-slate-800 flex flex-col items-center justify-center border-t-8 border-brand-gold">
                    <div class="absolute -top-6 -right-6 bg-blue-600 text-white w-20 h-20 rounded-full flex items-center justify-center font-bold shadow-lg floating">
                        <div class="text-center text-xs">
                            <span class="block text-xl">35+</span>
                            Years
                        </div>
                    </div>
                    <i class="fas fa-graduation-cap text-6xl text-brand-blue mb-4"></i>
                    <h3 class="text-2xl font-bold font-serif text-center mb-2">Class 1 to 8</h3>
                    <p class="text-center text-slate-500 mb-6">Foundation for a bright future</p>
                    <div class="w-full space-y-3">
                        <div class="flex items-center gap-3 bg-slate-50 p-3 rounded-lg">
                            <i class="fas fa-check-circle text-green-500"></i>
                            <span class="font-medium text-sm">NCERT Pattern</span>
                        </div>
                        <div class="flex items-center gap-3 bg-slate-50 p-3 rounded-lg">
                            <i class="fas fa-check-circle text-green-500"></i>
                            <span class="font-medium text-sm">English Medium</span>
                        </div>
                        <div class="flex items-center gap-3 bg-slate-50 p-3 rounded-lg">
                            <i class="fas fa-check-circle text-green-500"></i>
                            <span class="font-medium text-sm">RTE Approved</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-10 bg-white shadow-sm -mt-10 relative z-20 max-w-6xl mx-auto rounded-xl mx-4 lg:mx-auto">
        <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center divide-x divide-slate-100">
            <div data-aos="zoom-in" data-aos-delay="100">
                <div class="text-3xl md:text-4xl font-bold text-brand-blue mb-1">16</div>
                <div class="text-sm text-slate-500 font-medium">Dedicated Teachers</div>
            </div>
            <div data-aos="zoom-in" data-aos-delay="200">
                <div class="text-3xl md:text-4xl font-bold text-brand-blue mb-1">2</div>
                <div class="text-sm text-slate-500 font-medium">Support Staff</div>
            </div>
            <div data-aos="zoom-in" data-aos-delay="300">
                <div class="text-3xl md:text-4xl font-bold text-brand-blue mb-1">1988</div>
                <div class="text-sm text-slate-500 font-medium">Established</div>
            </div>
            <div data-aos="zoom-in" data-aos-delay="400">
                <div class="text-3xl md:text-4xl font-bold text-brand-blue mb-1">100%</div>
                <div class="text-sm text-slate-500 font-medium">Commitment</div>
            </div>
        </div>
    </section>

    <!-- About & Leadership -->
    <section id="about" class="py-20 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-brand-gold font-bold tracking-wider uppercase text-sm mb-2">Who We Are</h2>
                <h3 class="text-3xl md:text-4xl font-serif font-bold text-slate-800">Legacy of Learning</h3>
                <div class="w-20 h-1 bg-brand-blue mx-auto mt-4 rounded-full"></div>
            </div>

            <div class="grid md:grid-cols-2 gap-12 items-center mb-20">
                <div data-aos="fade-right">
                    <p class="text-slate-600 leading-relaxed text-lg mb-6">
                        <strong>Sanskar Junior High School</strong> has been a beacon of knowledge in Ballia since 1988. Located in the heart of Shastrinagar, we provide a nurturing environment where tradition meets modern education.
                    </p>
                    <p class="text-slate-600 leading-relaxed text-lg mb-6">
                        As an RTE Approved institution following the NCERT pattern, we ensure that every student from Class 1 to 8 receives quality education in an English Medium environment. Our "Sanskar Family" consists of 16 highly qualified teachers and supportive non-teaching staff, all dedicated to the holistic development of your child.
                    </p>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-6" data-aos="fade-left">
                    <!-- Head of School Card -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-b-4 border-brand-blue text-center hover:transform hover:scale-105 transition">
                        <div class="w-20 h-20 bg-slate-200 rounded-full mx-auto mb-4 flex items-center justify-center text-slate-400 text-3xl">
                            <i class="fas fa-user-tie"></i>
                        </div>
                        <h4 class="text-xl font-bold text-slate-800">Mr. Vinod Kumar Srivastava</h4>
                        <p class="text-brand-gold font-medium text-sm mb-2">Head of School</p>
                        <p class="text-xs text-slate-500">Leading with vision and dedication.</p>
                    </div>

                    <!-- Vice Principal Card -->
                    <div class="bg-white p-6 rounded-xl shadow-lg border-b-4 border-brand-blue text-center hover:transform hover:scale-105 transition">
                        <div class="w-20 h-20 bg-slate-200 rounded-full mx-auto mb-4 flex items-center justify-center text-slate-400 text-3xl">
                            <i class="fas fa-chalkboard-teacher"></i>
                        </div>
                        <h4 class="text-xl font-bold text-slate-800">Anil Kumar Mishra</h4>
                        <p class="text-brand-gold font-medium text-sm mb-2">Vice Principal</p>
                        <p class="text-xs text-slate-500">Ensuring academic excellence.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Achievements -->
    <section id="achievements" class="py-20 bg-gradient-to-br from-brand-blue to-blue-900 text-white relative overflow-hidden">
        <!-- Decoration -->
        <div class="absolute top-0 left-0 w-full h-full overflow-hidden opacity-10">
             <i class="fas fa-medal absolute top-10 left-10 text-9xl"></i>
             <i class="fas fa-star absolute bottom-10 right-10 text-9xl"></i>
        </div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center mb-16">
                <h2 class="text-brand-gold font-bold tracking-wider uppercase text-sm mb-2">Hall of Fame</h2>
                <h3 class="text-3xl md:text-4xl font-serif font-bold">Awards & Recognition</h3>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Award 1 -->
                <div class="bg-white/10 backdrop-blur-md p-8 rounded-2xl border border-white/20 hover:bg-white/20 transition" data-aos="fade-up" data-aos-delay="0">
                    <div class="text-brand-gold text-4xl mb-4"><i class="fas fa-trophy"></i></div>
                    <h4 class="text-xl font-bold mb-3">Viksit Bharat Buildathon 2025</h4>
                    <p class="text-blue-100 text-sm">
                        Honored with the prestigious award for contribution towards educational development and nation-building.
                    </p>
                </div>

                <!-- Award 2 -->
                <div class="bg-white/10 backdrop-blur-md p-8 rounded-2xl border border-white/20 hover:bg-white/20 transition" data-aos="fade-up" data-aos-delay="100">
                    <div class="text-brand-gold text-4xl mb-4"><i class="fas fa-file-alt"></i></div>
                    <h4 class="text-xl font-bold mb-3">NCERT (SEAS) Host 2023</h4>
                    <p class="text-blue-100 text-sm">
                        Successfully hosted the State Educational Achievement Survey (SEAS) paper, demonstrating our administrative capability.
                    </p>
                </div>

                <!-- Award 3 -->
                <div class="bg-white/10 backdrop-blur-md p-8 rounded-2xl border border-white/20 hover:bg-white/20 transition" data-aos="fade-up" data-aos-delay="200">
                    <div class="text-brand-gold text-4xl mb-4"><i class="fas fa-comments"></i></div>
                    <h4 class="text-xl font-bold mb-3">Pariksha Pe Charcha</h4>
                    <p class="text-blue-100 text-sm">
                        Active participation and recognition in the Prime Minister's interactive program with students and teachers.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Admission Section -->
    <section id="admission" class="py-20 bg-slate-50">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-white rounded-3xl shadow-2xl overflow-hidden flex flex-col md:flex-row">
                <div class="bg-brand-gold p-10 md:w-2/5 text-white flex flex-col justify-center">
                    <h3 class="text-3xl font-serif font-bold mb-4">Admissions Open</h3>
                    <p class="text-xl font-medium mb-6">Session 2026-27</p>
                    <ul class="space-y-4 mb-8">
                        <li class="flex items-center gap-3"><i class="fas fa-check"></i> Class 1 to 8</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check"></i> English Medium</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check"></i> NCERT Curriculum</li>
                    </ul>
                    <div class="mt-auto">
                         <p class="text-sm opacity-80 mb-1">Contact for inquiry:</p>
                         <p class="text-xl font-bold">9838528470</p>
                    </div>
                </div>
                <div class="p-10 md:w-3/5">
                    <h4 class="text-2xl font-bold text-slate-800 mb-6">Apply Now</h4>
                    <form onsubmit="event.preventDefault(); alert('Thank you! This is a demo form. Please contact the school directly.');" class="space-y-4">
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-sm font-medium text-slate-600 mb-1">Student Name</label>
                                <input type="text" class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-brand-blue focus:border-transparent outline-none" placeholder="John Doe">
                            </div>
                            <div>
                                <label class="block text-sm font-medium text-slate-600 mb-1">Class</label>
                                <select class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-brand-blue outline-none">
                                    <option>Class 1</option>
                                    <option>Class 2</option>
                                    <option>Class 3</option>
                                    <option>Class 4</option>
                                    <option>Class 5</option>
                                    <option>Class 6</option>
                                    <option>Class 7</option>
                                    <option>Class 8</option>
                                </select>
                            </div>
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-slate-600 mb-1">Parent's Name</label>
                            <input type="text" class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-brand-blue outline-none" placeholder="Parent Name">
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-slate-600 mb-1">Phone Number</label>
                            <input type="tel" class="w-full px-4 py-2 rounded-lg border border-gray-300 focus:ring-2 focus:ring-brand-blue outline-none" placeholder="+91 XXXXX XXXXX">
                        </div>
                        <button type="submit" class="w-full bg-brand-blue text-white font-bold py-3 rounded-lg hover:bg-blue-800 transition shadow-md mt-4">
                            Submit Inquiry
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-900 text-white pt-16 pb-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mb-12">
                <!-- Brand -->
                <div>
                    <h3 class="text-2xl font-serif font-bold mb-4 text-white">Sanskar <span class="text-brand-gold">JHS</span></h3>
                    <p class="text-slate-400 text-sm leading-relaxed mb-6">
                        Empowering students since 1988 with quality education, moral values, and academic excellence.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-slate-800 rounded-full flex items-center justify-center hover:bg-brand-gold transition"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="w-10 h-10 bg-slate-800 rounded-full flex items-center justify-center hover:bg-brand-gold transition"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="w-10 h-10 bg-slate-800 rounded-full flex items-center justify-center hover:bg-brand-gold transition"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>

                <!-- Contact Info -->
                <div>
                    <h4 class="text-lg font-bold mb-6 border-l-4 border-brand-gold pl-3">Contact Us</h4>
                    <ul class="space-y-4 text-sm text-slate-300">
                        <li class="flex items-start gap-3">
                            <i class="fas fa-map-marker-alt mt-1 text-brand-gold"></i>
                            <span>Shastrinagar, Ballia,<br>Uttar Pradesh - 277001</span>
                        </li>
                        <li class="flex items-center gap-3">
                            <i class="fas fa-phone mt-1 text-brand-gold"></i>
                            <a href="tel:9838528470" class="hover:text-white transition">9838528470</a>, 
                            <a href="tel:9721760309" class="hover:text-white transition">9721760309</a>
                        </li>
                        <li class="flex items-center gap-3">
                            <i class="fas fa-envelope mt-1 text-brand-gold"></i>
                            <a href="mailto:srivastavavinod@gmail.com" class="hover:text-white transition">srivastavavinod@gmail.com</a>
                        </li>
                        <li class="flex items-center gap-3">
                            <i class="fas fa-globe mt-1 text-brand-gold"></i>
                            <a href="https://sanskarjuniorhighschool-1988.github.io/Sanskarjhs1988./" class="hover:text-white transition">https://sanskarjuniorhighschool-1988.github.io/Sanskarjhs1988./</a>
                        </li>
                    </ul>
                </div>

                <!-- Quick Links & Map Placeholder -->
                <div>
            <div class="border-t border-slate-800 pt-8 flex flex-col md:flex-row justify-between items-center gap-4 text-xs text-slate-500">
                <p>&copy; 2025 Sanskar Junior High School. All Rights Reserved.</p>
                <div class="flex space-x-4">
                    <a href="#" class="hover:text-white">Privacy Policy</a>
                    <a href="#" class="hover:text-white">Terms of Use</a>
                </div>
            </div>
        </div>
    </footer> 

    <!-- Floating WhatsApp Widget -->
    <a href="https://wa.me/919838528470" target="_blank" class="fixed bottom-6 right-6 w-14 h-14 bg-green-500 rounded-full flex items-center justify-center text-white text-2xl shadow-2xl hover:scale-110 transition-transform z-40" aria-label="Chat on WhatsApp">
        <i class="fab fa-whatsapp"></i>
    </a>
    
    <!-- JavaScript -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        // Initialize Animations
        AOS.init({
            duration: 800,
            once: true,
            offset: 100
        });

        // Mobile Menu Toggle
        const btn = document.getElementById('mobile-menu-btn');
        const menu = document.getElementById('mobile-menu');

        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });

        // Close mobile menu on link click
        menu.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                menu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
