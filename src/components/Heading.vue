<template>
  <h1>{{ headingText }}</h1>
</template>

<script>
export default {
  props: {
    headingText: {
      type: String,
      required: true
    }
  }
}
</script>

<style>
@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
