<template>
  <div>
    <TheHeader />

    <main>
      <Nuxt />
    </main>
    
    <TheFooter />
  </div>
</template>

<script>
export default {
  mounted() {
    AOS.init();
  },
}
</script>