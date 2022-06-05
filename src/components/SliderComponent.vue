<template>
      <!-- Slider Section Start -->

    <div class="container-fluid my-5">
        <div class="container">
            <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0"
                        class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
                        aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
                        aria-label="Slide 3"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3"
                        aria-label="Slide 4"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="./../assets/images/S1.jpg" class="d-block w-100" alt="..." />
                    </div>
                    <div class="carousel-item">
                        <img src="./../assets/images/S2.jpg" class="d-block w-100" alt="..." />
                    </div>
                    <div class="carousel-item">
                        <img src="./../assets/images/S3.jpg" class="d-block w-100" alt="..." />
                    </div>
                    <div class="carousel-item">
                        <img src="./../assets/images/S4.jpg" class="d-block w-100" alt="..." />
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Slider Section End -->
</template>

<script>


export default {
    name: 'SliderComponent',

}
</script>

<style scoped>
/* Slider Section Start */

.carousel-inner img {
    height: 300px;
}

.carousel-indicators button {
    height: 15px !important;
    width: 15px !important;
    border-radius: 50%;
}

@media only screen and (max-width: 600px) {
    .carousel-inner img {
        height: 300px;
    }

    .dropdown-menu>li:hover {
        background-color: #f1f1f1;
    }

    .dropdown-menu>li:hover>.submenu {
        display: block;
    }
}

/* Slider Section End */
</style>