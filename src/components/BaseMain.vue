<template>
<main>
    <div>
        <SectionHero/>
        <SectionProducts/>
    </div>
</main>
</template>

<script>
import SectionProducts from '../components/sections/SectionProducts.vue'
import SectionHero from '../components/sections/SectionHero.vue'

export default {
    name: 'BaseMain',
    components: {
        SectionProducts,
        SectionHero,
    }
}
</script>

<style>
   
</style>