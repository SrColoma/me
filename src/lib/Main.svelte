<script lang="ts">
  // import "$src/app.postcss";
  import Competencias from "@components/Competencias.svelte";
  import Experiencia from "@components/Experiencia.svelte";
  import Header from "@components/Header.svelte";
  import Idiomas from "@components/Idiomas.svelte";
  import Links from "@components/Links.svelte";
</script>


<div class="container mx-auto mt-20 h-auto px-10 lg:w-1/2">
  <!-- fondo -->
  <div id="background" class="opacity-50">
    <div class="w-full h-full rounded-full bg-amber-100 blur-3xl fixed -top-1/2 -left-2/3"></div>
    <div class=" w-full h-full rounded-full bg-red-200 blur-3xl fixed -top-72 -right-2/3"></div>
  </div>

  <!-- boton para descarga -->
  <div class="absolute top-0 right-0 mt-10 mr-10">
    
    <a href="https://drive.google.com/file/d/1DzpRs7pqPOOk57UaCFgU47UtsmC5E3Ji/view?usp=sharing">
      <button type="button" class="text-gray-900 bg-gradient-to-r from-red-200 via-red-300 to-yellow-200 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-red-100 dark:focus:ring-red-400 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-2 mb-2">descargar CV</button>
    </a>
  </div>

  <!-- contenido -->
  <div id="content" class="backdrop-blur-lg">
    <Header />
    <Experiencia />
    <Competencias />
    <Links />
    <Idiomas />
    
  </div>

</div>
