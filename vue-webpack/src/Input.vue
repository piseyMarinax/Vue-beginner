<template>
    <div>
        <input type="text" name="" id="" v-model="message">
        <p>{{ message }}</p>
    </div>
</template>

<script>
    export default {
        name: "app-input",
        data() {
            return{
                message : '123'
            }
        }
    }
</script>

<style scoped>

</style>