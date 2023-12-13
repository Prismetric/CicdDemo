<template>
    <div class="section">
       <div class = "information">
        <ul>
            <t>Our Online Food Ordering System Caters</t>
        </ul>
       </div>
       <div class="content">
            <div class="card">
                <st>Pizza ordering Ststem</st>
            </div>
            <div class="card">
                <st>Pizza ordering Ststem</st>
            </div>
            <div class="card">
                <st>Pizza ordering Ststem</st>
            </div>
       </div>
       <div class="content2">
            <div class="card">
                <st>Pizza ordering Ststem</st>
            </div>
            <div class="card">
                <st>Pizza ordering Ststem</st>
            </div>
            <div class="card">
                <st>Pizza ordering Ststem</st>
            </div>
       </div>
    </div>
    </template>
<script>
export default {
  name: 'Section2Style'
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.content{
    display: flex;
}
.content2{
    display: flex;
    margin-top: 5%;   
}
.card{
    width: 400px;
    height: 150px;
    background-color: #fff;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    display: flex;
    margin-right: 20px;
}
.section{
    padding-top: 10%;
    height: 500px;
}
.information{
    width: 100%;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
  margin: 15px;
  text-align: center;
}
li {
  display: inline-block;
  margin: 15px;
  text-align: left;
}
p {
  display: inline-block;
  margin: 15px;
  text-align: left;
}
t {
  color: black;
  font-size: 250%;
  font-weight: 600;
  text-shadow: 0 10px 8px rgba(0, 0, 0, 0.1); /* Set your desired shadow properties */  
  margin: 10px;
}
st {
  color: black;
  font-size: 150%;
  font-weight: 200;
}
</style>
