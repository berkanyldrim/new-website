<template>
    <!-- Main Body Start -->
    <section class="w-100 float-left service-con padding-top padding-bottom position-relative" id="service-con" >
        <div class="container">
            <div class="service-inner-con position-relative">
                
                <div class="generic-title text-center">
                    <h6>About</h6>
                    <h2 class="mb-0">Brief Summary of <br>
                        My Life
                    </h2>
                </div>
                <div class="service-box wow fadeInUp">
                    <div class="row">
                        <!-- Education Area Start -->
                        <div class="col-lg-6 col-md-6">
                        <div class="service-box-item">
                            <figure class="mb-0">
                                <img src="assets/image/service-icon1.png" alt="service-icon" class="img-fluid">
                            </figure>
                            <div class="service-box-item-content">
                                <h4>Education</h4>
                                <p>My education life
                                </p>
                                <a href="#" data-toggle="modal" data-target="#Education">Read More</a>
                            </div>
                        </div>
                        </div>
                        <!-- Education Area End -->

                        <!-- Experience Area Start -->
                        <div class="col-lg-6 col-md-6">
                        <div class="service-box-item">
                            <figure class="mb-0">
                                <img src="assets/image/service-icon2.png" alt="service-icon" class="img-fluid">
                            </figure>
                            <div class="service-box-item-content">
                                <h4>Professional Experience </h4>
                                <p>Information about my professional experience
                                </p>
                                <a href="#" data-toggle="modal" data-target="#Experience">Read More</a>
                            </div>
                        </div>
                        </div>
                        <!-- Experience Area End -->
                    </div>
                    <div class="row mb-0">
                        <!-- Course Area Start -->
                        <div class="col-lg-6 col-md-6">
                        <div class="service-box-item">
                            <figure class="mb-0">
                                <img src="assets/image/service-icon3.png" alt="service-icon" class="img-fluid">
                            </figure>
                            <div class="service-box-item-content">
                                <h4>Courses and Certificates</h4>
                                <p>Courses I have attended and certificates I have received
                                </p>
                                <a href="#" data-toggle="modal" data-target="#Course">Read More</a>
                            </div>
                        </div>
                        </div>
                        <!-- Course Area End -->

                        <!-- More information Area Start -->
                        <div class="col-lg-6 col-md-6">
                        <div class="service-box-item mb-0">
                            <figure class="mb-0">
                                <img src="assets/image/service-icon4.png" alt="service-icon" class="img-fluid">
                            </figure>
                            <div class="service-box-item-content">
                                <h4>More Information</h4>
                                <p>Hobbies , areas of interest ,personal characteristics 
                                </p>
                                <a href="#" data-toggle="modal" data-target="#Information">Read More</a>
                            </div>
                        </div>
                        </div>
                        <!-- More information Area End -->
                    </div>
                </div>
            </div>
            <EducationModal></EducationModal>
            <ExperienceModal></ExperienceModal>
            <CourseAndCertificateModal></CourseAndCertificateModal>
            <MoreInformationModal></MoreInformationModal>
        </div>
    </section>
    <!-- Main Body Start -->
</template>

<script>
import EducationModal from  "./ModalsComponents/EducationModal.vue"
import ExperienceModal from "./ModalsComponents/ExperienceModal.vue"
import CourseAndCertificateModal from "./ModalsComponents/CourseAndCertificateModal.vue"
import MoreInformationModal from "./ModalsComponents/MoreInformationModal.vue"
export default {
    name:'MainBody',
    components: {
    EducationModal,
    ExperienceModal,
    CourseAndCertificateModal,
    MoreInformationModal
}
}
</script>