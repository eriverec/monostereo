<template>
  <div>
    <div class="ini">
      <h1 data-aos="zoom-in">Acompáñanos en esta aventura</h1>
      <h2 data-aos="zoom-in-up" v-rellax="rellax">
        <b-icon icon="chevron-compact-down"></b-icon>
      </h2>
    </div>
  </div>
</template>

<style scoped>
.ini {
  text-align: center;
  color: white;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  -webkit-transform: translate(-50%, -50%);
  text-transform: uppercase;
}

</style>
<script>
export default {
  data() {
    return {
      rellax: {
        speed: -1,
      },
    };
  },
};
</script>

