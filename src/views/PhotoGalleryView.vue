<template>
    <HeaderComponent></HeaderComponent>
    <SliderComponent></SliderComponent>
    <PaginationComponent></PaginationComponent>
    <div class="photo_gallery_main">
        <div class="container">
            <div class="row">
                <h1>Photo Gallery</h1>
                <hr>
            </div>
            <div class="row">
                <div class="col-md-6 col-12">
                    <div class="photo_gallery_card">
                        <div class="photo_gallery_title">
                            <h5>Orientation and Discussion meeting of Scholarship holder Students of IIUC</h5>
                        </div>
                        <div class="photo_gallery_img">
                            <img src="./../assets/images/image60.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-12">
                    <div class="photo_gallery_card">
                        <div class="photo_gallery_title">
                            <h5>Orientation and Discussion meeting of Scholarship holder Students of IIUC</h5>
                        </div>
                        <div class="photo_gallery_img">
                            <img src="./../assets/images/image60.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-12">
                    <div class="photo_gallery_card">
                        <div class="photo_gallery_title">
                            <h5>Orientation and Discussion meeting of Scholarship holder Students of IIUC</h5>
                        </div>
                        <div class="photo_gallery_img">
                            <img src="./../assets/images/image60.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-12">
                    <div class="photo_gallery_card">
                        <div class="photo_gallery_title">
                            <h5>Orientation and Discussion meeting of Scholarship holder Students of IIUC</h5>
                        </div>
                        <div class="photo_gallery_img">
                            <img src="./../assets/images/image60.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-12">
                    <div class="photo_gallery_card">
                        <div class="photo_gallery_title">
                            <h5>Orientation and Discussion meeting of Scholarship holder Students of IIUC</h5>
                        </div>
                        <div class="photo_gallery_img">
                            <img src="./../assets/images/image60.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-12">
                    <div class="photo_gallery_card">
                        <div class="photo_gallery_title">
                            <h5>Orientation and Discussion meeting of Scholarship holder Students of IIUC</h5>
                        </div>
                        <div class="photo_gallery_img">
                            <img src="./../assets/images/image60.png" alt="">
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-12">
                    <div class="photo_gallery_card">
                        <div class="photo_gallery_title">
                            <h5>Orientation and Discussion meeting of Scholarship holder Students of IIUC</h5>
                        </div>
                        <div class="photo_gallery_img">
                            <img src="./../assets/images/image60.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <FooterComponent></FooterComponent>
</template>

<script>
import FooterComponent from "@/components/Footer/FooterComponent.vue";
import HeaderComponent from "@/components/Header/HeaderComponent.vue";
import PaginationComponent from "@/components/PaginationComponent.vue";
import SliderComponent from "@/components/SliderComponent.vue";

export default {
    name: 'PhotoGalleryView',
    components: {
        FooterComponent,
        HeaderComponent,
        PaginationComponent,
        SliderComponent,
    }

}
</script>

<style scoped>

.photo_gallery_main {
    box-sizing: border-box;
    overflow: hidden;
    margin: 30px 0px;
}

.photo_gallery_main h1 {
    font-size: 30px;
    color: black;
    text-align: center;

}

.photo_gallery_card {
    margin-top: 30px;
}

.photo_gallery_main hr {
    height: 5px;
    background-color: black;
    width: 20%;
    display: block;
    margin: auto;
    border: none;
    outline: none;

}

.photo_gallery_card {
    background-color: aqua;

}

.photo_gallery_title h5 {
    color: white;
    font-size: 14px;
    text-align: left;
    background-color: #0F075A;
    padding: 10px 10px;
    margin-bottom: 0px;
}

.photo_gallery_img img {
    width: 100%;
}

</style>