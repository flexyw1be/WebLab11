<script setup>
import {defineProps} from "vue"
const props = defineProps({title:""})
</script>

<template>
<div class="mt-6 border border-gray-800 flex-col items-center min-h-20 min-w-20">
  <h1 class="text-center font-bold">{{props.title}}</h1>
</div>
</template>
