<template>
  <div>
    <h1 class="subtitle">{{head}}</h1>
  </div>
</template>

<script>
export default {
  name: "heading",
  props: {
    head: String
  }
};
</script>

<style scoped>
.subtitle {
  color: white;
  margin-left: 5px;
  margin-top: -10px;
}
</style>