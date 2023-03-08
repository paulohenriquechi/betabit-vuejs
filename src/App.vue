<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import Lifecycle from './components/Lifecycle.vue';
  import Pessoa from './components/Pessoa.vue';
  export default {
    name: "App",
    components: {
      PrimeiroComponente,
      Lifecycle,
      Pessoa
    }
  }
</script>

<template>
    <PrimeiroComponente/>
    <Lifecycle/>
    <Pessoa/>
</template>
