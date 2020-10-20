<template>
    <div>
        <Nav/>
        <div class="conc p-8 mx-10 mb-8" style="background: rgba(252, 190, 4, 0.1); border-radius: 20px;">
            <p class="text-xl text-center font-bold mb-3 text-black">What is Snax?</p>
            <p class="text-lg text-center max-w-4xl mx-auto font-normal text-gray-800">Snax is a ordering platform where you can get food and drinks anytime. It is also a SaaS product whereby we offer out services to people who need a ordering platform.</p>
        </div>
        <div class="conc p-8 mx-10 mb-8" style="background: rgba(252, 190, 4, 0.1); border-radius: 20px;">
            <p class="text-xl text-center font-bold mb-3 text-black">Where can i get the Snax App?</p>
            <p class="text-lg text-center max-w-4xl mx-auto font-normal text-gray-800">It's available on Google Play Store for now.</p>
        </div>
        <div class="conc p-8 mx-10 mb-8" style="background: rgba(252, 190, 4, 0.1); border-radius: 20px;">
            <p class="text-xl text-center font-bold mb-3 text-black">How do become a vendor?</p>
            <p class="text-lg text-center max-w-4xl mx-auto font-normal text-gray-800">Just <a target="_blank" href="http://snax-api.lazybuy.online/register" style="color: #FC9604;">Register</a> to become a vendor and wait till you're approved.</p>
        </div>
        <div class="conc p-8 mx-10 mb-8" style="background: rgba(252, 190, 4, 0.1); border-radius: 20px;">
            <p class="text-xl text-center font-bold mb-3 text-black">What foods are available?</p>
            <p class="text-lg text-center max-w-4xl mx-auto font-normal text-gray-800">We provide snax from our approved vendors and there are different categories to choose from.</p>
        </div>
        <div class="conc p-8 mx-10 mb-8" style="background: rgba(252, 190, 4, 0.1); border-radius: 20px;">
            <p class="text-xl text-center font-bold mb-3 text-black">How can i pay?</p>
            <p class="text-lg text-center max-w-4xl mx-auto font-normal text-gray-800">You pay through the App on any delivery</p>
        </div>
        <Foot/>
    </div>
</template>

<style scoped>
@media (min-width: 200px) and (max-width: 320px) {
    .conc{
    padding: 20px;
    margin-left: 1rem;
    margin-right: 1rem;
  }
}
@media (min-width: 321px) and (max-width: 500px) {
    .conc{
    padding: 20px;
    margin-left: 1.20rem;
    margin-right: 1.20rem;
  }
}
</style>