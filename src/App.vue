<script setup>
//import HelloWorld from './components/HelloWorld.vue'
//import TheWelcome from './components/TheWelcome.vue'
import MyNev from './components/MyNev.vue'
import MyCard from './components/MyCard.vue'
import items from './mune.json'
</script>

<template>
<div>
  <header>
    <MyNev/>

    
    


    <!--<img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>-->
  </header>

  <main>
    <TheWelcome />
    <div className="grid-container">
      <MyCard v-bind="items[0]"/>
      <MyCard v-bind="items[1]"/>
      <MyCard v-bind="items[2]"/>
      <MyCard v-bind="items[3]"/>
      <MyCard v-bind="items[4]"/>
      <MyCard v-bind="items[5]"/>
      <MyCard v-bind="items[6]"/>
      <MyCard v-bind="items[7]"/>
      <MyCard v-bind="items[8]"/>
      <MyCard v-bind="items[9]"/>
      <MyCard v-bind="items[10]"/>
      <MyCard v-bind="items[11]"/>
    </div>

  </main>
</div>
</template>

<style scoped>

*{
  background-color: darkkhaki;
}

/*header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}*/
</style>
