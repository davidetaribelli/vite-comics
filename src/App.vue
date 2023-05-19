<script>
import AppHeader from './components/AppHeader.vue';
import AppMainUp from './components/AppMainUp.vue';
import AppMainDown from './components/AppMainDown.vue';
import AppFooterUp from './components/AppFooterUp.vue';
import AppFooterDown from './components/AppFooterDown.vue';

export default {
  components: {
    AppHeader,
    AppMainUp,
    AppMainDown,
    AppFooterUp,
    AppFooterDown,
  }
}
</script>

<template>
  <!-- header -->
  <header class="bg-light">
    <AppHeader />
  </header>

  <!-- main -->
  <main>
    <!-- parte superiore main -->
    <section id="mainUp" class="bg-dark">
      <AppMainUp />
    </section>

    <!-- parte inferiore main -->
    <section id="mainDown">
      <AppMainDown />
    </section>

  </main>

  <!-- footer -->
  <footer>
    <!-- parte superiore footer -->
    <section id="footerUp">
      <AppFooterUp />
    </section>
    <!-- parte inferiore footer -->
    <section id="footerDown">
      <AppFooterDown />
    </section>
  </footer>
</template>




