<template>
    <div class="footer-social">
        <div class="container">
            
            <div class="sign-button">
                SIGN-UP NOW!
            </div>

            <div class="social-box">

                <h3>FOLLOW US</h3>
                <img src="../assets/img/footer-facebook.png" alt="facebook-logo">
                <img src="../assets/img/footer-twitter.png" alt="facebook-logo">
                <img src="../assets/img/footer-youtube.png" alt="facebook-logo">
                <img src="../assets/img/footer-pinterest.png" alt="facebook-logo">
                <img src="../assets/img/footer-periscope.png" alt="facebook-logo">

            </div>
        

        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    @import '@/styles/variables.scss';

    .footer-social {
        background: #333;
        position: relative;
        z-index: 1001;

        .container {
            width: $max-width;
            margin: 0 auto;
            height: 100px;
            display: flex;
            justify-content: space-between;
            align-items: center;

            .sign-button {
                display: inline-block;
                padding: 13px;
                font-size: 14px;
                color: white;
                border: 2px $tipically-blue solid;
            }

            .social-box {
                display: flex;
                justify-content: space-between;
                align-items: center;

                h3 {
                    color: $tipically-blue;
                    padding: 0 15px;
                    font-size: 14px;
                }
                img {
                    padding: 0 5px;
                    height: 28px;
                }
            }
        }
    }
</style>