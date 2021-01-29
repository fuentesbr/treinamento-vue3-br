<template>
    <div>
        <h1 :style="{ textDecoration: decoration }">Hello {{ name }}!</h1>
        <input type="text" v-model="name"> 
        <br>
        <br>
        <a :href="link">Link pro curso!</a>
    </div>
</template>

<script>
export default {
    data: () => ({
        name: 'Cesar',
        decoration: 'underline',
        link: 'https://fuentes.net.br'
    })
}
</script>

<style>

</style>