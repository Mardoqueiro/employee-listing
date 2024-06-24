<template>
  <div class="container">
   <div class="row">
     <h1>Class Testing</h1>
   </div>
   <div class="row">
     <Employees/>
   </div>
  </div>
   
 </template>
 
 <script>
 import Employees from '@components/Employees.vue'

 export default {
   name: 'App',
   components: {
     Employees
   }
 }
 </script>
 
 <style>
 #app {
   font-family: Avenir, Helvetica, Arial, sans-serif;
   -webkit-font-smoothing: antialiased;
   -moz-osx-font-smoothing: grayscale;
   text-align: center;
   color: #2c3e50;
   margin-top: 60px;
 }
 
 </style>