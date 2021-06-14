<template>
  <div id="carouselPrincipal" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button
        type="button"
        data-bs-target="#carouselPrincipal"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselPrincipal"
        data-bs-slide-to="1"
        aria-label="Slide 2"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselPrincipal"
        data-bs-slide-to="2"
        aria-label="Slide 3"
      ></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <!-- <img
          src="https://images.unsplash.com/photo-1594759845217-e9c99af2b6a4?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8Y2xvdGhlJTIwbWFufGVufDB8fDB8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60"
          class="bd-placeholder-img"
          width="100%"
          height="100%"
          aria-hidden="true"
          preserveAspectRatio="xMidYMid slice"
          focusable="false"
          fill="#777"
          alt=""
        /> -->
        <img 
        src="../assets/img/jens-lindner-dP6g1YJWQcA-unsplash.jpg"
            class="bd-placeholder-img"
          width="100%"
          height="100%"
          aria-hidden="true"
          preserveAspectRatio="xMidYMid slice"
          focusable="false"
          fill="#777"
          alt=""
        
        />
        <div class="container">
          <div class="carousel-caption text-start">
            <h1>Las mejores ropas para cabaleleros.</h1>
            <p>
              Some representative placeholder content for the first slide of the
              carousel.
            </p>
            <p><a class="btn btn-lg btn-primary" href="#">Sign up today</a></p>
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="https://www.65ymas.com/uploads/s1/18/10/38/a-1.jpeg"
          alt=""
          class="bd-placeholder-img"
          width="100%"
          height="100%"
          aria-hidden="true"
          preserveAspectRatio="xMidYMid slice"
          focusable="false"
          fill="#777"
        />

        <div class="container">
          <div class="carousel-caption">
            <h1>Another example headline.</h1>
            <p>
              Some representative placeholder content for the second slide of
              the carousel.
            </p>
            <p><a class="btn btn-lg btn-primary" href="#">Learn more</a></p>
          </div>
        </div>
      </div>
      <div class="carousel-item">
        <img
          src="https://cdn.aarp.net/content/dam/aarp/entertainment/beauty-and-style/2019/04/1140-guys-cothes-too-big-esp.imgcache.rev.web.900.513.jpg"
          alt=""
          class="bd-placeholder-img"
          width="100%"
          height="100%"
          aria-hidden="true"
          preserveAspectRatio="xMidYMid slice"
          focusable="false"
          fill="#777"
        />
        <div class="container">
          <div class="carousel-caption text-end">
            <h1>Las mejores trajes & sastrerias.</h1>
            <p>
              Some representative placeholder content for the third slide of
              this carousel.
            </p>
            <p><a class="btn btn-lg btn-primary" href="#">Browse gallery</a></p>
          </div>
        </div>
      </div>
    </div>
    <button
      class="carousel-control-prev"
      type="button"
      data-bs-target="#carouselPrincipal"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next"
      type="button"
      data-bs-target="#carouselPrincipal"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>

<script>
export default {
  name: "Slider",
};
</script>

<style scoped>
.carousel {
  margin-bottom: 4rem;
}
.carousel-caption {
  bottom: 3rem;
  z-index: 10;
}

.carousel-item {
  height: 32rem;
}
.carousel-item > img {
  position: absolute;
  top: 0;
  left: 0;
  min-width: 100%;
  height: 32rem;
}
</style>