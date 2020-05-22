<template>
  <div v-bind="$attrs">
    <label class="text-gray-600 text-sm">{{ label }}</label>
    <div class="text-md  text-gray-700"><slot /></div>

  </div>
</template>

<script>
  export default {
    name: 'keyset',
    props: ['label']
  }
</script>

<style scoped>

</style>
