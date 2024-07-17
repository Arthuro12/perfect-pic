<script setup lang="ts">
/**
 *
 */

defineProps<{
  type: "submit" | "reset" | "button";
  buttonText: string;
}>();
</script>

<template>
  <button :type="type">{{ buttonText }}</button>
</template>
