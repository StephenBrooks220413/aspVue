<template>
    <div class="home">
        <div class="jumbotron">
            <h1>{{ msg }}</h1>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Home',
        props: {
            msg: String
        }
    };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>

