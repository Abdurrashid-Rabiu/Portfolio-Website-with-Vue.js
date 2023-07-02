<template>
  <div class="container-fluid bg-dark text-light p-5 text-center">
      <div class="container bg-dark p-5">
          <h1 class="display-4">Welcome To My Portfolio Website</h1>
          <hr class="my-4">
          <p class="lead">I am "Name"</p>
          <h2 class="display-5">Photographer</h2>
          <a class="btn btn-light btn-lg" href="\about" role="button">Learn more</a>
      </div>
  </div>
    

  <div class="container mt-5 mb-5">
      <h2>Recent Projects</h2>
      <div class="row">
          <p class="lead"></p>
          <div class="col-sm-12 col-md-6 col-lg-4 mt-2">
              <div class="card" style="width: 18rem;">
                  <img src="@/assets/conference.jpeg" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Conference</h5>
                    <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    <a href="#" class="btn btn-primary">Learn More</a>
                  </div>
              </div>
          </div>

          <div class="col-sm-12 col-md-6 col-lg-4 mt-2">
              <div class="card" style="width: 18rem;">
                  <img src="@/assets/girraffes-and-zebras.jpg" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Girraffes and Zebras</h5>
                    <p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
                    <a href="#" class="btn btn-primary">Learn More</a>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import "@/style.css";
</style>
