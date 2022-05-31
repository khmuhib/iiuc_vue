<template>
      <!-- Main Menu Start -->
    <div class="container-fluid p-0 header_main_menu">
        <div class="">
            <nav class="navbar navbar-expand-lg navbar-light shadow-sm">
                <div class="container-fluid">
                    <!-- <a class="navbar-brand" href="#">Navbar</a> -->
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                  </button>
                    <div class="container header_main_menu_mid">
                        <div class="collapse navbar-collapse justify-content-around" id="navbarNavDropdown">
                            <ul class="navbar-nav justify-content-between w-100">
                                <li class="nav-item">
                                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">About IIUC</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Administartion</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Admission</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Academic</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Research & Publication</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">IQAC</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Library</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Conference</a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">CGED</a>
                                </li>
                                <!-- <li class="nav-item dropdown">
                                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                              Dropdown link
                            </a>
                                    <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                                        <li><a class="dropdown-item" href="#">Action</a></li>
                                        <li><a class="dropdown-item" href="#">Another action</a></li>
                                        <li><a class="dropdown-item" href="#">Something else here</a></li>
                                    </ul>
                                </li> -->
                            </ul>
                        </div>
                    </div>
                </div>
            </nav>
        </div>
    </div>
    <!-- Main Menu End -->
</template>

<script>
export default {
    name: 'HeaderMainMenuComponent',

}
</script>

<style>
/* Main Menu Start */

.header_main_menu_mid ul li a {
    color: #120D5E!important;
    font-family: 'Rubik';
    font-style: normal;
    font-weight: 800;
    font-size: 18px;
    line-height: 26px;
}


/* Main Menu End */
</style>