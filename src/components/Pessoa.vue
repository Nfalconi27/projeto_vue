<template>
    <div>
        <h2>Esta é a descrição da pessoa: {{ nome }}</h2>
        <Info />
        <form />
    </div>
</template>

<script>
import Form from './form.vue';
import Info from './Info';

export default {
    name: "Pessoa",
    components: {
        Info,
        Form
    },
    data(){
        return{
            nome: "Mariana"
        }
        
    }
}

</script>