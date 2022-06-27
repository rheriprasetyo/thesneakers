<template>
  <div class="product">
    <HeaderSection />
 
         
      <!-- Breadcrumb Section Begin -->
    <div class="breacrumb-section text-start">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="breadcrumb-text product-more">
                        <router-link to="/"><i class="fa fa-home"></i> Home</router-link>
                        <span>Detail</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
 
    
    <div class="container mb-5">
        <div class="row">
            <div class="col text-left">
                <img class="img-fluid" :src="gambar_default" alt="">
                
                <!-- carousel start -->

        <div class="pt-5">
        <div class="container-lg pe-0 pl-0">

            <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
                
                <div class="container-lg pe-0 pl-0">


                    <div class="carousel-inner container-lg ml-0">
                
                        <div class="carousel-item active" data-bs-interval="10000">
                            <div class="row">
                                <div class="col">

                                    <div class="card" style="width: 10rem;" @click="changeImage(thumbs[0])" :class="thumbs[0] == gambar_default ? 'border border-warning' : 'border-0' ">
                                        <img src="img/retro-chunky-sneakers/retro-chunky-sneakers-1.jpg
                                        " class="card-img-top" alt="...">
                                    
                                    </div>

                                </div>

                                <div class="col">

                                    <div class="card" style="width: 10rem;" @click="changeImage(thumbs[1])" :class="thumbs[1] == gambar_default ? 'border border-warning' : 'border-0'">
                                        <img src="img/retro-chunky-sneakers/retro-chunky-sneakers-2.jpg" class="card-img-top" alt="...">
                                
                                    </div>

                                </div>
                                
                                <div class="col">

                                    <div class="card" style="width: 10rem;" @click="changeImage(thumbs[2])" :class="thumbs[2] == gambar_default ? 'border border-warning': 'border-0'">
                                        <img src="img/retro-chunky-sneakers/retro-chunky-sneakers-3.jpg" class="card-img-top" alt="...">
                                    
                                    </div>

                                </div>


                                
                        </div>
                        
                        </div>

                        <div class="carousel-item" data-bs-interval="10000">
                            <div class="row">
                                <div class="col">

                                    <div class="card" style="width: 10rem;" @click="changeImage(thumbs[3])" :class="thumbs[3] == gambar_default ? 'border border-warning' : 'border-0' ">
                                        <img src="img/retro-chunky-sneakers/retro-chunky-sneakers-4.jpg
                                        " class="card-img-top" alt="...">
                                    
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


                <!-- carousel end -->

            </div>
            <div class="col text-left">
                <p class="disable">MAN SHOES</p>
                <h3>Retro Chunky Sneakers</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aperiam possimus, laudantium aut asperiores dignissimos veniam perspiciatis. Corrupti dignissimos laborum fuga harum praesentium eligendi vitae fugit dolore voluptas dolores id non officia voluptatibus eaque quas modi dolorum ducimus quod beatae, vel officiis atque ex maiores. 
                </p>
                <p>
                    Odio quod neque, fugiat aliquam deleniti earum, quas commodi voluptate amet, assumenda aliquid quos quae sint beatae. Nisi alias expedita, modi tempore fuga maxime. Qui adipisci maiores omnis iste, explicabo amet numquam, velit recusandae libero consectetur eligendi atque corrupti sequi quia culpa ratione! Dolores error, ab, non dignissimos inventore libero voluptatum illum delectus eius, maiores nesciunt!
                </p>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas non optio libero officia? Illo, numquam quod? Cumque facere ut aliquid sapiente eum magni fugit, consectetur, veniam, quibusdam at soluta labore!
                </p>
                <h3 class="text-dark">
                    899.900 IDR
                </h3>
                <router-link to="/cart"> <button class="btn btn-lg btn-warning text-dark mt-3">ADD TO CART</button> </router-link>
            </div>
        </div>
    </div>

    <!-- Breadcrumb Section End -->

    <RelatedProductSection />

    <FooterSection />

  </div>
    

</template>

<script>

import HeaderSection from "@/components/HeaderSection.vue"
import FooterSection from "@/components/FooterSection.vue"
import RelatedProductSection from "@/components/RelatedProductSection.vue"




// import "@popperjs/core/dist/umd/popper.js";
// import "bootstrap/dist/css/bootstrap.min.css";
// import "bootstrap/dist/js/bootstrap.min.js";
// import * as Bootstrap from 'bootstrap';


export default{

  components: {
      HeaderSection,
      FooterSection,
      RelatedProductSection

 },

 data() {
    return {
        gambar_default: "img/retro-chunky-sneakers/retro-chunky-sneakers-1.jpg",
        thumbs: [
            "img/retro-chunky-sneakers/retro-chunky-sneakers-1.jpg",
            "img/retro-chunky-sneakers/retro-chunky-sneakers-2.jpg",
            "img/retro-chunky-sneakers/retro-chunky-sneakers-3.jpg",
            "img/retro-chunky-sneakers/retro-chunky-sneakers-4.jpg"
        ]
    }
 },

 methods: {
    changeImage(urlImage) {
        this.gambar_default = urlImage;
    }
 }



};

</script>
