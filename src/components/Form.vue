<script>
import InputText from './form/InputText.vue';
import Submit from './form/Submit.vue';
    export default{
        name: "Form",
        components: {
            InputText,
            Submit
        }
    }
</script>

<template>
    <form action="">
        <InputText/>
        <InputText/>
        <Submit/>
    </form>
</template>