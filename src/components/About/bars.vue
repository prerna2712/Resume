<template>
  <div>
    <div>
      <span class="icon">
        <i :class="code"></i>
      </span>
      {{name}}
    </div>
    <div>
      <progress class="progress is-small" :value="num" max="100"></progress>
    </div>
    <br>
  </div>
</template>

<script>
export default {
  name: "bars",
  props: {
    num: Number,
    name: String,
    code: String
  }
};
</script>

<style scoped>
.icon {
  color: black;
}
</style>