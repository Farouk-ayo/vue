<script setup>
import Navbar from "./components/Navbar.vue";
import { RouterView } from "vue-router";
import "vue-sonner/style.css";
import { Toaster } from "vue-sonner";
</script>

<template>
  <Toaster position="top-right" richColors />
  <Navbar />
  <RouterView />
</template>
