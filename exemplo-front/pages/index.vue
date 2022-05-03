<template>
  <div>
    <h1>{{titulo}}</h1>
    <input v-model="titulo" type="text" name="" id="">
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data: function(){
    return{
      titulo: "Página de exmplo"
    }
  }
}
</script>
<style>
</style>
