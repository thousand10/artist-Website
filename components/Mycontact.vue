<template>
  <div class="">
      <div class="container py-28 mx-auto max-w-4xl px-5">
        <h1 class="font-serif text-5xl pb-10 tracking-wide underline flex flex-col">
          <span>contact us using</span>
          <span>form below</span>
        </h1>

        <div class="max-w-xl">
          <form>
            <div class="py-2">
              <label for="Name" class="font-sans text-xl">Name</label>
              <input type="text" class="w-full py-2 border-2 border-gray-600 px-3">
            </div>
            <div class="py-2">
              <label for="Name" class="font-sans text-xl">Email</label>
              <input type="email" class="w-full py-2 border-2 border-gray-600 px-3">
            </div>
            <div class="py-2">
              <label for="Name" class="font-sans text-xl">Message</label>
              <textarea name="" class="w-full py-2 border-2 border-gray-600 px-3" id="" cols="30" rows="10"></textarea>
            </div>
            <button class="font-sans text-lg bg-green-500 py-3 w-full transition ease-in-out duration-200 hover:bg-green-400">
              Send Message
            </button>
          </form>
        </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>