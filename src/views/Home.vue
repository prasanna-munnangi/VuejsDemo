<template>
  <div>
    <HomeHero />
    <HomeDetails />
    <HomePlans />
  </div>
</template>

<script>
import HomeHero from '../components/HomeHero'
import HomeDetails from '../components/HomeDetails'
import HomePlans from '../components/HomePlans'

export default {
  name: 'home',
  components: {
    HomeHero,
    HomeDetails,
    HomePlans
  }
}
</script>
