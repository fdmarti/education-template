<template>
    <div class="options">
        <div class="block" v-for="(block,index) in options" :key="index" :style="{'background-color': block.color}">
            <img :src="block.url" :alt="block.text + ' logo'"/>
            <h1>{{block.text}}</h1>
        </div>
    </div>
</template>
<script setup>
import { ref } from "@vue/reactivity";

    const options = ref([
        { text : 'Learning', url : 'src/assets/images/book.svg', color: '#38c4c1' },
        { text : 'Philosophy', url : 'src/assets/images/light-bulb.svg', color: '#feca02' },
        { text : 'Practice', url : 'src/assets/images/hands.svg', color: '#fe7ec9' },
        { text : 'Games', url : 'src/assets/images/open-book.svg', color: '#488df4' },
    ]);

</script>
<style scoped>
    .options{
        display: flex;
        justify-content: center;
        padding-top: 65px;
    }
    .block{
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    h1{
        color:#FFF;   
        margin-bottom: 85px;     
    }

    img{
        height: 86px;
        margin-top: 85px;
    }
</style>