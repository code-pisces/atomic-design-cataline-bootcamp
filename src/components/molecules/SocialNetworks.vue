<template>
  <div class="social-networks">
    <SocialLink to="https://github.com/" name="Github" icon="github.svg" />
    <SocialLink to="https://twitter.com/" name="Twitter" icon="twitter.svg" />
    <SocialLink to="https://facebook.com/" name="Facebook" icon="facebook.svg" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms'

export default defineComponent({
  components: {
    SocialLink
  }
})
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>