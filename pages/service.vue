<template>
  <main @click="sayHello">
    PAGE: SERVICE
  </main>
</template>

<script>
export default {
  methods: {
    sayHello () {
      alert('hello')
    }
  }
}
</script>

