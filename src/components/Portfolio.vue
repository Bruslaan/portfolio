<template>
  <div class="py-12">
    <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center">
        <!-- <p
          class="text-base leading-6 text-indigo-600 font-semibold tracking-wide uppercase"
        >Services</p>-->
        <h1
          class="text-4xl tracking-tight leading-10 font-hairline hairline text-gray-100 sm:text-5xl sm:leading-none md:text-6xl"
        >My Recent Projects</h1>
        <!-- <p
          class="mt-4 max-w-2xl text-xl leading-7 text-gray-500 lg:mx-auto"
        >Lorem ipsum dolor sit amet consect adipisicing elit. Possimus magnam voluptatum cupiditate veritatis in accusamus quisquam.</p>-->
      </div>

      <div class="mt-20 flex  flex-wrap justify-center ">
        <div class="md:w-1/2 w-full">
          <img
            src="../assets/mockupApp.png"
            alt
          />
        </div>
        <div class="md:w-1/2 w-full px-10 flex flex-col justify-between text-left mt-4 md:mt-0 ">
          <div>
            <h4 class="text-2xl leading-6 font-medium text-gray-100">Some Shit here</h4>
            <p
              class="mt-5 text-gray-500"
            >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellat sunt, cum laboriosam quaerat reiciendis omnis alias ad est id neque nostrum animi iure beatae repudiandae voluptates voluptas reprehenderit. Voluptatem, voluptate!</p>
          </div>

          <div class="flex flex-col md:flex-row items-center justify-between">
            <div class="flex mt-4 md:mt-0 w-full justify-start">
              <button class="border px-3 py-2 md:w-32 w-full block bg-white ">Previous</button>
              <button class="border px-3 py-2 md:w-32 w-full bg-white">Next</button>
            </div>
            <div class="flex items-center mt-4 md:mt-0">
              <span class="bg-gray-500 w-4 h-4 rounded-full mx-2"></span>
              <span class="bg-white border w-4 h-4 rounded-full mx-2"></span>
              <span class="bg-white border w-4 h-4 rounded-full mx-2"></span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>