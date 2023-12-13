<template>
    <div class="section">
       <div class = "information">
        <ul>
            <t>Get your own online Food Ordering App and Website</t>
        </ul>
        <ul>
            <p> Integrate the food ordering system in your restaurant 
                and grab the future. our restaurant online ordering software is 
                capable enough to serve your purposes successfully. 
            </p>
            <ul>No commision</ul>
            <ul>More control on customer data</ul>
            <ul>Free QR Code Menu</ul>
            <ul>Free Oneli ordering system</ul>
        </ul>
       </div>
       <div class = "imagesec">
        <img src="../assets/imgs/s1img.jpg" alt="Your Image Alt Text" />
       </div>
    </div>
    </template>
<script>
export default {
  name: 'SectionStyle'
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.section{
    display: flex;
}
.information{
    width: 55%;
    height: 500px;
}
.imagesec{
    width: 45%;
    height: 500px;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
  margin: 15px;
  text-align: left;
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
</style>
