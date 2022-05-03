<script>
  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<button
  on:click={increment}
  class="rounded-full bg-orange-300 hover:bg-orange-400 active:bg-orange-600 active:text-white py-4 px-8 cursor-pointer"
>
  Clicks: {count}
</button>
