<template>
    <div>
       <h4 class="text subtitle">{{msg}}</h4>
       <hr class="solid">
    </div>
</template>

<script>
export default {
    name: "ques",
    props: {
        msg: String
    }
};
</script>

<style scoped>
.text{
    text-align: left;
    margin-top: 10px;
}
.solid{
    margin-top: -20px;
    width: 100px;
    height: 1.5px;
    background-color: lightslategray;
}
</style>