<template>
  <main class="page-about">
    PAGE: ABOUT
  </main>
</template>

<script>
export default {
  data () {
    return {
      elRoot: null
    }
  },
  methods: {
    sayHello () {
      alert('hello')
    }
  },
  mounted () {
    this.elRoot = document.querySelectorAll('.page-about')[0]
    this.elRoot.addEventListener('click', this.sayHello)
  },
  beforeDestroy () {
    this.elRoot.removeEventListener('click', this.sayHello)
  }
}
</script>
