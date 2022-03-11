<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex justify-center">
      <a href="https://github.com/alexohneander" class="text-2xl mx-2">
        <i class="fa-brands fa-github text-white"></i>
      </a>
      <a href="https://www.xing.com/profile/Alex_Wellnitz" class="text-2xl mx-2">
        <i class="fa-brands fa-xing text-white"></i>
      </a>
      <a href="https://dribbble.com/alexohneander" class="text-2xl mx-2">
        <i class="fa-brands fa-dribbble text-white"></i>
      </a>
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
