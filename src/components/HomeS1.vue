<template>
  <div class="section1 h-screen flex flex-col items-start sm:items-center md:flex-row text-left overflow-x-hidden">
     <div class="flex-1 px-12 md:px-10 lg:px-20 order-2 md:order-1 mt-16">
       <img class="absolute top-1 left-1 h-8 md:h-10" src="../assets/images/Navlogo.png"/>
       <p class="text-xs text-hiveaccent1 font-bold">GET STARTED</p>
       <h1 class="mt-1 md:mt-0 font-extrabold text-3xl sm:text-4xl lg:text-5xl">Show yourself &amp; </h1>
       <h1 class="font-extrabold text-3xl sm:text-4xl lg:text-5xl">Get Hired</h1>
       <button class="mt-2 bg-hiveaccent1 hover:text-hiveaccent2 text-hiveprimary1 font-bold py-2 px-4 rounded"><p>Sign Up for Free</p></button>
     </div>
     <div class="flex-1 flex flex-col self-center order-1 md:order-2">
       <img class="img1" src="../assets/images/section1.png"/>
     </div>
  </div>
</template>

<script>
export default {
  name: 'HomeS1'
}
</script>

<style scoped>
.img1{
  height:60vh;
  min-width: 400px;
  object-fit: contain;
}
@media (max-width:976px){
  .img1{
    height:50vh;
  }
}
@media (max-width:728px){
  .img1{
    padding-top:15vh;
    margin-bottom: 5vh;
  }
}
</style>
