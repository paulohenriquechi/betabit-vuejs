<script>
    export default{
        name: 'Lifecycle',
        data(){
            return{
                nome: 'Unknown'
            }
        },
        created(){
            this.nome = "Henrique"
        }
    }
</script>

<template>
    <h1>Meu nome é: {{ nome }}</h1>
</template>