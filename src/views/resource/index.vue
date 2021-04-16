<template>
  <div class="resource">
    <list />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import list from './components/list.vue'

export default Vue.extend({
  name: 'ResourceIndex',
  components: { list }
})
</script>

<style lang="scss" scoped></style>
