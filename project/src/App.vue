<template>
  <div>
    <cabecalho/>
    <PrimeiroComponente />
    <LifeCycle />
    <Pessoa/>
  </div>
</template>

<script>
import PrimeiroComponente from './components/primeiroComponente.vue'
import LifeCycle from './components/lifecycle.vue'
import Pessoa from './components/pessoa.vue'
import cabecalho from './components/header.vue'

export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle,
    Pessoa,
    cabecalho
  }
}
</script> 

<style>
body {
  background-color: #333;
  color: #fff
}
a {
  color: red;
}
</style>