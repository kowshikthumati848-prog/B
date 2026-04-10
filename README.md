<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BALANZA | Balanced Luxury Sleeper</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --balanza-green: #1b4332;
            --balanza-light-green: #d8f3dc;
        }
        .bg-balanza { background-color: var(--balanza-green); }
        .text-balanza { color: var(--balanza-green); }
        .border-balanza { border-color: var(--balanza-green); }
    </style>
</head>
<body class="bg-gray-50 font-sans">

    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <div class="w-10 h-10 bg-balanza rounded-lg flex items-center justify-center text-white font-bold text-xl">B</div>
                <span class="text-2xl font-bold text-balanza tracking-tight">BALANZA</span>
            </div>
            <div class="hidden md:flex space-x-8 font-medium text-gray-600">
                <a href="#" class="hover:text-balanza">Home</a>
                <a href="#about" class="hover:text-balanza">Safety</a>
                <a href="#experience" class="hover:text-balanza">The Recliners</a>
                <a href="#" class="bg-balanza text-white px-5 py-2 rounded-full">Login</a>
            </div>
        </div>
    </nav>

    <section class="bg-balanza py-16 px-6">
        <div class="container mx-auto text-center text-white mb-10">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">India's First Balanced Luxury Sleeper</h1>
            <p class="text-lg opacity-90">Experience airplane-style recliner cabins for the safest overnight journey.</p>
        </div>

        <div class="container mx-auto max-w-5xl bg-white p-4 rounded-xl shadow-2xl flex flex-col md:flex-row gap-4 items-center">
            <div class="flex-1 w-full border-r border-gray-200 px-4">
                <label class="block text-xs text-gray-500 uppercase font-bold">From</label>
                <input type="text" placeholder="Enter City" class="w-full py-2 outline-none text-lg">
            </div>
            <div class="flex-1 w-full border-r border-gray-200 px-4">
                <label class="block text-xs text-gray-500 uppercase font-bold">To</label>
                <input type="text" placeholder="Enter City" class="w-full py-2 outline-none text-lg">
            </div>
            <div class="flex-1 w-full px-4">
                <label class="block text-xs text-gray-500 uppercase font-bold">Date</label>
                <input type="date" class="w-full py-2 outline-none text-lg">
            </div>
            <button class="bg-orange-500 hover:bg-orange-600 text-white font-bold py-4 px-10 rounded-lg transition-all w-full md:w-auto">
                SEARCH BUSES
            </button>
        </div>
    </section>

    <section id="about" class="py-20 container mx-auto px-6">
        <div class="text-center mb-16">
            <h2 class="text-3xl font-bold text-gray-800">Why Choose Balanza?</h2>
            <div class="w-20 h-1 bg-balanza mx-auto mt-4"></div>
        </div>
        
        <div class="grid md:grid-cols-3 gap-12">
            <div class="bg-white p-8 rounded-2xl shadow-lg border-t-4 border-balanza text-center">
                <i class="fas fa-balance-scale text-4xl text-balanza mb-4"></i>
                <h3 class="text-xl font-bold mb-2">Balanced Layout</h3>
                <p class="text-gray-600">Our unique 1x1 side-balanced layout eliminates weight imbalance for maximum stability.</p>
            </div>
            <div class="bg-white p-8 rounded-2xl shadow-lg border-t-4 border-balanza text-center">
                <i class="fas fa-couch text-4xl text-balanza mb-4"></i>
                <h3 class="text-xl font-bold mb-2">Recliner Pods</h3>
                <p class="text-gray-600">Premium airplane-style reclining cabins designed for deep, undisturbed sleep.</p>
            </div>
            <div class="bg-white p-8 rounded-2xl shadow-lg border-t-4 border-balanza text-center">
                <i class="fas fa-shield-alt text-4xl text-balanza mb-4"></i>
                <h3 class="text-xl font-bold mb-2">Safety First</h3>
                <p class="text-gray-600">Enhanced engineering to reduce fire risks and prevent top-heavy tipping.</p>
            </div>
        </div>
    </section>

    <section id="experience" class="bg-gray-100 py-20">
        <div class="container mx-auto px-6 flex flex-col md:flex-row items-center gap-12">
            <div class="md:w-1/2">
                <img src="https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&q=80&w=1000" alt="Luxury Bus" class="rounded-3xl shadow-2xl">
            </div>
            <div class="md:w-1/2">
                <h2 class="text-4xl font-bold text-gray-800 mb-6">Redefining Long-Distance Travel</h2>
                <p class="text-gray-600 text-lg mb-6 leading-relaxed">
                    Unlike traditional 1x2 sleeper buses that feel cramped and unstable, Balanza offers private pods that focus on your well-being.
                </p>
                <ul class="space-y-4">
                    <li class="flex items-center space-x-3">
                        <i class="fas fa-check-circle text-green-600"></i>
                        <span>Noise-controlled interiors for peaceful rest</span>
                    </li>
                    <li class="flex items-center space-x-3">
                        <i class="fas fa-check-circle text-green-600"></i>
                        <span>Individual climate control in every pod</span>
                    </li>
                    <li class="flex items-center space-x-3">
                        <i class="fas fa-check-circle text-green-600"></i>
                        <span>Affordable luxury pricing for professionals</span>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <footer class="bg-balanza text-white py-12">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-2xl font-bold mb-4 tracking-widest uppercase">BALANZA</h2>
            <p class="opacity-70 mb-8 italic">Life Matters. Travel Balanced.</p>
            <div class="flex justify-center space-x-6 mb-8">
                <a href="#" class="text-2xl hover:text-green-300 transition"><i class="fab fa-facebook"></i></a>
                <a href="#" class="text-2xl hover:text-green-300 transition"><i class="fab fa-instagram"></i></a>
                <a href="#" class="text-2xl hover:text-green-300 transition"><i class="fab fa-twitter"></i></a>
            </div>
            <p class="text-sm opacity-50">&copy; 2026 Balanza Institute of Product Leadership. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
