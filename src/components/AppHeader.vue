<script>
export default {
  name: 'AppHeader'
}
</script>

<template>

  <header>
    <div class="container p-4 d-flex justify-content-between">
      <img src="../assets/img/avadabarbers-stickylogo-x1.png" alt="">
      <div class="nav">
        <i class="fa-solid fa-bars"></i>
        <i class="fa-solid fa-cart-shopping"></i>
      </div>
    </div>
  </header>
  
</template>

<style lang="scss" scoped>

  header{
   position: absolute; 
  }
  i{
    color: black;
  }
</style>