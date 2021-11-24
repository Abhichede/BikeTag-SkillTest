<template>
  <div class="footer-container">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-4 column">
          <span class="item">lorem ipsum</span>
          <span class="item">lorem ipsum</span>
          <span class="item">lorem ipsum</span>
          <span class="item">lorem ipsum</span>
          <span class="item">lorem ipsum</span>
        </div>
        <div class="col-8 column text-right">
          <span class="item">Lorem Ipsum is simply dummy text of the printing and typesetting</span>
          <span class="item">Lorem Ipsum is simply</span>
          <span class="item">Lorem Ipsum is simply dummy text of</span>
          <span class="item">Lorem Ipsum</span>
          <div class="social-links">
            Access nosas redes socials
            <span>
              FB
            </span>
            <span>
              YT
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Footer"
}
</script>
<style scoped>
.column {
  display: flex;
  flex-direction: column;
}
.footer-container {
  padding: 20px 0;
  background-color: #1F579E;
  color: white;
}
.item {
  font-weight: bold;
}
.social-links {
  font-size: 12px;
  font-weight: 400;
}
</style>