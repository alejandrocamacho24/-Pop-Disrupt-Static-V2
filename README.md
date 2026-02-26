<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pop Disrupt | Flavor Fusion</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0a0a0a;
            color: white;
        }
        .bento-card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .bento-card:hover {
            transform: translateY(-5px);
            background: rgba(255, 255, 255, 0.07);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        /* Gradient backgrounds for specific flavors to match the labels */
        .bg-smores { background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%); }
        .bg-dubai { background: linear-gradient(135deg, #3f6212 0%, #1a2e05 100%); }
        .bg-mexican { background: linear-gradient(135deg, #991b1b 0%, #450a0a 100%); }
        
        .custom-scrollbar::-webkit-scrollbar { width: 0px; }
    </style>
</head>
<body class="p-4 md:p-8">

    <nav class="max-w-7xl mx-auto flex justify-between items-center mb-12 relative z-50">
    <img src="Pop Disrupt title.png" 
         alt="Pop Disrupt" 
         class="h-8 md:h-12 object-contain" 
         style="filter: drop-shadow(0px 2px 4px rgba(0,0,0,0.5));">
    
    <div class="flex items-center gap-4">
        <span class="hidden md:block text-sm font-medium opacity-60">Elevate Your Snack</span>
        <img src="pd logo.png" 
             alt="PD" 
             class="h-10 w-10 rounded-xl border border-white/20 shadow-lg object-cover">
    </div>
</nav>

    <main class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-4 gap-4">
        
        <div class="md:col-span-3 md:row-span-2 relative overflow-hidden rounded-[2rem] bento-card p-8 flex flex-col justify-end min-h-[400px]">
            <div class="absolute inset-0 z-0">
                <img src="Campfire S'mores.jpg" class="w-full h-full object-cover opacity-40 scale-110 hover:scale-100 transition-transform duration-700" alt="Hero">
                <div class="absolute inset-0 bg-gradient-to-t from-[#0a0a0a] via-transparent to-transparent"></div>
            </div>
            <div class="relative z-10">
                <span class="px-3 py-1 bg-white/10 rounded-full text-xs font-bold uppercase tracking-widest mb-4 inline-block border border-white/20">New Drop</span>
                <h1 class="text-5xl md:text-70xl font-extrabold mb-4 tracking-tighter">THE SEASONING REVOLUTION.</h1>
                <p class="text-lg opacity-70 max-w-xl mb-6">Forget basic butter. We're disrupting the popcorn industry with flavors inspired by global trends and nostalgic treats.</p>
                <a href="YOUR_AMAZON_LINK" class="inline-flex items-center justify-center px-8 py-4 bg-white text-black font-bold rounded-2xl hover:bg-gray-200 transition-colors">
                    Shop Collection on Amazon
                </a>
            </div>
        </div>

        <div class="rounded-[2rem] bento-card p-6 flex flex-col justify-center items-center text-center">
            <h3 class="text-4xl font-bold text-yellow-500">8</h3>
            <p class="text-sm opacity-50 uppercase tracking-widest">Iconic Flavors</p>
        </div>

        <div class="rounded-[2rem] bento-card p-6 flex flex-col justify-center items-center text-center">
            <h3 class="text-4xl font-bold text-green-500">0</h3>
            <p class="text-sm opacity-50 uppercase tracking-widest">Boring Kernels</p>
        </div>

        <div class="md:col-span-4 mt-8">
            <div class="flex justify-between items-end mb-6">
                <h2 class="text-2xl font-bold px-2">Trending Flavors</h2>
                <span class="text-sm opacity-40">Scroll to explore →</span>
            </div>
            
            <div class="flex overflow-x-auto gap-4 pb-6 custom-scrollbar">
                
                <div class="min-w-[300px] rounded-[2rem] bento-card overflow-hidden group">
                    <img src="Dubai Chocolate.jpg" class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-500">
                    <div class="p-6">
                        <h4 class="font-bold text-xl">Dubai Chocolate</h4>
                        <p class="text-sm opacity-60 mb-4">Pistachio & Kunafa luxury.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs font-mono opacity-40">NET WT 2.85 OZ</span>
                            <div class="h-2 w-2 rounded-full bg-green-500"></div>
                        </div>
                    </div>
                </div>

                <div class="min-w-[300px] rounded-[2rem] bento-card overflow-hidden group">
                    <img src="Korean Hot Honey.jpg" class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-500">
                    <div class="p-6">
                        <h4 class="font-bold text-xl">Korean Hot Honey</h4>
                        <p class="text-sm opacity-60 mb-4">Sweet heat with a Seoul soul.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs font-mono opacity-40">NET WT 2.85 OZ</span>
                            <div class="h-2 w-2 rounded-full bg-red-500"></div>
                        </div>
                    </div>
                </div>

                <div class="min-w-[300px] rounded-[2rem] bento-card overflow-hidden group">
                    <img src="Mexican Street Corn.jpg" class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-500">
                    <div class="p-6">
                        <h4 class="font-bold text-xl">Mexican Street Corn</h4>
                        <p class="text-sm opacity-60 mb-4">Authentic Elote vibes.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xs font-mono opacity-40">NET WT 2.85 OZ</span>
                            <div class="h-2 w-2 rounded-full bg-yellow-500"></div>
                        </div>
                    </div>
                </div>

                </div>
        </div>

        <div class="md:col-span-4 mt-12 mb-20 text-center">
            <p class="text-white/20 mb-8 font-mono">POP DISRUPT © 2026 // FLAVOR FUSION TECHNOLOGY</p>
            <a href="YOUR_AMAZON_LINK" class="group relative inline-flex items-center justify-center px-12 py-6 font-bold text-white transition-all duration-200 bg-orange-600 font-pj rounded-full focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-900" role="button">
                Get the Full 8-Pack on Amazon
            </a>
        </div>
    </main>

</body>
</html>
