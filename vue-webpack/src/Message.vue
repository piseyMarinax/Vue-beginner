<template>
    <div>
        <h1>{{ message }}</h1>
        <app-input :msg="message"  @messageChanged="message=$event"></app-input>
    </div>
</template>

<script>

    import Input from './Input.vue';

    export default {
        name: "app-message",
        data(){
            return {
                message: 'This is a message'
            }
        },
        components:{
            'app-input': Input
        }
    }
</script>

<style scoped>

</style>