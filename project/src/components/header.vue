 <template>
<ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">Projetos</a></li>
    <li><a href="#">Contato</a></li>
    <li><a href="#">Sobre</a></li>
</ul>
 </template>

 <script>
export default {
    name: 'cabecalho'
}
</script>

<style scoped>
ul {
    list-style: none;
    display: flex;
    background: red;
}
li {
    margin-right: 10px;
}
a {
    color: #ddd;
    text-decoration: none;
    transition: .5s;
}
a:hover{
    color: turquoise
}
</style>