<script lang="ts">
  export let count: number = 0;
  export let count_1: number = 0;
  const increment = () => {
    count += 1;
  };

  const decrement = () => {
    count_1 -= 1;
  };
</script>

<button on:click={increment}>
  count is {count}
</button>

<button on:click={decrement}>
  count is {count_1}
</button>
