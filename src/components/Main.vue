<template>
  <main>
    <Welcome />
    <Doctors />
  </main>
</template>

<script>
import Welcome from './Welcome-section.vue'
import Doctors from './Doctors-section.vue'

export default {
    name: 'Main',
    components : {
      Welcome,
      Doctors
    }
}
</script>

<style lang="scss" scoped>

</style>