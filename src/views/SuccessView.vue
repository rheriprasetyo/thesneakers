<template>
    <div class="container">

    <div class="d-flex success-checkout align-items-center justify-content-center">
        <div class="col col-lg-4 text-center">
            <img src="img/success-buy.png" alt="" width="294">
            <h3 class="mt-4">
                Sukses Terbayar!
            </h3>
            <p class="mt-2">
                Silakan tunggu update terbaru dari kami via email yang sudah Anda daftarkan sebelumnya.
            </p>
            <div class="col d-flex align-items-center justify-content-center">
                <router-link to="/"> <a href="" class="primary-btn pd-cart mt-3 list-group-item bg-warning text-dark` text-center w-70 ps-3 pe-3">Back to Home</a> </router-link>
            </div>
        </div>
    </div>

    </div>
</template>

<script>
export default {
    name: "SuccessView",

}
</script>

<style scoped>
    a {
        text-decoration: none;
    }
</style>