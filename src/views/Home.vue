<template>
  <div class="home">
    <HeaderEdiots />
    <CarouselEdiots />
    <BrandEdiots />
    <FeatureEdiots />
    <DesignerEdiots />
    <FooterEdiots />
  </div>
</template>

<script>
  // @ is an alias to /src
  import HeaderEdiots from '@/components/HeaderEdiots.vue';
  import CarouselEdiots from '@/components/CarouselEdiots.vue';
  import BrandEdiots from '@/components/BrandEdiots.vue';
  import FeatureEdiots from '@/components/FeatureEdiots.vue';
  import DesignerEdiots from '@/components/DesignerEdiots.vue';
  import FooterEdiots from '@/components/FooterEdiots.vue';

  export default {
    name: 'Home',
    components: {
      HeaderEdiots,
      CarouselEdiots,
      BrandEdiots,
      FeatureEdiots,
      DesignerEdiots,
      FooterEdiots,
    },
  };
</script>
