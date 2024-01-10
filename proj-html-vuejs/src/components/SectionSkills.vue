<template lang="">
   <section id='section-skills'>
        <div class='container text-center'>
            <div class='row'>
                <div class='col-12 mt-5'>
                    <p>Donec est tristique eu massa pellentesque</p>
                </div>
                <div class='col-12 mt-2 fs-1'>
                    <h2>
                        Highly-skilled, independent professional freelancer
                    </h2>
                </div>
                <div class='col-12 mt-2'>
                    <button type="button" class="btn my-button">What is a VA exactly?</button>
                </div>
            </div>
            <div class='row mt-5'>
                <div classe='col-12'>
                    <div class='my-blue-box'>
                        1. 
                    </div>

                    <div class='my-blue-box'>
                        1. 
                    </div>


                    <div class='my-blue-box'>
                        1. 
                    </div>
                </div>
            </div>
        </div>
   </section>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">
@use '../styles/general.scss' as *;
@use '../styles/partials/variables' as *;
    

#section-skills{
    background-color: $blue-electric;
    background-image: url(/img/info-bg-3.svg);
    color: $main-color-text;
}

div .my-button{
        background-color: $orange;
        color: $main-color-text;
        font-size: .7rem;
        font-weight: bolder;
        width: 15%;
    }

    div.my-blue-box{
        width: calc(100% /3);
        // margin-right: .7rem;
        background-color: $dark-blue;
        height: 100%;
    }

</style>