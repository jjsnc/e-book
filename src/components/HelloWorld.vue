<script setup lang="ts">
import { ref } from "vue";

defineProps<{ msg: string }>();

const count = ref(0);

function handleCount() {
  count.value++;
}
</script>

<template>
  <div class="page">{{ count }}</div>
  <div @click="handleCount">点击</div>
</template>

<style scoped lang="scss">
.read-the-docs {
  color: #888;
}
</style>
