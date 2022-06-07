<template>
<section class="jumbotron">
    <div class="container">
        <h3>CURRENT SERIES</h3>
    </div>
</section>
</template>

<script>
export default {
    name: 'SectionHero',
}
</script>

<style lang="scss" scoped>
    .jumbotron {
        background-image: url("../../assets/img/jumbotron.jpg");
        background-size: cover;
        height: 350px;
      
        .container {
            height: 100%;
            display: flex;
            align-items: flex-end;
        }
    }

    h3 {
        background-color: var(--tertiary-color);
        color: white;
        padding: .375rem 1.25rem;
        margin-bottom: -1rem;
        }
</style>