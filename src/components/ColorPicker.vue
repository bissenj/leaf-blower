<template>
  <div class="q-pa-md">
    <q-color
      v-model="nullModel"
      default-value="#285de0"
      style="max-width: 250px"
    />
  </div>
</template>

<script setup>
defineOptions({
    name: 'ColorPicker'
})

</script>