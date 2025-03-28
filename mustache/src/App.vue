<script setup lang="ts">
import { ref, computed } from 'vue'

const url = ref('https://vuejs.org/')
</script>

<template>
  <p><a v-bind:href="url" target="_blank">Vue.jsのサイト</a></p>
  <p><a :href="url" target="_blank">Vue.jsのサイト（省略形）</a></p>
  <p><a v-bind:href="url + 'guide/introduction.html'" target="_blank">Vue.jsガイドのページ</a></p>
</template>
