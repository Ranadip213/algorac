<template>
  <div
    class="font-mono w-full h-full bg-one bg-fixed bg-cover text-white bg-center"
  >
    <NavBar />
    <div
      class="w-full pt-4 pr-5 pb-6 pl-5 mt-0 mr-auto mb-0 ml-auto space-y-5 sm:py-8 md:py-12 sm:space-y-8 md:space-y-16 max-w-7xl"
    >
      <div class="flex flex-col items-center sm:px-5 md:flex-row">
        <div
          class="flex flex-col items-start justify-center w-full h-full pt-6 pr-0 pb-6 pl-0 mb-6 md:mb-0 md:w-1/2"
        >
          <div
            class="flex flex-col items-start justify-center h-full space-y-3 transform md:pr-10 lg:pr-16 md:space-y-5"
          >
            <div
              class="bg-green-500 flex items-center leading-none rounded-full pt-1.5 pr-3 pb-1.5 pl-2 uppercase inline-block"
            >
              <p class="inline">
                <svg
                  class="w-3.5 h-3.5 mr-1"
                  fill="currentColor"
                  viewbox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0
                  00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755
                  1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1
                  0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                  />
                </svg>
              </p>
              <p class="inline text-xs font-medium">projects</p>
            </div>
            <a class="text-4x1 font-bold leading-none lg:text-5xl xl:text-6xl"
              >Projects handled under ALGORAC.</a
            >
            <div class="pt-2 pr-0 pb-0 pl-0"></div>
          </div>
        </div>
        <div class="w-full md:w-1/2">
          <div class="block">
            <img src="../assets/prj_1.svg" />
          </div>
        </div>
      </div>
      <div class="grid grid-cols-12 sm:px-5 gap-x-8 gap-y-16">
        <div
          class="flex flex-col items-start col-span-12 space-y-3 sm:col-span-6 xl:col-span-4"
        >
          <img src="../assets/prj_1.svg" />
          <p
            class="bg-green-500 flex items-center leading-none text-sm font-medium pt-1.5 pr-3 pb-1.5 pl-3 rounded-full uppercase inline-block"
          >
            1.
          </p>
          <a class="text-lg font-bold sm:text-xl md:text-2xl">Project 1</a>
          <p class="text-sm">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam,
          </p>
          <div class="pt-2 pr-0 pb-0 pl-0">
            <p class="text-sm font-medium inline">By:</p>
            <a class="inline text-xs font-medium mt-0 mr-1 mb-0 ml-0 underline"
              >ALGORAC</a
            >
            <p class="inline text-xs font-medium mt-0 mr-1 mb-0 ml-1">
              · DD/MM/YYYY ·
            </p>
          </div>
        </div>
        <div
          class="flex flex-col items-start col-span-12 space-y-3 sm:col-span-6 xl:col-span-4"
        >
          <img src="../assets/prj_2.svg" />
          <p
            class="bg-green-500 flex items-center leading-none text-sm font-medium pt-1.5 pr-3 pb-1.5 pl-3 rounded-full uppercase inline-block"
          >
            2.
          </p>
          <a class="text-lg font-bold sm:text-xl md:text-2xl">Project 2</a>
          <p class="text-sm">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam,
          </p>
          <div class="pt-2 pr-0 pb-0 pl-0">
            <p class="text-sm font-medium inline">By:</p>
            <a class="inline text-xs font-medium mt-0 mr-1 mb-0 ml-0 underline"
              >ALGORAC</a
            >
            <p class="inline text-xs font-medium mt-0 mr-1 mb-0 ml-1">
              · DD/MM/YYYY ·
            </p>
          </div>
        </div>
        <div
          class="flex flex-col items-start col-span-12 space-y-3 sm:col-span-6 xl:col-span-4"
        >
          <img src="../assets/prj_3.svg" />
          <p
            class="bg-green-500 flex items-center leading-none text-sm font-medium pt-1.5 pr-3 pb-1.5 pl-3 rounded-full uppercase inline-block"
          >
            3.
          </p>
          <a class="text-lg font-bold sm:text-xl md:text-2xl">Project 3</a>
          <p class="text-sm">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam,
          </p>
          <div class="pt-2 pr-0 pb-0 pl-0">
            <p class="text-sm font-medium inline">By:</p>
            <a class="inline text-xs font-medium mt-0 mr-1 mb-0 ml-0 underline"
              >ALGORAC</a
            >
            <p class="inline text-xs font-medium mt-0 mr-1 mb-0 ml-1">
              · DD/MM/YYYY ·
            </p>
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>
<script>
import NavBar from "@/components/NavBar.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "Projects",
  data() {},
  components: {
    NavBar,
    Footer,
  },
};
</script>
