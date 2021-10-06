<template>
  <nav class="nav-bar">
    <nav-item text="Serviços" to="/services" />
    <nav-item text="Sobre mim" to="/services" />
    <nav-item text="Cases" to="/services" />
    <nav-item text="Contato" to="/services" />
  </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { NavItem } from '@/components/atoms';

export default defineComponent({
  components: { NavItem }
});
</script>

<style lang="scss" scoped>
.nav-bar {
  width: max-content;
  display: grid;
  grid-auto-flow: column;
  grid-gap: 2.5rem;
}
</style>
