<template>
    <div class="description">
        <h3 :style="{'text-align' : textAlign}">{{title}}</h3>
        <p :style="{'text-align' : textAlign}">{{!content ? 'We are group of teachers who really love childrens and enjoy every moment.' : content}}</p>
    </div>
</template>
<script>
import { computed } from '@vue/runtime-core'
export default{
    props : ['title','content','align'],

    setup(props){
        const textAlign = computed(() => !props.align ? 'left' : 'right');

        return {
            textAlign
        }
    }
}
</script>
<style scoped>
.description {
    padding: 40px 20px;
}

p {
    font-weight: 400;
    font-style: italic;
    font-size: 1.125rem;
    line-height: 1.7;
}

</style>