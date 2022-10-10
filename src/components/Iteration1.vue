<template>
    <img :src="imagen" />
    <div :class="classes">Hola Mundo</div>
    <div :style="{backgroundColor: 'blue', color: 'red'}">Hola Mundo</div>
 
 </template>
 <script setup>
 
 const imagen = 'https://1000marcas.net/wp-content/uploads/2020/02/logo-Google.png';
 const classes = ['text', 'color', 'bg']
 
 </script>
 <style scoped>
 .text {
     font-size: 20px;
 }
 
 .color {
     color: pink;
 }
 
 .bg {
     background-color: red;
 }
 img  {
     width: 20vw;
 }
 
 </style>