<script setup>
import GreatGrandChild from './GreatGrandChild.vue';
import useNumbers from '@/composables/useNumbers';

const { numbers } = useNumbers();
</script>

<template>
  <div>
    <h1>Grand Child</h1>
    {{ numbers }}
    <div class="line"></div>
    <GreatGrandChild />
  </div>
</template>