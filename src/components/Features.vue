<template>
    <div class="features">
        <section>
            <h5>KEY FEATURES</h5>
            <h3>Service We Provide</h3>
            <div class="cards flex">
                <CardSimple v-for="(item, index) in itemsCards" :key="index" :item="item"/>
            </div>
        </section>
    </div>
</template>
<script setup>
    import CardSimple from './UI/CardSimple.vue';

    const itemsCards = [
        { title :  'ENVIRONMENT', titleColor : '#fe7ec9' ,url : 'src/assets/images/enviroment.svg'},
        { title :  'ACTIVE LEARNING', titleColor : '#488df4'  ,url : 'src/assets/images/learning.svg'},
        { title :  'CREATIVE LESSONS', titleColor : '#38c4c1'  ,url : 'src/assets/images/lessons.svg'},
        { title :  'QUALIFIED TEACHER', titleColor : '#feca02 '  ,url : 'src/assets/images/qualified-teacher.svg'},
    ];

</script>
<style scoped>
.features {
    padding-bottom: 80px;
    background-color: #feca02;
}

.cards {
    justify-content: space-between;
}

h5,
h3 {
    color: #ffffff;
}

h5 {
    padding-top: 80px;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: 300;
    font-size: 1.5rem;
}

h3 {
    margin: 10px;
    padding-bottom: 40px;
    font-weight: 700;
    font-size: 2.25rem;
    line-height: 1.2;
}

</style>