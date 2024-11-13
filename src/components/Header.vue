<script>
 export default{
   name: 'Header'
 }
</script>

<template>
    <nav>
      <ul class="bg-purple-100 flex gap-5">
        <li>
          <a href="#">Home</a>
        </li>
        <li class="relative group">
          <a href="#">item</a>
          <ul class="absolute w-20 hidden group-hover:block">
            <li><a href="#">Sub item</a></li>
            <li><a href="#">Sub item2</a></li>
          </ul>
        </li>
      </ul>
    </nav>
</template>

<style scoped>

</style>
