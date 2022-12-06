<template>
  <div class="def">
    <div>{{ pageObj.name }}</div>
  </div>
</template>

<script>
export default {
  name: "PageC",
  components: {},
  props: {
    pageObj: Object,
  },
};
</script>

<style lang="scss" scoped>
.def {
  text-align: center;
}
</style>