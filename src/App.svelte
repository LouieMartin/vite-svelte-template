<script lang="ts">
  let count = 0;

  function increment() {
    count++;
  }

  function decrement() {
    count--;
  }
</script>

<main>
  <div class="flex flex-col justify-center items-center h-screen text-gray-900">
    <h1 class="font-bold text-6xl">Count {count}</h1>
    <button class="border border-gray-900 p-3 rounded-full w-52 mt-5" on:click={increment}>Increment</button>
    <button class="border border-gray-900 p-3 rounded-full w-52 mt-5" on:click={decrement}>Decrement</button>
  </div>
</main>

<style global lang="scss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
