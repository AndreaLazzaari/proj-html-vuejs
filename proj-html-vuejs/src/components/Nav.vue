<template lang="">
    <nav class="navbar navbar-expand-lg pt-3">
        <div class="container-fluid">

            <a class="navbar-brand ms-4 me-5" href="#">
                <img src="../img/logo.png" alt="avada logo" width="30" height="30">
            </a>

            <div class="collapse navbar-collapse" id="navbarScroll">
                <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll">
                    <li class="nav-item">
                    <a class="nav-link active text-white" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link text-white" href="#">About</a>
                    </li>
                    <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle text-white" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        Services
                    </a>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item text-white" href="#">Action</a></li>
                        <li><a class="dropdown-item text-white" href="#">Another action</a></li>
                        <li><hr class="dropdown-divider text-white"></li>
                        <li><a class="dropdown-item text-white" href="#">Something else here</a></li>
                    </ul>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link text-white" href="#">Journal</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link text-white" href="#">Contct</a>
                    </li>
                </ul>
                <ul class="navbar-nav me-5 my-2 my-lg-0 navbar-nav-scroll">
                    <li class="nav-item">
                    <a class="nav-link text-white" href="#">1.800.123.4567</a>
                    </li>
                    <button type="button" class="btn text-white">Get a free consulation</button>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    
}
</script>
<style lang="scss">
@use '../styles/general.scss' as *;
@use '../styles/partials/variables' as *;

    nav a{
        color: $main-color-text
    }
    // ul button{
    //     background-color: $main-color-text;
    //     color: $blue-electric;
    //     font-size: .7rem;
    //     font-weight: bolder;
    //     width: 30%;
    // }
</style>