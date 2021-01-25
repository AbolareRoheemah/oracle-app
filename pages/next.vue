<template>
    <div id="container">
        <Cliped />

        <Categories />
    </div>
</template>

<script>
import Categories from '~/components/categories.vue';
import Cliped from '~/components/cliped.vue';

    export default {
        components: { Categories },
    }
</script>

<style scoped>


</style>