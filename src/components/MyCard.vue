<template lang="">
    <div>

      <div class="card">
        <img :src="image" alt="name" style="max-width: 500px; width:100%" >
            <div class="container">
                <h4><b>{{ southern }}</b></h4>
                <p>{{ information }}</p>
                <p>{{ month }}</p>
            </div>
            
      </div>  
    </div>
</template>
<script>
export default {
    props:['southern','information','month','image']
    
}
</script>
<style scoped>

*{
  text-align: center;
  box-sizing: border-box;
  padding: 2%;
}

.card {
  box-shadow: 0 4px 8px 0 rgb(163, 4, 4);
  transition: 0.3s;
  width: 80%;
  height: 100%;
  font-size: 22px;
  display: flex;
  margin-left: auto;
  margin-right: auto;
  background-color: rgb(245, 209, 120);
  color: rgb(158, 117, 12);
}

.card:hover {
  box-shadow: 0 5px 10px 0 rgba(223, 162, 31, 0.897);
}

.container {
  padding: 2px 16px;
}
    
</style>