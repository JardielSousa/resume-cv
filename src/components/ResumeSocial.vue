<template>
  <ul class="resume-social list-unstyled">
    <ItemResumeSocial class="mb-3" icon="linkedin-in" link="linkedin.com/in/jardielsousa"></ItemResumeSocial>
    <ItemResumeSocial class="mb-3" icon="github-alt" link="github.com/jardielsousa"></ItemResumeSocial>
    <ItemResumeSocial class="mb-3" icon="gitlab" link="gitlab.com/jardielsousa"></ItemResumeSocial>
    <ItemResumeSocial icon="twitter" link="twitter.com/jar_sousa"></ItemResumeSocial>
  </ul>
</template>

<script>
import ItemResumeSocial from "./ItemResumeSocial.vue";

export default {
  name: "resumeSocial",
  components: { ItemResumeSocial }
};
</script>

<style>
</style>