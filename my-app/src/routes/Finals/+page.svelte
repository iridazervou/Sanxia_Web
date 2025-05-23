<script>
  import logo from '$lib/images/LogoOnly.png';
  import i2024 from '$lib/images/image 11 (2).png'
  import i13 from '$lib/images/image 13.png'
  import i14 from '$lib/images/image 14.png'

  let Home = ["Home"];
  let Indigo = ["Indigo dyeing center"];
  let Workshop = ["Workshop"];
  let News = ["News"];
</script>

<div class="flex mt-2 pt-2 ml-2">
<img class="w-8 radius-15" src={logo} alt="Logo" />
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
    <img class="brightness-50 mt-6" src="{i2024}" alt="">
    <div class="absolute top-40 md:ml-8 mr-100">
    <h1 class="text-white mt-20 text-5xl">Final Showcase Phoenix of Sanxia Workshop 2024</h1>
    </div>
</div>

<div>
    <h2 class="ml-110 mt-15 mb-8 font-semibold text-xl">Phoenix of Sanxia Workshop 2024 - Final Showcase</h2>
    <p class="ml-20 mr-20 tracking-wide">Creativity, tradition, and color come together in this year's Phoenix of Sanxia Workshop,
         where students have transformed fabric into stunning works of art.
          Through the time-honored techniques of natural dyeing,
           they’ve experimented with patterns, textures,
            and cultural storytelling to bring their visions to life.
Each piece in this collection reflects the dedication, craftsmanship, and creativity
 of our participants—blending tradition with innovation.
  As you browse their creations, immerse yourself in the vibrant hues and intricate
   designs that tell a story of exploration and artistry.
Join us in celebrating the talent and hard work of these budding artists as they
 share their final projects with the world!</p>
</div>

<div class="grid grid-rows-1 grid-cols-2 place-items-center mt-15 mb-8">
    <img class="rounded-xl" src="{i13}" alt="">
    <img class="rounded-xl" src="{i14}" alt="">
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




