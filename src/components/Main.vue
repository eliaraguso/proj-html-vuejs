<template>
  <main>
    <Welcome />
    <Doctors />
    <Services />
    <Facilities />

  </main>
</template>

<script>
import Welcome from './Welcome-section.vue';
import Doctors from './Doctors-section.vue';
import Services from './Services-section.vue';
import Facilities from './Facilities-section.vue';



export default {
    name: 'Main',
    components : {
      Welcome,
      Doctors,
      Services,
      Facilities,
    }
}
</script>

<style lang="scss" scoped>

</style>