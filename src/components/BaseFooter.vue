<template>
  <footer class="footer">
      <div class="footer__top">
        <div>
            <img src="../assets/img/buy-comics-digital-comics.png">
            <div>DIGITAL COMICS</div>
        </div>
        <div>
            <img src="../assets/img/buy-comics-merchandise.png">
            <div>DIGITAL COMICS</div>
        </div>
        <div>
            <img src="../assets/img/buy-comics-subscriptions.png">
            <div>DIGITAL COMICS</div>
        </div>
        <div>
            <img src="../assets/img/buy-comics-shop-locator.png">
            <div>DIGITAL COMICS</div>
        </div>
        <div>
            <img src="../assets/img/buy-comics-digital-comics.png">
            <div>DIGITAL COMICS</div>
        </div>
      </div>
      <div class="footer__middle"></div>
      <div class="footer__bottom"></div>
  </footer>
</template>

<script>
export default {
    name: 'BaseFooter',
}
</script>

<style lang="scss" scoped>
    .footer {
        background-color: var(--tertiary-color);
    
    &__top {
        display: flex;
        justify-content: space-around;

        img {
            width: 30%;
        }
    }
}
</style>