<template>
    <div>

        <h5 class="text">Enter 4 Random Digits</h5>
        <div class="card-main">
            <p class="spText">Will my friend be 
            true in his dealings?</p>
            <small class="small">Find out now</small>
            
            
            <div class="fourBox">
                <input type="tel" class="box">
                <input type="tel" class="box">
                <input type="tel" class="box">
                <input type="tel" class="box">
            </div>
            <nuxt-link to= "/dashboard/result"><img src="~/assets/randomArrow.png" alt="" class="downArrow"></nuxt-link>
        </div>
        <small id="small">Trusted by 300+ forward-thinking individuals and groups</small>
    </div>
</template>

<script>
    // import SmallOracle from '~/components/small-oracle.vue';
    // import image from '~/assets/randomArrow.png';

    export default {
       
    }
</script>

<style scoped>
/* All styles here are not to be taken to the main css file. !important */
.text {
    white-space: nowrap;
}
.spText {
    top: 30px;
    padding: 0px 27px;
    font-size: 18px;
    line-height: 20px;
}
.small {
    top: 33%;
    white-space: nowrap;
}
/* this one will be moved */

</style>