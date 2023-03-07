<script>
    export default{
        name: "PrimeiroComponente",
        data(){
            return {
                nome: "Henrique"
            }
        }
    }
</script>

<template>
    <div>
        <h1>Hello Vue</h1>
        <p>Meu nome é {{ nome }}</p>
    </div>
</template>