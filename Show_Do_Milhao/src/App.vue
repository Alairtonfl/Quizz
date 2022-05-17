<template>
  <div id="App">
    <router-view />
  </div>
</template>


<script>
export default {
  name: "App",
};
</script>

<style scoped>
    *{
     height: 625px;
     background-color: #000;   
    }
    body, html {
    width: 100%;
    height: 100%;
    }
</style>
