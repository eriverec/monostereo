<template>
  <footer >    

      <main>
    <h3>Listo para esta aventura?</h3>
    <div class="redes">
      <b-button variant="primary"><img src="~/static/itu.png"> iTunes</b-button>
      <b-button variant="success"><img src="~/static/spo.png"> Spotify</b-button>
      <b-button variant="danger"><img src="~/static/you.png"> Youtube</b-button>

    </div>
  </main>
     <p>M O N O S T E R E O</p>
    <small> © Copyright, <a href="https://github.com/eriverec">Eri Vera</a>.</small>
  </footer>


</template>


<style scoped>  

img{
  width: 20px;
}
.btn{
     margin: 10px;
}



main {
  border-bottom: 1px solid rgba(0, 0, 0, 0.2);
  padding: 10vh 0 14vh;
  position: relative;
  text-align: center;
  overflow: hidden;
}


footer {
  background: #dddee1;
  padding: 5vh 0;
  text-align: center;
  position: relative;
  background-image: linear-gradient(to top, #fbc2eb 0%, #a6c1ee 100%);
}

small {
  opacity: 0.5;
  font-weight: 300;
}
small a {
  color: inherit;
}

p{
  margin-top: 1rem;
}

</style>

