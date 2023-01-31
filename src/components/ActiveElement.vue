<template>
  <section>
    <h6>(active element)</h6>
    <h2>{{ topicTitle }}</h2>
    <p>{{ text }}</p>
  </section>
</template>

<script>
export default {
  props: ['topicTitle', 'text']
};
</script>

<style lang="scss" scoped>
section {
  background-color: #e0b1b1;

  h6 {
    margin: 0;
    padding: 0;
  }
}
</style>
