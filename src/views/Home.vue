<template>
  <div class="home">
    <HeaderShayna/>
    <HeroSectionCarousel/>
    <BannerSection/>
    <InstaGalleries/>
    <PartnerLogo/>
    <FooterShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroSectionCarousel from '@/components/HeroSectionCarousel.vue'
import BannerSection from '@/components/BannerSection.vue'
import InstaGalleries from '@/components/InstaGalleries.vue'
import PartnerLogo from '@/components/PartnerLogo.vue'
import FooterShayna from '@/components/FooterShayna.vue'
 
export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroSectionCarousel,
    BannerSection ,
    InstaGalleries,
    PartnerLogo,
    FooterShayna
  }
}
</script>
