<template>
    <div class="block">
        <h1>Kids Loved How We Treat Them</h1>
        <p>Paragraph. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur id suscipit ex. Suspendisse rhoncus laoreet purus quis elementum. Phasellus sed efficitur dolor, et ultricies sapien. Quisque fringilla sit amet dolor commodo efficitur. Aliquam et sem odio. In ullamcorper nisi nunc, et molestie ipsum iaculis sit amet.</p>
    </div>
</template>
<style scoped>
.block {
    padding: 80px 0 20px 0;
    background-color: #f2f2f2;
}

h1 {
    position: relative;
    color: #488df4;
    font-size: 3.75rem;
}

h1::after {
    content: '';
    position: absolute;
    top: 110px;
    left: 48%;
    width: 70px;
    height: 5px;
    border-radius: 10px;
    background-color: #000000;
}

p {
    max-width: 790px;
    margin: 70px auto;
    text-align: center;
    font-weight: 400;
    font-size: 1.25rem;
    line-height: 1.7;
}



</style>