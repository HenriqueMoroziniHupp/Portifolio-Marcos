<template>
  <div class="social-networks">
    <SocialLink name="Github" to="https://www.github.com" icon="github.svg" />
    <SocialLink name="Facebook" to="https://www.facebook.com" icon="facebook.svg" />
    <SocialLink name="twitter" to="https://www.twitter.com" icon="twitter.svg" />
  </div>
</template>

<script lang="ts">
  import Vue from 'vue'

  export default Vue.extend({
    
  })
</script>
<style lang="scss" scoped>
.social-networks {
  display: grid;
  gap: 1rem;
}
</style>