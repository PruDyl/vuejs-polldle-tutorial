<template>
  <div>
    <createPolldle/>
    <footerPolldle/>
    <resultPolldle/>
  </div>
</template>

<script>
import footerPolldle from "@/components/FooterPolldle.vue";
import createPolldle from "@/components/CreatePolldle.vue";
import resultPolldle from "@/components/ResultPolldle.vue";

export default {
  name: "app",
  components: { footerPolldle, createPolldle, resultPolldle }
};
</script>

<style>
</style>
