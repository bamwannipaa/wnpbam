<template lang="">
    <div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#news">News</a></li>
            <li><a href="#contact">Contact</a></li>
            <li style="float:right"><a class="active" href="#about">About</a></li>
        </ul><br>

    </div>

    <div class="c1">
        <h1>12 ประเพณีทางภาคใต้</h1>
        </div><br>

</template>


<script>
export default {
    
}
</script>

<style scoped>

*{
  color: rgb(48, 30, 210);
}

.c1{
  text-align: center;
  text-decoration: underline ;
  text-shadow: 3px 2px rgb(99, 217, 238);
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #e4e670;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  color: black;
  font-size: 20px;
}

li a:hover:not(.active) {
  background-color: #111;
}

้.c1{
  text-align: center;
}

.active {
  background-color: #d87751;
}
    
</style>