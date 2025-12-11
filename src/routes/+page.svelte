<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-tripod-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-tripod-primary)]"></span>
                        <span class="text-white text-sm font-medium">Tri-POD vOS</span>
                        <span class="text-gray-400 text-sm">is live</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Unify your promo operations. From sourcing to fulfillment.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        The first Vertical Operating System for promotional product distributors. Integrated workflow automation, instant supplier payments, and enterprise logistics—all in one platform.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Get started
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            See how it works
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 - Order Management -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500">ORDER #45821</div>
                                <div class="h-8 px-3 bg-[var(--color-tripod-primary)]/20 rounded text-[var(--color-tripod-primary)] text-xs flex items-center justify-center font-bold">In Production</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-24 bg-gray-100 rounded-lg w-full flex items-center justify-center">
                                    <div class="text-gray-400 text-xs">T-Shirt Preview</div>
                                </div>
                                <div class="flex justify-between text-xs">
                                    <span class="text-gray-500">Qty: 500</span>
                                    <span class="font-semibold">$2,450.00</span>
                                </div>
                                <div class="h-2 w-full bg-gray-100 rounded-full overflow-hidden">
                                    <div class="h-full bg-[var(--color-tripod-primary)] w-3/4"></div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) - Tech Pack -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-gradient-to-br from-[var(--color-tripod-primary)] to-[var(--color-tripod-primary-hover)] p-6">
                                <div class="flex justify-between items-center">
                                    <div class="text-white font-semibold text-sm">AI Tech Pack</div>
                                    <div class="h-8 w-8 bg-white/20 rounded-full flex items-center justify-center">
                                        <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                    </div>
                                </div>
                            </div>
                            <div class="p-6 flex-grow">
                                <div class="space-y-3">
                                    <div class="flex items-center gap-2 text-xs">
                                        <div class="w-2 h-2 rounded-full bg-green-500"></div>
                                        <span class="text-gray-600">Print zones detected</span>
                                    </div>
                                    <div class="flex items-center gap-2 text-xs">
                                        <div class="w-2 h-2 rounded-full bg-green-500"></div>
                                        <span class="text-gray-600">Specs generated</span>
                                    </div>
                                    <div class="flex items-center gap-2 text-xs">
                                        <div class="w-2 h-2 rounded-full bg-green-500"></div>
                                        <span class="text-gray-600">Quote ready</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 - Payment -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs font-semibold text-gray-500">SUPPLIER PAYMENT</div>
                                <div class="h-8 px-3 bg-green-100 rounded text-green-600 text-xs flex items-center justify-center font-bold">Instant</div>
                            </div>
                            <div class="space-y-3">
                                <div class="p-3 bg-gray-50 rounded">
                                    <div class="text-xs text-gray-500 mb-1">Amount</div>
                                    <div class="text-2xl font-bold">$1,850.00</div>
                                </div>
                                <div class="flex items-center gap-2 text-xs text-gray-600">
                                    <svg class="w-4 h-4 text-green-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                    Paid instantly via Tri-POD
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Logos Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by forward-thinking promotional product distributors</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-50">
                    <!-- Distributor placeholder logos -->
                    <div class="text-white font-bold text-xl tracking-wider">PROMO+</div>
                    <div class="text-white font-bold text-xl tracking-wider">SWAG CO</div>
                    <div class="text-white font-bold text-xl tracking-wider">BRAND GEAR</div>
                    <div class="text-white font-bold text-xl tracking-wider">MERCH PRO</div>
                    <div class="text-white font-bold text-xl tracking-wider">LOGO WORKS</div>
                </div>
            </div>
        </section>

        <!-- Triple Moat Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-tripod-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">The Triple Moat</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Three engines.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Compounding value.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Visual Card -->
                    <div class="bg-gradient-to-br from-[var(--color-tripod-primary)] to-[var(--color-tripod-primary-hover)] rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Three Circles representing engines -->
                            <div class="flex flex-col gap-6">
                                <!-- Workflow Engine -->
                                <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                    <div class="flex items-center gap-3">
                                        <div class="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center">
                                            <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                                        </div>
                                        <div>
                                            <div class="text-white font-semibold text-sm">Workflow</div>
                                            <div class="text-white/60 text-xs">AI-powered automation</div>
                                        </div>
                                    </div>
                                </div>
                                
                                <!-- Money Engine -->
                                <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                    <div class="flex items-center gap-3">
                                        <div class="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center">
                                            <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                                        </div>
                                        <div>
                                            <div class="text-white font-semibold text-sm">Money</div>
                                            <div class="text-white/60 text-xs">Instant supplier payments</div>
                                        </div>
                                    </div>
                                </div>
                                
                                <!-- Network Engine -->
                                <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                    <div class="flex items-center gap-3">
                                        <div class="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center">
                                            <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9c1.657 0 3-4.03 3-9s-1.343-9-3-9m0 18c-1.657 0-3-4.03-3-9s1.343-9 3-9m-9 9a9 9 0 019-9"></path></svg>
                                        </div>
                                        <div>
                                            <div class="text-white font-semibold text-sm">Network</div>
                                            <div class="text-white/60 text-xs">Enterprise logistics power</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Built to scale. Designed to win.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Three integrated engines that create compounding value. Workflow automation eliminates manual work. Instant payments unlock cash flow. Network effects deliver enterprise pricing. Together, they're unstoppable.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Tri-POD vOS</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Your entire promo operation.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">In one unified system.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Explore the platform
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-tripod-primary)]"></span>
                                AI Tech Pack Generator
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Instant Supplier Payment</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Turbine Network</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Team Stores</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Vibe Engine</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">One-Click Operations</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="AI Tech Pack Generator" 
                            description="Eliminate Adobe Illustrator dependency. Powered by Gemini 2.5, our AI automatically detects print zones and generates complete technical specifications in seconds."
                            icon="lab"
                            image="lab"
                        />
                         <FeatureRow 
                            title="Instant Supplier Payment" 
                            description="Remove cash flow constraints. Tri-POD pays suppliers instantly on your behalf while you offer Net-30 terms to clients. No more juggling payment schedules."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Turbine Network" 
                            description="Access enterprise pricing. Our logistics network aggregates order volume across all customers, giving you National Account pricing tiers typically reserved for industry giants."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Team Stores" 
                            description="Launch e-commerce in 30 seconds. Turn any quote into a live Team Store or Pop-up Shop. Unified inventory and fulfillment across B2B and DTC channels."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Vibe Engine" 
                            description="Create agency-quality presentations. Generate stunning product boards with one click using style presets like Executive, Hype, and Tech. No design software needed."
                            icon="guard"
                            image="guard"
                        />
                         <FeatureRow 
                            title="One-Click Operations" 
                            description="Replace swivel-chair workflows. Single-click operations replace multi-system juggling. From sourcing to shipping, everything flows through one unified interface."
                            icon="lock"
                            image="collateral"
                        />
                    </div>
                </div>

                <!-- Omnichannel Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-[var(--color-tripod-primary)]/20 to-[var(--color-tripod-primary)]/10 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-[var(--color-tripod-primary)]/10 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-[var(--color-tripod-primary)] relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Omnichannel by default. Launch Team Stores and Company Swag Shops in seconds using your existing curated assets.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        See e-commerce in action
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Customer Success Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by forward-thinking distributors. See how they're winning.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Card -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-end">
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-2xl tracking-tight">PromoWorks</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-tripod-primary)] flex items-center justify-center text-white font-bold">+</div>
                                    <div class="flex items-center gap-2 text-white font-semibold text-xl tracking-tight">
                                        <svg width="28" height="28" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <circle cx="6" cy="18" r="3" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <circle cx="12" cy="6" r="3" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <circle cx="18" cy="18" r="3" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M9 16.5L10.5 8.5M13.5 8.5L15 16.5" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                        </svg>
                                        Tri-POD
                                    </div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-4 max-w-md">
                                    How a $5M distributor eliminated Excel spreadsheets and scaled to $12M in 18 months
                                </h3>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-[var(--color-tripod-primary)]/20 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white font-semibold mb-2">BrandGear</div>
                                    <p class="text-gray-400 text-sm">Instant payments unlocked 3x growth</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-[var(--color-tripod-primary)]/20 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-white font-semibold mb-2">SwagCo</div>
                                    <p class="text-gray-400 text-sm">Launched 50+ Team Stores in first quarter</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-[var(--color-tripod-primary)]/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-[var(--color-tripod-primary)]/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Stop juggling systems. <span class="text-[var(--color-tripod-primary)]">Start winning.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Built for distributors who are tired of Excel, email, and swivel-chair workflows. Get instant supplier payments, AI automation, and enterprise pricing power.
                        </p>
                        <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-4 py-2 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                            Platform Docs
                            <kbd class="bg-black/30 px-1.5 py-0.5 rounded text-xs text-gray-400 font-mono">D</kbd>
                        </div>
                    </div>
                </div>

                <!-- Integrations -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        Suppliers. Shipping carriers. Payment processors.<br>
                        <span class="text-gray-400">Whatever tools you use,<br>Tri-POD connects seamlessly.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        Explore all integrations
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['SAGE', 'commonsku', 'Shopify', 'Stripe', 'FedEx', 'UPS', 'QuickBooks', 'Zapier'] as logo}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center grayscale opacity-60 hover:grayscale-0 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-xl uppercase tracking-wider">{logo}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Learn about the future of promo operations.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-[var(--color-tripod-primary)]/20 to-[var(--color-tripod-primary)]/10 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="text-6xl font-bold text-[var(--color-tripod-primary)]/30">AI</div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Product Update</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-[var(--color-tripod-primary)] transition-colors">How AI Tech Packs are eliminating Adobe Illustrator dependency</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-gray-200 to-gray-300 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="flex gap-4">
                                    <div class="w-16 h-16 rounded-full bg-[var(--color-tripod-primary)] blur-xl opacity-60"></div>
                                    <div class="w-20 h-20 rounded-full bg-[var(--color-tripod-primary)] blur-xl opacity-40"></div>
                                    <div class="w-12 h-12 rounded-full bg-[var(--color-tripod-primary)] blur-xl opacity-80"></div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Industry Insights</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-[var(--color-tripod-primary)] transition-colors">Why mid-market distributors are winning with instant supplier payments</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

