<script setup>
</script>

<template>
  <header class="flex justify-between bg-[#DAFFFB] py-10 px-20">
    <h1 class="text-[#04364A] text-4xl font-['Poppins'] font-semibold">Kevin Kangur</h1>
    <div class="flex gap-20">
      <a class="text-[#04364A] text-2xl font-['Poppins'] font-medium hover:text-[#176B87]" href="#">Home</a>
      <a class="text-[#04364A] text-2xl font-['Poppins'] font-medium hover:text-[#176B87]" href="#">About</a>
      <a class="text-[#04364A] text-2xl font-['Poppins'] font-medium hover:text-[#176B87]" href="#">Skills</a>
      <a class="text-[#04364A] text-2xl font-['Poppins'] font-medium hover:text-[#176B87]" href="#">Work</a>
    </div>
    <div class="flex gap-10">
      <a href="https://twitter.com/kangur_kevin"><img class="w-10" src="src/img/twitter-icon.png" alt=""></a>
      <a href="https://github.com/KevinKangur"><img class="w-10" src="src/img/github-icon.png" alt=""></a>
      <a href="#"><img class="w-10" src="src/img/facebook-icon.png" alt=""></a>
    </div>
  </header>

  <section class="flex justify-between items-center bg-[#DAFFFB] py-32 px-20">
    <div class="flex flex-col gap-3">
      <p class="text-[#04364A] text-3xl font-['Poppins'] font-medium">Hello, I'm Kevin</p>
      <h1 class="text-[#04364A] text-7xl font-['Poppins'] font-bold">
        <span class="block">Web</span>
        <span class="block">Developer</span>
      </h1>
      <p class="text-[#04364A] text-3xl font-['Poppins'] font-medium">based in Estonia, Saaremaa</p>
    </div>
    <div>
      <img class="w-[450px] rounded-[50%]" src="src/img/Nimetu.png" alt="">
    </div>
  </section>
  <section class="bg-[#DAFFFB] py-20 px-20">
    <div class="flex flex-col gap-4">
      <h1 class="text-[#176B87] text-7xl font-['Poppins'] font-bold">about.</h1>
      <p class="text-[#04364A] text-2xl font-['Poppins']">
        <span class="block">Hello, I'm Kevin Kangur. I'm an 18 year old student, </span>
        <span class="block">studying web development at Kuressaare Ametikool (Kuressaare Regional Training Centre).</span>
        <span class="block">I've been studying software development for a little over an year.</span>
        <span class="block">I'm always ready to learn new things.</span>
      </p>
    </div>
  </section>
  <section class="bg-[#DAFFFB] py-20 px-20">
    <div class="flex flex-col gap-20">
      <div>
        <h1 class="text-[#176B87] text-7xl font-['Poppins'] font-bold">skills.</h1>
      </div>
      <div class="grid grid-cols-9 grid-rows-2 justify-items-center gap-10">
        <div class="col-start-2 flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
          <div>
            <img src="src/img/HTML5.png" alt="">
          </div>
          <div>
            <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold">HTML</p>
          </div>
        </div>
        <div class="flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
          <div>
            <img src="src/img/CSS3.png" alt="">
          </div>
          <div>
            <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold">CSS</p>
          </div>
        </div>
        <div class="flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
          <div>
            <img src="src/img/JavaScript.png" alt="">
          </div>
          <div>
            <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold">JavaScript</p>
          </div>
        </div>
        <div class="flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
          <div>
            <img src="src/img/Tailwind.png" alt="">
          </div>
          <div>
            <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold text-center">Tailwind</p>
          </div>
        </div>
        <div class="flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
          <div>
            <img src="src/img/Python.png" alt="">
          </div>
          <div>
            <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold text-center">Python</p>
          </div>
        </div>
        <div class="flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
          <div>
            <img src="src/img/MySQL.png" alt="">
          </div>
          <div>
            <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold text-center">MySQL</p>
          </div>
        </div>
        <div class="flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
          <div>
            <img src="src/img/PHP.png" alt="">
          </div>
          <div>
            <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold text-center">PHP</p>
          </div>
        </div>
        <div class="col-start-4 flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
          <div>
            <img src="src/img/Vitejs.png" alt="">
          </div>
          <div>
            <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold text-center">Vite</p>
          </div>
        </div>
        <div class="flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
          <div>
            <img src="src/img/NodeJS.png" alt="">
          </div>
          <div>
            <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold text-center">Node</p>
          </div>
        </div>
        <div class="flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
          <div>
            <img src="src/img/Vue.png" alt="">
          </div>
          <div>
            <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold text-center">Vue</p>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="bg-[#DAFFFB] py-20 px-20">
    <div class="flex flex-col gap-8">
      <div>
        <h1 class="text-[#176B87] text-7xl font-['Poppins'] font-bold">work.</h1>
      </div>
      <div>
        <h2 class="text-[#176B87] text-5xl font-['Poppins'] font-bold">recent works.</h2>
      </div>
      <div>
        <div class="bg-[#64CCC5]">

        </div>
      </div>
    </div>
  </section>
</template>