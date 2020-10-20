<template>
    <div class="flex items-center p-10 relative" x-data="{ open: false }">
        <img src="../assets/Snax.svg" alt="">
        <button x-on:click="open = true" class="menu hidden ml-auto inline-flex items-center justify-center p-2 rounded-md text-gray-400 focus:outline-none transition duration-150 ease-in-out" aria-label="Main menu" aria-expanded="false">
            <svg class="block h-10 w-10" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
            </svg>
        </button>
        <div class="nav flex items-center ml-auto">
            <a href="/" class="mx-4 font-semibold text-gray-800">Home</a>
            <a href="/faqs" class="mx-4 font-semibold text-gray-800">FAQs</a>
            <a target="_blank" href="http://snax-api.lazybuy.online/register" class="mx-4 py-3 font-bold px-10 rounded-full" style="background:rgba(252, 150, 4, 0.1); color:#FC9604;">REGISTER</a>
        </div>
        <div x-show.transition="open" x-on:click.away="open = false" class="absolute right-0 left-0 w-full p-4 bg-white border rounded shadow-xl" style="top: 120px;">
            <a href="/" class="transition-colors font-semibold duration-200 block px-4 py-2 text-lg text-gray-900 rounded">Home</a>
            <a href="/faqs" class="transition-colors font-semibold duration-200 block px-4 mb-4 py-2 text-lg text-gray-900 rounded">FAQs</a>
            <a target="_blank" href="http://snax-api.lazybuy.online/register" class="transition-colors duration-200 font-semibold block px-4 py-3 text-lg text-center text-gray-900 rounded-full" style="background:rgba(252, 150, 4, 0.1); color:#FC9604;">REGISTER</a>

        </div>
    </div>
</template>

<style scoped>
@media (min-width: 320px) and (max-width: 480px) {
    .nav{
        display: none;
    }
    .menu{
        display: block;
    }

}
</style>