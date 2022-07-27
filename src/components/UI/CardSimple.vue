<template>
    <div class="simple-card flex shadow">
        <div class="position-image">
            <img :src="item.url" :alt="item.title + ' icon '">
        </div>
        <h3 :style="{'color' : item.titleColor}">{{item.title}}</h3>
        <p>{{!item.content ? 'Suspendisse vulputate eros in velit fermentum cursus. Nulla fringilla justo tellus' : item.content}}</p>
    </div>
</template>
<script>
export default{
    props:['item']
}
</script>
<style scoped>
.simple-card {
    flex-direction: column;
    justify-content: center;
    width: 280px;
    min-height: 350px;
    background-color: #ffffff;
}

.position-image {
    text-align: center;
}

img {
    width: 80px;
    height: 80px;
    padding: 40px 0;
}

p{
    padding: 20px;
    font-style: italic;
    font-size: 1rem;
}

</style>