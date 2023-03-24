<template>
  <div>
    <PrimeiroComponente /> <!--<chamada do componente-->
    <p>O dado do app é {{ testando }}</p>
    <LifeCycle />
    <Pessoa />
    <Form />
  </div>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue';
  import LifeCycle from './components/LifeCycle.vue';
  import Pessoa from './components/Pessoa.vue';
  import Form from './components/form.vue';


  export default{
    name: 'App',
    components:{
      PrimeiroComponente,
      LifeCycle,
      Pessoa,
      Form
    },
    data(){ //também é possível incluir o data aqui
      return{
        testando: "Teste"
      }
    }
  }
</script>