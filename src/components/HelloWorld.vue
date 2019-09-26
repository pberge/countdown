<template>
  <div class="counter">
    <Countdown deadline="October 3, 2019"/>
  </div>
</template>

<script>
import Countdown from 'vuejs-countdown'

export default {
  name: 'HelloWorld',
  components: {
    Countdown
  }
}
</script>

<style scoped>
</style>
