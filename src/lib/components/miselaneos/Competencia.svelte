<script lang="ts">
  export let competencia: string;
  export let nivel: number;
</script>

<div class="grid grid-rows-2">
  <span>{competencia}</span>
  <span class="text-xs">
    {#each Array(nivel) as _, index (index)}
      ⭐
    {/each}
  </span>
</div>
