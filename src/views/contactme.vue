<template>
    <div class="contactme">
        <!-- list of components -->
         <NavBar />
        <body>
            <div class="content">
                <Email />
                <Facebook />
                <Instagram />
                <LinkedIn />
                <div class="content-inside"></div>
            </div>
        </body>
        <Footer />
  </div>
</template>

<script>
import Email from "@/components/Email.vue";
import Facebook from "@/components/Facebook.vue";
import Instagram from "@/components/Instagram.vue";
import LinkedIn from "@/components/LinkedIn.vue";

export default {
  name: "home",
  components: {
    Email,
    Facebook,
    Instagram,
    LinkedIn,
  },
};
</script>