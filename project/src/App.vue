<template>
  <div>
    <PrimeiroComponente />
    <LifeCycle />
    <Pessoa/>
  </div>
</template>

<script>
import PrimeiroComponente from './components/primeiroComponente.vue'
import LifeCycle from './components/lifecycle.vue'
import Pessoa from './components/pessoa.vue'

export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle,
    Pessoa
  }
}
</script>