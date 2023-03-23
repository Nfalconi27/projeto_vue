<template>
  <div>
    <PrimeiroComponente /> <!--<chamada do componente-->
    <!--<h1>Ola Mundo!</h1>-->
    <p>O dado do app é {{ testando }}</p>
  </div>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue';

  export default{
    name: 'App',
    components:{
      PrimeiroComponente
    },
    data(){ //também é possível incluir o data aqui
      return{
        testando: "Teste"
      }
    }
  }
</script>