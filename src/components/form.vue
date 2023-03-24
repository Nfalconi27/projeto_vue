<template>
    <div>
        <h2>Meu Formulário: </h2>
        <InputText />
        <InputText />
        <submit />
    </div>
    
</template>

<script>
import InputText from './form/InputText.vue';
import Submit from './form/Submit.vue';

export default{
    name: "form",
    components: { InputText, Submit }
}
    

</script>
