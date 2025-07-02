<template>
  <div class="home">
    <HelloWorld />
    <chadura-component />
    <strong-we />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import ChaduraComponent from "@/components/ChaduraComponent.vue";
import StrongWe from "@/components/StrongWe.vue";
export default {
  name: "HomeView",
  components: {
    HelloWorld,
    ChaduraComponent,
    StrongWe,
  },
};
</script>
<style scoped></style>
