<template>
  <div id="app">
    <div class="container">
      <div class="columns">
        <div class="column is-two-fifths">
          <sidebar />
        </div>
        <div class="column is-three-fifths">
          <about />
        </div>
      </div>
      <div>
        <projects />
      </div>
    </div>
  </div>
</template>

<script>
import sidebar from "./components/sidebar.vue";
import about from "./components/about.vue";
import projects from "./components/projects.vue";
export default {
  name: "App",
  components: {
    sidebar,
    about,
    projects
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.containers {
  background-color: orange;
  height: 100%;
  width: 100%;
}
</style>
