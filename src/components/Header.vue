<template>
  <div>
    <div
      class="mx-auto max-w-screen-xl px-4  sm:px-6 lg:px-8 xl:mt-28 flex flex-wrap justify-center items-center h-screen"
    >
      <div class="text-center md:text-right md:w-1/2">
        <h2
          class="text-4xl tracking-tight leading-10 font-hairline hairline text-gray-900 sm:text-5xl sm:leading-none md:text-6xl"
        >Ruslan Noschajew</h2>

        <span class="text-yellow-800 font-hairline hairline text-2xl">Software Developer</span>
        <p
          class="text-xl text-gray-700 mt-10"
        >Lorem ipsum dolor sit amet consectetur adipisicing elit</p>
        <div class="mt-5 sm:mt-8 sm:flex justify-center md:justify-end">
          <div class="rounded-md shadow">
            <a
              href="#"
              class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base leading-6 font-medium rounded-md text-white bg-gray-600 hover:bg-indigo-500 focus:outline-none focus:shadow-outline transition duration-150 ease-in-out md:py-4 md:text-lg md:px-10"
            >Contact Me</a>
          </div>
          <div class="mt-3 sm:mt-0 sm:ml-3">
            <a
              href="#"
              class="w-full flex items-center justify-center px-8 py-3 border border-gray-600 text-base leading-6 font-medium rounded-md text-gray-700 hover:text-indigo-600 hover:bg-indigo-100 focus:outline-none focus:shadow-outline focus:border-indigo-300 transition duration-150 ease-in-out md:py-4 md:text-lg md:px-10"
            >Portfolio</a>
          </div>
        </div>
      </div>

      <div class="md:w-1/2 mt-10 flex justify-center">
        <img
          class="object-cover rounded-full h-64 w-64"
          src="https://images.unsplash.com/photo-1534188753412-3e26d0d618d6?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2734&q=80"
        />
       
      </div>
       <!-- <SpeechBuble/> -->
    </div>
  </div>
</template>

<script>
import SpeechBuble from './SpeechBuble.vue'
export default {
    components:{
        SpeechBuble
    }
};
</script>

<style>
</style>