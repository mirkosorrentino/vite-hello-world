<script>
export default {
    name: "AppTitle",
    data(){
        return {
            title: "La mia prima app con Vite!"
        }
    }
}
</script>

<template>
    <h1> {{ title }} </h1>
</template>

<style>
h1 {
    font-size: 3rem;
    font-family: sans-serif;
    color: red;
    font-weight: 700;
    text-align: center;
}
</style>