<template>
    
    <!-- Carousel start -->
    <div class="container-lg hero-section">
    
        <div id="myCarousel" class="carousel carousel-dark slide" data-bs-ride="carousel">

            <!-- <div class="carousel-indicators">
                <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="0" class="active" aria-label="Slide 1" aria-current="true"></button>
                <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="1" aria-label="Slide 2" class=""></button>
                <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="2" aria-label="Slide 3" class=""></button>
            </div> -->
            
            
              <div class="carousel-inner">

                  <div class="carousel-item active">
            
                      <img class="img-fluid" src="img/hero-3.jpg" alt="">

                      <div class="container">
                          <div class="carousel-caption text-end text-dark">
                              <h1>Example headline.</h1>
                              <p>Some representative placeholder content for the first slide of the carousel.</p>
                              <p><a class="btn btn-lg btn-warning text-dark" href="#">Shop now</a></p>
                          </div>
                    </div>

                  </div>

                  <div class="carousel-item">
              
                      <img class="img-fluid" src="img/hero-4.jpg" alt="">

                      <div class="container">
                        <div class="carousel-caption text-end text-dark">
                          <h1>Another example headline.</h1>
                          <p>Some representative placeholder content for the second slide of the carousel.</p>
                          <p><a class="btn btn-lg btn-warning text-dark" href="#">Shop now</a></p>
                        </div>
                      </div>
                  </div>

                  <div class="carousel-item">
              
                      <img class="img-fluid" src="img/hero-2.jpg" alt="">

                      <div class="container">
                        <div class="carousel-caption text-center text-white">
                          <h1>One more for good measure.</h1>
                          <p>Some representative placeholder content for the third slide of this carousel.</p>
                          <p><a class="btn btn-lg btn-warning text-dark" href="#">Shop now</a></p>
                        </div>
                      </div>
                  </div>
                  

              </div>
            

            <!-- panan kanan kiri -->
              <button class="carousel-control-prev flex-column align-items-start" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button class="carousel-control-next flex-column align-items-end" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </button>
            
             
        </div>

    </div>
    <!-- Carousel end -->

</template>

<script>
export default {
    name : "HeroSection"
}
</script>