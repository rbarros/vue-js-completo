<template>
  <div id="titulo">
    {{ titulo }}
    <button @click="titulo += '#'">Alterar</button>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      titulo: 'Teste Data usando Vue JS!!'
    }
  }
}
</script>

<style>
  #titulo {
    background-color: chocolate;
    color: #fff;
  }
</style>