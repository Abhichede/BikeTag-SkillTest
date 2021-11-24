<template>
  <div>
    <Header/>
    <slot></slot>
    <Footer/>
  </div>
</template>
<script>
import Footer from "./Footer.vue";
export default {
    name: "Layout",
    components: { Footer }
}
</script>