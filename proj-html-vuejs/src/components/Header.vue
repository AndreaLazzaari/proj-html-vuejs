<template lang="">
    <header>
        <Nav/>
        <section class='jumbo'>
            <div class='my-jumbo-container d-flex'>
                <div class='big-div-text'>

                </div>
                <div class='small-div-img'>

                </div>
            </div>
        </section>
    </header>
</template>

<script>
import Nav from './Nav.vue';
export default {
    components:{
        Nav,
    }
}
</script>

<style lang="scss">
@use '../styles/general.scss' as *;

    header{
        background-color: #0d1267;
        // color: $main-color-text;
    }
</style>