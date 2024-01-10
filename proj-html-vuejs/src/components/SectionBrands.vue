<template lang="">
    <section>
        <div class='container text-center mt-5'>
            <a href="#">Trusted by these amazing brands</a>
            <nav class="navbar navbar-expand-lg bg-body-tertiary mt-3">
                <div class="container">
                    <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item ms-4">
                            <a class="navbar-brand" href="#">
                                <img src="../../public/img/brand-1-200x67.jpg" alt="Hemisferio's logo" width="200" height="80">
                            </a>
                        </li>
                        <li class="nav-item ms-4">
                            <a class="navbar-brand" href="#">
                                <img src="../../public/img/brand-7-200x67.jpg" alt="Urbano's logo" width="200" height="80">
                            </a>
                        </li>
                        <li class="nav-item ms-4">
                            <a class="navbar-brand" href="#">
                                <img src="../../public/img/brand-3-200x67.jpg" alt="Forniture's logo" width="200" height="80">
                            </a>
                        </li>
                        <li class="nav-item ms-4">
                            <a class="navbar-brand" href="#">
                                <img src="../../public/img/brand-4-200x67.jpg" alt="Interior's logo" width="200" height="80">
                            </a>
                        </li>
                        <li class="nav-item ms-4">
                            <a class="navbar-brand" href="#">
                                <img src="../../public/img/brand-5-200x67.jpg" alt="Spaces's logo" width="200" height="80">
                            </a>
                        </li>
                    </ul>
                    </div>
                </div>
            </nav>
        </div>
        <TextBox 
            :iconSrc='infoBoxList[1].icon'
            :title='infoBoxList[1].titolo'
            :text='infoBoxList[1].paragrafo' 
            :imgSrc='infoBoxList[1].mainImage'
            :direction='infoBoxList[1].inverse'
        />
    </section>
</template>

<script>
import TextBox from './TextBox.vue';
export default {
    components:{
        TextBox,
    },
    data() {
        return {
            infoBoxList: [
                {
                    icon: '/img/icon-1-2x-200x155.png',
                    titolo: 'Find the ultimate virtual assistant for your business',
                    paragrafo: 'Donec est tristique eu massa pellentesque non sit sit donec. Proin auctor est vehicula',
                    mainImage: '/img/info-5-2x-400x432.png',
                    inverse: false
                },

                {
                    icon: '/img/icon-2-2x-200x127.png',
                    titolo: 'Professional who works to help your business',
                    paragrafo: 'Donec est tristique eu massa pellentesque non sit sit donec. Proin auctor est vehicula',
                    mainImage: '/img/info-8-2x-400x407.png',
                    inverse: true
                },
        ]
        }
    },
}
</script>

<style lang="scss">
@use '../styles/general.scss' as *;
@use '../styles/partials/variables' as *;
    
</style>