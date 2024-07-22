<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex flex-col items-center">
      <div class="header__logo">
        <nuxt-link to="/">
          <img src="/images/uploads/logo.png" alt="Logo" />
        </nuxt-link>
      </div>
      <div class="footer__text mt-4 text-center">
        <p class="text-white">Serving El Paso, Santa Teresa, and Las Cruces</p>
        <p class="text-white font-bold">123-456-7890</p>
      </div>
    </div>
  </footer>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator';

@Component
export default class Footer extends Vue {}
</script>

<style lang="scss">
.footer {
  background-color: $bluise;
}
</style>
