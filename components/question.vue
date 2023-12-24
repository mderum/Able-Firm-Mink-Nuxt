<template>
  <div class="question-container">
    <span class="question-text heading4">{{ Question }}</span>
    <span class="question-text1">{{ Answer }}</span>
  </div>
</template>

<script>
export default {
  name: 'Question',
  props: {
    Answer: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non volutpat turpis. Mauris luctus rutrum mi ut rhoncus.',
    },
    Question: {
      type: String,
      default: 'What types of cars do you sell?',
    },
  },
}
</script>

<style scoped>
.question-container {
  gap: var(--dl-space-space-unit);
  flex: 1;
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.question-text {
  font-weight: 700;
  line-height: 1.6;
}
.question-text1 {
  color: var(--dl-color-gray-800);
  line-height: 1.6;
}
</style>
