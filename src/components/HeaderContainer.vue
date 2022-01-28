<template>
    <header>
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="logo">
        </div>

        <nav>
            <ul>
                <!-- dicitura per usare un props, nel v-for è necessaria una :key univoca -->
                <li v-for="(item, index) in navItems" :key="index"> {{ item }} </li>
            </ul>
        </nav>

    </header>
</template>

<script>
export default {

    // dicitura per "pescare" un data dalla app.vue
    props: {
        navItems : Array,
    }
    
}
</script>


<style lang="scss" scoped>
    @import '@/styles/variables.scss';

    header {
        margin: 0 auto;
        width: $max-width;
        display: flex;
        justify-content: space-between;
        align-items: center;
        
        .logo {
            img {
                height: 60px;
            }
        }

        ul {
            display: flex;
            align-items: center;
            list-style: none;

            li {
                font-size: 13px;
                padding:  0 15px;
                height: 80px;
                line-height: 80px;
                border-bottom: 5px transparent solid;

                &:hover {
                    border-color: $tipically-blue;
                }

            }
        }
    }

</style>