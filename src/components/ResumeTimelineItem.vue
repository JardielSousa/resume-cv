<template>
  <article class="resume-timeline-item position-relative">
          
    <div class="resume-timeline-item-header mb-2">
      <div class="d-flex flex-column flex-md-row">
        <h3 class="resume-position-title font-weight-bold mb-1">{{ positionTitle }}</h3>
        <div class="resume-company-name ml-auto">{{ companyName }}</div>
      </div><!--//row-->
      <div class="resume-position-time">{{ positionTime }}</div>
    </div><!--//resume-timeline-item-header-->
    <div class="resume-timeline-item-desc">
      <p><slot></slot></p>
      <h4 v-if="technologiesUsed.length > 0" class="resume-timeline-item-desc-heading font-weight-bold">Tecnologias usadas:</h4>
      <ul v-if="technologiesUsed.length > 0" class="list-inline">
        <li class="list-inline-item" v-for="t in technologiesUsed" :key="t">
          <span class="badge badge-primary badge-pill">{{ t }}</span>
        </li>
      </ul>
    </div><!--//resume-timeline-item-desc-->

  </article><!--//resume-timeline-item-->
</template>

<script>
export default {
  name: "resumeTimelineItem",
  props: [
    "position-title",
    "company-name",
    "position-time",
    "technologies-used"
  ]
}
</script>

<style>

</style>