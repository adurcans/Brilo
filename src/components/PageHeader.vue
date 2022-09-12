<template>
<div class="head">
    <a href="#home">Home</a>
    <a href="#news">News</a>
    <a href="#contact">Contact</a>
</div>

</template>

<style scoped>
.head{
  overflow:hidden;
  background-color: orange;
  margin:25px;
  width:70%;
  height:7%;
  position: fixed;
  
  top: 0%;
  transform: translate(-50%, -50%);
}
.head a{
    float: right;
    color: white;
    text-align: center;
    padding: 16px 18px;
    text-decoration: none;
    font-size: 17px;
}
.head a:hover{
    background-color: grey;
    color: white;
}


</style>