<script setup>
  import {reactive} from 'vue'
  const state = reactive({showParagraph:false});
</script>

<template>
<div>
    <h1 class="text-center font-bold text-2xl">
        Тут могла бы быть фотография красивого котика, но мне лень это реализовывать
    </h1>
    <div class="border-red-2 p-6">
        <p class="text-center text-amber-4">
          может в следующий раз котики будут!
        </p>
    </div>
</div>

</template>
