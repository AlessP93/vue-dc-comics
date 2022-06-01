<template>
  <header class="header">
      <div class="container">
        <div class="header__logo">
            <img src="../assets/img/dc-logo.png">
        </div>
        <nav class="header__nav">
            <ul>
                <li><a href="#">link</a></li>
                <li><a href="#">link</a></li>
                <li><a href="#">link</a></li>
                <li><a href="#">link</a></li>
                <li><a href="#">link</a></li>
                <li><a href="#">link</a></li>
                <li><a href="#">link</a></li>
                <li><a href="#">link</a></li>
                <li><a href="#">link</a></li>
                <li><a href="#">link</a></li>
            </ul>
        </nav>
      </div>
  </header>
</template>

<script>
export default {
    name: 'BaseHeader',
}
</script>

<style lang="scss" scoped>
.header {
    justify-content: space-between;

    &__logo {
        padding: .625rem;

        img {
            width: 80%;
        }
    }


    &__nav {
        align-self: center;
        ul {
            display: flex;
            list-style: none;
            column-gap: 2.5rem
        }
        a {
            text-decoration: none;
            color: black;
        }
    }
}
.container {
     display: flex;
     justify-content: space-between;
    }
</style>