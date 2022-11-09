<template>
    <header>
        <h1>{{titolo}}</h1>
    </header>
</template>

<script>
    export default {
        name: 'AppTitle',
        data() {
            return {
                titolo: 'La mia prima app con Vite!'
            }
        }
    }
</script>

<style lang="css" scoped>
header {
    width: 100%;
    height: 70px;
    padding: 20px;
}
</style>