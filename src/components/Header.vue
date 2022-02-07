<template>
  <header>
    <Title />
  </header>
</template>

<script>
import Title from "@/components/Title.vue";
export default {
  name: "Header",
  Title,
};
</script>

<style>
header {
  background-color: red;
  height: 50px;
}
</style>