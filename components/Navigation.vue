<template>
  <div class="bg-black">
      <div class="container py-5 mx-auto flex justify-around items-center">
          <h1 class="font-serif text-4xl tracking-wider text-green-300 font-bold">Alex_wixx</h1>
          <ul class="flex">
              <li class="font-serif text-white tracking-wider text-lg mr-9 border-transparent transition ease-in-out duration-200 border-2 hover:border-green-100 px-3 py-1  ">
                  <NuxtLink to="/">Homepage</NuxtLink>
              </li>
              <li class="font-serif text-white tracking-wider text-lg mr-9 border-transparent transition ease-in-out duration-200 border-2 hover:border-green-100 px-3 py-1">
                  <NuxtLink to="/artworks">Artworks</NuxtLink>
              </li>
              <li class="font-serif text-white tracking-wider text-lg mr-9 border-transparent transition ease-in-out duration-200 border-2 hover:border-green-100 px-3 py-1 ">
                  <NuxtLink to="/contact">Contact</NuxtLink>
              </li>
          </ul>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>