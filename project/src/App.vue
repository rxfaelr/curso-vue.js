<template>
  <div>
    <PrimeiroComponente />
    <LifeCycle />
  </div>
</template>

<script>
import PrimeiroComponente from './components/primeiroComponente.vue'
import LifeCycle from './components/lifecycle.vue'

export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle
  }
}
</script>