<template>
  <nut-navbar @on-click-back="back" @on-click-title="title" title="Header">
    <template #left>
      <div>back</div>
    </template>
    <template #right>
      <ShareN width="16px" />
    </template>
  </nut-navbar>

</template>

<script setup>
import { ShareN, Cart2, MoreX } from '@nutui/icons-vue';
const back = () => {
  console.log('Click Back');
};
const title = () => {
  console.log('Click Title');
};
const rightClick = () => {
  console.log('Click Right');
};
const icon = () => {
  console.log('Click Icon');
};
</script>
