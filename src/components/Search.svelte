<script>
  let searchItem = "";
</script>

<div class="flex my-2">
  <div class="flex-1 mr-2">
    <a href={`/search/${searchItem}`}
      ><span class="font-bold bg-blue-900 text-white rounded-full px-3 py-1"
        >Search</span
      >
    </a>
  </div>
  <div class="flex-1">
    <input
      class="bg-blue-100 rounded-md"
      type="text"
      name="search"
      bind:value={searchItem}
    />
  </div>
</div>
