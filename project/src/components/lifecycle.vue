<template>
    <h1>Meu nome é {{ nome }}</h1>
  </template>
  
  <script>
  export default {
    name: 'LifeCycle',
    data() {
      return { 
        nome: "Ainda não sei"
      }
    },
    created() {
        setTimeout(() => {
            this.nome = "carlao"
        }, 1000);
      this.nome = "rafael"
      this.lifecycle()
    },
    mounted () {
        setTimeout ( () => {
            this.nome = "jorge"
        },2000);
        this.lifecycle()
    },
    methods: {
      lifecycle (){
        console.log("deu certo")
      }
    }
  }
  </script>