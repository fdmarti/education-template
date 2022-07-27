<template>
    <div class="methods">
        <section class="block flex">
            <div class="block-card shadow gir-rainbow"></div>
            <div class="block-card shadow">
                <h3>Innovative Methods of Teaching</h3>
                <p>Small and mid-size companies often have trouble finding suitable office space in Amsterdam. The creative industry has seemingly unrealistic demands when it comes to office locations: an incubator of ideas, which is spacious and inspiring, with a unique design at a great location with car access. Photography</p>
            </div>
            <div class="block-card shadow boy-screaming"></div>
        </section>
    </div>
</template>
<style scoped>
.methods {
    padding: 50px 0;
    background-color: #fe7ec9;
}

.block-card {
    width: 390px;
    background-color: #ffffff;
    background-position: 0% 0% ;
}

.gir-rainbow {
    background-image: url('../assets/images/gir-rainbow.jpg');
}

.boy-screaming {
    background-image: url('../assets/images/boy-screaming.jpg');
    background-size: cover;
}

.block {
    justify-content: center;
    height: 500px;
    column-gap: 10px;
}

h3 {
    padding: 40px 20px 10px 20px;
    text-align: left;
    font-weight: 700;
    font-size: 1.875rem;
    line-height: 1.2;
}

p {
    padding: 0 20px;
    text-align: left;
    font-weight: 400;
    font-size: 1.2rem;
    line-height: 1.7;
}


</style>