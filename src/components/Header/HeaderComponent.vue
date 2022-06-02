<template>
    <!-- Header Top Start -->
    <div class="container-fluid header_top_menu_main">
        <div class="container">
            <div class="row">
                <div class="col-md-5 col-12 p-0">
                    <marquee class="header_top_menu_marquee">
                        <span><i class="fa fa-grav" aria-hidden="true"></i> Admission Open for
                            MBA and MBM, Summer 2022</span>
                        <span><i class="fa fa-grav" aria-hidden="true"></i> Admission Open for
                            MBA and MBM, Summer 2022</span>
                    </marquee>
                </div>
                <div class="col-md-7 col-12 p-0">
                    <div class="header_top_menu_right">
                        <ul>
                            <li>
                                <a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Login</a>
                            </li>
                            <li>
                                <a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Faculties</a>
                            </li>
                            <li>
                                <a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Alumni</a>
                            </li>
                            <li>
                                <a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Webmail</a>
                            </li>
                            <li>
                                <a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>G Suite</a>
                            </li>
                            <li>
                                <a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Career</a>
                            </li>
                            <li>
                                <a href="#"><i class="fa fa-sign-in" aria-hidden="true"></i>Transport</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Header Top End -->

    <!-- Header Bottom Start -->
    <div class="container-fluid header_bottom_main">
        <div class="container">
            <div class="row py-2">
                <div class="col-md-6 col-12 p-0">
                    <div class="header_bottom_left">
                        <img src="./../../assets/images/logo.png" alt="" class="img-fluid" />
                    </div>
                </div>
                <div class="col-md-6 col-12 p-0">
                    <div class="header_bottom_right">
                        <button><i class="fa fa-search" aria-hidden="true"></i></button>
                        <button>Quick Contact</button>
                        <button>Clearance Form</button>
                        <button>Quick Info</button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Header Bottom End -->

    <!-- Menu Line Start -->
    <div class="header_menu_top"></div>
    <!-- Menu Line End -->

    <!-- Main Menu Start -->
    <div class="container-fluid p-0 header_main_menu">
        <div class="">
            <!-- ============= COMPONENT ============== -->
            <nav class="navbar navbar-expand-lg navbar-dark bg-white shadow">
                <div class="container-fluid">
                    <!-- <a class="navbar-brand" href="#">Brand</a> -->
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#main_nav"
                        aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse justify-content-center" id="main_nav">
                        <ul class="navbar-nav justify-center">
                            <li class="nav-item active">
                                <router-link to="/" href="#" class="nav-link">Home</router-link>
                                <!-- <a class="nav-link" href="#">Home </a> -->
                            </li>
                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown">
                                    About IIUC
                                </a>
                                <ul class="dropdown-menu">
                                    <li>
                                        <router-link to="/iiuc-history" href="#" class="dropdown-item">IIUC History</router-link>
                                        <!-- <a class="dropdown-item" href="#"> IIUC History </a> -->
                                    </li>
                                    <li>
                                        <router-link class="dropdown-item" href="/" to="/board-of-trustees"> Board of Trustees </router-link>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Action and Fomer IIUC VC & Pro-VC</a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#">
                                            Message &raquo;
                                        </a>
                                        <ul class="submenu dropdown-menu">
                                            <li>
                                                <a class="dropdown-item" href="#">Vice-Chancellor</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Pro Vice-Chancellor</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Chairman, BoT</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Treasurer</a>
                                            </li>
                                            <!-- <li>
                                                <a class="dropdown-item" href="#">Submenu item 3 &raquo;
                                                </a>
                                                <ul class="submenu dropdown-menu">
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 1</a>
                                                    </li>
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 2</a>
                                                    </li>
                                                </ul>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 4</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 5</a>
                                            </li> -->
                                        </ul>
                                    </li>

                                    <li>
                                        <a class="dropdown-item" href="#"> Photo Gallery </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Mission and Vision </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#">
                                            IIUC Infra-Structure &raquo;
                                        </a>
                                        <ul class="submenu dropdown-menu">
                                            <li>
                                                <a class="dropdown-item" href="#">Board of Trustees</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">It Facilites</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Transport Facilites</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Central Mosque</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Medical Center</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Auditorium</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Student Hall</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Sports and Recreation</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Library Automation</a>
                                            </li>
                                            <!-- <li>
                                                <a class="dropdown-item" href="#">Submenu item 3 &raquo;
                                                </a>
                                                <ul class="submenu dropdown-menu">
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 1</a>
                                                    </li>
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 2</a>
                                                    </li>
                                                </ul>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 4</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 5</a>
                                            </li> -->
                                        </ul>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Location Map </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> IIUC Ranking </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Foreign Collaboration </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Contact Us </a>
                                    </li>
                                </ul>
                            </li>
                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown">
                                    Administartion
                                </a>
                                <ul class="dropdown-menu">
                                    <li>
                                        <a class="dropdown-item" href="#"> IIUC History </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Board of Trustees </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Action and Fomer IIUC VC & Pro-VC</a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#">
                                            Message &raquo;
                                        </a>
                                        <ul class="submenu dropdown-menu">
                                            <li>
                                                <a class="dropdown-item" href="#">Vice-Chancellor</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Pro Vice-Chancellor</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Chairman, BoT</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Treasurer</a>
                                            </li>
                                            <!-- <li>
                                                <a class="dropdown-item" href="#">Submenu item 3 &raquo;
                                                </a>
                                                <ul class="submenu dropdown-menu">
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 1</a>
                                                    </li>
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 2</a>
                                                    </li>
                                                </ul>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 4</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 5</a>
                                            </li> -->
                                        </ul>
                                    </li>

                                    <li>
                                        <a class="dropdown-item" href="#"> Photo Gallery </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Mission and Vision </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#">
                                            IIUC Infra-Structure &raquo;
                                        </a>
                                        <ul class="submenu dropdown-menu">
                                            <li>
                                                <a class="dropdown-item" href="#">Board of Trustees</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">It Facilites</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Transport Facilites</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Central Mosque</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Medical Center</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Auditorium</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Student Hall</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Sports and Recreation</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Library Automation</a>
                                            </li>
                                            <!-- <li>
                                                <a class="dropdown-item" href="#">Submenu item 3 &raquo;
                                                </a>
                                                <ul class="submenu dropdown-menu">
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 1</a>
                                                    </li>
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 2</a>
                                                    </li>
                                                </ul>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 4</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 5</a>
                                            </li> -->
                                        </ul>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Location Map </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> IIUC Ranking </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Foreign Collaboration </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Contact Us </a>
                                    </li>
                                </ul>
                            </li>
                            <li class="nav-item dropdown">
                                <a class="nav-link dropdown-toggle" href="#" data-bs-toggle="dropdown">
                                    Admission
                                </a>
                                <ul class="dropdown-menu">
                                    <li>
                                        <a class="dropdown-item" href="#"> IIUC History </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Board of Trustees </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Action and Fomer IIUC VC & Pro-VC</a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#">
                                            Message &raquo;
                                        </a>
                                        <ul class="submenu dropdown-menu">
                                            <li>
                                                <a class="dropdown-item" href="#">Vice-Chancellor</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Pro Vice-Chancellor</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Chairman, BoT</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Treasurer</a>
                                            </li>
                                            <!-- <li>
                                                <a class="dropdown-item" href="#">Submenu item 3 &raquo;
                                                </a>
                                                <ul class="submenu dropdown-menu">
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 1</a>
                                                    </li>
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 2</a>
                                                    </li>
                                                </ul>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 4</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 5</a>
                                            </li> -->
                                        </ul>
                                    </li>

                                    <li>
                                        <a class="dropdown-item" href="#"> Photo Gallery </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Mission and Vision </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#">
                                            IIUC Infra-Structure &raquo;
                                        </a>
                                        <ul class="submenu dropdown-menu">
                                            <li>
                                                <a class="dropdown-item" href="#">Board of Trustees</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">It Facilites</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Transport Facilites</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Central Mosque</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Medical Center</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Auditorium</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Student Hall</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Sports and Recreation</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Library Automation</a>
                                            </li>
                                            <!-- <li>
                                                <a class="dropdown-item" href="#">Submenu item 3 &raquo;
                                                </a>
                                                <ul class="submenu dropdown-menu">
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 1</a>
                                                    </li>
                                                    <li>
                                                        <a class="dropdown-item" href="#">Multi level 2</a>
                                                    </li>
                                                </ul>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 4</a>
                                            </li>
                                            <li>
                                                <a class="dropdown-item" href="#">Submenu item 5</a>
                                            </li> -->
                                        </ul>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Location Map </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> IIUC Ranking </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Foreign Collaboration </a>
                                    </li>
                                    <li>
                                        <a class="dropdown-item" href="#"> Contact Us </a>
                                    </li>
                                </ul>
                            </li>
                        </ul>
                    </div>
                    <!-- navbar-collapse.// -->
                </div>
                <!-- container-fluid.// -->
            </nav>

            <!-- ============= COMPONENT END// ============== -->
        </div>
    </div>
    <!-- Main Menu End -->

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
                        <img src="./../../assets/images/S1.jpg" class="d-block w-100" alt="..." />
                    </div>
                    <div class="carousel-item">
                        <img src="./../../assets/images/S2.jpg" class="d-block w-100" alt="..." />
                    </div>
                    <div class="carousel-item">
                        <img src="./../../assets/images/S3.jpg" class="d-block w-100" alt="..." />
                    </div>
                    <div class="carousel-item">
                        <img src="./../../assets/images/S4.jpg" class="d-block w-100" alt="..." />
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
    name: "HeaderComponent",
};

document.addEventListener("DOMContentLoaded", function () {
    // make it as accordion for smaller screens
    if (window.innerWidth < 992) {
        // close all inner dropdowns when parent is closed
        document
            .querySelectorAll(".navbar .dropdown")
            .forEach(function (everydropdown) {
                everydropdown.addEventListener("hidden.bs.dropdown", function () {
                    // after dropdown is hidden, then find all submenus
                    this.querySelectorAll(".submenu").forEach(function (everysubmenu) {
                        // hide every submenu as well
                        everysubmenu.style.display = "none";
                    });
                });
            });

        document.querySelectorAll(".dropdown-menu a").forEach(function (element) {
            element.addEventListener("click", function (e) {
                let nextEl = this.nextElementSibling;
                if (nextEl && nextEl.classList.contains("submenu")) {
                    // prevent opening link if link needs to open dropdown
                    e.preventDefault();
                    if (nextEl.style.display == "block") {
                        nextEl.style.display = "none";
                    } else {
                        nextEl.style.display = "block";
                    }
                }
            });
        });
    }
    // end if innerWidth
});
// DOMContentLoaded  end
</script>

<style scoped>
/* Header Top Start */

.header_top_menu_main {
    background: linear-gradient(180deg, #0f075a 0%, #151262 36.57%, #495e96 100%);
}

.header_top_menu_marquee {
    color: #41ff8d !important;
    padding: 4px 0px !important;
}

.header_top_menu_right ul {
    display: table;
    float: right;
    margin-bottom: 0px !important;
}

.header_top_menu_right ul li {
    display: inline-block;
    border-right: 2px solid #acb7d7;
    color: white;
}

.header_top_menu_right ul li:last-child {
    border-right: none;
}

.header_top_menu_right ul li a {
    display: block;
    padding: 10px 5px !important;
    color: white;
    font-family: "Rubik", sans-serif;
    font-size: 15px;
    font-weight: 400;
    line-height: 19px;
    letter-spacing: 0em;
    text-align: left;
    text-decoration: none;
}

.header_top_menu_right ul li a svg {
    margin: 0px 5px;
}

@media only screen and (max-width: 600px) {
    .header_top_menu_right ul {
        display: block;
        float: none;
        margin-bottom: 10px !important;
        background-color: #31aed3;
    }

    .header_top_menu_right ul li {
        border-right: none;
    }
}

/* Header Top End */

/* ================================== */

/* Header Bottom Start */

.header_bottom_right {
    padding: 20px 0px !important;
    display: table;
    float: right;
}

.header_bottom_right button {
    background-color: #31aed3;
    border-radius: 4px;
    padding: 05px 15px !important;
    border: none;
    outline: none;
    font-family: "Rubik", sans-serif;
    font-size: 14px;
    font-weight: 500;
    line-height: 17px;
    letter-spacing: 0em;
    text-align: left;
    color: #ffffff;
    margin-left: 10px !important;
}

@media only screen and (max-width: 600px) {
    .header_bottom_right {
        padding: 20px 0px !important;
        display: block;
        float: none;
    }

    .header_bottom_right button {
        background-color: #31aed3;
        border-radius: 4px;
        padding: 5px 5px !important;
        border: none;
        outline: none;
        font-family: "Rubik", sans-serif;
        font-size: 14px;
        font-weight: 500;
        line-height: 17px;
        letter-spacing: 0em;
        text-align: left;
        color: #ffffff;
        margin-left: 10px !important;
    }
}

/* Header Bottom End */

/* ================================== */

/* Menu Line Start */

.header_menu_top {
    height: 20px;
    background-color: #72006d;
}

/* Menu Line End */

/* Main Menu Start */

.header_main_menu_mid ul li a {
    color: #120d5e !important;
    font-family: "Rubik";
    font-style: normal;
    font-weight: 800;
    font-size: 18px;
    line-height: 26px;
}



#main_nav ul li a {
    color: #120d5e !important;
    font-family: "Rubik";
    font-style: normal;
    font-weight: 800;
    font-size: 18px;
    line-height: 26px;
}

/* ============ desktop view ============ */
@media all and (min-width: 992px) {
    .dropdown-menu li {
        position: relative;
    }

    .dropdown-menu .submenu {
        display: none;
        position: absolute;
        left: 100%;
        top: -7px;
    }

    .dropdown-menu .submenu-left {
        right: 100%;
        left: auto;
    }

    .dropdown-menu>li:hover {
        background-color: #f1f1f1;
    }

    .dropdown-menu>li:hover>.submenu {
        display: block;
    }
}

/* ============ desktop view .end// ============ */

/* ============ small devices ============ */
@media (max-width: 991px) {
    .dropdown-menu .dropdown-menu {
        margin-left: 0.7rem;
        margin-right: 0.7rem;
        margin-bottom: 0.5rem;
    }
}

/* ============ small devices .end// ============ */

/* Main Menu End */

/* Slider Section Start */

.carousel-inner img {
    height: 542px;
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
