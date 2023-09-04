<script setup>
    defineProps({
        title: String
    })
</script>

<template>
    <div>
        <h3>{{ title }}</h3>
        <img src="@/assets/banner.jpg"/>
    </div>
</template>

<style scoped>
    img {
        width: 300px;
        height: 300px;
    }
    h3 {
        color: black;
    }
</style>