<template>
  <div>
    <div class="footer">
      <div class="columns">
        <div class="column is-half">
          <div class="content subtitle"><u>{{head}}</u></div>
          <div class="mar">{{textin}}</div>
        </div>
        <div class="column is-half">
          <img src="./Photos/screenshot.png" />
        </div>
      </div>
    </div>
    <br>
  </div>
</template>

<script>
export default {
  name: "eachpro",
  props: {
    head: String,
    textin: String
  }
};
</script>

<style scoped>
.subtitle {
  text-align: left;
}
.mar{
    text-align: left;
}
</style>