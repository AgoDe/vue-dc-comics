<template>
    <main>
         <div class="jumbotron"></div>
    </main>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    @import '@/styles/variables.scss';
    main {
        background: black;
        color: white;
        line-height: 200px;
        text-align: center;

        .jumbotron {
            height: 400px;
            background-image: url(../assets/img/jumbotron.jpg);
            background-size: cover;
        }
    }
</style>