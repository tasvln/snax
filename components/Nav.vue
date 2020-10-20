<template>
    <div class="flex items-center p-10">
        <img src="../assets/Snax.svg" alt="">
        <div class="nav flex items-center ml-auto">
            <a href="/" class="mx-4 font-semibold text-gray-800">Home</a>
            <a href="/faqs" class="mx-4 font-semibold text-gray-800">FAQs</a>
            <a target="_blank" href="http://snax-api.lazybuy.online/register" class="mx-4 py-3 font-bold px-10 rounded-full" style="background:rgba(252, 150, 4, 0.1); color:#FC9604;">REGISTER</a>
        </div>
    </div>
</template>

<style scoped>
@media (min-width: 320px) and (max-width: 480px) {
    .nav{
        display: none;
    }
}
</style>