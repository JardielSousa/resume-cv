<template>
  <li>
    <a :href="`https://${link}`" target="blank">
      <span class="fa-container text-center mr-2">
        <i :class="['fab', `fa-${ icon }`, 'fa-fw']"></i>
      </span>{{ link }}
    </a>
  </li>
</template>

<script>
export default {
  name: "itemResumeSocial",
  props: ["icon", "link"]
};
</script>

<style>
</style>