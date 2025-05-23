   <script>

    import logo from '$lib/images/LogoOnly.png'
    import dye from '$lib/images/dye.png'
    import group from '$lib/images/06_11_49 1.png'
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
    <img class="brightness-50 mt-6" src="{dye}" alt="">
    <div class="absolute top-40 md:ml-18 mr-100">
    <h1 class="text-white text-5xl">Keeping tradition alive with the Phoenix of Sanxia Workshop</h1>
    <hr class="my-12 h-px bg-white border-0">
    <p class="text-white text-lg w-120 mt-8">A Workshop focusing on creativity,
         craftmanship and cultural preservation.</p>
    </div>
</div>

<div>
    <h2 class="text-3xl ml-110 mt-12">Phoenix of Sanxia Workshop</h2>
    <p class="mt-15 ml-20 mr-20">This 12 week residency offers fashion design students
         the opportunity to learn traditional Indigo dyeing techniques
          in Sanxia and incorporate them into conteporary fashion.
           Over the course of the program, each participant will create
            two complete fashion looks, starting with faric dyeing
             and mooving through the entire design and garment construction
              process. At the end of the porgram, students will present their
               finished garments, wich will be elidgeble for display and sale
                at local shops in Sanxia.</p>
                <img class="mt-15 mx-auto w-240 rounded-lg" src="{group}" alt="">
</div>

<div class="grid grid-rows-1 grid-cols-2 place-items-center mt-8">
    <div>
    <h2 class="text-2xl">Each student will:</h2>
    <ul>
        <li class="mb-1">Learn 5-7 indigo dyeing techniqeus</li>
        <li class="mb-1">Create 1-2 complete fashion looks </li>
        <li class="mb-1">Receive 3 credits</li>
        <li class="mb-1">Receive a certificate of completion & digital portfolio</li>
    </ul>
    </div>
    <div>
        <h2 class="text-2xl">Universities that we collaborate with:</h2>
     <ul>
        <li class="mb-1">National Taiwan University of Science and Technology</li>
        <li class="mb-1">Asia Eastern University of Science and Technology</li>
        <li class="mb-1">Fu Jen Catholic University</li>
        <li class="mb-1">Ming Chuan University</li>
    </ul>
    </div>
</div>

<div class="ml-55 mt-15 font-semibold">
    <p>Interested in our Workshop? Please complete the application form below to secure your spot.
         Spaces are limited, so apply early!</p>
         <p>If you have any questions or need help
             with the application, please don't hesitate to contact us at PhoenixOfSanxia@gmail.com.</p>
</div>

<div class="bg-gray-100 pt-15 mt-15 pb-25">
  <div>
    <h3 class="ml-130 font-medium text-3xl">Application Form</h3>
  </div>
 <form class="mx-auto ml-30 mr-30 mt-15">
  <div class="flex flex-wrap -mx-3 mb-6">
    <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-first-name">
        First Name
      </label>
      <input class="appearance-none block w-full bg-gray-200 text-gray-700 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" id="grid-first-name" type="text" placeholder="First Name">
    </div>
    <div class="w-full md:w-1/2 px-3">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-last-name">
        Last Name
      </label>
      <input class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-last-name" type="text" placeholder="Last Name">
    </div>
  </div>
 <div class="flex flex-wrap -mx-3 mb-6">
    <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-first-name">
        Birthday
      </label>
      <input class="appearance-none block w-full bg-gray-200 text-gray-700 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" id="grid-first-name" type="text" placeholder="Birthday">
    </div>
    <div class="w-full md:w-1/2 px-3">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-last-name">
        Gender
      </label>
      <input class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-last-name" type="text" placeholder="Gender">
    </div>
  </div>
   <div class="flex flex-wrap -mx-3 mb-6">
    <div class="w-full md:w-1/2 px-3 mb-6 md:mb-0">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-first-name">
        City
      </label>
      <input class="appearance-none block w-full bg-gray-200 text-gray-700 rounded py-3 px-4 mb-3 leading-tight focus:outline-none focus:bg-white" id="grid-first-name" type="text" placeholder="City">
    </div>
    <div class="w-full md:w-1/2 px-3">
      <label class="block uppercase tracking-wide text-gray-700 text-xs font-bold mb-2" for="grid-last-name">
        University
      </label>
      <input class="appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight focus:outline-none focus:bg-white focus:border-gray-500" id="grid-last-name" type="text" placeholder="University">
    </div>
  </div>
</form>
<button style="background-color: rgba(39, 55, 81, 1);" class="float-right mr-30 mt-3 rounded-xl p-1 text-white cursor-pointer">Send Application</button>
</div>