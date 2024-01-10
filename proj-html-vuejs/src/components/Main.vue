<template lang="">
    <main>
        <SectionServices />
        <SectionSkills />
        <SectionBrands />

    </main>
</template>

<script>
import SectionServices from './SectionServices.vue';
import SectionSkills from './SectionSkills.vue';
import SectionBrands from './SectionBrands.vue';
export default {
    components:{
        SectionServices,
        SectionSkills,
        SectionBrands,
    }
}
</script>

<style lang="">
    
</style>