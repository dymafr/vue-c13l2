<template>
  <h3>La page B</h3>
  <br />
  <span>Utilisateur : {{ username }}</span>
  <input v-model="username" />
</template>

<script lang="ts">
export default {
  name: 'PageB',
};
</script>

<script setup lang="ts">
import { ref } from 'vue';
const username = ref('');
</script>

<style scoped lang="scss"></style>
