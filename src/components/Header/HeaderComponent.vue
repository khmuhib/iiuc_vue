<template>
    <!-- Header Top Start -->
    <div class="container-fluid header_top_menu_main">
        <div class="container">
            <div class="row">
                <div class="col-md-5 col-12 p-0">
                    <marquee class="header_top_menu_marquee">
                        <span v-for="(item, i) in marquee" :key="i"><i :class="item.icon" aria-hidden="true"></i>
                            {{ item.title }}
                        </span>
                    </marquee>
                </div>
                <div class="col-md-7 col-12 p-0">
                    <div class="header_top_menu_right">
                        <ul>
                            <li v-for="(item, i) in header_top" :key="i">
                                <router-link to="/"><i :class=item.icon aria-hidden="true"></i>{{ item.title }}
                                </router-link>
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
                        <img :src="logo" alt="" class="img-fluid" />
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
                            <!-- <li class="nav-item active">
                                <router-link to="/" href="#" class="nav-link">Home</router-link>
                            </li> -->
                            <li class="nav-item dropdown" v-for="(item, i) in main_menu" :key="i">
                                <router-link :to=item.link :class="item.sub_menu ? 'nav-link dropdown-toggle' : 'nav-link'" data-bs-toggle="dropdown">
                                    {{ item.title }}
                                </router-link>


                                <ul class="dropdown-menu" v-if="item.sub_menu">
                                    <li v-for="(sub_item, j) in item.sub_menu" :key="j">
                                        <router-link :to=sub_item.link class="dropdown-item">
                                            {{ sub_item.title }} <span v-if="sub_item.mega_sub_menu">&raquo;</span>
                                        </router-link>
                                        <ul class="submenu dropdown-menu" v-if="sub_item.mega_sub_menu">
                                            <li v-for="(mega_sub_menu, k) in sub_item.mega_sub_menu" :key="k">
                                                <router-link :to=mega_sub_menu.link class="dropdown-item">{{ mega_sub_menu.title }}</router-link>
                                            </li>
                                        </ul>
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


</template>

<script>
import logo from "./../../assets/images/logo.png"

export default {
    name: "HeaderComponent",
    data() {
        return {

            logo: logo,
            header_top: [
                {
                    title: 'Title1',
                    link: '#',
                    icon: 'fa fa-home'
                },
                {
                    title: 'Title2',
                    link: '#',
                    icon: 'fa fa-home'
                },
                {
                    title: 'Title3',
                    link: '#',
                    icon: 'fa fa-home'
                },
                {
                    title: 'Title4',
                    link: '#',
                    icon: 'fa fa-home'
                },
            ],
            main_menu: [
                {
                    title: 'Home',
                    link: '/'
                },
                {
                    title: 'About IIUC',
                    link: '#',
                    sub_menu: [
                        {
                            title: 'IIUC History',
                            link: '/iiuc-history',
                        },
                        {
                            title: 'Board of Trustees',
                            link: '/board-of-trustees',
                        },
                        {
                            title: 'Acting and fomer IIUC VC & Pro-VC',
                            link: '/about-former-view',
                        },
                        {
                            title: 'Message',
                            link: '#',
                            mega_sub_menu: [
                                {
                                    title: 'Vice-Chancellor',
                                    link: '/about-vc-view',
                                },
                                {
                                    title: 'Pro Vice-Chancellor',
                                    link: '/about-pro-vc-view',
                                },
                                {
                                    title: 'Chairman BOT',
                                    link: '/about-chairman-view',
                                },
                                {
                                    title: 'Treasurer',
                                    link: '/about-treasurer-view',
                                },
                            ]
                        },
                    ]
                },
                {
                    title: 'Menu02',
                    link: '#'
                },
                {
                    title: 'Menu02',
                    link: '#'
                },
                {
                    title: 'Menu02',
                    link: '#'
                },
                {
                    title: 'Menu03',
                    link: '#',
                    sub_menu: [
                        {
                            title: 'Sub01',
                            link: '#'
                        },
                        {
                            title: 'Sub02',
                            link: '#'
                        },
                        {
                            title: 'Sub03',
                            link: '#',
                            mega_sub_menu: [
                                {
                                    title: 'Mega01',
                                    link: '#'
                                },
                                {
                                    title: 'Mega02',
                                    link: '#'
                                },
                                {
                                    title: 'Mega03',
                                    link: '#'
                                },
                                {
                                    title: 'Mega04',
                                    link: '#'
                                },
                            ],
                        },
                        {
                            title: 'Sub04',
                            link: '#'
                        },
                    ]
                },
                {
                    title: 'Menu04',
                    link: '#'
                },
            ],

            marquee: [
                {
                    title: 'Marquee1',
                    icon: 'fa fa-home',
                },
                {
                    title: 'Marquee2',
                    icon: 'fa fa-home',
                },
                {
                    title: 'Marquee3',
                    icon: 'fa fa-home',
                },
                {
                    title: 'Marquee4',
                    icon: 'fa fa-home',
                },
                {
                    title: 'Marquee5',
                    icon: 'fa fa-home',
                },
            ],
        };
    },
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
marquee span {
    margin-left: 15px;
}

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

    .navbar-dark .navbar-toggler {
        background-color: #31AED3;
    }
}

/* ============ small devices .end// ============ */

/* Main Menu End */


</style>
