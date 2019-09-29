<template>
  <section class="resume-section skills-section mb-5">
    <h2 class="resume-section-title text-uppercase font-weight-bold pb-3 mb-3">Competências & Ferramentas</h2>
    <div class="resume-section-content">
        <div class="resume-skill-item">
          <h4 class="resume-skills-cat font-weight-bold">Frontend</h4>
          <ul class="list-unstyled mb-4">

            <ResumeSkillName name="jQuery" progress-value="85"></ResumeSkillName>
            <ResumeSkillName name="Javascript" progress-value="70"></ResumeSkillName>
            <ResumeSkillName name="Vue js" progress-value="45"></ResumeSkillName>
            <ResumeSkillName name="HTML/CSS" progress-value="90"></ResumeSkillName>

          </ul>
        </div><!--//resume-skill-item-->
        
        <div class="resume-skill-item">
            <h4 class="resume-skills-cat font-weight-bold">Backend</h4>
          <ul class="list-unstyled">
            <ResumeSkillName name="Java" progress-value="85"></ResumeSkillName>
            <ResumeSkillName name="Spring" progress-value="70"></ResumeSkillName>
            <ResumeSkillName name="Ruby on Rails" progress-value="35"></ResumeSkillName>
            
          </ul>
        </div><!--//resume-skill-item-->
        
        <div class="resume-skill-item">
            <h4 class="resume-skills-cat font-weight-bold">Others</h4>
            <ul class="list-inline">
              <li class="list-inline-item"><span class="badge badge-light">DevOps</span></li>
              <li class="list-inline-item"><span class="badge badge-light">Code Review</span></li>
              <li class="list-inline-item"><span class="badge badge-light">Git</span></li>
              <li class="list-inline-item"><span class="badge badge-light">Unit Testing</span></li>
              <li class="list-inline-item"><span class="badge badge-light">SQL</span></li>
              <li class="list-inline-item"><span class="badge badge-light">Api Rest</span></li>
              <li class="list-inline-item"><span class="badge badge-light">Json API</span></li>
              <li class="list-inline-item"><span class="badge badge-light">JWT</span></li>
              <li class="list-inline-item"><span class="badge badge-light">JMS</span></li>
            </ul>
        </div><!--//resume-skill-item-->
    </div><!--resume-section-content-->
  </section><!--//skills-section-->
</template>

<script>
import ResumeSkillName from "./ResumeSkillName.vue";

export default {
  name: "skillsSection",
  components: { ResumeSkillName }
}
</script>

<style>

</style>