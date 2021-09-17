<template>
    <div class="flex flex-col justify-center" id="hero">
        <div class="container max-w-4xl mx-auto">
            <h1 class="font-serif text-5xl tracking-wider pb-4 text-white font-bold">Hi, im <span class="border-b-2 border-green-400 text-gray-300 font-sans">Alex</span> i paint for a living</h1>
            <p class="font-sans text-xl text-white pb-5">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Molestias hic molestiae nemo inventore in aspernatur illo doloremque maxime!</p>
            <div class="">
            <button class="bg-green-400 py-3 px-10 shadow-xl tracking-wide transition ease-in-out duration-150 hover:bg-green-300 ">
                <NuxtLink to="/artworks">Visit my artworks</NuxtLink>
            </button>
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