<script lang="ts">
  // import "$src/app.postcss";
  import Competencias from "@components/Competencias.svelte";
  import Experiencia from "@components/Experiencia.svelte";
  import Header from "@components/Header.svelte";
  import Idiomas from "@components/Idiomas.svelte";
  import Links from "@components/Links.svelte";
</script>


<div class="container mx-auto mt-20 h-auto px-10 lg:w-1/2">
  
  <div id="background" class="opacity-50">
    <div class="w-full h-full rounded-full bg-amber-100 blur-3xl fixed -top-1/2 -left-2/3"></div>
    <div class=" w-full h-full rounded-full bg-red-200 blur-3xl fixed -top-72 -right-2/3"></div>
  </div>

  <div id="content" class="backdrop-blur-lg">
    <Header />
    <Experiencia />
    <Competencias />
    <Links />
    <Idiomas />

  </div>

</div>
