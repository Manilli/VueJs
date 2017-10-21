<template>
  <div>
    <h2>Contacto</h2>
    <li v-for= "tar in tarea" >
      {{tar}}
    </li>
  </div>

</template>

<script>
export default{
  data(){
    return{tarea:[
      'Primer elemento', 'Segundo', 'Tercero'
    ]
    }
  }
}
</script>

<style>
</style>
