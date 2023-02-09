<template>
    <div>
    <h1>olá vue</h1>
    <P>meu nome é {{ nome }} e trabalho como {{ profissao }}</P>
</div>
</template>

<script>
export default {
    name:'PrimeiroComponente',
    data (){
        return {
            nome: "rafael",
            profissao: "programador"
        }
    }
}
</script>