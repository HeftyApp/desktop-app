<script>
  import "../app.postcss";
  import "../app.scss";
  import SideBar from "$lib/SideBar.svelte";
</script>

<SideBar>

<div class="main">
  <slot>
</slot></div>
</SideBar>
<slot></slot>