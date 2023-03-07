<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import Lifecycle from './components/Lifecycle.vue';
  export default {
    name: "App",
    components: {
      PrimeiroComponente,
      Lifecycle
    }
  }
</script>

<template>
    <PrimeiroComponente/>
    <Lifecycle/>
</template>
