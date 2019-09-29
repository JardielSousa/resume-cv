<template>
   <li class="mb-2">
    <div class="resume-skill-name">{{ name }}</div>
    <div class="progress resume-progress">
      <div class="progress-bar theme-progress-bar-dark" role="progressbar" :style="`width: ${progressValue}%`" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100"></div>
    </div>
  </li>
</template>

<script>
export default {
  name: "resumeSkillName",
  props: [ "name", "progress-value" ]
}
</script>

<style>

</style>