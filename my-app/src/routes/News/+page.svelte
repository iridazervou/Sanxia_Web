   <script>
    import logo from '$lib/images/LogoOnly.png'
    import image from '$lib/images/1024x768_attractions-image-wot5dkgorkc6atuknj5qyq 1.png'
    import i2023 from '$lib/images/Group 26 (1).png'
    import i2024 from '$lib/images/Group 27.png'
    import Insta from '$lib/images/Instagram.png'

    let Home = ["Home"];
    let Indigo = ["Indigo dyeing center"];
    let Workshop = ["Workshop"];
    let News = ["News"];
    </script>

    <div class="flex mt-2 pt-2 ml-2">
     <img class="w-8" src={logo} alt="Logo" />
     <h1 class="self-center font-semibold text-2xl">Phoenic of Sanxia</h1>
     <div class="absolute md:ml-200 self-center">
  <ul class="flex space-x-12">
    <li><a href="/Home" class="hover:opacity-50">{Home}</a></li>
    <li><a href="/Indigo" class="hover:opacity-50">{Indigo}</a></li>
    <li><a href="/Workshop" class="hover:opacity-50">{Workshop}</a></li>
    <li><a href="/News" class="hover:opacity-50">{News}</a></li>
  </ul>
</div>
</div>

<div class="relative">
  <img class="brightness-50 mt-6 radius-15" src="{image}" alt="">
  <div class="absolute top-55 right-32">
  <h1 class="text-white text-7xl">Latest News</h1>
  <hr class="my-12 h-px bg-white border-0">
  <p class="text-white text-lg w-120 mt-8">A page dedicated in staying
     up tp date with the latest news in Sanxia.</p>
  </div>
</div>

<div class="grid grid-rows-2 grid-cols-0 place-items-center gap-15 mt-18 mb-12">
  <div class="relative">
    <a href="/Finals" class="absolute text-white text-2xl mt-35 ml-10 hover:opacity-70">Final Showcase Phoenix of Sanxia Workshop 2024</a>
    <img class="w-210" src="{i2024}" alt="">
  </div>
  <div class="relative">
   <p class="absolute text-white text-2xl mt-35 ml-10">Final Showcase Phoenix of Sanxia Workshop 2023</p>
   <img class="w-210" src="{i2023}" alt="">
  </div>
</div>

<footer style="background-color: rgba(127, 95, 74, 1);" class="text-white py-4 px-3 mt-16">
    <div class="container mx-auto flex flex-wrap items-center justify-between">
        <div class="w-full md:w-1/2 md:text-center md:mb-0 mb-8">
            <p class="text-xs text-gray-200 md:text-sm">Copyright 2025 &copy; All Rights Reserved</p>
        </div>
        <div class="w-full md:w-1/2 md:text-center md:mb-0 mb-8">
            <ul class="list-reset flex justify-center flex-wrap text-xs md:text-sm gap-3">
                <li><a href="https://www.instagram.com/phoenix_of_sanxia/" class="text-gray-200 hover:text-white">Follow on Instagram</a></li>
            </ul>
        </div>
    </div>
</footer>

