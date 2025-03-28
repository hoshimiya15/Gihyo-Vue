<script setup lang="ts">
import { ref, computed } from 'vue'

const widthOrHeight = ref('height')
const widthOrHeightValue = ref(500)
</script>

<template>
  <p><img alt="VueLogo" src="./assets/logo.svg" v-bind:[widthOrHeight]="widthOrHeightValue" /></p>
</template>
