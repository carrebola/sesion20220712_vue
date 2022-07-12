<template>
  <div class="about">
    <h1>Personas</h1>
    <ul>
      <li v-for="item in arrayPersonas" :key="item.nombre">
      {{item.nombre}} {{item.apellido}}
      </li>
    </ul>
  </div>
  </template>


<script>
  export default  {
    data() {
      return {
        arrayPersonas: [
          {
            nombre: 'Pepe',
            apellido: 'Gote'
          },
          {
            nombre: 'Raul',
            apellido: 'Traderecha'
          }
        ]
      }
    },
    mounted(){
      
    }
  }
</script>

<style lang="scss" scoped>

</style>