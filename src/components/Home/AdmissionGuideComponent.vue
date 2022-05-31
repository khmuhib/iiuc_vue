<template>
      <!-- Admisson Guide Start -->
    <div class="container-fluid admission_guide_main">
        <div class="container py-4">
            <ul class="nav nav-pills mb-3 justify-content-center" id="pills-tab" role="tablist">
                <li class="nav-item" role="presentation">
                    <button class="nav-link active" id="pills-home-tab" data-bs-toggle="pill" data-bs-target="#pills-home-x" type="button" role="tab" aria-controls="pills-home-x" aria-selected="true">Admission Guideline</button>
                </li>
                <li class="nav-item" role="presentation">
                    <button class="nav-link" id="pills-profile-tab" data-bs-toggle="pill" data-bs-target="#pills-profile-y" type="button" role="tab" aria-controls="pills-profile-y" aria-selected="false">Admission Menu</button>
                </li>
                <li class="nav-item" role="presentation">
                    <button class="nav-link" id="pills-contact-tab" data-bs-toggle="pill" data-bs-target="#pills-contact-z" type="button" role="tab" aria-controls="pills-contact" aria-selected="false">Admission Contact</button>
                </li>
                <li class="nav-item" role="presentation">
                    <button class="nav-link" id="pills-contact-tab" data-bs-toggle="pill" data-bs-target="#pills-contact-a" type="button" role="tab" aria-controls="pills-contact" aria-selected="false">Admission FAQ</button>
                </li>
            </ul>
            <div class="tab-content" id="pills-tabContent">
                <div class="tab-pane fade show active" id="pills-home-x" role="tabpanel" aria-labelledby="pills-home-tab">
                    <div class="ratio ratio-16x9">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/go9k_9eQc4Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div class="row p-2 admission_guide_card_main">
                        <div class="col-md-3 col-6 my-2">
                            <div class="admission_guide_card">
                                <img src="images/Vector.png" alt="">
                                <span>300+</span>
                                <span>Foreign Students</span>
                            </div>
                        </div>
                        <div class="col-md-3 col-6 my-2">
                            <div class="admission_guide_card" style="background-color: #31AED3;">
                                <img src="images/Vector.png" alt="">
                                <span>300+</span>
                                <span>Foreign Students</span>
                            </div>
                        </div>
                        <div class="col-md-3 col-6 my-2">
                            <div class="admission_guide_card" style="background-color: #852481;">
                                <img src="images/Vector.png" alt="">
                                <span>300+</span>
                                <span>Foreign Students</span>
                            </div>
                        </div>
                        <div class="col-md-3 col-6 my-2">
                            <div class="admission_guide_card" style="background-color: #086B30;">
                                <img src="images/Vector.png" alt="">
                                <span>300+</span>
                                <span>Foreign Students</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="tab-pane fade" id="pills-profile-y" role="tabpanel" aria-labelledby="pills-profile-tab">

                    <div class="ratio ratio-16x9">
                        <iframe width="560" height="315" src="https://www.youtube.com/embed/1b7G5bgJz5k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div class="row p-2">
                        <div class="col-md-3 col-6 my-2">
                            <div class="admission_guide_card">
                                <img src="images/Vector.png" alt="">
                                <span>300+</span>
                                <span>Foreign Students</span>
                            </div>
                        </div>
                        <div class="col-md-3 col-6 my-2">
                            <div class="admission_guide_card">
                                <img src="images/Vector.png" alt="">
                                <span>300+</span>
                                <span>Foreign Students</span>
                            </div>
                        </div>
                        <div class="col-md-3 col-6 my-2">
                            <div class="admission_guide_card">
                                <img src="images/Vector.png" alt="">
                                <span>300+</span>
                                <span>Foreign Students</span>
                            </div>
                        </div>
                        <div class="col-md-3 col-6 my-2">
                            <div class="admission_guide_card">
                                <img src="images/Vector.png" alt="">
                                <span>300+</span>
                                <span>Foreign Students</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="tab-pane fade" id="pills-contact-z" role="tabpanel" aria-labelledby="pills-contact-tab">.zzz..</div>
                <div class="tab-pane fade" id="pills-contact-a" role="tabpanel" aria-labelledby="pills-contact-tab">.aaa..</div>
            </div>

        </div>
    </div>
    <!-- Admisson Guide End -->
</template>

<script>
export default {
    name: 'AdmissionGuideComponent',

}
</script>

<style>

/* Admission Guide Start */

.admission_guide_main {
    background-color: #E0F3F9;
}

.admission_guide_card {
    background-color: #0F075A;
    text-align: center;
    color: white;
    padding: 35px 0px;
    width: 100%;
}

.admission_guide_card img {
    display: block;
    margin: auto;
}

.admission_guide_card span {
    display: block;
}

.admission_guide_main .nav-pills .nav-link.active {
    background-color: #E0F3F9;
    color: #086B30!important;
    border-bottom: 4px solid #086B30;
    border-radius: 0px;
    text-align: left;
    font-family: 'Rubik';
    font-style: normal;
    font-weight: 900;
    font-size: 16px;
    line-height: 26px;
    /* identical to box height */
    /* tertiary */
}


/* Admission Guide End */
</style>