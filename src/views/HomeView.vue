<template>
  <div class="home">
    <HelloWorld />
    <chadura-component />
    <strong-we />
    <saas-components />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import ChaduraComponent from "@/components/ChaduraComponent.vue";
import StrongWe from "@/components/StrongWe.vue";
import SaasComponents from "@/components/SaasComponents.vue";
export default {
  name: "HomeView",
  components: {
    HelloWorld,
    ChaduraComponent,
    StrongWe,
    SaasComponents,
  },
};
</script>
<style scoped></style>
