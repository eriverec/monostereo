<template>
  <div class="videos">
    <h3 data-aos="fade">ÚLTIMO VIDEO</h3>
    <div  data-aos="fade">
      <a href="https://youtu.be/_iwUI38BZGY" target=_blank>
      <b-img src="~/static/lanochemas.jpg" fluid alt="Responsive image"></b-img>
      </a>
    </div>
  </div>
</template>

<style scoped>
.videos {
  
  text-align: center;
  color: white;
  background: blueviolet;
  padding: 30px;
  background-image: url('../static/mesa1.jpg');
  background-attachment: fixed;
  background-position: center center;
    background-size: cover;
}
h3{
  padding-bottom: 5%;
}



</style>

<script>
export default {
  data() {
    return {
      rellax: {
        speed: 3,
      },
    };
  },
};
</script>


