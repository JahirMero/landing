<script setup lang="ts">

</script>

<template>
  <div class="home">
    <br>
    <br>
    <div class="header">
      <H1 class="title">Somos lo mejor en <b>Hamburguesas</b> </H1>
      <p></p>
      <br>
    <br>
    <br>
    <br>
      <div class="combo-header">
      <div class="texto">
        <h3 class="subtitulo">Combo parrilla</h3>
        <p class="descripcion">hamburguesa + coca-cola</p>
      </div>
      <div class="img">
        <img src="https://img.freepik.com/foto-gratis/deliciosa-hamburguesa-queso_1232-503.jpg?w=2000" alt="">
      </div>
    </div>
    <br>
    <br>
    <div class="combo-header">
      <div class="texto">
        <h3 class="subtitulo">Combo parrilla</h3>
        <p class="descripcion">hamburguesa + coca-cola</p>
      </div>
      <div class="img">
        <img src="https://img.freepik.com/foto-gratis/deliciosa-hamburguesa-queso_1232-503.jpg?w=2000" alt="">
      </div>
    </div>
    <br>
    <br>
    <div class="combo-header">
      <div class="texto">
        <h3 class="subtitulo">Combo parrilla</h3>
        <p class="descripcion">hamburguesa + coca-cola</p>
      </div>
      <div class="img">
        <img src="https://img.freepik.com/foto-gratis/deliciosa-hamburguesa-queso_1232-503.jpg?w=2000" alt="">
      </div>
    </div>
    <br>
    <br>
    <div class="combo-header">
      <div class="texto">
        <h3 class="subtitulo">Combo parrilla</h3>
        <p class="descripcion">hamburguesa + coca-cola</p>
      </div>
      <div class="img">
        <img src="https://img.freepik.com/foto-gratis/deliciosa-hamburguesa-queso_1232-503.jpg?w=2000" alt="">
      </div>
    </div>
    </div>
    <br>
    <h2 class="title"> <b>Bebidas</b></h2>
    <div class="scrollsito">
      <div :key="index" class="bebidas" v-for="(item,index) in 10 ">
        <div class="bebidas-img">
          <img  src="https://licoreschullavida.com/wp-content/uploads/2020/07/Coca-cola-1-litro.jpg" alt="">
        </div>
        <div class="nombre">fanta</div>
      </div>
    </div>
  </div>
</template>

<style >
  .scrollsito{
    display: flex;
    overflow-y: auto ;
    
  }
  .bebidas{
    background-color: rgb(250, 348, 248);
    min-width: 100px;
    position: relative;
    padding: 5px;
    border-radius: 10px;
    margin: 5px;
  }
  .nombre{
    top: 10px;
    color: rgb(163, 163, 163) ;
  }
  .bebidas-img{
    width: 100%;


  }
  .title{
    font-weight: 10;
    background-color: aliceblue;
    border-radius: 20%;
    align-items: center;
  }

  .home{
    margin: 20px;
  }
  .combo-header{
    background-color: rgb(8, 179, 2);
    color: white;
    padding: 10px;
    border-radius: 20px;
    display: flex;
    align-items: center;
    box-shadow: 5px 8px 12px rgba(0, 0, 0, 0.445);
    
  }
  .subtitulo{
    font-weight: 400;
    width: 80%;

  }
  .descripcion{
    font-weight: 300;
    width: 50%;
  }
  .img{
    width: 50%;
    object-fit: cover;
  }
  img{
    width: 100%;
  }

</style>
