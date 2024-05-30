<script>
  import "../app.css";
  import Navbar from "$lib/Navbar.svelte";
</script>

<div class="merriweather-regular">
  <Navbar />
  <slot />
</div>

<style>
  .merriweather-regular {
    font-family: "Merriweather", serif;
    font-weight: 400;
    font-style: normal;
  }
</style>
