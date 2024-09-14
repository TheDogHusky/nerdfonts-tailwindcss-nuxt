<script setup lang="ts">
const props = defineProps<{
  name: string
}>();

const iconClass = computed(() => {
  return `nf ${props.name}`;
});
</script>

<template>
  <i :class="iconClass"></i>
</template>

<style scoped>
@import url('~/assets/css/nf.css');
</style>