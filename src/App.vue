<template>
  <div>
    <PrimeiroComponente /> <!--<chamada do componente-->
    <p>O dado do app é {{ testando }}</p>
    <LifeCycle />
  </div>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue';
  import LifeCycle from './components/LifeCycle.vue';

  export default{
    name: 'App',
    components:{
      PrimeiroComponente,
      LifeCycle
    },
    data(){ //também é possível incluir o data aqui
      return{
        testando: "Teste"
      }
    }
  }
</script>