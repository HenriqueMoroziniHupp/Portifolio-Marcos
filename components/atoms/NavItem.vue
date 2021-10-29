<template>
  <a class="nav-item" :href="to">
    {{ text }}
  </a>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  props: {
    text: { type: String, required: true },
    to: { type: String, required: true }
  }
})
</script>

<style lang="scss" scoped>
.nav-item {
  color: #293947;
  text-decoration: none;
  font-size: 1.3rem;
}
</style>
