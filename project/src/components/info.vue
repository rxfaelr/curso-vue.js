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
    </p>
</div>
</template>

<script>
export default {
    name: 'Info',
    data () {
        return {
            esta_trabalhando: false,
            mostrar_email: true,
            email: 'rafael@gmail.com'
        }
    }
}
</script>