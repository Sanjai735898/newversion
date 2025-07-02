<template>
  <div class="w-full">
    <!-- Hero Section -->
    <div>
      <img
        src="../assets/chadura.svg"
        alt="Chadura"
        class="w-full h-auto object-contain"
      />
    </div>

    <!-- Content Section -->
    <div class="max-w-7xl mx-auto px-4">
      <h1 class="text-4xl font-bold my-5 text-center">
        Software as a Services(Saas)
      </h1>
      <div class="grid md:grid-cols-2 space-x-40 my-10 item-center">
        <p class="my-5">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores, eum
          odit? Natus mollitia soluta et quos recusandae possimus, delectus
          nostrum fugit voluptates corrupti illo labore eaque nulla maxime
          pariatur eveniet.

          <img
            src="../assets/percentage.svg"
            alt="percentage.icon"
            class="sm:w-full mt-10 md:mt-36 w-96"
          />
        </p>
        <img
          src="../assets/chadura.img2.svg"
          alt="chadura.img"
          style="width: 400px"
          class="md:-translate-x-20 chadura"
        />
        <h4
          class="sm:-translate-y-64 md:float-left relative z-10 -bottom-44 right-36"
        >
          SaaS Development
        </h4>
        <div class="clear-both"></div>
        <h5
          class="sm:-translate-y-64 relative z-10 -bottom-36 left-72 md:-translate-x-14 lg:translate-x-20"
        >
          90%
        </h5>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ChaduraImg",
};
</script>

<style scoped>
/* Prevent any image overflow */
img {
  max-width: 100%;
  height: auto;
  display: block;
}
@media screen and (max-width: 767px) {
  h4 {
    position: relative;
    bottom: 60px;
  }
  h5 {
    position: relative;
    bottom: 80px;
    left: 450px;
  }
  .chadura {
    margin-top: 20px;
  }
}
</style>
