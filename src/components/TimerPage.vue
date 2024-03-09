<template>
  <div class="flex flex-col h-screen w-full bg-priamry">
    <div class="w-full h-32 flex items-center">
      <div class="text-white text-xl pl-4 font-semibold hover:cursor-pointer">PLAY - TINO</div>
    </div>
    <div class="w-full h-60 flex justify-center items-center">
      <div class="flex items-baseline">
        <div class="text-4xl md:text-5xl lg:text-7xl text-timer-stop font-extrabold text-outline">정각을</div>
        <div class="text-xl md:text-2xl lg:text-4xl text-white font-bold">맞춰라!</div>
      </div>
    </div>
    <div class="w-full h-full flex items-start justify-center">
      <div class="bg-white min-h-80 py-7 h-auto w-9/12 rounded-2xl flex flex-col justify-center items-center gap-6">
        <div class="text-4xl md:text-5xl lg:text-7xl text-timer-stop">06.00</div>
        <div class="w-8/12 h-40 bg-timer-bg rounded-2xl border-priamry border-4 flex items-center justify-center">
          <div class="text-8xl">02.38</div>
        </div>
        <div class="flex justify-center gap-4">
          <div class="w-24 h-12 hover:bg-timer-start hover:text-white text-timer-start border-timer-start border-2 flex items-center justify-center rounded-md mx-4">
            <div class="text-2xl font-semibold hover:cursor-pointer">START</div>
          </div>
          <div class="w-24 h-12 bg-timer-stop text-white flex items-center justify-center rounded-md mx-4">
            <div class="text-2xl font-semibold hover:cursor-pointer">STOP</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data() { 
      return {
      }
    }
  }
</script>

<style scoped>
.text-outline {
  text-shadow:
    -1px -1px 0 white, 1px -1px 0 white,
    -1px 1px 0 white, 1px 1px 0 white,
    0px -2px 0 white, 0px 2px 0 white,
    -2px 0px 0 white, 2px 0px 0 white,
    -2px -2px 0 white, 2px -2px 0 white,
    -2px 2px 0 white, 2px 2px 0 white,
    -1px -2px 0 white, 1px -2px 0 white,
    -1px 2px 0 white, 1px 2px 0 white,
    -2px -1px 0 white, 2px -1px 0 white,
    -2px 1px 0 white, 2px 1px 0 white;
}
</style>