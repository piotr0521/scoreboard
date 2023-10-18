<script setup>
</script>

<template>
  <div id="team" class="mt-4 z-10 w-full px-5">
    <div class="flex text-4xl font-bold">
      <div class="flex basis-1/2 border-4 border-slate-400 rounded-lg mr-1">
        <div class="uppercase flex-1 p-3 bg-red-800 text-white font-bold shadow-inner">westside</div>
        <div class="uppercase w-16 p-3 text-center bg-gradient-to-b from-slate-400 via-30% via-slate-300 to-slate-400">10</div>
      </div>
      <div class="flex flex-row-reverse basis-1/2 border-4 border-slate-400 rounded-lg ml-1">
        <div class="uppercase flex-1 p-3 bg-blue-800 text-white font-bold text-end shadow-inner">northwest</div>
        <div class="uppercase w-16 p-3 text-center bg-gradient-to-b from-slate-400 via-30% via-slate-300 to-slate-400">10</div>
      </div>
    </div>
  </div>
  <div id="now-display">
    <div class="grid grid-rows-2 grid-cols-4 grid-flow-col gap-y-2 p-2 pb-5 rounded-md">
      <div class="col-span-1 border-b-2 uppercase font-bold text-lg text-lime-300">now dispalying:</div>
      <div class="col-span-2 text-white">Press the "Start Clock" button to continue.</div>
      <div class="col-span-1 border-b-2 uppercase text-center font-bold text-2xl text-white italic">scoreboard</div>
      <div class="row-span-2 col-span-1"></div>
      <div class="row-span-2 col-span-1 flex">
        <div class="border-4 rounded-md flex-1 mr-1"></div>
        <div class="border-4 rounded-md flex-1 ml-1"></div>
      </div>
    </div>
  </div>
  <div id="btn-list" class="flex p-3">
    <div class="uppercase text-2xl text-white font-bold mx-3">QUICK</div>
    <div class="font-bold border-2 text-white text-center rounded-md w-24 ml-2 p-1">test button</div>
    <div class="font-bold border-2 text-white text-center rounded-md w-24 ml-2 p-1">button 1</div>
    <div class="font-bold border-2 text-white text-center rounded-md w-24 ml-2 p-1">button 2</div>
  </div>
</template>

<style scoped>
#now-display {
  width: calc(100% - 15rem);
  background: #475569;
}
#btn-list {
  width: calc(100% - 15rem);
  background: #3a414c;
  border-radius: 0 0 10px 10px;
}
</style>
