<template>
    <div class="special">
        <section>
            <h5>FACILITY</h5>
            <h2>Make your Children's life Special</h2>

            <div class="card flex">
                <div class="block ash-ketchum"></div>
                <div class="block flex">
                    <h3>Relaxation and comfort</h3>
                    <p>Set up in 2000, Kidzcare is arranged in a wonderfully protected, Landmark Building. Phasellus scelerisque sed leo quis gravida. Fusce lobortis libero ut arcu blandit pharetra.</p>
                    <a href="/">READ MORE</a>
                </div>
            </div>
        </section>
    </div>
</template>
<style scoped>
.special {
    padding: 60px;
    background-color: #38c4c1;
}

.card {
    height: 600px;
    background-color: #ffffff;
}

h5 {
    color: #ffffff;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-weight: 300;
    font-size: 1.5rem;
}

h2 {
    margin: 15px 0 40px;
    color: #ffffff;
    font-weight: 700;
    font-size: 2.25rem;
    line-height: 1.2;
}

h3 {
    text-align: left;
    font-weight: 700;
    font-size: 2.25rem;
    line-height: 1.2;
}

p {
    font-weight: 400;
    font-size: 1.125rem;
    line-height: 1.7;
}

a {
    width: 150px;
    margin-top: 20px;
    padding: 20px;
    border-radius: 10px;
    background-color: #fe7ec9;
    color: #ffffff;
    text-align: center;
}

.block {
    flex-direction: column;
    justify-content: center;
    width: 50%;
    padding: 50px;
}

.ash-ketchum {
    background-image: url('../assets/images/ash-ketchum.jpg');
    background-position: 50% 50%;
}

</style>