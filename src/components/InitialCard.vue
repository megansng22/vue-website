<template>
    <div class="intialcard">
    <img src="../assets/logo.png" class="logo"/>
    <h1 class="initialheader">Hi! Welcome to my portfolio.</h1>
    <h4 class="extratext">follow the links below to see:</h4>
    <b-button>
     <a
        id="aboutme"
        style="float: none"
        href="introblurb.vue"
        target="_blank"
        >who I am</a
     >
    </b-button>
    <b-button>
     <a
        id="mywork"
        style="float: none"
        href="workexamples.vue"
        target="_blank"
        >what I do</a
     >
    </b-button>
    <b-button>
     <a
        id="contactme"
        style="float: none"
        href="contactme.vue"
        target="_blank"
        >where to find me</a
     >
    </b-button>
    </div>
</template>

<script>
export default {
    props: ["name"],
};
</script>
<style>

</style>
