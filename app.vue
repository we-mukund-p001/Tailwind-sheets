<template>
<div class="font-[inter]">
  <NuxtPage/>
</div>

</template>
<script setup>

import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'

onMounted(() => {
  initFlowbite();
})


</script>