<template>
    <v-container fluid fill-height class="home-hero">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black white--text text-xs-center">Shop Your Way</div>
            <div class="display-4 font-weight-black white--text text-xs-center mb-3">BUY NOW</div>
            <div class="display-1 font-weight-bold white--text text-xs-center">Finally have all the gear you need at your fingertips</div>
            <v-btn fab class="mt-5 orange darken-4">
            <v-icon large color="white">Shop now</v-icon>
            </v-btn>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomeHero'
};
</script>

<style scoped>
.home-hero {
    background: url('https://images.pexels.com/photos/1598347/pexels-photo-1598347.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940');
    background-size: cover;
    width: 100%;
    height: 100%;
}
</style>