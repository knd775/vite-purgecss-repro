<script>
  const test = true;
</script>

<div class="container h-full mx-auto flex justify-center items-center">
  <div class="space-y-5">
    <h1 class="h1" class:text-red-500={test}>
      This should be red, set by a class directive
    </h1>
    <h1 class="h1 text-blue-500">This should be blue, but set directly</h1>
  </div>
</div>
