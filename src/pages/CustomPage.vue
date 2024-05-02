<template>
  <q-page class="flex flex-center">   
    <div>
      <h1 style="font-size: 2em">Custom Page</h1>
      <p>This is a quasar app.  For testing purposes. </p>
      <VertList />
      <BannerInline />
      <ColorPicker />
      <SampleDialog />
    </div>
  </q-page>
</template>

<script setup>
  import VertList from 'components/VertList.vue'
  import BannerInline from 'components/BannerInline.vue'
  import ColorPicker from 'components/ColorPicker.vue'
  import SampleDialog from 'components/SampleDialog.vue'

  defineOptions({
    name: 'CustomPage'
  });
</script>
