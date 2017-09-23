<template>
    <div id="app">
    <my-menu title="Primeira aplicação" teste="na parte de componente"></my-menu>
        <h1>{{ msg }}</h1>

    </div>
</template>

<script>
    import myMenu from "./myMenu.vue";

    export default {
        components: {
            myMenu
        },

        data () {
            return {
                msg: 'Hoje é dia de miça doidho, ce góspeu e pá na pas de Jová vei doido'
            }
        }
    }
</script>

<style>
    body {
        font-family: Helvetica, sans-serif;
    }
</style>
