<template>
    <div class="workexamples">
        <!-- list of components -->
         <NavBar />
        <body>
            <div class="content">
                <TechTeam />
                <LKY />
                <YouServe />
                <div class="content-inside"></div>
            </div>
        </body>
        <Footer />
  </div>
</template>

<script>
import TechTeam from "@/components/TechTeam.vue";
import LKY from "@/components/LKY.vue";
import YouServe from "@/components/YouServe.vue";


export default {
  name: "home",
  components: {
    TechTeam,
    LKY,
    YouServe
  },
};
</script>