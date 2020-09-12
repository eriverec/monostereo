<template>
  <div class="artistas">
    <h3 data-aos="fade">ARTÍSTAS</h3>
    <b-container fluid data-aos="fade">
      <b-row>
        <b-col>
          <b-img rounded="circle" thumbnail fluid src="https://picsum.photos/250/250/?image=54" alt="Image 1"></b-img>
        </b-col>
        <b-col>
          <b-img rounded="circle" thumbnail fluid src="https://picsum.photos/250/250/?image=58" alt="Image 2"></b-img>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<style scoped>
.artistas{
  text-align: center;
  color: white;
  background: blueviolet;
  padding: 30px;
  background-image: url('../static/calle.jpg');
  background-attachment: fixed;
  background-position: center center;
    background-size: cover;
}
h3{
  padding-bottom: 5%;
}
</style>


