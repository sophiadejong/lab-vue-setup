<template>
    <img :src="imagen" />
    <div :style="{backgroundColor: 'white', color: 'red'}">Hello there!</div>
 
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