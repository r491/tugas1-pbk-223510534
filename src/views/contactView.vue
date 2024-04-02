<script setup>
import contact from '../components/contact.vue'
</script>
<template>
  <div class="contact">
   <contact/>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .contact {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
