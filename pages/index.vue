<template>
  <div>
    <Nav/>
    <div class="blo-ck conc mx-10 p-8 flex items-center" style="background: rgba(252, 190, 4, 0.1); border-radius: 20px;">
      <div class="fullwidth w-1/2 mx-5">
        <p class="head text-4xl max-w-xl font-bold">Order Food & Drinks anytime from your phone</p>
        <p class="sub text-xl max-w-sm font-normal italic mt-4 text-gray-700">hey! Order food/drinks delicious food from our approved vendors around you.</p>
        <div class="blo-ck bl-ock flex mt-8 mb-16">
          <a href="" class="button bg-gray-900 flex items-center py-3 px-4" style="border-radius: 20px;">
            <img src="../assets/appstore.svg" alt="">
            <div class="mx-2">
              <p class="te-xt text-white font-semibold text-xl">App Store</p>
              <p class="text-white font-light text-sm text-center -mt-1">Coming soon!</p>
            </div>
          </a>
          <a href="" class="button bg-gray-900 flex items-center py-3 px-4 mx-3" style="border-radius: 20px;">
            <img src="../assets/googleplay.svg" alt="">
            <div class="mx-2">
              <p class="te-xt text-white font-semibold text-xl">Google Play</p>
            </div>
          </a>
        </div>
      </div>
      <div class="fullwidth w-1/2">
        <img class="mx-auto" src="../assets/img1.svg" alt="">
      </div>
    </div>
    <div class="blo-ck conc mx-10 my-10 p-8 flex items-center height" style="background: rgba(252, 190, 4, 0.1); border-radius: 20px;">
      <div class="w-1/2 fullwidth">
        <img class="mx-auto" src="../assets/img2.svg" alt="">
      </div>
      <div class="w-1/2 fullwidth mx-8 top">
          <p class="head text-4xl max-w-xl font-bold">Save & Quickly order your Foods/Drinks</p>
          <p class="sub text-xl max-w-sm font-normal italic mt-4 text-gray-700">Ordering haven’t felt so simple and easy till you try out snax, save your regular <b style="color:#FC9604">snax</b> and get it right on time.</p>
          <div class="mt-8">
            <a href="" class="midddle bg-gray-900 text-white font-semibold py-4 px-5" style="border-radius: 20px;">Learn more ></a>
          </div>
      </div>
    </div>
    <div class="blo-ck conc pad-ding mx-10 my-10 p-16" style="background: rgba(252, 190, 4, 0.1); border-radius: 20px;">
        <p class="head bottom  text-center text-black font-semibold text-3xl">Want an ordering app like <b style="color: #FC9604;">Snax?</b></p>
        <p class="sub down text-gray-600 mb-8 mt-2" style="text-align: center;">We the developers of Snax would love to offer our <br class="br"> services to you, so you can build your own platform.</p>
        <div class="my-16 " style="margin: 0 auto; text-align: center;">
          <a class="text-center text-white font-bold text-xl py-2 px-6 rounded-full" href="" style="background: #FCBE04;">Get Started</a>
        </div>
    </div>
    <div class="mx-10 conc padding my-48 p-8" style="border-radius: 20px;">
      <p class="head text-center font-bold text-4xl text-gray-800">Vendorship 😊</p>
      <p class="sub text-center my-4 text-gray-700">Want to be an approved vendor and work with us to <br class="br"> satisfy the taste buds of customers?</p>
      <div style="margin: 0 auto; text-align: center; margin-top: 60px;">
        <a href="" class="py-3 px-6 rounded-full font-bold text-xl" style="background: rgba(252, 190, 4, 0.1); color: #FC9604;">REGISTER NOW</a>
      </div>
    </div>
    <Foot/>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
@media (min-width: 200px) and (max-width: 320px) {
  .blo-ck{
    display: block;
  }
  .conc{
    padding: 20px;
    margin-left: 1rem;
    margin-right: 1rem;
  }
  .fullwidth{
    width: 100%;
    margin: 0;
  }
  .head{
    font-size: 1.75rem;
  }
  .sub{
    font-size: 1rem;
  }
  .button{
    width: 200px;
    margin: 20px auto;
  }
  .te-xt{
    font-size: 15px;
  }
  .top{
    margin-top: 40px;
  }
  .midddle{
    margin-bottom: 30px;
  }
  .height{
    height: 700px;
  }
  .br{
    display: none;
  }
  .bottom{
    margin-bottom: 15px;
  }
  .topp{
    margin-top: 50px;
  }
  .hgign{
    height: 400px;
  }
  .down{
    margin-bottom: 30px;
  }
  .padding{
    padding: 20px;
  }
}
@media (min-width: 321px) and (max-width: 500px) {
  .blo-ck{
    display: block;
  }
  .fullwidth{
    width: 100%;
    margin: 0;
  }
  .head{
    font-size: 2.0rem;
  }
  .sub{
    font-size: 1rem;
  }
  .button{
    width: 200px;
    margin: 20px auto;
  }
  .te-xt{
    font-size: 15px;
  }
  .top{
    margin-top: 40px;
  }
  .midddle{
    margin-bottom: 30px;
  }
  .br{
    display: none;
  }
  .bottom{
    margin-bottom: 15px;
  }
  .topp{
    margin-top: 50px;
  }
  .hgign{
    height: 400px;
  }
  .down{
    margin-bottom: 30px;
  }
  .padding{
    padding: 20px;
  }
  .pad-ding{
    padding: 40px;
  }
}
@media (min-width: 501px) and (max-width: 800px) {
  .head{
    font-size: 2rem;
  }
  .conc{
    margin-left: 1rem;
    margin-right: 1rem;
  }
  .fullwidth{
    margin-right: 25px;
    margin-left: 25px;
  }
  .button{
    width: 200px;
    margin: 20px auto;
  }
  .bl-ock{
    display: block;
    margin-right: auto;
  }
  .te-xt{
    font-size: 18px;
  }
}
@media (min-width: 801px) and (max-width: 1024px) {
  .full-width{
    margin-left: 25px;
  }
}
</style>
