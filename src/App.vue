<template>
  <div>
    <Button label="Haz clic" @click="saludar" />
  </div>
</template>

<script setup>
  function saludar() {
    alert("Hola desde PrimeVue!")
  }
</script>