<template>
  <button class="button is-rounded is-dark">
    <span class="icon">
      <i :class="code"></i>
    </span>
    <span>{{ hobby }}</span>
  </button>
</template>

<script>
export default {
  name: "hobbies",
  props: {
    hobby: String,
    code: String,
  }
};
</script>

<style scoped>
.button {
  margin-top: 5px;
  margin-bottom: 5px;
  margin-right: 10px;
  margin-left: 5px;
}
</style>