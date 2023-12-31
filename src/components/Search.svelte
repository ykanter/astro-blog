<script>
  let searchItem = "";
</script>

<a class="ml-10" href={`/search/${searchItem}`}>Search for: </a>
<input
  class="bg-blue-100 rounded-md"
  type="text"
  name="search"
  bind:value={searchItem}
/>
