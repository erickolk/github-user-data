<script>

export default {
  data(){
    return{
      count: 0
    }
  }
}

</script>

<template>
  <button  v-on:click="count++">Contador: {{ count }}</button>
</template>

<style>
#app{
  display: grid;
  place-content: center;
  min-height: 100vh;
}

button{
  font-size: 2rem;
}
</style>