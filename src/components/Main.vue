<template>
  <main>
    <Welcome />
    <Doctors />
    <Services />
    <Facilities />
    <Learn />

  </main>
</template>

<script>
import Welcome from './Welcome-section.vue';
import Doctors from './Doctors-section.vue';
import Services from './Services-section.vue';
import Facilities from './Facilities-section.vue';
import Learn from './LearnMore-section.vue'



export default {
    name: 'Main',
    components : {
      Welcome,
      Doctors,
      Services,
      Facilities,
      Learn,
    }
}
</script>

<style lang="scss" scoped>

</style>