<template>
    <HeaderComponent></HeaderComponent>
    <PaginationComponent></PaginationComponent>
    <div class="about_vc_view_main">
        <div class="container">
            <div class="row">
                <div class="about_vc_view_main_hero">
                    <div class="about_vc_view_main_hero_text">
                        <h5>Prof. Md. Anwarul Azim Arif</h5>
                        <p>The Hon’ble Vice-Chancellor</p>
                        <p>International Islamic University Chittagong</p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="about_vc_view_main_massage">
                    <h5>Message from The Hon’ble Vice-Chancellor:</h5>
                    <p>International Islamic University Chittagong (IIUC) was established in 1995 by the Islamic
                        University
                        Chittagong Trust (IUCT) with a mission of developing this university as an ideal institution of
                        higher learning and research in the private sector of Bangladesh. IUC Trust and its Syndicate
                        are
                        being run by academic scholars and leaders of international repute, consisting of scholars from
                        home
                        and abroad. The vision of IIUC is to combine quality education with morality so that the
                        graduates
                        of this university grow up with skill-based modern knowledge and strong morality for humanness.
                        In
                        the higher education sector of Bangladesh, IIUC has already established itself as a forerunner
                        of
                        addressing the challenges of globalization by providing appropriate knowledge imbued with
                        morality
                        in order to bring peace, progress and tranquility in human societies across the globe.

                    </p>

                    <p>Over the past years of its establishment, development and expansion, it has cut an image of one
                        of
                        the best ranking private universities in Bangladesh. And this is because of the fact that IIUC
                        has
                        qualified faculties in all the departments having sufficient library, lab and internet
                        facilities.
                        Currently IIUC has more than one lac fifty thousands books in its central library along with
                        five
                        thousand e-journals and each faculty has its seminar library with required books and journals. A
                        good number of IIUC graduates have obtained higher degrees from foreign universities which is
                        the
                        testimony of its best quality education. Many graduates of this university are being employed
                        within
                        the country and outside and are holding important positions both in private and public sectors.
                        A
                        few graduates of IIUC are also recruited in the teaching and non-teaching positions of public
                        universities. One of the unique features of IIUC is that it is providing separate education to
                        male
                        and female students. Moreover, IIUC has developed its 40 acres Permanent Campus at Kumira
                        (Sitakunda) – 22 km off Chittagong City and situated beside the Dhaka-Chittagong highway in a
                        hilly
                        area with required modern facilities and in a beautiful landscape with thin forest bounties.</p>

                    <p>I expect that the students of IIUC will try their best to take the fullest advantage of this
                        university, by freely interacting with teachers and officials of IIUC which has already become
                        their
                        chosen institution of higher learning and research.</p>

                    <p>May Allah help us all.</p>
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



export default {
    name: 'AboutVcView',
    components: {
        HeaderComponent,
        PaginationComponent,
        FooterComponent
    }

}
</script>

<style scoped>
.about_vc_view_main_hero {
    background-image: url("./../assets/images/Rectangle67.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;

    height: 550px;
    position: relative;
}

.about_vc_view_main_hero_text {
    position: absolute;
    bottom: 10px;
    left: 0px;
    right: 0px;
    margin: auto;
    text-align: left;
    margin-left: 20px;
    border-left: 4px solid #31AED3;
    padding-left: 10px;
}

.about_vc_view_main_hero_text h5 {
    font-size: 14px;
    font-weight: bolder;
    color: #31AED3;
}

.about_vc_view_main_hero_text p {
    color: white;
    font-weight: bolder;
}

.about_vc_view_main_massage {
    margin-top: 20px;
    margin-bottom: 20px;
    text-align: left;
}

.about_vc_view_main_massage h5 {
    font-size: 14px;
    font-weight: bolder;
    color: #31AED3;
}

.about_vc_view_main_massage p {
    color: black;
    font-size: 14px;
}

.about_vc_view_main_massage p:nth-child(2) {
    margin-top: 40px;
}

</style>