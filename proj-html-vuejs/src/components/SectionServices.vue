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
</template>

<script>
export default {
    
}
</script>

<style lang="scss">
@use '../styles/general.scss' as *;
@use '../styles/partials/variables' as *;
    

    .blue{
        color: $blue-electric;
    }
</style>