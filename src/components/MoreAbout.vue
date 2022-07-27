<template>
    <section class="more-about">
        <h5>About Us</h5>
        <h2>Best Pre School Education!</h2>

        <div class="main-block flex">
            <div class="block">
                <SmallDescription title="Funny and Happy" align="right"/>
                <SmallDescription title="Fulfill With Love" align="right"/>
                <SmallDescription title="Special Education" align="right"/>
            </div>
            <div class="block jumping-kid shadow"></div>
            <div class="block">
                <SmallDescription title="Professional Teaching"/>
                <SmallDescription title="Fully Equiped"/>
                <SmallDescription title="Transportation"/>
            </div>
        </div>

    </section>
</template>
<script setup>
import SmallDescription from './UI/SmallDescription.vue';
</script>
<style scoped>
.more-about {
    padding: 30px 0 100px 0;
}

.block {
    width: 390px;
}

.main-block {
    justify-content: center;
    column-gap: 20px;
    height: 550px;
}

h5 {
    margin-top: 25px;
    color: #808080;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: 300;
    font-size: 1.5rem;
}

h2 {
    margin: 15px 0 80px;
    font-weight: 700;
    font-size: 2.25rem;
    line-height: 1.2;
}

.jumping-kid {
    background-image: url('../assets/images/boy-jumping.jpg');
    background-position: 50% 50%;
    background-size: cover;
}


</style>