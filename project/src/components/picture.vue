<template>
    <img :src="avatar" :alt="descricao">
</template>

<script>
export default {
    name: 'foto',
    data () {
        return {
            avatar: "/img/imagem.jpeg",
            descricao: "imagem teste"
        }
    }
} 
</script>