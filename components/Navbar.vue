<template>
  <b-navbar toggleable="lg" type="dark" variant="light">
    <b-icon icon="grid3x3-gap-fill" style="width: 60px; height: 50px; padding-right: 20px;"></b-icon>
    <b-navbar-brand nuxt-link to="/" style="color: black;">サイトタイトル</b-navbar-brand>

    <!-- Right aligned nav items -->
    <b-navbar-nav class="ml-auto">
      <nuxt-link to="/help"><b-icon icon="question-square" style="width: 60px; height: 50px; padding-right: 20px; color: black;"></b-icon></nuxt-link>
      <nuxt-link to="/user"><b-icon icon="person" style="width: 60px; height: 50px; padding-right: 20px; color: black;"></b-icon></nuxt-link>
    </b-navbar-nav>
  </b-navbar>
</template>

<style scoped>
.navbar {
  border-top: 1px solid transparent;
  border-color: black;
}
</style>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'

@Component
export default class Navbar extends Vue {}
</script>
