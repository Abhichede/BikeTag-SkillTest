<template>
  <Layout>
    <HeroSection/>
    <div class="container">
      <div class="row body no-gutters justify-content-between">
        <div class="col-7">
          <PostContent />
          <hr>
          <AuthorCard />
        </div>
        <div class="col-4">
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
</style>