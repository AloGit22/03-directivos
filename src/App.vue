<template>
  <div>
    <h1>Universidad Tecnologica de Tehuacan</h1>
    <h1> Directivas en VUE.js</h1>
    <hr />
    <h2>v-text</h2>
    <span v-text="'Hola desde la directiva v-text'"></span>
    <br>
    <span>Hola desde la directiva v-text</span>
    <br>
    <span v-text="titulo"></span>
    <br>
    Esta es una transmutacion de texto con una variable de prop
  </div>
</template>
<script>
  export default {
    data: () => ({
      titulo:"Hola desde VUE.js",
    })
  };
</script>
<style>
  div {
    text-align: center;
    margin: 0px 2rem;
  }
</style>

