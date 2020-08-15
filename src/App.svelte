<script lang="ts">
  export let name: string = "World";
  export let count: number = 5;
  // code here
</script>

<style>
  /* styles here */
</style>

<main>
  <div class="center">
    <img src="favicon.png" alt="favicon" />
    <h1>Svelte App</h1>
    <h2>SpinSpire</h2>
    <p>High performance, Open Source Web &amp; Mobile!</p>
    {#each Array(count) as _, i}
      <p>Hello {name}:{i}</p>
    {/each}
    <p>
      <a href="https://spinspire.com/">spinspire.com</a>
      |
      <a href="https://youtube.com/spinspire">youtube.com/spinspire</a>
    </p>
  </div>
</main>
