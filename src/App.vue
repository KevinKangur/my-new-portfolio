<script setup>
</script>

<template>
  <header class="flex justify-between bg-[#DAFFFB] py-10 px-20">
    <h1 class="text-[#04364A] text-4xl font-['Poppins'] font-semibold">Kevin Kangur</h1>
    <div class="flex gap-20">
      <a class="text-[#04364A] text-2xl font-['Poppins'] font-medium hover:text-[#176B87]" href="#">Home</a>
      <a class="text-[#04364A] text-2xl font-['Poppins'] font-medium hover:text-[#176B87]" href="#">About</a>
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
    <div>
      <div>
        <h1 class="text-[#176B87] text-7xl font-['Poppins'] font-bold">work.</h1>
      </div>
      <div class="flex flex-col gap-8">
        <div>
          <h2 class="text-[#176B87] text-5xl font-['Poppins'] font-bold">HTML and CSS</h2>
        </div>
        <div>
          <h2 class="text-[#176B87] text-5xl font-['Poppins'] font-bold">Tailwind CSS</h2>
        </div>
        <div>
          <h2 class="text-[#176B87] text-5xl font-['Poppins'] font-bold">JavaScript</h2>
        </div>
        <div>
          <h2 class="text-[#176B87] text-5xl font-['Poppins'] font-bold">Python</h2>
        </div>
        <div>
          <h2 class="text-[#176B87] text-5xl font-['Poppins'] font-bold">PHP</h2>
        </div>
        <div>
          <h2 class="text-[#176B87] text-5xl font-['Poppins'] font-bold">Vue</h2>
        </div>
        <div>
          <h2 class="text-[#176B87] text-5xl font-['Poppins'] font-bold">React</h2>
        </div>
      </div>
    </div>
  </section>
</template>