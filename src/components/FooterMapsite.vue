<template>
    <div class="mapsite">

        <div class="container">

            <div class="mapsite-nav">

                <div>
                    <h5>DC COMICS</h5>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    
                    <h5>SHOP</h5>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>

                </div>

                <div>
                        <h5>DC</h5>
                    <ul>
                        <li>Terms Of Use</li>
                        <li>Privacy policy (New)</li>
                        <li>ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Rating</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>

                <div>
                    <h5>SITE</h5>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>

            </div>

            
            <img src="../assets/img/dc-logo-bg.png" alt="">

        </div>
        
        
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    @import '@/styles/variables.scss';

    .mapsite {
        background: url(../assets/img/footer-bg.jpg);
        height: 300px;
        
        .container {

            width: $max-width;
            margin: 0 auto;
            position: relative;
            padding: 30px 0 ;
            
            .mapsite-nav {
                display: flex;
                div {

                    margin: 0 15px;

                    h5 {
                        margin: 8px 0;
                        font-weight: bold;
                        font-size: 12px;
                        color: white;
                    }
                    ul {
                        list-style: none;

                        li {
                            font-size: 9px;
                            color: #888;
                            padding: 4px;
                        }
                    }
                }
            }

            img {
                position: absolute;
                height: 430px;
                bottom: -60px;
                right: 50px;
            }
           
        }

    }
</style>