<template>
  <nav class="nav">
    <div class="container">
      <button class="logo">Linkedin quiz training</button>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Nav"
}
</script>

<style lang="scss" scoped>
 .nav {
   display: flex;
   justify-content: center;
   .container {
     .logo {
       background: #0b66c2;
       color: white;
       border: none;
       font-size: 22px;
       border-radius: 3px;
       max-width: 132px;
     }
   }
 }
</style>