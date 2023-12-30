<script>
  let name = "";
</script>

<label class="ml-10" for="myname">Your name: </label>
<input
  class="bg-blue-100 rounded-md"
  name="myname"
  type="text"
  bind:value={name}
/>
{#if name.length > 0}
  <div class="ml-10">
    Hello {name}
  </div>
{/if}
