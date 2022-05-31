<template>
      <!-- Slider Section Start -->

    <div class="container-fluid">
        <div class="container">
            <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
                    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
                </div>
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="./../../assets/images/S1.jpg" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="./../../assets/images/S2.jpg" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="./../../assets/images/S3.jpg" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                        <img src="./../../assets/images/S4.jpg" class="d-block w-100" alt="...">
                    </div>
                </div>


                
                <!-- <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Next</span>
                </button> -->
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

<style>
/* Slider Section Start */

.carousel-inner img {
    height: 542px;
}

.carousel-indicators button {
    height: 15px!important;
    width: 15px!important;
    border-radius: 50%;
}

@media only screen and (max-width: 600px) {
    .carousel-inner img {
        height: 300px;
    }
}


/* Slider Section End */
</style>