<script>
export default {
  name: 'add-hero-btn',
  props: {
    text: {
      type: String,
      default: 'Add Hero',
    },
  },
};
</script>

<template>
  <a
    class="f6 link dim ph3 pv2 mb2 dib white bg-light-purple"
    href="#0"
    @click="$emit('add-hero', true)"
    >{{ text }}</a
  >
</template>
