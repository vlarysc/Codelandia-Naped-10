<template>
  <div class="home">
    <Main />
    <Article />
    <Aside />
    <Footer />
  </div>
</template>

<script>

import Main from "@/components/Main.vue";
import Article from "@/components/Article.vue";
import Aside from "@/components/Aside.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Main,
    Article,
    Aside,
    Footer,
  },
};
</script>
