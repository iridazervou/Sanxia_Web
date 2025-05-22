<script>
  import logo from '$lib/images/LogoOnly.png';
  import image from '$lib/images/1024x768_attractions-image-wot5dkgorkc6atuknj5qyq 1.png'
  import old_street from '$lib/images/p077sqgy 2.png'
  import temple from '$lib/images/IMG_0191.jpg'
  import workshop from '$lib/images/Workshop.png'
  import map from '$lib/images/Group 26.png'

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
    <img class="brightness-50 mt-6 radius-15" src="{image}" alt="title"/>
    <div class="absolute top-55 right-32">
    <h1 class="text-white text-7xl">Welcome to Sanxia</h1>
    <hr class="my-12 h-px bg-white border-0"/>
    <p class="text-white text-lg w-120 mt-8">Sanxia District,
         located in the southwestern part of New Taipei City,
         Taiwan, is a charming blend of rich history,
          vibrant culture, and natural beauty.</p>
</div>
</div>
<div class="my-15 ml-15">
    <h2 class="text-3xl">Sanxia old street</h2>
    <img class="absolute right-20 top-175 w-110 radius-15" src="{old_street}" alt="old_street">
    <p class="mt-15 mr-155">Sanxia Old Street refers to the south section of Minquan Street in New Taipei City.
         Its length is about two hundred meters, and its architecture dates back
          to the early days when the Republic of China was newly established.
           Walking along Sanxia Old Street is like walking into a time tunnel;
            the arched red brick hallways, the traditional architecture,
             the beams, columns, ancient wooden plaques, the squat maidens walls
              and the figure carvings upon the buildings are all very unique.
               Walking along this ancient street brings a feeling of nostalgia
                for the good old days, and makes visitors want to linger.</p>
                <p class="mt-22">During the time of Sanxia's heyday, the street was lined with shops that sold dyes, manufacturing materials,
                     and tea, and western-style houses were also being built quickly.
                      Nowadays, only the red brick buildings with arched hallways and Baroque
                       styled architecture remain to tell of their past glory.</p>
</div>
<div class="my-15 ml-15">
  <img class="w-100 h-70 absolute radius-15" src="{temple}" alt="temple">
    <h2 class="text-3xl ml-130 mt-20">Quingshui Zushi Temple</h2>
    <p class="mt-15 ml-130 mr-12">Qingshui Zushi (Qingshui Master) Temple was built in 1769. The temple was destroyed by an earthquake in 1833 and was rebuilt in 1867.
       However, during 1895, it was burned down by the Japanese army.
        After World War II, the restoration was led by the renowned artist
         Li Mei Shu. The restored temple presents refined carvings and 
         sculptures and it is the work of Taiwanese artists.</p>
</div>
<div class="relative">
  <h2 class="text-3xl ml-130 mt-40 mx-auto md:mb-8">Indigo dyeing workshops</h2>
    <p class="absolute text-white text-3xl mt-48 mr-80 ml-15">Our Phoenix of Sanxia Workshop offers students a creative space to
 explore various dyeing techniques and express individuality through 
 fabric.
</p>
<hr class="absolute h-px bg-white border-0"/>
<button class="cursor-pointer absolute text-white text-3xl mt-48 right-12 bottom-12">Learn more →</button>
  <img class="w-300 mx-auto md:mb-12" src="{workshop}" alt="workshop">
</div>
<div style="background-color: rgba(127, 95, 74, 1);" class="relative">
  <img class="md:mt-30" src="{map}" alt="map">
  <h3 style="background-color: rgba(127, 95, 74, 1);">Sanxia Map</h3>
  <ol style="background-color: rgba(127, 95, 74, 1);" class="absolute md:right-45">
    <li>Quingshui Zushi Temple</li>
    <li>Sanxia Old Street</li>
    <li>Indigo dyeing center</li>
    <li>Sanxia history museum</li>
    <li>Li Mei-shu Memorial Gallery</li>
  </ol>
  <p></p>
</div>
