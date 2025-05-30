<script>
    import Footer from "$lib/components/footer.svelte";
    import Jumbotron from "$lib/components/jumbotron.svelte";
    import Menu from "$lib/components/menu.svelte";

    let isMobileMenuOpen = false;
    const toggleMobileMenu = () => {
        isMobileMenuOpen = !isMobileMenuOpen;
    };
</script>

<nav class="">
    <div class="max-w-6xl mx-auto px-4 mt-5">
        <div class="flex justify-between items-center h-16">
            <div class="flex items-center">
                <a href="/" class="text-3xl md:text-4xl font-bold text-gray-800 flex"
                    > 
                    <span class="specialFont">
                        Kadosh 
                    </span>
                    <div class="text-lg md:text-lg ml-2 md:ml-3 font-light">
                        <div>Bakery&</div>
                        <div class="-mt-3">
                            Restaurant
                        </div>
                       </div
                    ></a
                >
            </div>
            <div class="hidden md:flex items-center space-x-4">
                <a href="/" class="text-gray-600 hover:text-gray-900">Home</a>
                <a href="/about" class="text-gray-600 hover:text-gray-900"
                    >About</a
                >
                <a href="/services" class="text-gray-600 hover:text-gray-900"
                    >Services</a
                >
                <a href="/contact" class="text-gray-600 hover:text-gray-900"
                    >Contact</a
                >
            </div>
            <div class="md:hidden">
                <button class="mobile-menu-button p-2" on:click={toggleMobileMenu} aria-label="Toggle mobile menu">
                    <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                </button>
            </div>
            <div class="hidden md:flex items-center">
                <button
                    class="bg-[#F6E120] cursor-pointer font-bold border-[#341713] border-4 text-[#341713] hover:border-8 transition-all duration-300 ease-in-out px-3 md:px-4 py-1 md:py-2 text-sm md:text-base rounded-full hover:bg-[#F6E120]"
                >
                   Make an Order
                </button>
            </div>
        </div>
    </div>
    <!-- Mobile menu -->
    <div class="md:hidden mobile-menu {isMobileMenuOpen ? '' : 'hidden'}">
        <div class="px-4 pt-2 pb-3 space-y-2 bg-white shadow-lg">
            <a href="/" class="block text-gray-600 hover:text-gray-900 py-2">Home</a>
            <a href="/about" class="block text-gray-600 hover:text-gray-900 py-2">About</a>
            <a href="/services" class="block text-gray-600 hover:text-gray-900 py-2">Services</a>
            <a href="/contact" class="block text-gray-600 hover:text-gray-900 py-2">Contact</a>
            <button
                class="w-full bg-[#F6E120] cursor-pointer font-bold border-[#341713] border-4 text-[#341713] hover:border-8 transition-all duration-300 ease-in-out px-4 py-2 rounded-full hover:bg-[#F6E120]"
            >
               Make an Order
            </button>
        </div>
    </div>
</nav>
<Jumbotron/>
<Menu/>
<Footer/>