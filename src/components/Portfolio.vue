<template>
  <div class="py-12 mt-40">
    <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center">
        <!-- <p
          class="text-base leading-6 text-indigo-600 font-semibold tracking-wide uppercase"
        >Services</p>-->
        <h1
          class="text-2xl tracking-tight leading-10 font-hairline hairline text-gray-900 sm:text-2xl sm:leading-none md:text-4xl"
        >My Recent Projects</h1>
        <!-- <p
          class="mt-4 max-w-2xl text-xl leading-7 text-gray-500 lg:mx-auto"
        >Lorem ipsum dolor sit amet consect adipisicing elit. Possimus magnam voluptatum cupiditate veritatis in accusamus quisquam.</p>-->
      </div>

      <div class="mt-20 flex flex-wrap justify-center">
        <div class="md:w-1/2 w-full">
          <img
            src="../assets/Safeat.png"
            class="mx-auto border shadow-sm transform hover:scale-105 transition ease-in duration-200"
          />
        </div>
        <div class="md:w-1/2 w-full px-10 flex flex-col justify-between text-left mt-4 md:mt-0">
          <div>
            <h4 class="text-2xl leading-6 font-medium text-gray-900">Saf'Eat Progressiv Web App</h4>
            <div class>
              <p
                class="mt-5 text-gray-600"
              >Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates quam error dolor optio provident, officia ducimus quo repellendus aliquam laboriosam ratione blanditiis aspernatur vero facere. Nemo quo voluptates cupiditate neque!</p>
              <br />

              <a
                href="https://www.safeat.de"
                class="hover:text-yellow-700"
                target="_blank"
              >www.safeat.de</a>

              <div class="mt-10">
                <h1>
                  Frontend:
                  <span class="text-gray-700">Vue Js · Tailwind CSS</span>
                </h1>
                <h1>
                  Backend:
                  <span class="text-gray-700">Node Js · Strapi · Mongo DB · Socket IO </span>
                </h1>
                <h1>
                  Payment:
                  <span class="text-gray-700">Strapi · PayPal Api</span>
                </h1>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="flex items-center mt-5 md:mt-0 justify-center">
        <span class="bg-orange-500 border border-gray-200 w-4 h-4 rounded-full mx-2"></span>
        <span class="bg-white border w-4 h-4 rounded-full mx-2"></span>
        <span class="bg-white border w-4 h-4 rounded-full mx-2"></span>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>