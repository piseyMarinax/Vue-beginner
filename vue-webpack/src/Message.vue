<template>
    <div>
        <h1>This is a message</h1>
        <app-input></app-input>
    </div>
</template>

<script>

    import Input from './Input.vue';

    export default {
        name: "app-message",
        components:{
            'app-input': Input
        }
    }
</script>

<style scoped>

</style>