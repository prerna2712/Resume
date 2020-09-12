<template>
  <div class="mar">
    <div>
      <ques msg="About Me" />
      <h2 class="text">
        <p>I am a Student Developer from Howrah, India, pursuing my bachelors' degree in Information Technology.</p>
        <p>Beside being a  Web Development and Competitive Programming enthusiast, I also like reading abount the hidden mysteries of the universe.</p>
      </h2>
    </div>
    <br />
    <br />
    <div>
      <ques msg="Education" />
      <div class="columns">
        <div class="column is-three-fifths">
          <strong>Bachelors' Dregree, Information Technology</strong>
          <p>Indian Institue of Engineering Science and Technology</p>
          <p>Shibpur, Howrah</p>
        </div>
        <div class="column">2019-2023</div>
      </div>
    </div>
    <br />
    <br />
    <div>
      <ques msg="Skills" />
      <br>
      <div class="columns">
        <div class="column is-half mar">
          <bars num="50" name="C++" code="fas fa-laptop-code fa-black" />
          <bars num="20" name="Flutter" code="fas fa-mobile" />
        </div>
        <div class="column is-half mar">
            <bars num="10" name="VueJS" code="fab fa-vuejs" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ques from "./About/ques.vue";
import bars from "./About/bars.vue";
export default {
  name: "about",
  components: {
    ques,
    bars
  }
};
</script>

<style scoped>
.text {
  text-align: left;
}
.column {
  text-align: left;
}
.mar{ 
    margin-right: 10px;
    margin-left: 10px;
}
</style>