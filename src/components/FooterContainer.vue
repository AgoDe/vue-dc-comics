<template>
    <footer>

        <footer-special/>

        <footer-mapsite/>

        <footer-social/>

    </footer>
</template>

<script>
import FooterSpecial from './FooterSpecial.vue';
import FooterMapsite from './FooterMapsite.vue';
import FooterSocial from './FooterSocial.vue';

export default {
    components: {
        FooterSpecial,
        FooterMapsite,
        FooterSocial,
    }
    
    
}
</script>

<style lang="scss" scoped>
    @import '@/styles/variables.scss';
</style>