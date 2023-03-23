<template>
    <div>
        <h1>Olá Vue!</h1>
        <p>Meu nome é {{ nome }} e trabalho como {{ profissao }}</p>
    </div>
</template>

<script>
    export default{
        name: 'PrimeiroComponente',
        data(){ // componente de inclusão de dados no componente
            return{
                nome: "Nelson",
                profissao: "programador"
            }
        }
    }
</script>