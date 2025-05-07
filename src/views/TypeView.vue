<script setup>
import Type from "../components/Types.vue"
const arrayOfTypes = ["Шотландская","Мейн-кун","Бенгальская"];
</script>

<template>
<div class="ml-2 flex gap-2">
  <Type v-for="(item,index) in arrayOfTypes" v-bind:id="index" :title="item"></Type>
</div>
  <p class="ml-2 text-gray-300"> 'это мои любимые породы кошек!!!!!!!'</p>


</template>

<style scoped>

</style>