<template>
  <div class="product">
       <img :src="image" :alt="title">
        <span> {{title}} </span>
  </div>
</template>

<script>
export default {
    name: 'CardProduct',
    props: {
        title: String,
        image: String
    }
}
</script>

<style lang="scss" scoped>

.product {


        
    img {
        height: 150px;
        width: 100%;
        object-fit: cover;
        object-position: top;
    }
}
</style>