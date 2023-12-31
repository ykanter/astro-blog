<script>
  let searchItem = "";
</script>

<a class="ml-10" href={`/search/${searchItem}`}
  ><span class="font-bold bg-blue-900 text-white rounded-full px-3 py-1"
    >Search</span
  > for:
</a>
<input
  class="bg-blue-100 rounded-md"
  type="text"
  name="search"
  bind:value={searchItem}
/>
