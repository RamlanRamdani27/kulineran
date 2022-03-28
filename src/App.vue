<template>
  <div id="app">
    <router-view />
    <footer-component />
  </div>
</template>

<script>
import FooterComponent from "@/components/FooterComponent.vue";

export default {
  components: {
    FooterComponent,
  },
};
</script>
