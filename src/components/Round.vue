<script setup>
</script>

<template>
  <div id="round" class="relative w-full mb-5">
    <div class="absolute h-5 bg-lime-300 rounded-full bar1 opacity-40"></div>
    <div class="absolute h-5 bg-lime-300 rounded-full bar2 opacity-70"></div>
    <div class="absolute h-5 bg-lime-300 rounded-full bar3 "></div>

    <div class="relative bg-slate-600 rounded-lg flex justify-between mx-5 py-5 px-3 top-5">
      <div class="flex items-center">
        <img src="../assets/imgs/edit.png" class="w-12 h-12" alt="edit icon">
        <div class="uppercase font-bold text-white ml-2">quick <br> eidt</div>
      </div>
      <div class="flex flex-row-reverse items-center">
        <img src="../assets/imgs/close.png" class="w-12 h-12" alt="edit icon">
        <div class="uppercase font-bold text-white mr-2 text-right">exit <br> game</div>
      </div>
    </div>

    <div class="absolute w-full h-16 top-16">
      <div class="absolute arc bg-black -top-8"></div>
      <div class="absolute rect bg-black"></div>
    </div>

    <div class="absolute w-full h-16 top-16 z-10 scale-95">
      <div class="absolute arc bg-slate-600 -top-7"></div>
      <div class="absolute rect bg-slate-600 top-1"></div>
    </div>

    <div id="period" class="absolute rounded-sm shadow-2xl shadow-slate-900 bg-gradient-to-b from-slate-400 via-30% via-slate-300 to-slate-400 -top-1 h-16 text-4xl font-bold italic bg-gray-200 w-64 flex justify-center uppercase">
      Period
      <div class="bg-slate-950 text-white h-full flex justify-center font-bold w-8">1</div>
    </div>

    <div class="absolute w-full flex justify-center items-center top-12 z-20 p-2">
      <div class="poss-left p-1">
        <img src="../assets/imgs/poss-right-default.png" class="h-12 w-full" alt="">
      </div>
      <div class="elapsed text-5xl font-bold w-64 text-center text-white bg-yellow-800 px-1">02:22</div>
      <div class="poss-right p-1">
        <img src="../assets/imgs/poss-left-default.png" class="h-12 w-full" alt="">
      </div>
    </div>

  </div>
</template>

<style scoped>
  .bar1 {
    width: calc(100% - 4rem);
    left: 2rem;
  }
  .bar2 {
    width: calc(100% - 5rem);
    left: 2.5rem;
  }
  .bar3 {
    width: calc(100% - 6rem);
    left: 3rem;
  }
  #period {
    left: calc(50% - 8rem);
  }
  .arc {
    width: calc(100% - 24rem);
    left: 12rem;
    height: 100%;
    border-radius: 50%;
  }
  .rect {
    width: calc(100% - 24rem);
    left: 12rem;
    height: 100%;
  }
  .poss-left {
    width: calc(50% - 22rem);
    /* background-repeat: no-repeat;
    background-size: cover;
    background-image: url('../assets/imgs/poss-right-default.png'); */
  }
  .poss-right {
    width: calc(50% - 22rem);
    /* background-repeat: no-repeat;
    background-size: cover;
    background-image: url('../assets/imgs/poss-left-default.png'); */
  }
</style>
