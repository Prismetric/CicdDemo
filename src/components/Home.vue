<template>
    <div class="home">
        <div class = "navbar">
            <t>foodiv</t>
        </div>
        <Section1 />
        <Section2 />
        </div>
    </template>
<script>
import Section1 from "./Section1.vue"
import Section2 from "./Section2.vue"
export default {
  name: 'HomePage',
  components:{
    Section1,
    Section2,
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar{
    width: 20%;
    align-self: self-start;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
t {
  color: rgb(247,99,48);
  font-size: 350%;
  font-weight: 900; 
  margin-top: 0%;
}
</style>
