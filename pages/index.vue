<template>
  <div>
    <NavigationBar />
    <div class="container">
      stuff
    </div>
  </div>
</template>

<script>
import NavigationBar from '../components/TheNavigationBar'
export default {
  components: {
    NavigationBar
  }
}
</script>

<style lang="scss" scoped>
.container {
  margin: 0 auto;
  padding: 0 1rem;
  min-height: 95vh;
  max-width: 1080px;
}
</style>
