<template lang="">
    <footer id='end'>
        <Nav />
    </footer>
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
@use '../styles/partials/variables' as *;

#end{
    background-color: $blue-electric;

}
    
</style>