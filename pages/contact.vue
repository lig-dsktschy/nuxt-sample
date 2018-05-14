<template>
  <main @click="changeTitle">
    PAGE: {{pageTitle}}
  </main>
</template>

<script>
export default {
  head () {
    return {
      title: 'CONTACT | nuxt-sample',
      meta: [
        { hid: 'description', name: 'description', content: 'This is contact page' },
        { hid: 'keyword', name: 'keyword', content: 'contact,ask,question,form' },
        { hid: 'og:title', property: 'og:title', content: 'CONTACT | nuxt-sample' }
      ]
    }
  },
  data () {
    return {
      pageTitle: 'CONTACT'
    }
  },
  methods: {
    changeTitle () {
      this.pageTitle = (this.pageTitle === 'CONTACT') ? 'contact' : 'CONTACT'
    }
  }
}
</script>
