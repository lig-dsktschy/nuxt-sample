<template>
  <div>
    <app-header/>
    <app-nav/>
    <nuxt/>
    <app-footer/>
  </div>
</template>

<script>
import AppHeader from '~/components/app-header'
import AppNav from '~/components/app-nav'
import AppFooter from '~/components/app-footer'

export default {
  components: {
    AppHeader,
    AppNav,
    AppFooter
  }
}
</script>

