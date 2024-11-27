<template>
  <div>
    <NuxtRouteAnnouncer />
    {{ numberExmp }}
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue';

const numberExmp = ref<number>(5);
</script>