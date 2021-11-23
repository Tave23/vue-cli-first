<template>
  <header>
     <h1>Questo è l'header</h1>
  </header>
</template>

<script>
export default {
   // gli si assegna il nome prima di importarlo
   name: "Header"
}
</script>

<style scoped>

   header{
      background: rebeccapurple;
      height: 80px;
      width: 100vw;
   }

   h1{
      text-align: center;
      color: white;
      line-height: 80px;
   }

</style>

