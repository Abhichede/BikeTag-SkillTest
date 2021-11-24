<template>
  <div class="content">
    <h3>Main Vistos</h3>
    <div class="post">
      <p class="title">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt</p>
      <span class="date">14/12/2021 - Author</span>
    </div>
    <div class="post">
      <p class="title">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt</p>
      <span class="date">14/12/2021 - Author</span>
    </div>
    <div class="post">
      <p class="title">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt</p>
      <span class="date">14/12/2021 - Author</span>
    </div>
    <div class="post">
      <p class="title">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt</p>
      <span class="date">14/12/2021 - Author</span>
    </div>
  </div>
</template>
<style scoped>
  .content {
    margin: 50px 0;
  }
  .post {
    padding: 20px 0;
  }
  .post .title {
    color: black;
    font-size: 18px;
    line-height: 25px;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    overflow: hidden;
    text-overflow: ellipsis;
    margin: 0;
  }
  .post .date {
    font-size: 12px;
    color: grey;
  }
</style>