<template>
    <div>
        <form name="contact" netlify>
        <input type="text" v-model="name" placeholder="Enter your name" style="height:40px;width:280px; padding:10px;">
        <h1>Hello {{name}}</h1>
        <input type="submit" value="Submit" class="submit">
        </form>
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

.submit {
    height: 50px;
    width: 150px;
    border-radius: 50px;
    border: 0;
    background-color: blueviolet;
    color: #fff;
    font-size: 1.2em;
    cursor: pointer;
}
</style>