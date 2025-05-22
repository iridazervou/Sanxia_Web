   <script>
    import logo from '$lib/images/LogoOnly.png'

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