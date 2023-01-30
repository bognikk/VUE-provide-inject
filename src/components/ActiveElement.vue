<template>
  <section>
    <h6>(active element)</h6>
    <h2>{{ topicTitle }}</h2>
    <p>{{ text }}</p>
  </section>
</template>

<script>
export default {
  props: ['topicTitle', 'text'],
};
</script>

<style scoped>
section {
  background-color: #E0B1B1;
}
h6 {
  margin: 0;
  padding: 0;
}
</style>
