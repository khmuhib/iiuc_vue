<template>
      <!-- Call To Action Start -->
    <div class="container-fluid footer_top_main">
        <div class="container">
            <div class="row py-3">
                <div class="col-md-6 col-12">
                    <div class="footer_top_left">
                        <div class="footer_top_left_logo">
                            <img src="./../../assets/images/footer_logo.png" alt="" class="img-fluid">
                        </div>
                        <div class="footer_top_left_text">
                            <h6>International Islamic University Chittagong (IIUC)</h6>
                            <p><i class="fa fa-sign-in" aria-hidden="true"></i>Kumira, Chattogram-4318</p>
                            <p><i class="fa fa-sign-in" aria-hidden="true"></i>+8802334461900-7</p>
                        </div>

                    </div>
                </div>
                <div class="col-md-6 col-12 ">
                    <div class="footer_top_right">
                        <h2>Follow Us</h2>
                        <i class="fa fa-sign-in" aria-hidden="true"></i>
                        <i class="fa fa-sign-in" aria-hidden="true"></i>
                        <i class="fa fa-sign-in" aria-hidden="true"></i>
                        <i class="fa fa-sign-in" aria-hidden="true"></i>
                    </div>

                </div>
            </div>
        </div>
    </div>


    <!--  Call to action End -->
</template>

<script>
export default {
    name: 'CallToAction'

}
</script>

<style>
/* Call to action Start */

.footer_top_main {
    background-color: #D9D6FB!important;
}

.footer_top_left {
    height: 100px;
}

.footer_top_left_logo {
    width: 25%;
    float: left;
}

.footer_top_left_logo img {
    height: 100px;
    width: 100px;
    display: block;
    margin: auto;
}

.footer_top_left_text {
    width: 75%;
    float: left;
    padding: 8px 0px;
}

.footer_top_left_text h6 {
    font-family: 'Rubik';
    font-style: normal;
    font-weight: bolder;
    font-size: 14px;
    line-height: 28px;
    color: #0F075A;
}

.footer_top_left_text p {
    margin: 0px!important;
}

.footer_top_right {
    text-align: right;
}

.footer_top_right h2 {
    font-family: 'Rubik';
    font-style: normal;
    font-weight: bolder;
    font-size: 16px;
    line-height: 28px;
    color: #0F075A;
}

@media only screen and (max-width: 600px) {
    .footer_top_right {
        text-align: left;
        margin-left: 30px;
        margin-top: 30px;
    }
}


/* Call to action End */
</style>