<script setup>
  import ArrivalsOriginal from '@/components/arrivals-original.component.vue';
  import Banner from '@/components/banner.component.vue';
  import OurCollection from '@/components/collection.component.vue';
  import Customize from '@/components/customize-tool.component.vue';
  import Deals from '@/components/deals.component.vue';
  import FooterEnd from '@/components/footer-end.component.vue';
  import Navigation from '@/components/navigation.component.vue';
  import NewProduct from '@/components/new-product.component.vue';
  import NewsLetter from '@/components/news-letter.component.vue';
  import Quotation from '@/components/quotation.component.vue';
  import SubBanner from '@/components/sub-banner.component.vue';
  import SubFooter from '@/components/sub-footer.component.vue';
  import SubNavigation from '@/components/sub-navigation.component.vue';
  import SubProduct from '@/components/sub-product.component.vue';
  import weeklyMarketplace from '@/components/weekly-marketplace.vue';
</script>

<template>
  <div class="container">
    <header>
      <Navigation />
      <SubNavigation />
    </header>
    <main class="main-section">
      <Banner />
      <OurCollection />
      <Deals />
      <ArrivalsOriginal />
      <NewProduct />
      <SubBanner />
      <SubProduct />
      <Quotation />
      <weeklyMarketplace />
      <Customize />
      <NewsLetter />
    </main>

    <footer>
      <SubFooter />
      <FooterEnd />
    </footer>
  </div>
</template>

<style lang="scss" scoped>
  .container {
    width: 100%;
    background-color: $color-bg-secondary;
  }

  .main-section {
    display: flex;
    flex-direction: column;
    gap: 2rem;
    margin: 0 20rem 10rem;
  }
</style>
