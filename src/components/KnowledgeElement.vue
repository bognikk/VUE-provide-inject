<template>
  <li>
    <h6>(knowlege element)</h6>
    <h3>{{ topicName }}</h3>
    <p>{{ description }}</p>
    <button @click="selectTopic(id)">Learn More</button>
  </li>
</template>

<script>
export default {
  inject: ['selectTopic'],
  props: ['id', 'topicName', 'description'],
};
</script>

<style scoped>
li {
  background-color: #F2D56F;
}
h6 {
  margin: 0;
  padding: 0;
}
</style>