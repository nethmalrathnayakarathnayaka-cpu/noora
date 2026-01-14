<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Space+Grotesk', sans-serif; background-color: #05070A; }
        .glow-effect { box-shadow: 0 0 50px -10px rgba(204, 255, 0, 0.3); }
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(10px); border: 1px solid rgba(255, 255, 255, 0.1); }
        @keyframes float { 0% { transform: translateY(0px); } 50% { transform: translateY(-20px); } 100% { transform: translateY(0px); } }
        .animate-float { animation: float 6s ease-in-out infinite; }
    </style>
</head>
<body class="text-white overflow-x-hidden">

    <nav class="flex justify-between items-center px-8 py-6 max-w-7xl mx-auto">
        <div class="text-2xl font-bold tracking-tighter italic">Nethmal <span class="text-[#CCFF00]">Rathnayaka</span></div>
        <div class="hidden md:flex space-x-8 text-sm uppercase tracking-widest text-gray-400">
            <a href="#" class="hover:text-white transition">About</a>
            <a href="#" class="hover:text-white transition">Tokenomics</a>
            <a href="#" class="hover:text-white transition">Roadmap</a>
        </div>
        <button class="glass px-6 py-2 rounded-full border border-[#CCFF00]/30 hover:bg-[#CCFF00] hover:text-black transition duration-300">
            Connect Wallet
        </button>
    </nav>

    <section class="relative max-w-7xl mx-auto px-8 py-20 lg:py-32 flex flex-col lg:flex-row items-center">
        
        <div class="w-full lg:w-1/2 z-10 text-center lg:text-left">
            <div class="inline-block px-4 py-1 glass rounded-full text-xs font-medium tracking-widest text-[#CCFF00] mb-6">
                🚀 TICKER: $NR — NOW LIVE ON PANCAKESWAP
            </div>
            <h1 class="text-5xl lg:text-7xl font-bold leading-tight mb-6">
                The Future of <span class="text-transparent bg-clip-text bg-gradient-to-r from-[#CCFF00] to-cyan-400">Decentralized</span> Digital Currency
            </h1>
            <p class="text-gray-400 text-lg mb-10 max-w-xl mx-auto lg:mx-0">
                Nethmal Rathnayaka ($NR) is a community-driven crypto project built on transparency, speed, and institutional-grade security.
            </p>
            
            <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start">
                <button class="px-8 py-4 bg-[#CCFF00] text-black font-bold rounded-xl glow-effect hover:scale-105 transition transform">
                    Buy $NR Token
                </button>
                <button class="px-8 py-4 glass text-white font-bold rounded-xl hover:bg-white/10 transition">
                    View Whitepaper
                </button>
            </div>

            <div class="mt-12 flex items-center justify-center lg:justify-start space-x-8 opacity-50">
                <div><span class="block text-2xl font-bold">1B</span><span class="text-xs uppercase">Supply</span></div>
                <div class="h-8 w-[1px] bg-gray-700"></div>
                <div><span class="block text-2xl font-bold">0%</span><span class="text-xs uppercase">Buy Tax</span></div>
                <div class="h-8 w-[1px] bg-gray-700"></div>
                <div><span class="block text-2xl font-bold">Locked</span><span class="text-xs uppercase">Liquidity</span></div>
            </div>
        </div>

        <div class="w-full lg:w-1/2 mt-20 lg:mt-0 relative flex justify-center">
            <div class="absolute w-72 h-72 bg-[#CCFF00] rounded-full filter blur-[120px] opacity-20 animate-pulse"></div>
            <div class="relative animate-float">
                <div class="w-64 h-64 lg:w-80 lg:h-80 rounded-full glass flex items-center justify-center border-2 border-[#CCFF00]/20 shadow-2xl">
                    <span class="text-6xl lg:text-8xl font-black text-[#CCFF00] drop-shadow-[0_0_15px_rgba(204,255,0,0.8)]">NR</span>
                </div>
                <div class="absolute -top-4 -right-4 glass p-4 rounded-2xl animate-bounce delay-700">💎</div>
                <div class="absolute -bottom-4 -left-4 glass p-4 rounded-2xl animate-bounce">⚡</div>
            </div>
        </div>
    </section>

    <div class="max-w-4xl mx-auto mb-20 px-8">
        <div class="glass p-4 rounded-2xl flex flex-col md:flex-row items-center justify-between gap-4 border-dashed border-[#CCFF00]/40">
            <span class="text-xs uppercase tracking-tighter text-gray-500 font-bold">Official Contract Address:</span>
            <code class="text-[#CCFF00] text-sm break-all font-mono">0xNethmalRathnayaka_Project_Contract_Address_2026</code>
            <button class="text-xs bg-white/10 hover:bg-white/20 px-3 py-1 rounded transition uppercase">Copy</button>
        </div>
    </div>

</body>
</html>
