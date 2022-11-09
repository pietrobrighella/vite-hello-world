<template>
    <div class="jumbo">
        <h1>{{title}}</h1>
    </div>
</template>

<script>
    export default {
        name: 'AppHero',
        data() {
            return {
                title: 'Titolo Jumbo',
            }
        }
    }
</script>

<style lang="css" scoped>
.jumbo {
    width: 100%;
    height: 500px;
    background-color: lightgray;
}

h1 {
    font-size: 96px;
    font-weight: 900;
    text-align: center;
}
</style>