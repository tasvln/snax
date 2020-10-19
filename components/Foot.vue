<template>
    <footer class="p-10 m-8 conc" style="background: rgba(252, 190, 4, 0.1); border-radius: 20px;">
        <div class="blo-ck flex items-center">
            <img class="img" src="../assets/Snax.svg" alt="">
            <div class="icon-bar flex items-center -mx-3 ml-auto">
                <a href="" class="mx-3"><img src="../assets/in.svg" alt=""></a>
                <a href="" class="mx-3"><img src="../assets/twitter.svg" alt=""></a>
                <a href="" class="mx-3"><img src="../assets/instagram.svg" alt=""></a>
            </div>
        </div>
        <div class="blo-ck flex items-center my-10">
            <div class="bottom">
                <p class="font-semibold cen-ter text-lg my-3 text-gray-700">DOWNLOAD THE APP</p>
                <div class="blo-ck flex items-center">
                    <a href="" class="button bg-gray-900 flex items-center py-3 px-4" style="border-radius: 20px;">
                        <img src="../assets/appstore.svg" alt="">
                        <div class="mx-2">
                        <p class="text-white te-xt font-semibold text-lg">App Store</p>
                        <p class="text-white font-light text-sm text-center -mt-1">Coming soon!</p>
                        </div>
                    </a>
                    <a href="" class="button goo-gle bg-gray-900 flex items-center py-3 px-4 mx-3" style="border-radius: 20px;">
                        <img src="../assets/googleplay.svg" alt="">
                        <div class="mx-2">
                        <p class="text-white te-xt font-semibold text-lg">Google Play</p>
                        </div>
                    </a>
                </div>
            </div>
            <div class="blo-ck cen-ter flex top items-center ml-auto -mx-4">
                <p><a class="font-bold mx-4 text-gray-800 text-xl" href="">Faqs</a></p>
                <p class="top"><a class="font-bold mx-4 text-gray-800 text-xl" href="">Become a vendor</a></p>
                <p class="top"><a class="font-bold mx-4 text-gray-800 text-xl" href="">T&Cs</a></p>
            </div>
        </div>
        <p class="text-center font-medium mt-12" style="color:#FC9604;">© 2020 - Snax</p>
    </footer>
</template>

<style scoped>
@media (min-width: 200px) and (max-width: 320px) {
  .blo-ck{
      display: block;
  }
  .img{
      margin: 0 auto;
      margin-top: 30px;
  }
  .icon-bar{
      margin: 0 auto;
      margin-top: 40px;
      justify-content: center;
  }
  .goo-gle{
      margin: 20px 0;
  }
  .cen-ter{
      text-align: center;
  }
  .te-xt{
      font-size: 15px;
  }
  .top{
      margin-top: 10px;
  }
  .bottom{
      margin-bottom: 40px;
  }
  .conc{
    padding: 20px;
    margin-left: 1rem;
    margin-right: 1rem;
  }
  .button{
      width: 200px;
      margin: 20px auto;
  }
}
@media (min-width: 321px) and (max-width: 500px) {
  .blo-ck{
      display: block;
  }
  .img{
      margin: 0 auto;
      margin-top: 30px;
  }
  .icon-bar{
      margin: 0 auto;
      margin-top: 40px;
      justify-content: center;
  }
  .goo-gle{
      margin: 20px 0;
  }
  .cen-ter{
      text-align: center;
  }
  .te-xt{
      font-size: 18px;
  }
  .top{
      margin-top: 10px;
  }
  .button{
      width: 200px;
      margin: 20px auto;
  }
  .bottom{
      margin-bottom: 40px;
  }
}
@media (min-width: 501px) and (max-width: 800px) {
  .blo-ck{
      display: block;
  }
  .img{
      margin: 0 auto;
  }
  .icon-bar{
      margin: 0 auto;
      margin-top: 40px;
      justify-content: center;
  }
  .goo-gle{
      margin: 20px 0;
  }
  .cen-ter{
      text-align: center;
  }
  .te-xt{
      font-size: 18px;
  }
  .top{
      margin-top: 10px;
  }
  .button{
      width: 200px;
      margin: 20px auto;
  }
  .bottom{
      margin-bottom: 40px;
  }
}
</style>