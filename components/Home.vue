<template>
    <div>
        <input type="text" v-model="name" placeholder="Enter your name" style="height:40px;width:280px; padding:10px;">
        <h1>Hello {{name}}</h1>
    </div>
</template>

<script>
    export default {
        data() {
            return{
                name: ''
            }
        }
    }
</script>

<style scoped>
h1 {
    font-size: 4em;
}
</style>