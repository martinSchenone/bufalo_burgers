<script>
  import "../app.css";
  import "../styles/font.css";
  import Nav from "../lib/Nav.svelte";
</script>

<Nav />
<slot />

<style>
    :global(body) {
    background-color: #e2c799;
    min-height: 100vh;
    font-family: "BURISC-Regular";
    font-size: 20px;
    font-weight: normal;
  }
</style>
