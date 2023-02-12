<template>
<div>
    <p>
        <p v-if="esta_trabalhando">Estou trabalhando</p>
        <p v-else>NAO TRABALHO</p>
        <p>utilizando as seguintes tecnologias:</p>
    <ul>
        <li>Vue.js</li>
        <li>Flutter</li>
        <li>C#</li>
    </ul>
    <p v-show="mostrar_email">mande um email para {{ email }}</p>
    <p>Para acessar meu portifolio basta <a v-bind:href="meu_link">basta clicar aqui</a></p>
    <foto/>
    </p>
</div>
</template>

<script>
import foto from './picture.vue';
export default {
    name: 'Info',
    components: {
        foto
    },
    data () {
        return {
            esta_trabalhando: false,
            mostrar_email: true,
            email: 'rafael@gmail.com',
            meu_link: 'https://rxfaelr.github.io/my-portfolio/'
        }
    }
}
</script>