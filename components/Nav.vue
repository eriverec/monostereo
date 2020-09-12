<template>
  <div>
    <b-navbar toggleable="lg" type="dark">
      <b-navbar-brand href="#" data-aos="zoom-in-right" v-rellax="rellax">
        <strong>MONOSTEREO</strong>
      </b-navbar-brand>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto"></b-navbar-nav>
      <a href="#">
        <b-img src="../static/instagram.png" alt="Circle image"></b-img>
      </a>
    </b-navbar>
  </div>
</template>

<style scoped>
img {
  width: 20px;
}
</style>
<script>
export default {
  data() {
    return {
      rellax: {
        speed: 5,
        vertical: true,
      },
    };
  },
};
</script>
