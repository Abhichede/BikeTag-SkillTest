<template>
  <div class="content text-center">
    <div class="head">
      Conheca o afora
    </div>
    <div class="body">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt
    </div>
    <div class="footer">
      <button class="btn btn-primary">Saber mais ></button>
    </div>
  </div>
</template>
<style scoped>
  .head {
    font-weight: bold;
    font-size: 20px;
    color: yellow;
  }
  .content {
    background: linear-gradient(rgba(37, 143, 224, 0.8), rgb(79,155,212, .8)), url("../static/kitchen.jpeg");
    border-radius: 20px;
    margin: 50px 0;
  }
  .content div {
    padding: 20px;
  }
  .btn-primary, .btn-primary:hover, .btn-primary:active {
    background-color: yellow;
    min-width: 200px;
    border-radius: 20px;
    border-color: yellow;
    color: black;
    font-weight: bold;
  }
</style>