<template>
  <footer class="app-footer">
    &copy; {{year}} TSUCHI
  </footer>
</template>

<script>
import getYear from '~/assets/js/get-year'

export default {
  data () {
    return {
      year: getYear()
    }
  }
}
</script>

<style lang="scss" scoped>
.app-footer {
  color: gray;
}
</style>
