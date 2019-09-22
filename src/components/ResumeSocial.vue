<template>
  <ul class="resume-social list-unstyled">
    <ItemResumeSocial icon="linkedin-in" link="linkedin.com/in/jardielsousa"></ItemResumeSocial>
    <ItemResumeSocial icon="github-alt" link="github.com/jardielsousa"></ItemResumeSocial>
    <ItemResumeSocial icon="gitlab" link="gitlab.com/jardielsousa"></ItemResumeSocial>
    <li>
      <a href="https://twitter.com/jar_sousa" target="blank">
        <span class="fa-container text-center mr-2">
          <i class="fab fa-twitter"></i>
        </span>twitter.com/jar_sousa
      </a>
    </li>
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