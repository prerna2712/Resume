<template>
  <div class="all1">
    <div class="center">
      <img class="Profile" alt="Profile" src="./Sidebar/Photos/Profile.jpg" />
      <h1 class="title">
        Prerna
        <span class="surname">Gupta</span>
      </h1>
      <h2 class="subtitle">A Student Developer</h2>
    </div>
    <div class="all">
      <div class="info">
        <heading head="I N F O" />
        <hr class="solid" />
        <info head="Email" body="prernagupta2712@gmail.com" code="fas fa-envelope fa-lg" />
        <info
          head="Institute"
          body="Indian Institute of Engineering Science and Technology"
          code="fas fa-university fa-lg"
        />
        <info head="Birth Date" body="Dec 27, 2000" code="fas fa-birthday-cake fa-lg" />
        <info head="Habitation" body="Howrah, India" code="fas fa-home fa-lg" />
      </div>
      <br />
      <div class="socials">
        <heading head="S O C I A L S" />
        <hr class="solid" />
        <a href="https://github.com/prerna2712" class="links">
          <u>
            <info head="github.com/prerna2712" code="fab fa-github fa-lg" />
          </u>
        </a>
        <a href="https://www.linkedin.com/in/prerna-gupta-271a47192" class="links">
          <u>
            <info head="linkedin.com/in/prerna-gupta2712" code="fab fa-linkedin fa-lg" />
          </u>
        </a>
        <a href="https://www.facebook.com/profile.php?id=100005325855936" class="links">
          <u>
            <info head="facebook.com/prernagupta" code="fab fa-facebook fa-lg" />
          </u>
        </a>
        <a href="https://www.instagram.com/prernagupta__27/" class="links">
          <u>
            <info head="instagram.com/prernagupta__27" code="fab fa-instagram fa-lg" />
          </u>
        </a>
      </div>
      <br />
      <div class="hobbies">
        <heading head="H O B B I E S" />
        <hr class="solid" />
        <p>
          <hobbies hobby="Reading" code="fas fa-book-open" />
          <hobbies hobby="Streaming-Anime" code="fas fa-video" />
          <hobbies hobby="Drawing" code="fas fa-palette" />
          <hobbies hobby="Coding" code="fas fa-code" />
          <hobbies hobby="Cooking" code="fas fa-utensils" />
        </p>
      </div>
    </div>
    <br />
  </div>
</template>

<script>
import info from "./Sidebar/info.vue";
import heading from "./Sidebar/heading.vue";
import hobbies from "./Sidebar/hobbies.vue";
export default {
  name: "sidebar",
  components: {
    info,
    heading,
    hobbies
  }
};
</script>

<style scoped>
.all1 {
  background-color: black;
}
.all {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  background-color: black;
  color: white;
  text-align: left;
}
.center {
  align-content: center;
  margin-bottom: 40px;
  background-color: black;
}
.surname {
  color: skyblue;
}
.Profile {
  vertical-align: middle;
  align-content: center;
  text-align: center;
  width: 140px;
  height: 140px;
  border-radius: 50%;
  margin: 20px;
}
.title {
  color: white;
  margin-top: 10px;
  margin-left: 15px;
}
.subtitle {
  margin-left: 15px;
  margin-top: -10px;
}
.solid {
  border-top: 3px solid white;
  margin-bottom: 15px;
  margin-right: 20px;
  margin-top: -3px;
  margin-left: 5px;
}
.grey {
  color: grey;
}
.links {
  color: grey;
}
.v-progress-circular {
  margin: 1px;
  height: 50px;
  width: 50px;
}
</style>