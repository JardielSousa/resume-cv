<template>
  <div class="resume-body p-5">
    <SummarySection></SummarySection>
    <div class="row">
      <div class="col-lg-9">
        <ExperienceSection></ExperienceSection>
      </div>
      <div class="col-lg-3">
        
        <SkillsSection></SkillsSection>

        <EducationSection></EducationSection>

        <ReferenceSection></ReferenceSection>

        <LanguageSection></LanguageSection>
        
        <InterestsSection></InterestsSection>
        
      </div>
    </div><!--//row-->
  </div><!--//resume-body-->
</template>

<script>
import SummarySection from "./SummarySection.vue";
import ExperienceSection from "./ExperienceSection.vue";
import SkillsSection from "./SkillsSection.vue";
import EducationSection from "./EducationSection.vue";
import ReferenceSection from "./ReferenceSection.vue";
import LanguageSection from "./LanguageSection.vue";
import InterestsSection from "./InterestsSection.vue";

export default {
  name: "resumeBody",
  components: {
    SummarySection,
    ExperienceSection,
    SkillsSection,
    EducationSection,
    ReferenceSection,
    LanguageSection,
    InterestsSection
  }
}
</script>

<style>

</style>