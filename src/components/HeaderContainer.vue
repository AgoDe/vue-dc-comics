<template>
    <header>
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="logo">
        </div>

        <nav>
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>

    </header>
</template>

<script>
export default {
    
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