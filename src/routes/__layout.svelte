<SideBar>
  <div class="main">
    <slot />
  </div>
</SideBar>
<slot />

<script>
  import "../app.postcss";
  import "../app.scss";
  import SideBar from "$lib/SideBar.svelte";
</script>
