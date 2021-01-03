<template>
  <div class="home">
    <HeaderShayna />
    <CarouselShayna />
    <BannerShayna />
    <InstagramShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue"
import CarouselShayna from "@/components/CarouselShayna.vue"
import BannerShayna from "@/components/BannerShayna.vue"
import InstagramShayna from "@/components/InstagramShayna.vue"
import PartnerShayna from "@/components/PartnerShayna.vue"
import FooterShayna from "@/components/FooterShayna.vue"

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    CarouselShayna,
    BannerShayna,
    InstagramShayna,
    PartnerShayna,
    FooterShayna,
  }
}
</script>
