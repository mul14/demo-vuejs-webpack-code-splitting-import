<template>
  <div>
    <Header />
    <MainContent />
    <Footer />
  </div>
</template>

<script>
export default {
  name: 'App',

  components: {
    Header: () => import('./Header.vue'),
    MainContent: () => import('./MainContent.vue'),
    Footer: () => import('./Footer.vue'),
  }
}
</script>
