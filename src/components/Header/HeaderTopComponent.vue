<template>
      <!-- Header Top Start -->
    <div class="container-fluid header_top_menu_main">
        <div class="container">
            <div class="row">
                <div class="col-md-5 col-12 p-0">
                    <marquee class="header_top_menu_marquee">
                        <span><i class="fa fa-grav" aria-hidden="true"></i> Admission Open for MBA and MBM, Summer 2022</span>
                        <span><i class="fa fa-grav" aria-hidden="true"></i> Admission Open for MBA and MBM, Summer 2022</span>
                    </marquee>
                </div>
                <div class="col-md-7 col-12 p-0">
                    <div class="header_top_menu_right">
                        <ul>
                            <li><a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Login</a></li>
                            <li><a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Faculties</a></li>
                            <li><a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Alumni</a></li>
                            <li><a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Webmail</a></li>
                            <li><a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>G Suite</a></li>
                            <li><a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Career</a></li>
                            <li><a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Transport</a></li>
                        </ul>

                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Header Top End -->
</template>

<script>
export default {
    name: 'HeaderTopComponent',

}
</script>

<style>
/* Header Top Start */

.header_top_menu_main {
    background: linear-gradient(180deg, #0F075A 0%, #151262 36.57%, #495E96 100%);
}

.header_top_menu_marquee {
    color: #41FF8D!important;
    padding: 4px 0px!important;
}

.header_top_menu_right ul {
    display: table;
    float: right;
    margin-bottom: 0px!important;
}

.header_top_menu_right ul li {
    display: inline-block;
    border-right: 2px solid #ACB7D7;
    color: white;
}

.header_top_menu_right ul li:last-child {
    border-right: none;
}

.header_top_menu_right ul li a {
    display: block;
    padding: 10px 5px!important;
    color: white;
    font-family: 'Rubik', sans-serif;
    font-size: 15px;
    font-weight: 400;
    line-height: 19px;
    letter-spacing: 0em;
    text-align: left;
}

.header_top_menu_right ul li a i {
    margin-right: 5px;
}

@media only screen and (max-width: 600px) {
    .header_top_menu_right ul {
        display: block;
        float: none;
        margin-bottom: 10px!important;
        background-color: #31AED3;
    }
    .header_top_menu_right ul li {
        border-right: none;
    }
}


/* Header Top End */

</style>