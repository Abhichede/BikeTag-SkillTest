<template>
  <Layout>
    <HeroSection/>
    <div class="container">
      <div class="row body no-gutters justify-content-between">
        <div class="col-lg-7 col-md-7 col-sm-12">
          <PostContent />
          <hr>
          <AuthorCard />
        </div>
        <div class="col-lg-4 col-md-4 col-sm-12">
          <CTACard />
          <SimilarPosts />
          <ExternalLinks />
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
import PostContent from "../components/PostContent.vue";
import AuthorCard from "../components/AuthorCard.vue";
import CTACard from "../components/CTACard.vue";
import SimilarPosts from "../components/SimilarPosts.vue";
import ExternalLinks from "../components/ExternalLinks.vue";
export default { components: { PostContent, AuthorCard, CTACard, SimilarPosts, ExternalLinks } }
</script>
<style scoped>
.image {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
}
.image legend {
  font-size: 12px;
}
.body {
  padding: 50px 0;
}
/* @media (max-width: 767px) {
  .body {
    flex-direction: column;
  }
} */
</style>