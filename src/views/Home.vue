<template>
  <div class="home">
    <details>
      <Banner />
      <TimeLine />
    </details>
    <div class="sidebar">
      <RecommendFollow></RecommendFollow>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import TimeLine from "@/components/TimeLine.vue";
import RecommendFollow from "@/components/TimeLine.vue";

export default {
  name: "Home",
  components: {
    TimeLine
  }
};
</script>

<style scoped>
</style>
