<template>
  <div id="strong-we">
    <h1
      class="sm:text-center text-5xl ms-10 md:text-4xl font-bold my-4 text-center"
    >
      We Strong In
    </h1>

    <div
      class="flex flex-col md:flex-row justify-center items-center gap-8 md:gap-16 my-16"
    >
      <div>
        <img src="../assets/css.svg" alt="css" />
      </div>
      <div>
        <img src="../assets/html.svg" alt="html" />
      </div>
      <div>
        <img src="../assets/python.svg" alt="python" />
      </div>
    </div>
    <div
      class="grid grid-cols-2 ms-10 md:flex justify-center items-center gap-8 md:gap-16 my-20"
    >
      <div>
        <img src="../assets/expresience.svg" alt="" />
      </div>
      <div>
        <img src="../assets/quick.svg" alt="" />
      </div>
      <div>
        <img src="../assets/best solutions.svg" alt="" />
      </div>
      <div>
        <img src="../assets/quick.svg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "strong-we",
};
</script>

<style scoped>
/* No need for media query; Tailwind handles responsiveness well */
</style>
