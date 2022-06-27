<template>
  <div class="home">

    <HeaderSection />

    <HeroSection />

    <ProductSection />

    <InstaSection />

    <PartnerSection />

    <FooterSection />
    
  </div>
</template>

<script>
// @ is an alias to /src

import HeaderSection from '@/components/HeaderSection.vue'
import HeroSection from '@/components/HeroSection.vue'
import ProductSection from '@/components/ProductSection.vue'
import InstaSection from '@/components/InstaSection.vue'
import PartnerSection from '@/components/PartnerSection.vue'
import FooterSection from '@/components/FooterSection.vue'




export default {
  name: 'HomeView',
  components: {
    
    HeaderSection,
    HeroSection,
    ProductSection,
    InstaSection,
    PartnerSection,
    FooterSection
  }
}
</script>
