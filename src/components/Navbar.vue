<template>
    <section>
        <nav class="navbar">
            <div class="logo">
                <h1><a href="/">Education</a></h1>
            </div>
            <div class="navbar-menu">
                <ul>
                    <li> <a href="">Home</a></li>
                    <li> <a href="">Portfolio</a></li>
                    <li> <a href="">Contacts</a></li>
                    <li> <a href="">Page 5</a></li>
                </ul>
            </div>
        </nav>
    </section>
</template>
<style scoped>
.navbar {
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding: 20px 0;
}

.logo a {
    color: #fe58b9;
    text-transform: uppercase;
    font-size: 1.8rem;
}

.navbar-menu ul {
    display: flex;
    justify-content: space-around;
}

li {
    width: 120px;
    padding: 10px;
    list-style: none;
    color: #1e1e1e;
    text-transform: uppercase;
    font-weight: 600;
}

</style>