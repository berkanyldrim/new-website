<template>
    <div id="Experience" class="modal fade" tabindex="-1" style="display: none;" aria-hidden="true">
         <div class="modal-dialog">
            <div class="modal-content">
               <div class="modal-header">
                  <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true" ><i class="far fa-times"></i></span></button>
               </div>
               <div class="modal-body service-model-content">
                  
                  <h2>Professional Experience</h2>
                  
                  <ul class="list-unstyled model-list mb-md-3 mb-2">
                     <li><i class="fas fa-laptop"></i>Jr. Frontend Developer at Albert  Software and Consulting services (Remote),
                        <ul class="chield-lu" > November 2021 - Present
                           <li class="chield-li">Supported both the web design and interface in the frontend, and the web projects, Converted design to code using technologies such as HTML, CSS, JavaScript, and Bootstrap.</li>
                        </ul>
                     
                     </li>
                     
                     <li><i class="fas fa-laptop"></i>Intern at NFS SOFT, Erzurum-Turkey
                        <ul class="chield-lu">Software Internship (3 Months) - 2020
                           <li class="chield-li">2 Website Projects</li>
                           <li class="chield-li">Converted design to code using technologies such as HTML, CSS,
                           JavaScript, and Bootstrap,designed a project using wordpress, Supported
                           both the web design and interface in the frontend</li>
                        </ul>
                     </li>

                     <li><i class="fas fa-laptop"></i> Intern at Kanmaz Information Technologies, Istanbul - Turkey
                        
                        <ul class="chield-lu">Hardware internship (1 month) - 2020
                           
                           <li class="chield-li">Working on computer components</li>
                           <li class="chield-li">Technical computer parts and information about</li>
                        </ul>
                        
                     </li>
                  </ul>
                  
               </div>
            </div>
         </div>
    </div>

</template>

<script>
export default {
    name:"ExperienceModal"
}
</script>

<style>
.chield-li{
   font-weight: 400 !important; 
}
.chield-lu{
   font-weight: 500 !important;
   margin-left: 10px;
}
</style>