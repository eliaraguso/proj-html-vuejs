<template>
  <main>
    <Welcome />
    <Doctors />
    <Services />
    <Facilities />
    <Learn />
    <Appointment />
    <Carousel />
  </main>
</template>

<script>
import Welcome from './Welcome-section.vue';
import Doctors from './Doctors-section.vue';
import Services from './Services-section.vue';
import Facilities from './Facilities-section.vue';
import Learn from './LearnMore-section.vue';
import Appointment from './Appointment-section.vue';
import Carousel from './Carousel-section.vue';


export default {
    name: 'Main',
    components : {
      Welcome,
      Doctors,
      Services,
      Facilities,
      Learn,
      Appointment,
      Carousel,
    }
}
</script>

<style lang="scss" scoped>

</style>