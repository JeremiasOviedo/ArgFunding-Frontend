<script>
import LandingPageBanner from './components/LandingPageBanner.vue'
import LandingPageCards from './components/LandingPageCards.vue'
import LandingPageInfo from './components/LandingPageInfo.vue'

export default{
  Name:"App",
  components: {
    LandingPageCards,
    LandingPageBanner,
    LandingPageInfo
  }
}

</script>

<template>
  <main>
    <LandingPageBanner/>
    <LandingPageCards/>
    <LandingPageInfo/>
  </main>
</template>




