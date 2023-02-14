<template>
<form action="" @submit="enviarForm($event)">
<div><InputText/></div>
<div><InputText/></div>
<div><Submit/></div>
</form>
</template>

<script>
import InputText from './form/inputText.vue'
import Submit from './form/submit.vue'

export default {
    name: 'Form',
    components: {
        Submit,
        InputText
    },
    methods: {
        enviarForm (e) {
            e.preventDefault();

            console.log("formulario enviado")
        }
    }
}
</script>