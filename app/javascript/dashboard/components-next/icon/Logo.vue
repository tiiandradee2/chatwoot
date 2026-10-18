<script setup>
import { useAttrs } from 'vue';
import { useMapGetter } from 'dashboard/composables/store';

const attrs = useAttrs();
const globalConfig = useMapGetter('globalConfig/get');
</script>

<template>
  <img
    v-if="globalConfig.logoThumbnail"
    v-bind="attrs"
    :src="globalConfig.logoThumbnail"
  />
  <svg
    v-else
    v-once
    v-bind="attrs"
    width="16"
    height="16"
    viewBox="0 0 16 16"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <rect width="16" height="16" rx="4" fill="#334155" />
    <path
      d="M3.5 6.75h9L11.2 11.5H4.8L3.5 6.75Z"
      stroke="white"
      stroke-width="1.2"
      stroke-linejoin="round"
    />
    <path
      d="M3.5 6.75 5.2 4.75h5.6l1.7 2"
      stroke="white"
      stroke-width="1.2"
      stroke-linecap="round"
      stroke-linejoin="round"
    />
  </svg>
</template>
