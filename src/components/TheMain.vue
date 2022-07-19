<template>
  <main class="main">
    <div class="container">
      <h1 class="h1">Lista de tarefas</h1>
      <section class="list">
        <FilmeVue 
          titulo="dragon ball"
          descricao="Dragon Ball is a Japanese media franchise created by Akira Toriyama in 1984. The initial manga, written and illustrated by Toriyama, was serialized in Weekly Shōnen Jump from 1984 to 1995, with the 519 individual chapters collected into 42 tankōbon volumes by its publisher Shueisha. Wikipedia"
        />
        <FilmeVue 
          titulo="dragon ball"
          descricao="Dragon Ball is a Japanese media franchise created by Akira Toriyama in 1984. The initial manga, written and illustrated by Toriyama, was serialized in Weekly Shōnen Jump from 1984 to 1995, with the 519 individual chapters collected into 42 tankōbon volumes by its publisher Shueisha. Wikipedia"
        /><FilmeVue 
          titulo="dragon ball"
          descricao="Dragon Ball is a Japanese media franchise created by Akira Toriyama in 1984. The initial manga, written and illustrated by Toriyama, was serialized in Weekly Shōnen Jump from 1984 to 1995, with the 519 individual chapters collected into 42 tankōbon volumes by its publisher Shueisha. Wikipedia"
        /><FilmeVue 
          titulo="dragon ball"
          descricao="Dragon Ball is a Japanese media franchise created by Akira Toriyama in 1984. The initial manga, written and illustrated by Toriyama, was serialized in Weekly Shōnen Jump from 1984 to 1995, with the 519 individual chapters collected into 42 tankōbon volumes by its publisher Shueisha. Wikipedia"
        /><FilmeVue 
          titulo="dragon ball"
          descricao="Dragon Ball is a Japanese media franchise created by Akira Toriyama in 1984. The initial manga, written and illustrated by Toriyama, was serialized in Weekly Shōnen Jump from 1984 to 1995, with the 519 individual chapters collected into 42 tankōbon volumes by its publisher Shueisha. Wikipedia"
        /><FilmeVue 
          titulo="dragon ball"
          descricao="Dragon Ball is a Japanese media franchise created by Akira Toriyama in 1984. The initial manga, written and illustrated by Toriyama, was serialized in Weekly Shōnen Jump from 1984 to 1995, with the 519 individual chapters collected into 42 tankōbon volumes by its publisher Shueisha. Wikipedia"
        /><FilmeVue 
          titulo="dragon ball"
          descricao="Dragon Ball is a Japanese media franchise created by Akira Toriyama in 1984. The initial manga, written and illustrated by Toriyama, was serialized in Weekly Shōnen Jump from 1984 to 1995, with the 519 individual chapters collected into 42 tankōbon volumes by its publisher Shueisha. Wikipedia"
        /><FilmeVue 
          titulo="dragon ball"
          descricao="Dragon Ball is a Japanese media franchise created by Akira Toriyama in 1984. The initial manga, written and illustrated by Toriyama, was serialized in Weekly Shōnen Jump from 1984 to 1995, with the 519 individual chapters collected into 42 tankōbon volumes by its publisher Shueisha. Wikipedia"
        /><FilmeVue 
          titulo="dragon ball"
          descricao="Dragon Ball is a Japanese media franchise created by Akira Toriyama in 1984. The initial manga, written and illustrated by Toriyama, was serialized in Weekly Shōnen Jump from 1984 to 1995, with the 519 individual chapters collected into 42 tankōbon volumes by its publisher Shueisha. Wikipedia"
        /><FilmeVue 
          titulo="dragon ball"
          descricao="Dragon Ball is a Japanese media franchise created by Akira Toriyama in 1984. The initial manga, written and illustrated by Toriyama, was serialized in Weekly Shōnen Jump from 1984 to 1995, with the 519 individual chapters collected into 42 tankōbon volumes by its publisher Shueisha. Wikipedia"
        />
      </section>
    </div>
  </main>
</template>

<script>
  import FilmeVue from './Filme.vue'
  export default {
    name: 'TheMain',
    components:{
      FilmeVue
    }
  }
</script>

<style>
.main{
  width: 100%;
}
.h1{
  margin: 10px;
  text-transform: uppercase;
}
.main .container{
  width: 100%;
  max-width: 1280px;
  margin: 0 auto;
}
.list{
  display: flex;
  gap: 5px;
  flex-wrap: wrap;
  justify-content: center;
}
</style>