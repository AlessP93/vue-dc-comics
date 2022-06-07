<template>
  <header class="header">
      <div class="container">
        <div class="header__logo">
            <img src="../assets/img/dc-logo.png">
        </div>
        <nav class="header__nav">
            <ul>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
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
            column-gap: 1.25rem;
            font-size: .75rem;
        }
        a {
            transition: all;
            text-decoration: none;
            color: black;
        }

        a:hover {
            color: var(--tertiary-color);
            }
    }
}
.container {
     display: flex;
     justify-content: space-between;
    }
</style>