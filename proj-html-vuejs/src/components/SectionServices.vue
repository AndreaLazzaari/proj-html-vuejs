<template lang="">
    <div class='container mt-5 p-1'>
        <a href="#">Available services</a>
        <div class='row'>
            <div class='col-3'>
                <div class="card mt-5" style="width: 18rem;">
                    <div class="card-body blue">
                        <h5 class="card-title fs-1 p-4">Answering phone calls</h5>
                        <p class="card-text p-3 lh-base">Elementum posuere mauris, ac ultricies eu orci massa at id tindident.</p>
                    </div>
                </div>
            </div>
            <div class='col-3'>
                <div class="card mt-5" style="width: 18rem;">
                    <div class="card-body blue">
                        <h5 class="card-title fs-1 p-4">Basic data entry</h5>
                        <p class="card-text p-3 lh-base">Accumanas odio id nec mauris, eu, tortor at. Vitae tincidunt enim quis.</p>
                    </div>
                </div>
            </div>
            <div class='col-3'>
                <div class="card mt-5" style="width: 18rem;">
                    <div class="card-body blue">
                        <h5 class="card-title fs-1 p-4">Organizing calendar</h5>
                        <p class="card-text p-3 lh-base">Elementum blandit erat odio quam pellentesque aliquam faucibus.</p>
                    </div>
                </div>
            </div>
            <div class='col-3'>
                <div class="card mt-5" style="width: 18rem;">
                    <div class="card-body blue">
                        <h5 class="card-title fs-1 p-4">Booking travels</h5>
                        <p class="card-text p-3 lh-base">Est dignissim ipsum tellus, hendrerit ac aliquam eu vel blandit ac amet ut ut.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class='container d-flex'>
        <ImgBox />
        <TextBox />
    </div>
</template>

<script>
import ImgBox from './ImgBox.vue';
import TextBox from './TextBox.vue';
export default {
    components:{
        ImgBox,
        TextBox,
    },
    data() {
        return {
            imgList: ['file:///C:/Users/Andrea/OneDrive/Documenti/Esercizi%20Boolean/proj-html-vuejs/proj-html-vuejs/src/img/info-5-2x-400x432.png', 
            'file:///C:/Users/Andrea/OneDrive/Documenti/Esercizi%20Boolean/proj-html-vuejs/proj-html-vuejs/src/img/info-8-2x-400x407.png'],

            infoBoxList: [
                {
                    src: '../img/icon-1-2x-200x155.png',
                    titolo: 'Find the ultimate virtual assistant for your business',
                    paragrafo: 'Donec est tristique eu massa pellentesque non sit sit donec. Proin auctor est vehicula'
                },

                {
                    src: '../img/icon-2-2x-200x127.png',
                    titolo: 'Professional who works to help your business',
                    paragrafo: 'Donec est tristique eu massa pellentesque non sit sit donec. Proin auctor est vehicula'
                },
        ]
        }
    },
}
</script>

<style lang="scss">
@use '../styles/general.scss' as *;
@use '../styles/partials/variables' as *;
    

    .blue{
        color: $blue-electric;
    }
    a{
        text-decoration: none;
        color: $orange;
    }
</style>