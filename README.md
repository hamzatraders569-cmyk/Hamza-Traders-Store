<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hamza Traders | Elite Beauty & Hydrating Cosmetics</title>
    <!-- Tailwind CSS (CDN) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        display: ['Space Grotesk', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            DEFAULT: '#2e1810', /* Premium Dark Brown */
                            light: '#4c291e',
                            gold: '#b8926a',
                            bg: '#fafaf7',       /* Minimal Light Background */
                            card: '#ffffff'
                        }
                    }
                }
            }
        }
    </script>
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
</head>
<body class="min-h-screen bg-[#fafaf7] text-gray-800 font-sans flex flex-col justify-between">

    <!-- Header / Navigation -->
    <header class="sticky top-0 z-50 bg-[#fafaf7]/80 backdrop-blur-md border-b border-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center gap-2">
                <span class="font-display text-2xl font-bold tracking-wider text-[#2e1810]">HAMZA TRADERS</span>
            </div>
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium tracking-wide text-gray-600">
                <a href="#home" class="hover:text-[#2e1810] transition-colors">Home</a>
                <a href="#products" class="hover:text-[#2e1810] transition-colors">Products</a>
                <a href="#about" class="hover:text-[#2e1810] transition-colors">Our Story</a>
                <a href="#contact" class="hover:text-[#2e1810] transition-colors">Contact</a>
            </nav>
            <div class="flex items-center gap-4">
                <button class="p-2 text-gray-600 hover:text-[#2e1810] relative">
                    <i data-lucide="shopping-bag" class="w-6 h-6"></i>
                    <span class="absolute top-1 right-1 bg-[#b8926a] text-white text-[10px] w-4 h-4 rounded-full flex items-center justify-between justify-center">0</span>
                </button>
            </div>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="home" class="relative overflow-hidden py-20 lg:py-32">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div class="space-y-6 z-10">
                    <span class="text-xs font-bold tracking-widest text-[#b8926a] uppercase">Premium Cosmetics Collection</span>
                    <h1 class="font-display text-5xl sm:text-6xl font-light tracking-tight text-[#2e1810] leading-tight">
                        Reveal Your <br><span class="font-medium italic text-[#b8926a]">Natural Glow</span>
                    </h1>
                    <p class="text-gray-600 text-lg max-w-md font-light">
                        Experience the ultimate hydration and elite beauty products crafted carefully for your skin's luxury.
                    </p>
                    <div class="pt-4">
                        <a href="#products" class="inline-block bg-[#2e1810] text-white font-medium text-sm tracking-wider uppercase px-8 py-4 hover:bg-[#4c291e] transition-all transform hover:-translate-y-0.5 shadow-sm">
                            Shop Collection
                        </a>
                    </div>
                </div>
                <div class="relative flex justify-center">
                    <div class="w-72 h-96 sm:w-80 sm:h-[450px] bg-gradient-to-tr from-[#2e1810] to-[#b8926a] rounded-t-full shadow-2xl overflow-hidden relative">
                        <!-- High-quality Placeholder Image -->
                        <img src="https://images.unsplash.com/photo-1608248597481-496100c8c836?q=80&w=600&auto=format&fit=crop" alt="Cosmetics" class="w-full h-full object-cover mix-blend-multiply opacity-90">
                    </div>
                    <!-- Minimal accent badge -->
                    <div class="absolute bottom-10 left-4 sm:left-10 bg-white p-4 shadow-xl border border-gray-100 flex items-center gap-3">
                        <div class="w-10 h-10 bg-[#fafaf7] rounded-full flex items-center justify-center text-[#b8926a]">
                            <i data-lucide="sparkles" class="w-5 h-5"></i>
                        </div>
                        <div>
                            <p class="text-xs font-bold text-[#2e1810]">100% Pure</p>
                            <p class="text-[10px] text-gray-500">Hydrating Formula</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Featured Products -->
        <section id="products" class="py-20 bg-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center max-w-xl mx-auto mb-16 space-y-3">
                    <h2 class="font-display text-3xl font-light tracking-tight text-[#2e1810]">Featured Essentials</h2>
                    <div class="w-12 h-[1px] bg-[#b8926a] mx-auto"></div>
                    <p class="text-sm text-gray-500 font-light">Explore our curated selection of elite beauty items</p>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                    <!-- Product 1 -->
                    <div class="group cursor-pointer">
                        <div class="aspect-[4/5] bg-[#fafaf7] overflow-hidden mb-4 relative flex items-center justify-center">
                            <img src="https://images.unsplash.com/photo-1620916566398-39f1143ab7be?q=80&w=600&auto=format&fit=crop" alt="Luxury Serum" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                            <span class="absolute top-4 left-4 text-[10px] tracking-widest font-bold uppercase bg-white px-3 py-1 text-[#2e1810] shadow-sm">Best Seller</span>
                        </div>
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-medium text-sm text-[#2e1810]">Elite Hydrating Serum</h3>
                                <p class="text-xs text-gray-400 mt-1">Advanced Skin Repair</p>
                            </div>
                            <span class="text-sm font-semibold text-[#2e1810]">Rs. 2,450</span>
                        </div>
                    </div>

                    <!-- Product 2 -->
                    <div class="group cursor-pointer">
                        <div class="aspect-[4/5] bg-[#fafaf7] overflow-hidden mb-4 relative flex items-center justify-center">
                            <img src="https://images.unsplash.com/photo-1556228720-195a672e8a03?q=80&w=600&auto=format&fit=crop" alt="Premium Perfume" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        </div>
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-medium text-sm text-[#2e1810]">ZH Ameer Hamza Perfume</h3>
                                <p class="text-xs text-gray-400 mt-1">Luxury Signature Scent</p>
                            </div>
                            <span class="text-sm font-semibold text-[#2e1810]">Rs. 3,890</span>
                        </div>
                    </div>

                    <!-- Product 3 -->
                    <div class="group cursor-pointer">
                        <div class="aspect-[4/5] bg-[#fafaf7] overflow-hidden mb-4 relative flex items-center justify-center">
                            <img src="https://images.unsplash.com/photo-1601049541289-9b1b7bbbfe19?q=80&w=600&auto=format&fit=crop" alt="Glow Cream" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        </div>
                        <div class="flex justify-between items-start">
                            <div>
                                <h3 class="font-medium text-sm text-[#2e1810]">Glow Moisturizing Cream</h3>
                                <p class="text-xs text-gray-400 mt-1">24h Radiant Moisture</p>
                            </div>
                            <span class="text-sm font-semibold text-[#2e1810]">Rs. 1,850</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer id="contact" class="bg-[#2e1810] text-gray-400 text-sm py-12 border-t border-[#4c291e]">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="space-y-4">
                <h4 class="font-display text-white text-lg font-bold tracking-wider">HAMZA TRADERS</h4>
                <p class="font-light text-xs text-gray-400 max-w-xs">Your premium destination for elite beauty, cosmetics, and premium fragrances.</p>
            </div>
            <div class="space-y-2">
                <h4 class="text-white font-medium text-xs tracking-widest uppercase mb-4">Quick Links</h4>
                <p><a href="#home" class="hover:text-white transition-colors">Home</a></p>
                <p><a href="#products" class="hover:text-white transition-colors">Products</a></p>
            </div>
            <div class="space-y-2">
                <h4 class="text-white font-medium text-xs tracking-widest uppercase mb-4">Contact Info</h4>
                <p class="flex items-center gap-2"><i data-lucide="mail" class="w-4 h-4"></i> info@hamzatraders.com</p>
                <p class="flex items-center gap-2"><i data-lucide="map-pin" class="w-4 h-4"></i> Lahore, Pakistan</p>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 mt-12 pt-6 border-t border-white/5 text-center text-xs">
            &copy; 2026 Hamza Traders. All Rights Reserved.
        </div>
    </footer>

    <!-- Initialize Lucide Icons -->
    <script>
        lucide.createIcons();
    </script>
</body>
</html>