<template>
  <section class="font-mono w-full h-full bg-black">
    <NavBar />
    <br />
    <br />
    <br />
    <div class="text-center pb-12">
      <h2 class="text-base font-bold text-indigo-50">|| OUR MENTORS IN ||</h2>
      <div>
        <h1
          class="font-bold text-3xl md:text-4xl lg:text-5xl font-heading text-gray-900"
        >
          <strong class="text-white"> ALGORAC </strong>
        </h1>
      </div>
      <img src="../assets/head.png" class="mx-auto" />
    </div>

    <div
      class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-3 gap-3"
    >
      <div class="card">
        <div
          class="w-full bg-white bg-opacity-40 backdrop-blur m-0 rounded-lg p-12 flex max-w-md mx-auto flex-col justify-center items-center"
        >
          <div class="mb-8">
            <img
              class="object-center object-cover rounded-full h-36 w-36"
              src="http://2.bp.blogspot.com/_lwBPBFdTaWM/TIeBFJY4EVI/AAAAAAAAAA8/hta0nczcYrk/s1600/canstockphoto1799922+teacher.jpg"
              alt="photo"
            />
          </div>
          <div class="text-center">
            <p class="text-xl text-gray-700 font-bold mb-2">NAME</p>
            <h3>designation</h3>
            <p class="text-base text-gray-400 font-normal">CONTACT</p>
          </div>
        </div>
      </div>
      <div class="card">
        <div
          class="w-full bg-white bg-opacity-40 backdrop-blur m-0 rounded-lg p-12 flex max-w-md mx-auto flex-col justify-center items-center"
        >
          <div class="mb-8">
            <img
              class="object-center object-cover rounded-full h-36 w-36"
              src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1170&q=80"
              alt="photo"
            />
          </div>
          <div class="text-center">
            <p class="text-xl text-gray-700 font-bold mb-2">NAME</p>
            <h3>designation</h3>
            <p class="text-base text-gray-400 font-normal">CONTACT</p>
          </div>
        </div>
      </div>
      <div class="card">
        <div
          class="w-full bg-white bg-opacity-40 backdrop-blur m-0 rounded-lg p-12 flex max-w-md mx-auto flex-col justify-center items-center"
        >
          <div class="mb-8">
            <img
              class="object-center object-cover rounded-full h-36 w-36"
              src="https://images.unsplash.com/photo-1499952127939-9bbf5af6c51c?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1176&q=80"
              alt="photo"
            />
          </div>
          <div class="text-center">
            <p class="text-xl text-gray-700 font-bold mb-2">NAME</p>
            <h3>designation</h3>
            <p class="text-base text-gray-400 font-normal">CONTACT</p>
          </div>
        </div>
      </div>
      <div class="card">
        <div
          class="w-full bg-white bg-opacity-40 backdrop-blur m-0 rounded-lg p-12 flex max-w-md mx-auto flex-col justify-center items-center"
        >
          <div class="mb-8">
            <img
              class="object-center object-cover rounded-full h-36 w-36"
              src="http://2.bp.blogspot.com/_lwBPBFdTaWM/TIeBFJY4EVI/AAAAAAAAAA8/hta0nczcYrk/s1600/canstockphoto1799922+teacher.jpg"
              alt="photo"
            />
          </div>
          <div class="text-center">
            <p class="text-xl text-gray-700 font-bold mb-2">NAME</p>
            <h3>designation</h3>
            <p class="text-base text-gray-400 font-normal">CONTACT</p>
          </div>
        </div>
      </div>
      <div class="card">
        <div
          class="w-full bg-white bg-opacity-40 backdrop-blur m-0 rounded-lg p-12 flex max-w-md mx-auto flex-col justify-center items-center"
        >
          <div class="mb-8">
            <img
              class="object-center object-cover rounded-full h-36 w-36"
              src="https://images.unsplash.com/photo-1438761681033-6461ffad8d80?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1170&q=80"
              alt="photo"
            />
          </div>
          <div class="text-center">
            <p class="text-xl text-gray-700 font-bold mb-2">NAME</p>
            <h3>designation</h3>
            <p class="text-base text-gray-400 font-normal">CONTACT</p>
          </div>
        </div>
      </div>
      <div class="card">
        <div
          class="w-full bg-white bg-opacity-40 backdrop-blur m-0 rounded-lg p-12 flex max-w-md mx-auto flex-col justify-center items-center"
        >
          <div class="mb-8">
            <img
              class="object-center object-cover rounded-full h-36 w-36"
              src="https://images.unsplash.com/photo-1499952127939-9bbf5af6c51c?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1176&q=80"
              alt="photo"
            />
          </div>
          <div class="text-center">
            <p class="text-xl text-gray-700 font-bold mb-2">NAME</p>
            <h3>designation</h3>
            <p class="text-base text-gray-400 font-normal">CONTACT</p>
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </section>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Mentors",
  data() {},
  components: {
    NavBar,
    Footer,
  },
};
</script>
<style>
.card {
  border: 50px;
  margin: 50px;
  box-shadow: 5px 5px 20px gray;
  overflow: hidden;
  border-radius: 5px;
  transition: 0.9s;
}
.card:hover {
  cursor: pointer;
  transform: scale(1.1);
}
</style>