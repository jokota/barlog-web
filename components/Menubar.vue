<template>
  <b-navbar toggleable="lg" type="dark">
    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <nuxt-link to="/lottery"><b-button variant="outline-info" size="lg" style=" border-color: white; color: black;"><b-icon icon="bullseye"></b-icon> 抽選発表</b-button></nuxt-link>
        <nuxt-link to="/news"><b-button variant="outline-info" size="lg" style=" border-color: white; color: black;"><b-icon icon="newspaper"></b-icon> お知らせ</b-button></nuxt-link>
        <nuxt-link to="/begginer"><b-button variant="outline-info" size="lg" style=" border-color: white; color: black;"><b-icon icon="egg"></b-icon> はじめての方へ</b-button></nuxt-link>
        <nuxt-link to="/questions"><b-button variant="outline-info" size="lg" style=" border-color: white; color: black;"><b-icon icon="question-circle"></b-icon> よくある質問</b-button></nuxt-link>
      </b-navbar-nav>
    </b-collapse>

    <!-- Right aligned nav items -->
    <b-navbar-nav class="ml-auto">
      <b-button variant="danger" size="lg" style="color: white; margin-right: 20px;" nuxt-link to="/signin"> ログイン </b-button>
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
import Vue from 'vue'

export default Vue.extend({})
</script>
