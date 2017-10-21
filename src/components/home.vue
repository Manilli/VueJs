<template>
  <div>
    <h2>Home</h2>
    <h1>{{campoX}}</h1>
      <input type="text" placeholder="Introducir tarea" v-model="nuevaTarea">
      <input type="button" value="Enviar tarea" v-on:click="agregarTarea">      
  </div>

</template>

<script>
export default{
  data(){
    return{nuevaTarea:'', campoX:''}
  },
   methods:{agregarTarea(){
     this.campoX=this.nuevaTarea;

   }}
}
</script>

<style>
</style>
