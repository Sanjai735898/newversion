<template>
  <div>
    <nav class="flex bg-gray-200 p-4 justify-between items-center">
      <div>
        <a href="#"><img src="../assets/chadura-logo.svg" alt="chadura" /></a>
      </div>
      <div class="flex">
        <ul class="hidden md:flex space-x-6">
          <li>
            <a href="#" class="flex items-center space-x-1">
              <span>Company</span>
              <svg
                width="10"
                height="5"
                viewBox="0 0 10 5"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path d="M5 5L0 0H10L5 5Z" fill="#575757" />
              </svg>
            </a>
          </li>

          <li>
            <a href="#" class="flex items-center space-x-1">
              <span>Technology</span>
              <img :src="icons" alt="icon" />
            </a>
          </li>

          <li>
            <a href="#" class="flex items-center space-x-1">
              <span>Services</span>
              <img :src="icons" alt="icon" />
            </a>
          </li>
          <li>
            <a href="#" class="flex items-center space-x-1">
              <span>Products</span>
              <img :src="icons" alt="icon" />
            </a>
          </li>

          <li><a href="#">Blogs</a></li>
          <li><a href="#">Workshop</a></li>
        </ul>
      </div>
      <!-- Right side nav -->
      <div class="hidden md:block">
        <button class="bg-blue-400 px-4 rounded-xl py-3 text-white font-bold">
          Enquire
        </button>
      </div>

      <!-- Hamburger icon: only visible on small devices -->
      <div class="block md:hidden manu-icon">
        <button @click="toggleMenu">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-8 h-8"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
            />
          </svg>
        </button>
      </div>
    </nav>
    <!-- mobile view -->
    <div v-show="isMenuopen" class="">
      <ul
        class="md:hidden space-y-1 manu-bar transition-all duration-75 ease-linear"
      >
        <li>
          <a
            href="#"
            class="hover:bg-slate-200 p-2 flex items-center md:space-x-1"
          >
            <span>Company</span>
            <svg
              width="10"
              height="5"
              viewBox="0 0 10 5"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path d="M5 5L0 0H10L5 5Z" fill="#575757" />
            </svg>
          </a>
        </li>

        <li>
          <a
            href="#"
            class="hover:bg-slate-200 p-2 flex items-center space-x-1"
          >
            <span>Technology</span>
            <img :src="icons" alt="icon" />
          </a>
        </li>

        <li>
          <a
            href="#"
            class="hover:bg-slate-200 p-2 flex items-center space-x-1"
          >
            <span>Services</span>
            <img :src="icons" alt="icon" />
          </a>
        </li>
        <li>
          <a
            href="#"
            class="hover:bg-slate-200 p-2 flex items-center space-x-1"
          >
            <span>Products</span>
            <img :src="icons" alt="icon" />
          </a>
        </li>

        <li>
          <a class="hover:bg-slate-200 p-2 flex items-center" href="#">Blogs</a>
        </li>
        <li>
          <a class="hover:bg-slate-200 p-2 flex items-center" href="#"
            >Workshop</a
          >
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import icons from "../assets/vector.svg";

export default {
  name: "HelloWorld",
  data() {
    return {
      icons,
      isMenuopen: false,
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuopen = !this.isMenuopen;
    },
  },
};
</script>

<style scoped>
/* Optional: Keep or adjust styles */
li img {
  position: relative;
  left: 0;
  bottom: 0;
  margin-left: 4px;
}
</style>
