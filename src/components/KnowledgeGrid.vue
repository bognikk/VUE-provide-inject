<template>
  <div>
    <h6>(knowledge grid)</h6>
    <ul>
      <knowledge-element
        v-for="topic in topics"
        :key="topic.id"
        :id="topic.id"
        :topic-name="topic.title"
        :description="topic.description"
      ></knowledge-element>
    </ul>
  </div>
</template>

<script>
export default {
  inject: ['topics'],
};
</script>

<style scoped>
div {
  background-color: #6FF2C4;
  padding: 10px;
  border-radius: 15px;
}

</style>
