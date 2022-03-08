<template>
  <div class="app-container">
    <my-addition></my-addition>
    <hr />
    <my-substration></my-substration>
  </div>
</template>

<script>
import Addition from '@/components/Addition.vue'
import Substration from '@/components/Subtraction.vue'
export default {
  name: 'MyApp',
  components: {
    'my-addition': Addition,
    'my-substration': Substration,
  },
}
</script>

<style></style>
