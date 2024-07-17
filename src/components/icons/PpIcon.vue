<script setup lang="ts">
defineProps<{
  name: string;
}>();
</script>

<template>
  <img :src="`../../assets/images/icons/${name}.svg`" width="20" height="20" />
</template>
