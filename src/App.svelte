<script lang="ts">
  import svelteLogo from "./assets/svelte.svg";
  import Counter from "./lib/Counter.svelte";
</script>

<main>
  <h1>Vite + Svelte</h1>

  <div class="card">
    <Counter count_1={50} count={42} />
  </div>
</main>
