<script setup>
import { ref, reactive, computed, onMounted, watch } from 'vue'
import childComp from "./components/childComp.vue"

const title = ref("Título")
const subtitle = ref("nah")
</script>

<template>
  <childComp>
    b
  </childComp>
</template>

<style></style>