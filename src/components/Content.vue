<template>
  <article class="resume-wrapper text-center position-relative">
    <div class="resume-wrapper-inner mx-auto text-left bg-white shadow-lg">
      <Header></Header>
      <ResumeBody></ResumeBody>
    </div>
  </article>
</template>

<script>
import Header from "./Header.vue";
import ResumeBody from "./ResumeBody.vue";

export default {
  name: "contentTemplate",
  components: { Header, ResumeBody }
}
</script>

<style>

</style>