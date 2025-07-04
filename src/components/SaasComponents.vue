<template>
  <div id="saas-components">
    <h1 class="text-4xl text-center">Saas With Chadura</h1>
    <div class="flex justify-center items-center gap-10 my-16">
      <div>
        <img src="../assets/img1.svg" alt="" />
      </div>
      <div>
        <img src="../assets/img2.svg" alt="" />
      </div>
      <div>
        <img src="../assets/img3.svg" alt="" />
      </div>
    </div>
    <div class="">
      <img
        src="../assets/img4.jpg"
        alt=""
        class="w-full h-auto object-contain mx-auto"
      />
      <div class="flex items-center justify-center my-16 gap-10 ms-5">
        <div>
          <img src="../assets/productdesign.svg" alt="" />
        </div>
        <div>
          <img src="../assets/developer.svg" alt="" />
        </div>
        <div>
          <img src="../assets/dataanalytics.svg" alt="" />
        </div>
      </div>
    </div>
    <div class="card flex justify-center items-center my-16 gap-10                                                  ">
      <h1 class="text-cyan-800 p-8 text-2xl border border-gray-300">
        Custome Software Development
      </h1>
      <h1 class="text-cyan-800 p-8 text-2xl border border-gray-300">
        Outsourcing Development
      </h1>
      <h1 class="text-cyan-800 p-8 text-2xl border borde                                                                                                                                                                                                                                                                                      r-gray-300">
        Software Product Development
      </h1>
    </div>
    <div class="my-16">
      <h1 class="text-4xl text-center">Frequently Asked Questions (FAQ)</h1>
      <div class="grid grid-cols-2 my-14 mx-auto text-center">
        <p class="my-4">
          1. What services does your Python consultancy offer?
          <img :src="ples" alt="" />
        </p>
        <p class="my-4">
          2. What industries commonly use Python? <img :src="ples" alt="" />
        </p>
        <p class="my-4">
          3. What are some popular Python libraries and frameworks you
          specialize in? <img :src="ples" alt="" />
        </p>
        <p class="my-4">
          4. Why should I choose Python for my project?
          <img :src="ples" alt="" />
        </p>
        <p class="my-4">
          5. Can you help migrate an existing project to Python?
          <img :src="ples" alt="" />
        </p>
        <p class="my-4">
          6. How do you ensure the quality of your Python code?
          <img :src="ples" alt="" />
        </p>
        <p class="my-4">
          7. How do you handle project management and communication?
          <img :src="ples" alt="" />
        </p>
        <p class="my-4">
          8.Do you offer training or workshops for Python?
          <img :src="ples" alt="" />
        </p>
        <p class="my-4">
          9. What kind of support do you provide after project completion?
          <img :src="ples" alt="" />
        </p>
        <p class="my-4">
          10. How can I get started with your Python consultancy?
          <img :src="ples" alt="" />
        </p>
      </div>
    </div>
  </div>
</template>
<script>
import ples from "../assets/+.svg";
export default {
  name: "saas-components",
  data() {
    return {
      ples,
    };
  },
};
</script>
