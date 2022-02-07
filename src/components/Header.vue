<template>
  <header>
    <Title />
  </header>
</template>

<script>
import Title from "@/components/Title.vue";
export default {
  name: "Header",
  components: {
    Title,
  },
};
</script>

<style scoped>
header {
  background-color: red;
  height: 100px;
}
</style>