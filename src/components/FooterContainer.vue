<template>
    <footer>

        <footer-special/>

        <footer-mapsite/>

        


    </footer>
</template>

<script>
import FooterSpecial from './FooterSpecial.vue'
import FooterMapsite from './FooterMapsite.vue'
export default {
    components: {
        FooterSpecial,
        FooterMapsite,
    }
    
    
}
</script>

<style lang="scss" scoped>
    @import '@/styles/variables.scss';
</style>