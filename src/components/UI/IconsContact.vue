<template>
    <div class="icon-contact">
        <img :src="url" :alt="text+ ' icon'" class="icon-img" :style="{'background-color':color}">
        <h5>{{text}}</h5>
    </div>
</template>
<script>
export default{
    props: ['url','text','color']
}
</script>
<style scoped>
.icon-contact {
    width: 300px;
    text-align: center;
}

.icon-img {
    width: 65px;
    height: 65px;
    padding: 30px;
    border-radius: 30px;
}

h5{
    margin-top: 20px;
    font-size: 1.2rem;
}

</style>