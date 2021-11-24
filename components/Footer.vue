<template>
  <div class="footer-container">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-4 col-md-4 col-sm-12 column text-center">
          <span class="item">lorem ipsum</span>
          <span class="item">lorem ipsum</span>
          <span class="item">lorem ipsum</span>
          <span class="item">lorem ipsum</span>
          <span class="item">lorem ipsum</span>
        </div>
        <div class="col-lg-8 col-md-8 col-sm-12 column right-column">
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
.right-column {
  text-align: right;
}
@media (max-width: 767px) {
  .right-column {
    text-align: center;
  }
}
</style>