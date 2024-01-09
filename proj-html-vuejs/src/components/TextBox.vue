<template lang="">
    <div class='my-text-box text-center'>
        <div>
            <img src="../img/icon-1-2x-200x155.png" alt="">
        </div>
        <h2>
            Testooooooooooooo
        </h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio sit po debitis repellendus nobis!</p>
        <button type="button" class="btn">What is a VA exactly?</button>
    </div>
</template>
<script>
export default {
    
}
</script>

<style lang="scss">
@use '../styles/general.scss' as *;
@use '../styles/partials/variables' as *;

    div.my-text-box{
        width: 60%;
        // background-color: red;

        button{
        background-color: $orange;
        color: $main-color-text;
        font-size: .7rem;
        font-weight: bolder;
        width: 30%;
    }}



   
</style>