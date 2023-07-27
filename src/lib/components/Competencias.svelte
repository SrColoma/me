<script>
  import Competencia from "./miselaneos/Competencia.svelte";
</script>

<div class="md:grid grid-cols-4 mb-10">
  <div class="col-span-1">
    <h6 class="text-sm text-slate-400 py-2">🦾Competencias</h6>
  </div>

  <div class="col-span-3 grid grid-cols-3">
    <Competencia competencia="Git" nivel={3} />
    <Competencia competencia="Git Flow" nivel={3} />
    <Competencia competencia="Github Actions" nivel={1} />
    <Competencia competencia="Docker" nivel={3} />
    <Competencia competencia="Flask" nivel={3} />
    <Competencia competencia="AWS" nivel={3} />
    <Competencia competencia="Flutter" nivel={3} />
    <Competencia competencia="Svelte" nivel={2} />
    <Competencia competencia="Photoshop" nivel={3} />
    <Competencia competencia="Godot" nivel={3} />
    <Competencia competencia="Unity3D" nivel={3} />
    <Competencia competencia="Figma" nivel={2} />
    <Competencia competencia="Graphql" nivel={1} />
    <Competencia competencia="Nestjs" nivel={1} />
    <Competencia competencia="Blender" nivel={3} />
    <Competencia competencia="Tailwind" nivel={1} />
    

  </div>
</div>
