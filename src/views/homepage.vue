<template>
    <div class="homepage">
        <!-- list of components -->
        <body>
            <div class="content">
                <InitialCard />
                <div class="content-inside"></div>
            </div>
        </body>
        <Footer />
  </div>
</template>

<script>
import InitialCard from "@/components/InitialCard.vue";
export default {
  name: "home",
  components: {
    InitialCard,
  },
};
</script>