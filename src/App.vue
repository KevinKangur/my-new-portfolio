<script setup>
</script>

<template>
  <header class="flex justify-between bg-[#DAFFFB] w-full py-4 px-20 fixed">
    <h1 class="text-[#04364A] text-4xl font-['Poppins'] font-semibold">Kevin Kangur</h1>
    <div class="flex gap-20">
      <a class="text-[#04364A] text-2xl font-['Poppins'] font-medium hover:text-[#176B87]" href="#home">Home</a>
      <a class="text-[#04364A] text-2xl font-['Poppins'] font-medium hover:text-[#176B87]" href="#about">About</a>
      <a class="text-[#04364A] text-2xl font-['Poppins'] font-medium hover:text-[#176B87]" href="#skills">Skills</a>
      <a class="text-[#04364A] text-2xl font-['Poppins'] font-medium hover:text-[#176B87]" href="#work">Work</a>
    </div>

    <div class="flex gap-10">
      <a href="https://twitter.com/kangur_kevin" target="_blank"><img class="w-10" src="src/img/twitter-icon.png" alt=""></a>
      <a href="https://github.com/KevinKangur" target="_blank"><img class="w-10" src="src/img/github-icon.png" alt=""></a>
      <a href="https://www.facebook.com/kevin.kangur.752" target="_blank"><img class="w-10" src="src/img/facebook-icon.png" alt=""></a>
    </div>
  </header>

  <section id="home" class="flex justify-between items-center bg-[#DAFFFB] py-32 px-20">
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

  <section id="about" class="bg-[#DAFFFB] py-20 px-20">
    <div class="flex flex-col gap-4">
      <h1 class="text-[#176B87] text-7xl font-['Poppins'] font-bold">about.</h1>
      <p class="text-[#04364A] text-2xl font-['Poppins']">
        <span class="block">Hello, I'm Kevin Kangur. I'm an 19 year old student, </span>
        <span class="block">studying web development at Kuressaare Ametikool (Kuressaare Regional Training Centre).</span>
        <span class="block">I've been studying software development for a little over two year.</span>
        <span class="block">I'm always ready to learn new things.</span>
      </p>
    </div>
  </section>

  <section id="skills" class="bg-[#DAFFFB] py-20 px-20">
    <div class="flex flex-col gap-20">

      <div>
        <h1 class="text-[#176B87] text-7xl font-['Poppins'] font-bold">skills.</h1>
      </div>

      <div class="grid grid-rows-2 justify-items-center gap-10">

        <div class="row-start-1 grid grid-cols-5 gap-x-10">

          <div class="flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
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
              <img src="src/img/Python.png" alt="">
            </div>
            <div>
              <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold text-center">Python</p>
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

        </div>

        <div class="row-start-2 grid grid-cols-4 gap-x-10">
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
              <img src="src/img/Vitejs.png" alt="">
            </div>
            <div>
              <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold text-center">Vite</p>
            </div>
          </div>

          <div class="flex flex-col items-center bg-[#64CCC5] rounded-[30px] w-40 p-5 justify-between">
            <div>
              <img src="src/img/Laravel.png" alt="">
            </div>
            <div>
              <p class="text-[#04364A] text-2xl font-['Poppins'] font-semibold text-center">Laravel</p>
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

    </div>
  </section>

  <section id="work" class="bg-[#DAFFFB] py-20 px-20">
    <div class="flex flex-col gap-8">

      <div>
        <h1 class="text-[#176B87] text-7xl font-['Poppins'] font-bold">work.</h1>
      </div>

      <div>
        <h2 class="text-[#176B87] text-5xl font-['Poppins'] font-bold">solo projects.</h2>
      </div>

      <div class="grid grid-cols-4 justify-items-center text-[#04364A]">

        <div class="bg-[#64CCC5] rounded-[30px] w-80 p-5">

          <div class="flex flex-col gap-4 h-full font-['Poppins'] justify-between">
            <p class="text-2xl font-semibold text-center">Food App</p>
            <p class="text-xl">Project for class using a Figma design</p>

            <div class="flex gap-4">
              <a href="https://github.com/KevinKangur/food-app" class="text-lg" target="_blank">Github</a>
              <a href="https://www.figma.com/design/HRMPgAMMzdzLn3aFJh5Wny/Proto-For-class?node-id=0-1&node-type=canvas&t=1ds2ArluraPwyqQA-0" class="text-lg" target="_blank">Figma</a>
            </div>

          </div>

        </div>

        <div class="bg-[#64CCC5] rounded-[30px] w-80 p-5">

          <div class="flex flex-col h-full font-['Poppins'] justify-between">
            <p class="text-2xl font-semibold text-center">Books REST API</p>
            <p class="text-xl">REST API practice for class</p>

            <div>
              <a href="https://github.com/KevinKangur/food-app" class="text-lg" target="_blank">Github</a>
            </div>

          </div>

        </div>

        <div class="bg-[#64CCC5] rounded-[30px] w-80 p-5">

          <div class="flex flex-col h-full font-['Poppins'] justify-between">
            <p class="text-2xl font-semibold text-center">AI Startup Tool</p>
            <p class="text-xl">School work for practicing Tailwind CSS</p>

            <div class="flex gap-4">
              <a href="https://github.com/KevinKangur/AI-startup-tool" class="text-lg" target="_blank">Github</a>
              <a href="https://www.figma.com/design/s1DkhIQz2nj6o4yu9YnjlO/Untitled?node-id=0-5&node-type=frame&t=vl8hwKY18CpQsdAO-0" class="text-lg" target="_blank">Figma</a>
            </div>

          </div>

        </div>

        <div class="flex flex-col justify-center">
          <a href="https://github.com/KevinKangur?tab=repositories&q=&type=&language=&sort=" target="_blank">
            <img class="" src="src/img/Arrow.png" alt="">
            <p>My GitHub</p>
          </a>
        </div>

      </div>

      <div>
        <h2 class="text-[#176B87] text-5xl font-['Poppins'] font-bold">group projects.</h2>
      </div>

      <div class="grid grid-cols-3 justify-items-center text-[#04364A]">

        <div class="bg-[#64CCC5] rounded-[30px] w-80 p-5">

          <div class="flex flex-col gap-4 h-full font-['Poppins'] justify-between">
            <p class="text-2xl font-semibold text-center">Baby project</p>
            <p class="text-xl">Group project about first aid for babies</p>

            <div class="flex gap-4">
              <a href="https://beebid.tak21matlik.itmajakas.ee/" class="text-lg" target="_blank">Site</a>
              <a href="https://github.com/markheinmets/Beeeeeebid" class="text-lg" target="_blank">Github</a>
              <a href="https://www.figma.com/design/DDzWd6rIe6t8CDYfI9jyLJ/Beebid_Tiim_3?node-id=0-1&node-type=canvas&t=jtAtKcA481TRikKo-0" class="text-lg" target="_blank">Figma</a>
            </div>

          </div>

        </div>

        <div class="bg-[#64CCC5] rounded-[30px] w-80 p-5">

          <div class="flex flex-col h-full font-['Poppins'] justify-between">
            <p class="text-2xl font-semibold text-center">Space Invaders game</p>
            <p class="text-xl">Class group project where we made Space Invaders</p>

            <div>
              <a href="https://github.com/StevenAltmae/Project-invaders" class="text-lg" target="_blank">Github</a>
            </div>

          </div>

        </div>

        <div class="bg-[#64CCC5] rounded-[30px] w-80 p-5">

          <div class="flex flex-col h-full font-['Poppins'] justify-between">
            
            <p class="text-2xl font-semibold text-center">AI Startup Tool</p>
            <p class="text-xl">School work for practicing Tailwind CSS</p>

            <div class="flex gap-4">
              <a href="https://tak21aavik.itmajakas.ee/KAK100/index.html" class="text-lg" target="_blank">Site</a>
              <a href="https://github.com/sander-aleks/KAK100Portfolio" class="text-lg" target="_blank">Github</a>
              <a href="https://www.figma.com/design/A7QbEvQccutgwBl1vWuL6v/KAK100PORTFOOLIO-team-library?node-id=0-1&node-type=canvas&t=ksZjuzICrrEJtieB-0" class="text-lg" target="_blank">Figma</a>
            </div>

          </div>

        </div>

      </div>

    </div>
  </section>

</template>