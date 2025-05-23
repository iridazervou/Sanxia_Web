<script>
  import logo from '$lib/images/LogoOnly.png';
  import title from '$lib/images/IMG_0179 2.png'
  import photo1 from '$lib/images/IMG_0169 1.png'
  import photo2 from '$lib/images/5f1ff34e5d67f197608677 1.png'
  import photo3 from '$lib/images/IMG_0167 1.png'
  import workshop from '$lib/images/Workshop.png'

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
   <img class="brightness-50 mt-6" src="{title}" alt="indigo">
 <div class="absolute top-55 md:ml-18">
  <h1 class="text-white text-7xl" >Sanxia’s indigo dyeing center</h1>
  <hr class="my-12 h-px bg-white border-0">
  <p class="text-white text-lg w-120 mt-8">A very important cultural hub in Sanxia
     district dedicated in preserving and promoting
      the regions tradition.</p>
 </div>
</div>
<div>
  <h2 class="text-3xl ml-110 mt-12">The Indigo dyeing center in Sanxia</h2>
  <p class="mt-15 ml-10 mr-10">The Sanxia Indigo Dyeing Centre is a cultural hub in Sanxia District,
     New Taipei City, dedicated to preserving and promoting the region's rich indigo dyeing heritage.
      Once known as "Dyeing Street" during the late Qing Dynasty, Sanxia was a prominent center for indigo dyeing,
       utilizing the local plant Strobilanthes formosanus to produce vibrant blue textiles .</p>
       <p class="mt-5 ml-10 mr-10">Established by Liu Yong-feng, a native of Sanxia with a passion for his town's cultural legacy,
         the centre offers visitors a chance to engage in hands-on indigo dyeing experiences.
         In addition to the workshops, the centre features a shop showcasing a variety of indigo-dyed products,
          from clothing to accessories, all crafted using time-honored methods.</p>
          <p class="mt-5 ml-10 mr-10 mb-12">For those interested in exploring this unique aspect of Taiwanese heritage,
             the Sanxia Indigo Dyeing Centre offers an enriching and creative experience,
              connecting the past with the present through the art of indigo dyeing.</p>
</div>
<div style="background-color: rgba(98, 120, 144, 1);" class=" place-items-center pt-12 pb-12 grid grid-rows-1 grid-cols-3">
  <img class="w-60 ml-5" src="{photo3}" alt="">
  <img class="w-80" src="{photo2}" alt="">
  <img class="w-60" src="{photo1}" alt="">
</div>
<div class="grid grid-rows-1 grid-cols-2 mt-15 mb-20 place-items-center">
  <div class="">
    <h2 class="text-3xl mt-8 place-self-center mb-8">Indigo dyeing workshops</h2>
    <p class="ml-35 mr-20">This workshop is perfect for students interested in art,
     fashion, sustainability, or simply looking to try something new.
      No prior experience is necessary—just bring your enthusiasm and
       curiosity!</p>
  </div>
  <div class="relative">
    <a href="/Workshop" class="absolute text-white top-15 left-28 text-xl font-bold hover:opacity-70">Workshop availability →</a>
    <img class="w-100 place-self-center" src="{workshop}" alt="">
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