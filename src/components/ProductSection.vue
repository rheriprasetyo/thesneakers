<template>

    <div class="pt-5">
        <div class="container-lg pe-0 pl-0">

            <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
                
                <div class="container-lg pe-0 pl-0">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
                        <!-- <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button> -->
                    </div>

                    <div class="carousel-inner container-lg ml-2">
                
                        <div class="carousel-item active" data-bs-interval="3000">
                        <div class="row">
                            <div class="col">

                                <div class="card border-0" style="width: 18rem;">
                                    <img src="img/retro-chunky-sneakers/retro-chunky-sneakers.jpg
                                    " class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <p class="text-black-50">MAN SHOES</p>
                                        <router-link :to="'/product'">
                                            <h5 class="card-title">Retro Chunky Sneakers</h5>
                                        </router-link>
                                        <p class="text-warning fs-5">899.900 IDR</p>
                                    </div>
                                </div>

                            </div>

                            <div class="col">

                                <div class="card border-0" style="width: 18rem;">
                                    <img src="img/rhuigi-running-sneakers/rhuigi-running-sneakers.jpg" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <p class="text-black-50">MAN SHOES</p>
                                        <h5 class="card-title">Rhuigi Running Sneakers</h5>
                                        <p class="text-warning fs-5">1.990.000 IDR</p>
                                    </div>
                                </div>

                            </div>
                            
                            <div class="col">

                                <div class="card border-0" style="width: 18rem;">
                                    <img src="img/running-spumefoam-sneakers/running-spumefoam-sneakers.jpg" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <p class="text-black-50">MAN SHOES</p>
                                        <h5 class="card-title">Running Spumefoam</h5>
                                        <p class="text-warning fs-5">1.990.000 IDR</p>
                                    </div>
                                </div>
                            </div>

                            <div class="col">

                                <div class="card border-0" style="width: 18rem;">
                                    <img src="img/contrasting-plimsolls-sneakers/contrasting-plimsolls-sneakers.jpg" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <p class="text-black-50">MAN SHOES`</p>
                                        <h5 class="card-title">Contrasting Plimsolls</h5>
                                        <p class="text-warning fs-5">599.900 IDR</p>
                                    </div>
                                </div>
                            </div>
                        
                            
                        </div>
                        
                        <!-- </div> 
                        <div class="carousel-item"> -->
                        
                        </div>

                        <div class="carousel-item" data-bs-interval="5000">
                        <div class="row">
                            <div class="col instagram-photo">
                                  
                                <div class="card border-0 insta-item set-bg mb-3" style="width: 19rem; height: 22.5rem;background-image: url('img/contrast-trek-sneakers/contrast-trek-sneakers.jpg')">

                                     <!-- <img src="img/contrast-trek-sneakers/contrast-trek-sneakers.jpg" class="card-img-top" alt="..."> -->
                                    <div class="card-body">
                                            <p class="text-black-50">MAN SHOES</p>
                                            <!-- <h5 class="card-title">Contrast Trek Sneakers</h5>
                                            <p class="fs-5 text-warning bg-light">1.199.900 IDR</p> -->
                                    </div>

                                    <div class="inside-text">

                                        <div class="btn-group" role="group" aria-label="Button group with nested dropdown">
                                        <button type="button" class="btn btn-warning">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" class="bi bi-cart-plus-fill" viewBox="0 0 16 16">
                                            <path d="M.5 1a.5.5 0 0 0 0 1h1.11l.401 1.607 1.498 7.985A.5.5 0 0 0 4 12h1a2 2 0 1 0 0 4 2 2 0 0 0 0-4h7a2 2 0 1 0 0 4 2 2 0 0 0 0-4h1a.5.5 0 0 0 .491-.408l1.5-8A.5.5 0 0 0 14.5 3H2.89l-.405-1.621A.5.5 0 0 0 2 1H.5zM6 14a1 1 0 1 1-2 0 1 1 0 0 1 2 0zm7 0a1 1 0 1 1-2 0 1 1 0 0 1 2 0zM9 5.5V7h1.5a.5.5 0 0 1 0 1H9v1.5a.5.5 0 0 1-1 0V8H6.5a.5.5 0 0 1 0-1H8V5.5a.5.5 0 0 1 1 0z"/>
                                            </svg>
                                        </button>
                                        <router-link to="/product">
                                            <button type="button" class="btn btn-warning fs-5">Quick View</button>
                                        </router-link>
                                        </div>

                                        
                                        
                                        

                                    </div>

                                </div>

                                <div class="card-body">
                                    <h5 class="card-title">Contrast Trek Sneakers</h5>
                                    <p class="fs-5 text-warning">1.199.900 IDR</p>
                                    
                                </div>
                                
                            </div>

                            <div class="col">
                                
                                <div class="card border-0" style="width: 18rem;">
                                    <img src="img/multi-piece-running/multi-piece-running-sneakers.jpg" class="card-img-top" alt="...">
                                    <!-- button start -->
                                    <!-- <div class="btn-group" role="group" aria-label="Basic example">
                                        <button type="button" class="btn btn-primary">Left</button>
                                        
                                        <button type="button" class="btn btn-primary">Right</button>
                                    </div> -->
                                    <!-- button end -->
                                    <div class="card-body">
                                        <p class="text-black-50">MAN SHOES</p>
                                        <h5 class="card-title">Multi Piece Running</h5>
                                        <p class="text-warning fs-5">990.900 IDR</p>
                                    </div>
                                </div>
                                
                            </div> 

                            <div class="col">
                                <div class="card border-0" style="width: 18rem;">
                                    <img src="img/knit-sneakers/knit-sneakers.jpg" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <p class="text-black-50">MAN SHOES</p>
                                        <h5 class="card-title">Knit Sneakers</h5>
                                        <p class="text-warning fs-5">599.900 IDR</p>
                                    </div>
                                </div>
                            </div>
                            <div class="col">
                                <div class="card border-0" style="width: 18rem;">
                                    <img src="img/multi-piece-running/multi-piece-running-sneakers.jpg" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <p class="text-black-50">MAN SHOES</p>
                                        <h5 class="card-title">Multi Piece Running</h5>
                                        <p class="text-warning fs-5">990.900 IDR</p>
                                    </div>
                                </div>
                            </div>
                            
                        </div>
                        
                        </div>
                
                    </div>

                </div>

                <!-- Panah Kanan kiri -->
                <button class="carousel-control-prev align-middle" style="width: 2%;" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next justify-content-end" style="width: 2%;" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>
        
        </div>
    </div>

</template>

<script>





  export default {
     name: "ProductSection"

  }

</script>

<style scoped>


</style>