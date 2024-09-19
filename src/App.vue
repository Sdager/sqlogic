<script setup>
// import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
 import Headerk from './components/Headerk.vue'
  import MainCard from './components/MainCard.vue'
  import Uslugi from './components/Uslugi.vue';
</script>

<template>
 <div><header>
<Headerk/>
    <!-- <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav> -->
</header>
<main>
<MainCard/>
<Uslugi/>
</main>
</div>

</template>

<style scoped>
template {  
 
  padding: 0px;
  margin: 0px;
 
}
header{
padding: 0.9em;
}
</style>
