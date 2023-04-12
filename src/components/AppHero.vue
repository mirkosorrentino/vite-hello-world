<script>
export default {
    name: "AppTitle",
    data(){
        return {
            jumboParagraph: "Con Vite all'inizio sembra tutto più complicato ma poi si potranno gestire grandi progetti.",
            jumboImage: "img/download.jpg"
        }
    }
}
</script>

<template>
    <div class="jumbotron">
        <img :src="jumboImage" alt="Duomo di Milano">
        <h3> {{ jumboParagraph }} </h3>
    </div>
</template>

<style>
.jumbotron {
    width: 100%;
    padding: 50px 0;
    background-color: aqua;
    display: flex;
    justify-content: space-around;
    align-items: center;
}
</style>