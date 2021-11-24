<template>
  <div class="container">
    <div class="row header-container justify-content-between align-items-center">
      <div class="col-4 logo">Logo.JPG</div>
      <div class="col-8">
        <a href="/" class="link">Home</a>/
        <a href="#" class="link">Nassos Produtos</a>/
        <a href="#" class="link">Bolg</a>/
        <a href="#" class="link">Fale Conosco</a>
      </div>
    </div>
    <div class="row breadcrumbs">
      Home / Bolg / Dicas de  applicacao de produto / Tudo o que voce precia
    </div>
  </div>
</template>
<script>
export default {
  name: "Header"
}
</script>
<style scoped>
  .header-container {
    padding: 30px;
  }
  .link {
    padding: 0 20px;
    text-decoration: none;
    color: black;
  }
  .link:active {
    color: blue;
  }
  .breadcrumbs {
    font-size: 12px;
    margin-left: 30px;
  }
  .logo {
    padding: 15px 20px;
    background: black;
    color: white;
    text-transform: uppercase;
    font-size: 30px;
    font-weight: 800;
    max-width: 200px;
  }
</style>