<template>
  <div class="container mx-auto px-4" id="app">
    <nav-bar />
    <router-view />
  </div>
</template>
<script lang="ts">
import { defineComponent } from "vue";
import NavBar from "@/components/NavBar.vue";

export default defineComponent({
  name: "Home",
  components: {
    NavBar
  }
});
</script>
<style src="@/assets/styles/app.css"></style>
