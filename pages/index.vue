<template>
  <div>
    <div class="first-sec">
      <Nav />
      <div class="flex items-center blo-ck mx-10 my-10">
        <div class="w-1/2 full-width">
          <div class="my-6">
            <img src="../assets/emoji1.svg">
          </div>
          <div class="my-6">
            <p class="font-extrabold mid-text text-5xl full-width-max max-w-lg my-4">Food + Ordering Platform Template For Startups</p>
            <p class="italic text-lg max-w-sm my-4">With our already made template, you can get your own ordering platform on both Web and Mobile.</p>
          </div>
        </div>
        <div class="w-1/2 full-width">
            <img src="../assets/img1.png" class="mx-auto img" style="max-width: 500px;" />
        </div>
      </div>
    </div>
    <div class="mx-10 my-32">
      <div>
        <p class="text-4xl font-bold my-4 text-center mid-text full-width-max max-w-lg mx-auto">Get An App + A Dashboard To Manage Your Startup</p>
        <p class="italic text-lg max-w-lg my-4 text-center mx-auto te-xt-left">Your app comes with a dashboard that meets with the needs of your startup</p>
      </div>
      <div class="my-16">
        <img src="../assets/dashboard.svg" class="mx-auto img" style="max-width: 900px" />
      </div>
    </div>
    <div class="mx-10 my-10">
      <p class="text-4xl font-bold my-10 text-center mid-text">How it works?</p>
      <div class="flex blo-ck card-box -mx-8">
        <div class="w-1/3 cards my-10 full-width p-10 mx-8" style="background: rgba(252, 190, 4, 0.1); border-radius: 30px;">
          <div>
            <img src="../assets/emoji2.svg" />
          </div>
          <div class="mt-4">
            <p class="text-2xl font-bold my-4 max-w-xs">Get started by filling up the form</p>
            <p class="italic text-lg max-w-xs my-4">Fill up a short form so we can know what you want to be build.</p>
          </div>
        </div>
        <div class="w-1/3 cards my-10 full-width p-10 mx-8" style="background: rgba(252, 190, 4, 0.1); border-radius: 30px;">
          <div>
            <img src="../assets/emoji3.svg" />
          </div>
          <div class="mt-4">
            <p class="text-2xl font-bold my-4 max-w-xs">Get an email from the team</p>
            <p class="italic text-lg max-w-xs my-4">Get a response from the team to know the next steps to be taken</p>
          </div>
        </div>
        <div class="w-1/3 cards my-10 full-width p-10 mx-8" style="background: rgba(252, 190, 4, 0.1); border-radius: 30px;">
          <div>
            <img src="../assets/emoji4.svg" />
          </div>
          <div class="mt-4">
            <p class="text-2xl font-bold my-4 max-w-xs">Leave the rest to us</p>
            <p class="italic text-lg max-w-xs my-4">Just kick back and relax, we’d handle the rest from here!</p>
          </div>
        </div>
      </div>
    </div>
    <div class="p-8 my-40 mx-10 flex blo-ck items-center" style="background: rgba(252, 190, 4, 0.1); border-radius: 30px;">
      <img src="../assets/mockup.svg" class="-mt-24 cards cards-1 mr-auto mx-10">
      <div class="gts">
        <p class="font-light text-3xl mid-text">Get started now and</p>
        <p class="font-bold text-3xl mid-text">Build your Startup Seemlessly</p>
      </div>
      <NuxtLink to="/getstarted" class="py-3 font-bold text-2xl px-8 rounded-full ml-auto bg-white norm-text" style="color:#FC9604;">GET STARTED</NuxtLink>
    </div>
    
    <Foot/>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
.first-sec{
  background: linear-gradient(180deg, rgba(252, 190, 4, 0.1) 0%, rgba(255, 255, 255, 0) 108.88%);
  height: 100%;
}
@media (min-width: 200px) and (max-width: 320px) {
  .blo-ck{
    display: block;
  }
  .mid-text{
    font-size: 1.75rem;
    text-align: left;
  }
  .te-xt-left{
    text-align: left;
  }
  .full-width{
    width: 100%;
  }
  .full-width-max{
    max-width: 100%;
  }
  .img{
    max-width: 100% !important;
    margin: 40px 0;
  }
  .cards{
    margin-left: 0px;
    margin-right: 0px;
  }
  .card-box{
    margin-left: 0px;
    margin-right: 0px;
  }
  .norm-text{
    font-size: initial;
  }
  .gts{
    margin: 40px 0;
  }
}
@media (min-width: 321px) and (max-width: 699px) {
  .blo-ck{
    display: block;
  }
  .mid-text{
    font-size: 1.75rem;
    text-align: left;
  }
  .te-xt-left{
    text-align: left;
  }
  .full-width{
    width: 100%;
  }
  .full-width-max{
    max-width: 100%;
  }
  .img{
    max-width: 100% !important;
    margin: 40px 0;
  }
  .cards{
    margin-left: 0px;
    margin-right: 0px;
  }
  .card-box{
    margin-left: 0px;
    margin-right: 0px;
  }
  .norm-text{
    font-size: initial;
  }
  .gts{
    margin: 40px 0;
  }
}
@media (min-width: 700px) and (max-width: 1000px) {
  .blo-ck{
    display: block;
  }
  .mid-text{
    font-size: 1.75rem;
    text-align: left;
  }
  .te-xt-left{
    text-align: left;
  }
  .full-width{
    width: 100%;
  }
  .img{
    max-width: 500px !important;
    margin: 40px auto;
  }
  .cards{
    margin-left: 0px;
    margin-right: 0px;
  }
  .card-box{
    margin-left: 0px;
    margin-right: 0px;
  }
  .norm-text{
    font-size: initial;
  }
  .gts{
    margin: 40px 0;
  }
}
@media (min-width: 1000px) and (max-width: 1024px) {
  .cards-1{
    margin-left: 0px;
    margin-right: 0px;
  }
  .norm-text{
    font-size: initial;
  }
}
</style>
