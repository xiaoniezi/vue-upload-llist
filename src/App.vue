<template>
    <div id="app">
        <img src="./assets/logo.png">
        <upload-list />
    </div>
</template>

<script>
import UploadList from '@/components/uploadList'

export default {
    name: 'app',
    components: {
        UploadList
    }
}
</script>

<style>
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>