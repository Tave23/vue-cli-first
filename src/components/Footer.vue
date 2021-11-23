<template>
  <footer>
     <h4>Questo è il Footer</h4>
     <ul>
        <li><a href="#">link utile n1</a></li>
        <li><a href="#">link utile n2</a></li>
        <li><a href="#">link utile n3</a></li>
     </ul>
  </footer>
</template>

<script>
export default {
   // gli si assegna il nome prima di importarlo
   name: "Footer"
}
</script>

<style scoped>

   footer{
      height: 80px;
      width: 100vw;
      background: black;
      color: white;
      text-align: center;
   }

   h4{
     padding: 15px;
     font-size: 18px;
   }

   ul{
      display: flex;
      align-items: center;
      justify-content: space-around;
   }

   li{
      list-style: none;
      
   }

   li a{
      color: white;
      text-decoration: none;
   }
</style>