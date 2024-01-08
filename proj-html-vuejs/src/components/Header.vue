<template lang="">
    <header>
        <Nav/>
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
        background-color: $blue-electric;
        color: $main-color-text;
    }
</style>