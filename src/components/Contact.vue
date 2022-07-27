<template>
    <section class="flex contact">
        <IconsContact url="src/assets/images/location.svg" text="123 WEST STREET, NEWTOWN" color="#fe7ec9"/>
        <IconsContact url="src/assets/images/cellphone.svg" text="+1 234 567 89 00" color="#feca02"/>
        <IconsContact url="src/assets/images/mail.svg" text="WEBMASTER@GMAIL.COM" color="#38c4c1"/>
    </section>
</template>
<script setup>
import IconsContact from './UI/IconsContact.vue';
</script>
<style scoped>
.contact{
    justify-content: center;
    padding: 100px 0;
}
</style>