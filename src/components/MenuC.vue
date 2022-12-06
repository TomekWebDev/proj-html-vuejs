<template>
  <div class="def">
    <PageC v-for="(elem, index) in pages" :key="index" :pageObj="elem" />
  </div>
</template>

<script>
import PageC from "./PageC.vue";

export default {
  name: "MenuC",
  components: { PageC },
  props: {
    pages: Array,
  },
};
</script>

<style lang="scss" scoped>
.def {
  display: flex;
  width: 70%;
  justify-content: space-around;
  text-align: center;
}
</style>