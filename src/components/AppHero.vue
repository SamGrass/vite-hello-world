<script>
    export default {
        name: "AppHero"
    }
</script>

<template>
    <div class="jumbotron">
        <h2>Questo è un jumbotron</h2>
    </div>
</template>

<style>
    .jumbotron {
        background-image: url(../assets/jumbotron.png);
        height: 400px;
        background-size: cover;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    h2 {
        font-size: 3rem;
        color: rgb(200, 212, 20);
    }
</style>