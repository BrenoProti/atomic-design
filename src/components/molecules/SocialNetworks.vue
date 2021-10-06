<template>
  <div class="social-networks">
    <SocialLink
      name="GitHub"
      icon="github.svg"
      to="http://www.github.com"
    />
    <SocialLink
      name="Twitter"
      icon="twitter.svg"
      to="http://www.twitter.com"
    />
    <SocialLink
      name="Facebook"
      icon="facebook.svg"
      to="http://www.facebook.com"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { SocialLink } from '@/components/atoms';

export default defineComponent({
  components: { SocialLink }
});
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
