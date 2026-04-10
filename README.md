BALANZA
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BALANZA | Premium Balanced Sleeper</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        .glass-morphism {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
        }
        .seat-booked { background-color: #e5e7eb; cursor: not-allowed; }
        .seat-available { border: 2px solid #1b4332; cursor: pointer; }
        .seat-available:hover { background-color: #d8f3dc; }
        .balanza-gradient { background: linear-gradient(135deg, #1b4332 0%, #2d6a4f 100%); }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans leading-normal">

    <nav class="glass-morphism sticky top-0 z-50 border-b border-green-100">
        <div class="container mx-auto px-6 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-3">
                <div class="p-2 bg-green-900 rounded-lg">
                    <i class="fas fa-bus text-white text-xl"></i>
                </div>
                <div>
                    <span class="text-2xl font-bold text-green-900 block leading-none">BALANZA</span>
                    <span class="text-[10px] uppercase tracking-widest font-semibold text-green-700">Balanced • Safe • Modern</span>
                </div>
            </div>
            <div class="hidden lg:flex items-center space-x-8 text-sm font-bold uppercase tracking-wider">
                <a href="#booking" class="text-green-900 hover:text-green-600">Book Tickets</a>
                <a href="#safety" class="text-green-900 hover:text-green-600">Safety Tech</a>
                <a href="#experience" class="text-green-900 hover:text-green-600">The Cabins</a>
                <button class="border-2 border-green-900 text-green-900 px-6 py-2 rounded-full hover:bg-green-900 hover:text-white transition">My Bookings</button>
            </div>
        </div>
    </nav>

    <header class="balanza-gradient py-20 px-6 text-white relative overflow-hidden">
        <div class="container mx-auto flex flex-col lg:flex-row items-center relative z-10">
            <div class="lg:w-1/2 mb-12 lg:mb-0">
                <h1 class="text-5xl lg:text-7xl font-extrabold mb-6 leading-tight">Life Matters.<br><span class="text-green-300">Travel Balanced.</span></h1>
                <p class="text-xl opacity-90 mb-8 max-w-lg">Introducing India's first dual-side-balanced sleeper with airplane-style private reclining cabins for the safest 600-800km journeys.</p>
                <div class="flex space-x-4">
                    <a href="#booking" class="bg-white text-green-900 px-8 py-4 rounded-xl font-bold shadow-lg hover:bg-green-50 transition">Book Now</a>
                    <a href="#safety" class="bg-transparent border border-white px-8 py-4 rounded-xl font-bold hover:bg-white hover:text-green-900 transition">View Safety Features</a>
                </div>
            </div>
            <div class="lg:w-1/2">
                <img src="https://images.unsplash.com/photo-1570125909232-eb263c188f7e?auto=format&fit=crop&q=80&w=1000" alt="Balanza Bus" class="rounded-3xl shadow-2xl border-4 border-white/20">
            </div>
        </div>
    </header>

    <section id="booking" class="-mt-12 relative z-20 container mx-auto px-6">
        <div class="bg-white rounded-2xl shadow-2xl p-8 grid lg:grid-cols-4 gap-6 items-end">
            <div>
                <label class="text-xs font-bold text-gray-500 uppercase mb-2 block">Leaving From</label>
                <div class="relative">
                    <i class="fas fa-map-marker-alt absolute left-3 top-4 text-green-700"></i>
                    <input type="text" placeholder="Hyderabad" class="w-full pl-10 pr-4 py-3 bg-gray-50 border border-gray-200 rounded-lg focus:ring-2 focus:ring-green-500 outline-none">
                </div>
            </div>
            <div>
                <label class="text-xs font-bold text-gray-500 uppercase mb-2 block">Going To</label>
                <div class="relative">
                    <i class="fas fa-route absolute left-3 top-4 text-green-700"></i>
                    <input type="text" placeholder="Bengaluru" class="w-full pl-10 pr-4 py-3 bg-gray-50 border border-gray-200 rounded-lg focus:ring-2 focus:ring-green-500 outline-none">
                </div>
            </div>
            <div>
                <label class="text-xs font-bold text-gray-500 uppercase mb-2 block">Travel Date</label>
                <input type="date" class="w-full px-4 py-3 bg-gray-50 border border-gray-200 rounded-lg focus:ring-2 focus:ring-green-500 outline-none">
            </div>
            <button class="bg-orange-500 hover:bg-orange-600 text-white font-black py-4 rounded-lg shadow-lg transform transition active:scale-95 uppercase tracking-widest">
                Search Balanza
            </button>
        </div>
    </section>

    <section class="py-24 container mx-auto px-6">
        <div class="flex flex-col lg:flex-row gap-16 items-center">
            <div class="lg:w-1/2 order-2 lg:order-1">
                <div class="bg-white p-6 rounded-3xl shadow-xl border border-gray-100">
                    <div class="flex justify-between items-center mb-6">
                        <h4 class="font-bold text-lg">Select Your Recliner Cabin</h4>
                        <div class="flex space-x-2">
                            <span class="w-4 h-4 seat-available rounded"></span> <span class="text-xs">Available</span>
                            <span class="w-4 h-4 bg-green-900 rounded"></span> <span class="text-xs">Selected</span>
                        </div>
                    </div>
                    <div class="grid grid-cols-2 gap-20 bg-gray-50 p-10 rounded-xl relative">
                        <div class="absolute inset-y-0 left-1/2 w-1 bg-gray-200 -translate-x-1/2"></div>
                        <div class="space-y-4">
                            <div class="w-full h-12 seat-available rounded-lg flex items-center justify-center text-xs font-bold">L1</div>
                            <div class="w-full h-12 seat-available rounded-lg flex items-center justify-center text-xs font-bold">L2</div>
                            <div class="w-full h-12 bg-green-900 text-white rounded-lg flex items-center justify-center text-xs font-bold">L3</div>
                            <div class="w-full h-12 seat-available rounded-lg flex items-center justify-center text-xs font-bold">L4</div>
                        </div>
                        <div class="space-y-4">
                            <div class="w-full h-12 seat-available rounded-lg flex items-center justify-center text-xs font-bold">R1</div>
                            <div class="w-full h-12 seat-booked rounded-lg flex items-center justify-center text-xs font-bold">R2</div>
                            <div class="w-full h-12 seat-available rounded-lg flex items-center justify-center text-xs font-bold">R3</div>
                            <div class="w-full h-12 seat-available rounded-lg flex items-center justify-center text-xs font-bold">R4</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="lg:w-1/2 order-1 lg:order-2">
                <span class="text-green-700 font-black uppercase tracking-widest text-sm">Balanced Layout</span>
                <h2 class="text-4xl font-bold mt-4 mb-6">Science of Stability</h2>
                <p class="text-gray-600 text-lg mb-6">Traditional sleeper buses use an uneven $1 \times 2$ configuration, leading to dangerous weight imbalance. Balanza fixes this with a strictly balanced single-row layout on both sides.</p>
                <div class="grid grid-cols-2 gap-4">
                    <div class="p-4 bg-green-50 rounded-xl">
                        <h5 class="font-bold text-green-900">Equal Weight</h5>
                        <p class="text-xs text-green-700">Better road grip and zero tipping risk.</p>
                    </div>
                    <div class="p-4 bg-green-50 rounded-xl">
                        <h5 class="font-bold text-green-900">Noise Control</h5>
                        <p class="text-xs text-green-700">Acoustically insulated interior cabins.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="experience" class="bg-green-900 py-24 text-white">
        <div class="container mx-auto px-6 text-center mb-16">
            <h2 class="text-4xl font-bold mb-4">Airplane-Style Reclining Cabins</h2>
            <p class="opacity-70 max-w-2xl mx-auto">Skip the cramped berths. Our private cabins feature premium sofa-to-bed recliners with individual charging and climate control.</p>
        </div>
        <div class="container mx-auto px-6 grid md:grid-cols-3 gap-8">
            <div class="group overflow-hidden rounded-3xl relative">
                <img src="https://images.unsplash.com/photo-1540518614846-7eded433c457?auto=format&fit=crop&q=80&w=600" class="w-full h-80 object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-black/40 p-8 flex flex-col justify-end">
                    <h4 class="font-bold text-xl">Full Privacy</h4>
                    <p class="text-sm opacity-80">Personal cabins with sliding partitions.</p>
                </div>
            </div>
            <div class="group overflow-hidden rounded-3xl relative">
                <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&q=80&w=600" class="w-full h-80 object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-black/40 p-8 flex flex-col justify-end">
                    <h4 class="font-bold text-xl">Smart Entertainment</h4>
                    <p class="text-sm opacity-80">Dedicated screen and high-speed Wi-Fi.</p>
                </div>
            </div>
            <div class="group overflow-hidden rounded-3xl relative">
                <img src="https://images.unsplash.com/photo-1494438639946-1ebd1d20bf85?auto=format&fit=crop&q=80&w=600" class="w-full h-80 object-cover group-hover:scale-110 transition duration-500">
                <div class="absolute inset-0 bg-black/40 p-8 flex flex-col justify-end">
                    <h4 class="font-bold text-xl">Soft Sleep Tech</h4>
                    <p class="text-sm opacity-80">Orthopedic mattresses for long journeys.</p>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-white pt-20 pb-10 border-t border-gray-100">
        <div class="container mx-auto px-6 grid md:grid-cols-4 gap-12 mb-16">
            <div class="col-span-2">
                <div class="flex items-center space-x-3 mb-6">
                    <div class="p-2 bg-green-900 rounded-lg text-white">B</div>
                    <span class="text-2xl font-bold tracking-tight">BALANZA</span>
                </div>
                <p class="text-gray-500 max-w-sm">Dedicated to solving India's night-travel safety problem through disruptive engineering and premium comfort[cite: 78].</p>
            </div>
            <div>
                <h5 class="font-bold mb-6">Quick Links</h5>
                <ul class="space-y-4 text-gray-500 text-sm font-medium">
                    <li><a href="#" class="hover:text-green-700 transition">About the Concept</a></li>
                    <li><a href="#" class="hover:text-green-700 transition">Fleet Technology</a></li>
                    <li><a href="#" class="hover:text-green-700 transition">Safety Standards</a></li>
                </ul>
            </div>
            <div>
                <h5 class="font-bold mb-6">Support</h5>
                <ul class="space-y-4 text-gray-500 text-sm font-medium">
                    <li><a href="#" class="hover:text-green-700 transition">Privacy Policy</a></li>
                    <li><a href="#" class="hover:text-green-700 transition">Ticket Cancellation</a></li>
                    <li><a href="#" class="hover:text-green-700 transition">Contact Us</a></li>
                </ul>
            </div>
        </div>
        <div class="container mx-auto px-6 pt-10 border-t border-gray-100 text-center">
            <p class="text-xs text-gray-400 font-bold tracking-widest uppercase">Designed for Institute of Product Leadership by Thumati Kowshik[cite: 9, 105].</p>
        </div>
    </footer>

</body>
</html>
