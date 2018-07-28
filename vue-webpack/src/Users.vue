<template>
    <div>
        <h1>User</h1>

        <h2>Team ID : {{ $route.params.teamID }}</h2>

        <button @click="goHome">Home</button>
    </div>
</template>

<script>
    export default {
        name: "Users",
        watch:{
            '$route' (ro,from){
                // alert(this.$route.params.teamID);
            }
        },
        created(){
            // alert(this.$route.params.teamID);
        },
        methods:{
            goHome(){
                this.$router.push('/');
            }
        }
    }
</script>

