<template>
<footer class="footer">
      <div class="ft-blu">
        <div class="container">
            <div class="footer__top">
                <div>
                    <img src="../assets/img/buy-comics-digital-comics.png">
                    <small>DIGITAL COMICS</small>
                </div>
                <div>
                    <img src="../assets/img/buy-comics-merchandise.png">
                    <small>DC MERCHANDISE</small>
                </div>
                <div>
                    <img src="../assets/img/buy-comics-subscriptions.png">
                    <small>SUBSCRIPTIONS</small>
                </div>
                <div>
                    <img src="../assets/img/buy-comics-shop-locator.png">
                    <small>COMIC SHOP LOCATOR</small>
                </div>
                <div>
                    <img src="../assets/img/buy-dc-power-visa.svg">
                    <small>DC POWER VISA</small>
                </div>
            </div>
        </div>
    </div>
    <div class="ft-black">
        <div class="container">
            <div class="footer__middle">
                <div class="list">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                         <li><a href="#">News</a></li>
                    </ul>
                    <div>
                        <h3>SHOP</h3>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                            
                        </ul>
                    </div>
                </div>
                <div>
                    <h3>DC</h3>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy policy (New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Helps</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                <div>
                    <h3>SITES</h3>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Pwer Visa</a></li>
                    </ul>
                </div>
                <img src="../assets/img/dc-logo-bg.png">
            </div>
        </div>
    </div>
    <div class="ft-grey">
        <div class="container">
            <div class="footer__bottom">
                <div><button>SIGN-UP NOW!</button></div>
                <div class="social">
                    <h3>FOLLOW US</h3>
                    <img src="../assets/img/footer-facebook.png">
                    <img src="../assets/img/footer-twitter.png">
                    <img src="../assets/img/footer-youtube.png">
                    <img src="../assets/img/footer-pinterest.png">
                    <img src="../assets/img/footer-periscope.png">
                </div>
            </div>
        </div>
    </div>
</footer>
</template>

<script>
export default {
    name: 'BaseFooter',
}
</script>

<style lang="scss" scoped>
        .ft-blu {
            width: 100%;
            background-color: var(--tertiary-color);
            padding: 1.25rem;
            color: white;
        }

        .footer__top {
            display: flex;
            justify-content: space-between;
            padding: .625rem;
            align-items: center;

            small {
                margin-left: .625rem;
                align-self: center;
            }

            img {
                width: 20%;
            }
        }

        .ft-black {
            background-image: url('../assets/img/footer-bg.jpg');
            height: 21.875rem;
            overflow: hidden;
            
        }

        .footer__middle {
            display: flex;
            justify-content: space-between;
            
            h3 {
                color: white;
                padding: 1.25rem 0;
            }

            .list ul {
               list-style: none ;
            }

            a {
                text-decoration: none;
                color: rgb(145, 145, 145);
                font-size: .75rem;
            }

            img {
                 margin-top: -6.25rem;
            }
        }

        .ft-grey {
            width: 100%;
            background-color: var(--fourthy-color);
        }

        .footer__bottom {
            display: flex;
            justify-content: space-between;
           
            button {
                border: .1875rem solid var(--tertiary-color);
                background-color: var(--fourthy-color);
                color: white;
                padding: .625rem;
                
                
            }

            h3 {
                color: var(--tertiary-color);
            }

            .social {
                display: flex;
                align-items: center;
                gap: 1.25rem;
                padding: 40px;
                
            }

        }
</style>