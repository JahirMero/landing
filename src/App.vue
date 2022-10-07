<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <br>
    <br>
    <br>
    <div class="wrapper">

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">Recetas de la casa</RouterLink>
      </nav>
    </div>
    
    
  </header>
  

  <RouterView />
  <div id="app">
      <navbar-container>
        <navbar-content>
          
          <RouterLink to="/contacto">
            <i class='bx bx-menu bx-burst bx-sm' ></i>
          </RouterLink>
          <router-link to="/contacto">
            <i class='bx bxl-whatsapp bx-tada bx-sm' ></i>
          </router-link>
          <router-link to="/contacto">
            <i class='bx bxs-message-dots bx-burst bx-sm' ></i>
          </router-link>
            
        </navbar-content>
      </navbar-container>
    </div>

</template>

<style scoped>
  /*
.hola1{
  background-color: #58D69C;
  align-items: center;
  position: fixed;
  font-size: 2.5rem;
  top: 500px;
  left: 40px;
  box-shadow: 5px 8px 12px 10px rgba(0, 0, 0, 0.445);

}
.hola2{
  position: fixed;
  align-items: center;
  background-color: #58D69C;
  font-size: 3rem;
  bottom: 100px;
  left: 200px;
  box-shadow: 5px 8px 12px 10px rgba(0, 0, 0, 0.445);
}*/
  
navbar-container{
  width: 100%;
  position: fixed;
  bottom: 0;
  background-color: rgb(245, 229, 14);
  left: 0%;
  height: 80px;
  

}
navbar-content{
    padding: 30px;
    display: flex;
    justify-content: space-between; 
    
}
a{
  color: rgb(0, 0, 0);

}



header {
  line-height: 1.5;
  max-height: 100vh;
}

nav {
  width: 100%;
  font-size: 20px;
  text-align: center;
  
}

nav a.router-link-exact-active {
  color: rgb(9, 255, 0);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
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

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
