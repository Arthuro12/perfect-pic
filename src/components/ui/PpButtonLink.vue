<script setup lang="ts">
/**
 *
 */

defineProps<{
  isIconOnly: boolean;
  buttonText: string;
  link: string;
}>();
</script>

<template>
  <a v-if="isIconOnly" :href="link"></a>
  <a v-else :href="link">{{ buttonText }}</a>
</template>
