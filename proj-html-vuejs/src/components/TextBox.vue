<template lang="">
    <div class='container d-flex mt-5'> 

        <div class='my-img-box'>
            <img :src="imgSrc" alt="">
        </div>

        <div class='my-text-box text-center'>
            <div>
                <img :src="iconSrc" alt="">
            </div>
            <h2>
                {{ title }}
            </h2>
            <p> {{ text }}</p>
            <button type="button" class="btn">What is a VA exactly?</button>
        </div>

    </div>


</template>
<script>
export default {
    props: [
        'iconSrc',
        'title',
        'text',
        'imgSrc',
        'direction',

    ]
}
</script>

<style lang="scss">
@use '../styles/general.scss' as *;
@use '../styles/partials/variables' as *;

    div.my-text-box{
        width: 60%;

        button{
        background-color: $orange;
        color: $main-color-text;
        font-size: .7rem;
        font-weight: bolder;
        width: 20%;
    }}


    div.my-img-box{
        width: 40%;
        
    }


   
</style>