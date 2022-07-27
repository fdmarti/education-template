<template>
    <div class="footer">
        <section>
            <div class="footer-text flex">
               <h5>HEADLINE</h5>
               <h5>HEADLINE</h5>
               <h5>HEADLINE</h5>
            </div>
             <div class="footer-social flex">
                <a href="/" target="_blank">
                    <img src="../assets/images/facebook.png" alt="facebook logo">
                </a>
                 <a href="/" target="_blank">
                    <img src="../assets/images/twitter.png" alt="twitter logo">
                </a>
                 <a href="/" target="_blank">
                    <img src="../assets/images/instagram.png" alt="instagram logo">
                </a>
                 <a href="/" target="_blank">
                    <img src="../assets/images/linedin.png" alt="linkedin logo">
                </a>
            </div>
        </section>
    </div>
</template>
<style scoped>
.footer {
    padding: 80px 0 30px 0;
    background-color: #fe58b9;
}

.footer-text{
    justify-content: center;
}

h5{
    color:#FFF;
    width: 300px;
}

.footer-social{
    margin-top: 100px;
    justify-content: center;
    column-gap: 30px;
}

img{
    width: 40px;
    height: 40px;
}

</style>