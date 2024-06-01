<script lang="ts">
  import './app.scss';
</script>

<nav>
  <a href="/">Home</a>
  <a href="/about">About</a>
</nav>

<main>
  <slot />
</main>

<style>
  main {
    max-width: 900px;
    border: 1px solid;
    box-sizing: border-box;
    margin: 0 auto;
  }
</style>