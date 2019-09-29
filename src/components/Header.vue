<template>
  <header class="resume-header pt-4 pt-md-0">
    <div class="media flex-column flex-md-row">
      <img class="mr-3 img-fluid picture mx-auto" src="../assets/profile.png" alt="">
      <div class="media-body p-4 d-flex flex-column flex-md-row mx-auto mx-lg-0">
        <div class="primary-info">
          <h1 class="name mt-0 mb-1 text-white text-uppercase text-uppercase">Jardiel Sousa</h1>
          <div class="title mb-3">Desenvolvedor Backend</div>
          <ul class="list-unstyled">
            <li class="mb-2"><a href="#"><i class="far fa-envelope fa-fw mr-2" data-fa-transform="grow-3"></i>Jardiel.Sousa@gmail.com</a></li>
            <li><a href="#"><i class="fas fa-mobile-alt fa-fw mr-2" data-fa-transform="grow-6"></i>+55 86 9 9441.0241</a></li>
          </ul>
        </div><!--//primary-info-->
        <div class="secondary-info ml-md-auto mt-2">
          <ResumeSocial></ResumeSocial>
        </div><!--//secondary-info-->
        
      </div><!--//media-body-->
    </div><!--//media-->
  </header>
</template>

<script>
import ResumeSocial from "./ResumeSocial.vue";

export default {
  name: "headerTemplate",
  components: { ResumeSocial }
}
</script>

<style>

</style>