<template>
  <div class="menu-create">
    <create-or-edit />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import createOrEdit from './components/createOrEdit.vue'
export default Vue.extend({
  name: 'MenuCreate',
  components: { createOrEdit }
})
</script>
<style lang='scss'>
</style>
