<template>
  <main>
    <Welcome />
    <Doctors />
    <Services />

  </main>
</template>

<script>
import Welcome from './Welcome-section.vue';
import Doctors from './Doctors-section.vue';
import Services from './Services-section.vue'


export default {
    name: 'Main',
    components : {
      Welcome,
      Doctors,
      Services,
    }
}
</script>

<style lang="scss" scoped>

</style>