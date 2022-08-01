<template>
    <section class="about">
        <h5>About Us</h5>
        <h2>Best Pre School Education!</h2>

        <div class="pictures-about flex">
            <img src="../assets/images/picture-girl.jpg" class="main-img shadow" alt="picture of a girl in yellow">
            <div class="more-info-about flex">
                <div class="cards-about flex">
                    <Card icon='src/assets/images/teachers.svg' title="TEACHERS" color="#ebfcfc"/>
                    <Card icon='src/assets/images/diamond.svg' title="OUR MISSION" color="#fff2fa"/>
                </div>
                <div class="subpictures-about flex">
                    <img src="../assets/images/young-girl.jpg" class="pictures shadow" alt="picture of a young girl in lightblue">
                    <img src="../assets/images/young-boy.jpg" class="pictures shadow" alt="picture of a boy in pink">
                </div>
            </div>
        </div>
    </section>
</template>
<script setup>
import Card from './UI/Card.vue';
</script>
<style scoped>
.about {
    padding: 40px 0;
}

h5 {
    color: #808080;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: 300;
    font-size: 1.5rem;
}

h2 {
    margin: 15px 0 40px;
    font-weight: 700;
    font-size: 2.25rem;
    line-height: 1.2;
}

.pictures-about {
    justify-content: space-between;
}

.main-img {
    max-height: 776px;
}

.more-info-about {
    align-items: center;
    flex-direction: column;
    justify-content: center;
}

.pictures {
    min-width: 370px;
    margin: 0 20px 10px;
}

@media (max-width:1450px) {
    .pictures-about{
        flex-direction: column;
    }
    .main-img {
        width: 600px;
        margin: 0 auto;
    }
}


</style>