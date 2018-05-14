<template>
  <nav>
    <nuxt-link class="anchor" to="/">index</nuxt-link>
    <nuxt-link class="anchor" to="/about">about</nuxt-link>
    <nuxt-link class="anchor" to="/service">service</nuxt-link>
    <nuxt-link class="anchor" to="/contact">contact</nuxt-link>
  </nav>
</template>

<style lang="scss" scoped>
.anchor {
  margin-right: 20px;
  color: gray;
  &:visited {
    color: #41b883;
  }
}
</style>
