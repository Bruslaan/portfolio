<template>
  <div class="py-12">
    <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center">
        <!-- <p
          class="text-base leading-6 text-indigo-600 font-semibold tracking-wide uppercase"
        >Services</p>-->
        <h1
          class="text-4xl tracking-tight leading-10 font-hairline hairline text-gray-100 sm:text-5xl sm:leading-none md:text-6xl"
        >My Services</h1>
        <!-- <p
          class="mt-4 max-w-2xl text-xl leading-7 text-gray-500 lg:mx-auto"
        >Lorem ipsum dolor sit amet consect adipisicing elit. Possimus magnam voluptatum cupiditate veritatis in accusamus quisquam.</p>-->
      </div>

      <div class="mt-24">
        <ul class="grid md:grid-cols-3 md:col-gap-8 md:row-gap-10 col-gap-4 row-gap-4">
          <li v-for="(service,index) in services" :key="index">
            <div class="flex flex-col p-3 rounded-lg hover:shadow-md bg-gray-600 h-64">
              <img class="rounded-full bg-white w-10 h-10 ml-4 my-3 object-cover" src="https://images.unsplash.com/photo-1543610892-0b1f7e6d8ac1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=934&q=80">
       
              <div class="ml-4">
                <h4 class="text-2xl leading-6 font-medium text-white">{{service}}</h4>
                <p
                  class="mt-2 text-base leading-6 text-white"
                >Lorem ipsum, dolor sit amet consectetur adipisicing elit. s suscipit</p>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data(){
    return{
      services:["App Dev", "Web Dev", "Game Dev", "Backend Dev", "Desktop Apps","Cloud Apps"]
    }
  }
};
</script>

<style>
</style>