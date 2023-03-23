<template>
  <PrimeiroComponente /> <!--<chamada do componente-->
  <!--<h1>Ola Mundo!</h1>-->
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue';

  export default{
    name: 'App',
    components:{
      PrimeiroComponente
    }
  }
</script>