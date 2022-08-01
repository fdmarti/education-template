<template>
    <div class="card shadow" :style="{'background-color' : color}">
        <div class="icon-position">
            <img :src="icon" :alt="title + ' icon '" class="icon" :style="{'background-color' : backgroundColor}">
        </div>  
        <h4>{{title}}</h4>
        <p>{{!content ? 'Sample text. Lorem ipsum dolor sit amet, consectetur adipiscing elit nullam nunc justo sagittis suscipit ultrices.' : content}}</p>
        <a href="/" :style="{'background-color' : backgroundColor}"> Read more </a>
    </div>
</template>
<script>
import { computed } from '@vue/runtime-core'
    export default{
        props : ['icon','title','content','color'],

        setup(props){
            const backgroundColor = computed(() => props.color === '#fff2fa' ? '#fe58b9' : '#38c4c1');

            return{
                backgroundColor
            }
        }
    }
</script>
<style scoped>
.card {
    height: 430px;
    margin: 0 20px 10px;
}

.icon-position {
    display: flex;
    justify-content: end;
}

.icon {
    width: 50px;
    height: 50px;
    margin: 30px;
    padding: 20px;
    border-radius: 50%;
}

h4 {
    margin: 10px 30px;
    color: #808080;
    text-align: right;
    text-transform: uppercase;
    font-weight: 300;
    font-size: 1.5rem;
}

p {
    margin: 20px 15px;
    font-weight: 400;
    font-style: italic;
    font-size: 0.875rem;
    line-height: 1.7;
}

a {
    float: right;
    margin: 30px;
    padding: 10px;
    border-radius: 10px;
    color: #ffffff;
    text-transform: uppercase;
    font-weight: 500;
}

@media (max-width:1450px) {
    .card{
        margin-top: 50px;
        max-width: 370px;
    }
}


</style>