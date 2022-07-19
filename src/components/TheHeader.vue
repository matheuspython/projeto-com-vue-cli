<template>
  <header class="header">
    {{ title }}
  </header>
</template>

<script>
  export default {
    name:"TheHeader",
    props: {
      title: String
    }

  }
</script>

<style>
  .header{
    height: 75px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #373738;
    color: #fff;
    font-weight: bold;
    font-size: 20px;
  }
</style>