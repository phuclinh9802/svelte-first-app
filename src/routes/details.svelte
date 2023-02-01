<script lang="ts">
  import { goto } from "@roxi/routify";

  const goHome = () => {
    $goto("/");
  };
</script>

<h1>Details Page</h1>

<button on:click={() => goHome()}>Go back to Home page</button>
