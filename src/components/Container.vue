<template>
    <div class="cont">
        <img alt="Image" src="images/9.jpeg" width="180" height="250">
        <h1>Aleš Ďurčanský</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <p>Nulla pellentesque enim at semper eleifend. Nunc sit amet volutpat turpis.</p>
        <p>Integer gravida lacus eget ante tincidunt, at facilisis nisi et gravida.</p> 
        <p>Donec facilisis mattis auctor. Vestibulum ante ipsum primis in faucibus orci.</p>
        <a href="#home" target="_blank">Learn more</a>
        
    </div>

</template>

<style scoped>
.cont{
  overflow:hidden;
  color:grey;
  border: 2px;
  margin:25px;
  width:60%;
  height:30%;
  text-align: left;
  position:fixed;
  top: 30%;
  transform: translate(-50%, -50%);
}

.cont img{
    float: right;
}

a:link, a:visited {
  background-color: orange;
  color: white;
  margin:3%;
  padding: 8px 30px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}
a:hover, a:active {
  background-color: grey;
}

.textField{
    float:left;
    border: 2px;
    background-color: white;
}


</style>