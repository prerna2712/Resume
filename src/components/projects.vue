<template>
  <div>
    <eachpro
      head="Open-source Resume"
      textin="This is my first open source project, you can check it out on my github page
  "
    />
  </div>
</template>

<script>
import eachpro from "./Projects/eachpro.vue";
export default {
  name: "projects",
  components: {
    eachpro
  }
};
</script>

<style scoped>
</style>