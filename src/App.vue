<template>
 <!-- <nav>
    <router-link to="/">Home</router-link> |
    <button @click="goAbout">About</button>
  </nav>
  <router-view/> -->
 <div class="container-fluid pb-5 mb-5 mb-sm-0 pb-sm-0 d-sm-flex align-items-sm-center">
  <button class="d-none d-sm-flex fixed-left"><img src="./assets/back.png" alt="" srcset=""></button>
  <div class="col-sm-5">

  <h1 class="p-2 titulo">Zapatero</h1>
  <hr />
  <p class="text-start py-2 px-sm-5 parrafo">
   Zapatero Remendón era el maestro que reparaba todo tipo de calzado y que, en
   cada Barrio, permitía que el calzado tuviera más larga vida, sobretodo cuando
   el “par” de zapatos eran para ir al colegio y para la misa dominguera (claro
   que debidamente lustrados).
  </p>
   </div>
  <!-- Carousel de Imagenes -->
  <div
   id="carouselExampleSlidesOnly"
   class="carousel slide col-sm-7 mt-sm-5"
   data-bs-ride="carousel"
  >
   <div class="carousel-inner">
    <div class="carousel-item active">
     <img src="https://backendmuseopichilemu.com/wp-content/uploads/2022/05/Zapatero-Remendon-Web.jpg" class="img-fluid" alt="..." />
    </div>
    <div class="carousel-item">
     <img src="https://backendmuseopichilemu.com/wp-content/uploads/2022/05/Tanume-Web-1024x798.jpg" class="img-fluid" alt="..." />
    </div>
    <div class="carousel-item">
     <img src="https://backendmuseopichilemu.com/wp-content/uploads/2022/05/Zapatero-Remendon-Web.jpg" class="img-fluid" alt="..." />
    </div>
   </div>
  </div>
  <button class="fixed-left mt-3"><img src="./assets/back.png" alt="" srcset=""></button>

  <footer
    class="container-fluid footer fixed-bottom text-center d-flex justify-content-center"
  >
    <div class="col-11 d-flex">
      <p class="fs-6">
        Una produccion de
        <a
          class="footer__link fs-6"
          href="http://www.pichilemunews.cl/"
          target="_blank"
          >www.pichilemunews.cl</a
        >
      </p>
    </div>
  </footer>
 </div>
</template>
<script>
// import axios from "axios";
export default {
 // methods:{
 //   goAbout: function () {
 //     this.$router.push('/about');
 //     console.log('holi')
 //   }
 // }
 data() {
  return {
   data: [],
  };
 },
 // mounted() {
 //   axios
 //     .get('https://backendmuseopichilemu.com/index.php/wp-json/wp/v2/posts/122')
 //     .then((data) => (this.data = data))
 // }
};
</script>

<style>
#app {
 font-family: 'Old Standard TT', serif;
 -webkit-font-smoothing: antialiased;
 -moz-osx-font-smoothing: grayscale;
 text-align: center;
 color: #2c3e50;
}

nav {
 padding: 30px;
}

nav a {
 font-weight: bold;
 color: #2c3e50;
}

nav a.router-link-exact-active {
 color: #42b983;
}
.carousel-item img {
  max-height: 600px;
}
.titulo {
  font-size: 38px;
}
.parrafo {
  font-size: 18px;
}
.footer {
  font-family: "Old Standard TT", serif;
  text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.1);
  background-image: url(https://images.unsplash.com/photo-1615800098779-1be32e60cca3?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2020&q=80);
}
.footer div {
  border-top: 1.5px solid #1d1d1d;
  justify-content: center;
  align-items: center;
  padding: 0.5rem;
}
.footer p {
  margin-bottom: 0;
}
.footer a {
  text-decoration: none;
  font-family: "Roboto mono", sans-serif;
  font-style: italic;
}
</style>
