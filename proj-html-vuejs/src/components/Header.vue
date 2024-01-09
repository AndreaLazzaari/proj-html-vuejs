<template lang="">
    <header>
        <Nav/>
        <section class='jumbo'>
            <div class='my-jumbo-container d-flex'>
                <div class='big-div-text'>
                    <h1>
                        Independent professional who works remotely to help whith your business.
                    </h1>
                    <p>Mauris aliquam libero, fementum quis eros, messa sagittis. Lectus mattis elit purus venenatis.</p>
                    <button type="button" class="btn">What is a VA exactly?</button>
                </div>
                <div class='small-div-img'>
                    <img src="../img/info-5-400x444.jpg" alt="img ragazza che prende appunti">
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
@use '../styles/partials/variables' as *;

    header{
        background-color: $blue-electric;
        color: $main-color-text;
        background-image: url(../img/footer-bg-1.svg);
    }
    div.my-jumbo-container{
        margin: 0 auto;
        max-width: 950px;
        
    }
    div.big-div-text{
        width: 60%;
        text-align: center;
        margin-right: 3.5rem;
        
        button{
        background-color: $main-color-text;
        color: $blue-electric;
        font-size: .7rem;
        font-weight: bolder;
        width: 30%;
    }
    h1{
        font-weight: bolder;
        font-size: 2.6rem;
        margin-top: 2rem;
    }
    p{
        font-size: .9rem;
        margin-top: 1.5rem;
        margin-bottom: 1.5rem;
    }}
    div.small-div-img{
        width: 40%;
    img{
        object-fit: contain;
        object-position: center;  
    }}

   
</style>