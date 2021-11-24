<template>
  <div class="content row no-gutters">
    <div class="profile-pic col-4">
      <img src="../static/Abhijit.png" alt="Abhijit">
    </div>
    <div class="info column col-8">
      <span class="name">Nome do Autor</span>
      <span class="description">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt
      </span>
    </div>
  </div>
</template>
<style scoped>
  .column {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }
  .content {
    padding: 30px;
    margin: 50px 0;
    background: #3B91D9;
    border-radius: 10px;
  }
  .info {
    color: white;
  }
  .info .name {
    font-weight: bold;
  }
  .profile-pic img{
    width: 100px;
  }
  @media (max-width: 767px) {
    .profile-pic img{
      width: 70px;
    }
  }
</style>