<template>
<div>
  <article class="media">
    <figure class="media-left">
      <p class="icons">
        <i :class="code"></i>
      </p>
    </figure>
    <div class="media-content">
      <div class="content">
         <div class="head">{{ head }}</div>
      <div class="grey">{{ body }}</div>
      </div>
    </div>
  </article>
</div>
</template>

<script>
export default {
  name: "info",
  props: {
    head: String,
    body: String,
    code: String
  }
};
</script>

<style scoped>
.grey {
  color: grey;
  margin-bottom: 15px;
}
.margin {
  margin-left: 15px;
}
.head{
  margin-bottom: -5px;
}
.media-left{ 
  margin-left: 10px;
}
.icons{
  color: white;
}
</style>