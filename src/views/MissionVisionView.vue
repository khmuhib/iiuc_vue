<template>
  <HeaderComponent></HeaderComponent>
  <SliderComponent></SliderComponent>
  <PaginationComponent></PaginationComponent>
  <div class="mission_vision_main">
    <div class="container">
      <div class="row">
        <div class="mission_vision_card">
          <h5>Mission</h5>
          <p>
            International Islamic University Chittagong (IIUC) is one of the top
            graded government approved private universities in Bangladesh.
            Having fulfilled the requirements as laid down in the Private
            University Act of 1992, and after obtaining the necessary clearance
            from the University Grants Commission (UGC), and the permission of
            Government of Bangladesh (GOB) through the Ministry of Education,
            International Islamic University Chittagong (IIUC) started
            functioning on February 11 1995. The credit for the idea of
            establishing this University goes to International Islamic
            University Chittagong Trust (IIUCT). IIUC framed its own Statues,
            Ordinances and Regulations governing the manifold activities of IIUC
            – academic, administrative, financial, student welfare, discipline
            etc. as per the Private University Act, 1992, 1998 and revised Act,
            2010. Most statutory bodies formed under the provisions of the Act
            have since then been functioning.
            <br /><br />
            The Mission of the University is to produce through the pursuit of
            education properly trained up manpower to contribute t
            socio-economic development and moral upliftment of the society and
            to cultivate in our students expertise as we as ethical sensitivity,
            intelligence and an ability to think independently beyond their
            areas of study, so that they can sustain justice in all walks of
            life.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="mission_vision_card">
          <h5>Vision</h5>
          <p>
            The Vision of the University is to offer nationally competitive and
            internationally recognized opportunities for learning to make this
            University as the Centre of Excellence in different areas of
            scholarship, like Shari’ah and Islamic Studies, Business Studies,
            Social Science, Science & Engineering, Arts & Humanities, Law, and
            such other faculties that will be introduced in future. Its door is
            open to the admission seekers from all over the world, regardless of
            race, region and religion. This university cherished the dream of
            becoming one of the highest seat of learning and creator of
            knowledge in the South East Asia.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="mission_vision_card">
          <h5>Objective</h5>
          <p>
            1. To create a new generation of competent youths who will be equipped with academic excellence, professional expertise and adorned with moral height. <br> 2. To follow a policy of continued Modernization of knowledge and academic curricula in different disciplines of education so that its students can imbibe the true spirit of religious value as an effective guiding principle in their profession and daily life.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="mission_vision_card">
          <h5>Motto</h5>
          <p>
            The Moto of the University is to “Combine Quality with Morality”.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="mission_vision_card">
          <h5>Teaching Methods & policy</h5>
          <p>
            <span>1. Methods:</span> outcome-based education (OBE) and Bi – Semester system of Continuous Quality Improvement (CQI) through self-examination and external review. In this process students are evaluated throughout a course of study rather that exclusively by examination at the end. It is multidimensional and based on students (a) Attendance in the classes (b) Performance in Assignments and Class Tests (c) Scores in the Mid-Term and the Final examination (d) Lab. Reports (e) Thesis/Project/Internship (f) Presentations (g) Viva-Voce (f) Industry Visits (g) Co-Curricular and Extra-Curricular activities <br><br>
            <span>2. Policy:</span> The University is committed to the life-long success of students in its undergraduate and master’s program through high-quality instruction and learning experiences. IIUC ha Integrated Education policy, where a student achieves holistic learning through awareness of his surroundings and other relevant knowledge bases. IIUC emphasizes the diffusion of scientific, technical and profession knowledge on the other hand. In this regard, there are some courses for the students of all Faculties at IIUC, which are not a part of the main curriculum of the Departments, but those are named as University Requirement Courses (URC). <br><br>
            <span>3. Morality Development Program:</span> IIUC incorporates studies on the values of mutual respect & peaceful co-existence in the in the courses under the “Development Program (MDP)” which includes all students of the university irrespective of caste, creed or religion. <br><br>
            <span>4. Co-Curricular and Extra-Curricular activities:</span> IIUC supports student participation in a broad array of Co-Curricular and Extra-Curricular activities as an integral component of its commitment to student life and success. These programs mainly includes leadership training, cultural, environmental, recreational and social activities, debating & public speaking programs, intellectual discussions, games & sports, excursion and study tour home & abroad to complement academic pursuits. By this programs student earn capacity to express out themselves properly, maintain personality and learn to respect people of other faiths through mutual understanding among various regions, religions, belief and cultures. All Co and Extra-curricular activities are run by the club named after the Department, Computer Club and Business Club etc under the close supervision and monitoring of students Affairs Division (STAD). <br><br>
            <span>5. Students Advisor:</span> IIUC provides student counseling, career and student welfare counseling by the Student Advisor of respective section of the students semester.01775953422
          </p>
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
  name: "MissionVisionView",
  components: {
    FooterComponent,
    HeaderComponent,
    PaginationComponent,
    SliderComponent,
  },
};
</script>

<style scope>
.mission_vision_main {
  margin: 30px 0px;

}

.mission_vision_card {
  text-align: left;
}

.mission_vision_card h5 {
  font-size: 16px;
  font-weight: bold;
  color: #130b63;
}

.mission_vision_card p {
  font-size: 14px;
}

.mission_vision_card p span {
    font-weight: bold;
    color: #086B30;
}
</style>
