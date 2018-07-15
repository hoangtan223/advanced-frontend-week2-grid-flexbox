<template>
  <div class='container'>
    <div class="column">
      <div class="time">
        <span>7:30 am</span>
        <span>Tue 23rd Feb</span>
      </div>
      <div></div>
      <div class="location">
        <span class="country">- Sweden</span>
        <span class="city">Stockholm</span>
      </div>
    </div>
    <div class="column">
      <img src="../assets/Weather.svg" alt="weather logo">
    </div>
    <div class="column">
      <span class="degree">-7</span>
      <div class="description">
        <span>Clear</span>
        <span>with periodic</span>
        <span>cloud</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Weather',
  data () {
    return {}
  }
}
</script>

<style>

</style>
