<script setup>
    import ArticleItem from './ArticleItem.vue';
</script>
<template>
    <div>
        <ul>
            <li><a>Featured Articles</a></li>
        </ul>
    </div>
    <div class="container">
        <div class="grid"><ArticleItem title="Why Baldur's Gate III is GOTY"/></div>
        <div class="grid"><ArticleItem title="Starfield releases next week"/></div>
        <div class="grid"><ArticleItem title="How good is Metal Gear Solid 2: Sons of Liberty"/></div>
    </div>
</template>

<style scoped>
    ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
        overflow: hidden;
        background-color: #dddddd;
        text-align: center;
    }

    li a {
        padding: 20px;
        background-color: #dddddd;
        font-size: x-large;
        display: inline-block;
    }
    .container {
        padding: 10px;
    }
    .grid {
        background-color: rgba(255, 255, 255, 0.8);
        border: 1px solid rgba(0, 0, 0, 0.8);
        padding: 20px;
        font-size: 30px;
        text-align: center;
    }

    @media (min-width: 1024px) {
        .container {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        padding: 10px;
    }
    .grid {
        background-color: rgba(255, 255, 255, 0.8);
        border: 1px solid rgba(0, 0, 0, 0.8);
        padding: 20px;
        font-size: 30px;
        text-align: center;
    }
    }
</style>