<template>
  <div class="box">
    <h1>{{ titulo }}</h1>
    <p>{{ descricao }}</p>
  </div>
</template>

<script>
  export default {
    name: 'FilmeVue',
    props: {
      titulo: String,
      descricao: String,
    }
  }
</script>

<style>
  .box{
    width: 100%;
    max-width: 300px;
    color: white;
    border-radius: 12px;
    border: 1px solid #fff;
    padding: 15px;
    transition: .4s;
  }
  .box h1{
    text-transform: uppercase;
  }
  .box:hover{
    max-width: 350px;
    border: 1px solid #0dff86;
    color: #0dff86;
  }
</style>