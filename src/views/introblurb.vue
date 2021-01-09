<template>
    <div class="introductoryblurb">
        <!-- list of components -->
        <body>
            <div class="content">
                <IntroductoryBlurb />
                <IntroductoryPic />
                <div class="content-inside"></div>
            </div>
        </body>
        <Footer />
  </div>
</template>

<script>
import IntroductoryBlurb from "@/components/IntroductoryBlurb.vue";
import IntroductoryPic from "@/components/IntroductoryPic.vue";

export default {
  name: "home",
  components: {
    IntroductoryBlurb,
    IntroductoryPic,
  },
};
</script>