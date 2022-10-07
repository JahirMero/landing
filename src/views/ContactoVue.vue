<script>
  //import { defineComponent,orMounted, ref, watch } from "vue";
  //import {usePlaceStore} from '../../composables/usePlacesStore';
  //import Mapboxgl from 'mapbox-gl'

  //const mapElement = ref<HTMLDivElement>();
  //const {userLocation, isUserLocationReady}=usePlacesStore();
  //const iniMap = () => {
    //if(!mapElement.value)throw new Error('Div Element no exist');
    //if(!userLocation.value)throw new Error('user location no existe');
    //const map = new Mapboxgl.Map({
      //container: mapElement.value,
      //style:'mapbox://styles/mapbox/streets-vll',
      //center: userLocation.value,
      //zoom:15
    //});
  //}
  //orMounted(() => {
    //if(isUserLocationReady.value)
    //return iniMap();
  //})
  //watch( isUserLocationReady,(newVal)=>{
    //if(isUserLocationReady.value) iniMap();
 // })
  //return {
//    isUserLocationReady,
  //  mapElement
 // }
</script>
<template>
    <div class="contacto">
      <br>
      <h2 class="h">ESTAMOS UBICADOS
        EN PLAZA SESAMO, FRENTE A ESTO Y LO OTRO, 
        ALADO DE LAS MENESTRAS DEL NEGRO
      </h2>
      <br>
      <h2>GPS</h2>
      <br>
      <h2 class="h">contacto: 0999999999</h2>
    </div>
  </template>
  
  <style>
    .h{
        text-align: center;
    }
  @media (min-width: 1024px) {
    .about {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }
  }
  </style>
  