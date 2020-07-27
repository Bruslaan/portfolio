<template>
  <div class="mx-auto max-w-4xl mt-20">
    <div class="flex flex-wrap justify-center mb-10">
      <div class="md:w-1/3 w-full px-10">
        <h1 class="text-white text-3xl">About Me</h1>
      </div>
      <div class="md:w-2/3 w-full px-10">
        <p class="text-gray-600 text-xl border-b border-gray-700 pb-4">
          Hello! I'm Ruslan, a
          <span class="text-gray-100">software engineer</span>
          based in Germany Munic.
          <br />
          <br />I enjoy
          <span class="text-gray-100">creating software</span>, whether that be
          <span class="text-gray-100">websites, applications</span>, or even
          <span class="text-gray-100">games</span>. My goal is to always build products that provide
          <span
            class="text-gray-100"
          >responsiv and performant</span> experiences.
          Shortly after receiving my
          <span class="text-gray-100">master's degree from Technische University in Munic</span>, I joined the cloud engineering team at Rohde & Schwarz where I worked on their cloud infrastructure.
        </p>
      </div>
    </div>

    <div class="flex flex-wrap justify-center">
      <div class="md:w-1/3 w-full px-10 mb-5 md:mb-0">
        <h1 class="text-white text-3xl">My Services</h1>
      </div>
      <div class="md:w-2/3 w-full px-10">
        <div
          class="border-b border-gray-700 pb-4 mb-4"
          v-for="service in services"
          :key="service.name"
        >
          <a
            class="flex items-center cursor-pointer select-none"
            @click="service.show=!service.show"
          >
            <h1 class="text-white text-2xl">{{service.name}}</h1>
            <img
              src="../assets/arrowDown.svg"
              alt
              class="h-3 ml-3"
              :class="service.show?'transform rotate-180':''"
            />
          </a>

          <p v-if="service.show" class="text-gray-100 my-3">{{service.dropDown}}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    callIT() {
      console.log("hallo world");
      this.show = !this.show;
    }
  },
  data() {
    return {
      services: [
        {
          name: "Web Dev",
          show: false,
          dropDown:
            "JavaScript · VueJs · React ·  NodeJs · Express · Flutter  · Tailwind · Linux · Docker · GIT · Strapi"
        },
        {
          name: "Mobile Application",
          show: false,
          dropDown: "Swift · Flutter"
        },
        {
          name: "Cloud Dev",
          show: false,
          dropDown:
            "Kubernetes · OpenShift · Linux · Terraform · GO Lang · Kubernetes Operator"
        },
        {
          name: "Game Dev",
          show: false,
          dropDown: "Unity 3D · Blender"
        },
        {
          name: "UX Design",
          show: false,
          dropDown: "Adobe XD · Sketch"
        }
      ]
    };
  }
};
</script>

<style>
</style>