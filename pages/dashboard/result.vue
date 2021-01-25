<template>
    <div class="contain">

        <h5 class="text">The 0racle says:</h5>
        <div class="card-main">
            <p class="spText">You can purchase local phone numbers in any country. Incoming calls can be answered in the app or forwarded to any mobile phone number.</p>
        </div>
            <nuxt-link to="/next">
            <div class="wrap"><img src="~/assets/refresh.png" alt="" class="refresh"></div>
            </nuxt-link>


        <small id="small">Trusted by 300+ forward-thinking individuals and groups</small>
    </div>
</template>

<script>
// import SmallOracle from '~/components/small-oracle.vue';

    export default {
        
    }
</script>

<style scoped>
.spText {
    top: 0px;
    padding: 15% 0px 25%;
    font-size: 18px;
    line-height: 23px;
    text-align: center;
}
.card-main {
    height: 251.58px;
    overflow-y: scroll;
}
.refresh {
    position: absolute;
    left: 50%;
    transform: translate(-50%,0);
    top: 90%;
    /* bottom: 0; */
}
#small {
    padding: 150px 40px 0px ;
    bottom: 0%;
}
</style>