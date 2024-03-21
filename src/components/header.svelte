<script lang="ts">
  import MenuItem from "./menuItem.svelte";
</script>

<div class="flex justify-between items-center p-4 max-w-7xl mx-auto">
  <div class="flex gap-4">
    <MenuItem />
    <MenuItem />
  </div>
  <div class="flex gap-x-3 items-center">
    <a
      href="/"
      class="text-2xl text-purple-100 font-bold py-1 px-2 bg-purple-800 rounded-xl hover:text-purple-800 hover:bg-purple-100"
    >
      RSMovie
    </a>
  </div>
</div>
