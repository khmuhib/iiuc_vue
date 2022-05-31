<template>
      <!-- New Archive Start -->
    <div class="container-fluid news_archive_main">
        <div class="container">
            <div class="row py-2">
                <div class="col-md-2 mt-2 col-12">
                    <div class="news_archive_title">
                        <h3>News<br><span><b>Archive</b></span></h3>
                    </div>
                </div>
                <div class="col-md-10">
                    <div class="owl_carousole_main mt-2">
                        <div class="owl-carousel owl-theme">
                            <div class="item">
                                <div class="row">
                                    <div class="col-md-4 col-12">
                                        <div class="item_left">
                                            <img src="images/S1.jpg" alt="">
                                        </div>
                                    </div>
                                    <div class="col-md-8 col-12">
                                        <div class="item_right">
                                            <h3>দিনব্যাপী বর্ণাঢ্য আয়োজনে আইআইইউসি উদযাপন করলো বিজয়ের সুবর্ণ জয়ন্তী </h3>
                                            <p>19 April, 2021</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="item">
                                <div class="row">
                                    <div class="col-md-4 col-12">
                                        <div class="item_left">
                                            <img src="images/S1.jpg" alt="">
                                        </div>
                                    </div>
                                    <div class="col-md-8 col-12">
                                        <div class="item_right">
                                            <h3>দিনব্যাপী বর্ণাঢ্য আয়োজনে আইআইইউসি উদযাপন করলো বিজয়ের সুবর্ণ জয়ন্তী </h3>
                                            <p>19 April, 2021</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="item">
                                <div class="row">
                                    <div class="col-md-4 col-12">
                                        <div class="item_left">
                                            <img src="images/S1.jpg" alt="">
                                        </div>
                                    </div>
                                    <div class="col-md-8 col-12">
                                        <div class="item_right">
                                            <h3>দিনব্যাপী বর্ণাঢ্য আয়োজনে আইআইইউসি উদযাপন করলো বিজয়ের সুবর্ণ জয়ন্তী </h3>
                                            <p>19 April, 2021</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="item">
                                <div class="row">
                                    <div class="col-md-4 col-12">
                                        <div class="item_left">
                                            <img src="images/S1.jpg" alt="">
                                        </div>
                                    </div>
                                    <div class="col-md-8 col-12">
                                        <div class="item_right">
                                            <h3>দিনব্যাপী বর্ণাঢ্য আয়োজনে আইআইইউসি উদযাপন করলো বিজয়ের সুবর্ণ জয়ন্তী </h3>
                                            <p>19 April, 2021</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="item">
                                <div class="row">
                                    <div class="col-md-4 col-12">
                                        <div class="item_left">
                                            <img src="images/S1.jpg" alt="">
                                        </div>
                                    </div>
                                    <div class="col-md-8 col-12">
                                        <div class="item_right">
                                            <h3>দিনব্যাপী বর্ণাঢ্য আয়োজনে আইআইইউসি উদযাপন করলো বিজয়ের সুবর্ণ জয়ন্তী </h3>
                                            <p>19 April, 2021</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </div>
    <!-- New Archive End -->
</template>

<script>
export default {
    name: 'NewsArchiveComponent',
}
</script>

<style>
/* News Archive Start */

.news_archive_main {
    overflow: hidden;
    background-color: #D9D6FB;
    margin: 0px 0px;
}

.news_archive_title {
    border-right: 4px solid #120D5E;
    display: table;
    padding: 2px 18px;
    margin-top: 40px;
}

.news_archive_title h3 {
    font-family: 'Rubik';
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 30px;
    color: #120D5E;
}

.owl_carousole_main {}

.item {
    overflow: hidden;
}

.item_left {
    height: 150px;
    width: 100%;
    float: left;
}

.item_left img {
    height: 150px!important;
    width: 100%!important;
}

.item_right {
    width: 100%;
    float: left;
    padding: 0px 10px;
}

.item_right h3 {
    font-family: 'Rubik';
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 38px;
    /* or 158% */
    color: #000000;
    margin-top: 30px;
}

.owl-dots {
    display: none;
}

.owl_carousole_main {
    position: relative;
}

.owl-prev {
    position: absolute;
    top: 60px;
    left: -82px;
    right: 0px;
    bottom: 0px;
    margin: auto;
    height: 30px!important;
    width: 30px!important;
    border-radius: 50%!important;
    background-color: #0F075A!important;
    color: white;
}

.owl-prev span {
    color: white;
}

.owl-next span {
    color: white;
}

.owl-next {
    position: absolute;
    top: 60px;
    /* left: 0px; */
    right: -82px;
    bottom: 0px;
    margin: auto;
    height: 30px!important;
    width: 30px!important;
    border-radius: 50%!important;
    background-color: #0F075A!important;
    color: white;
}

@media only screen and (max-width: 600px) {
    .news_archive_title {
        border: none;
        display: block;
        text-align: center;
        margin-top: 0px;
    }
    .item_left {
        width: 100%;
        text-align: center;
    }
    .item_right {
        width: 100%;
    }
    .item_right h3 {
        text-align: center;
    }
    .item_right p {
        text-align: center;
    }
}


/* News Archive End */
</style>