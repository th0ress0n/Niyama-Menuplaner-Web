<template>
  <Settings>
    <Layout slot-scope="{header, body, footer}">
      <Header slot="header" :header="header"></Header>
      <Body slot="body" :body="body"></Body>
      <Footer slot="footer" :footer="footer"></Footer>
    </Layout>
  </Settings>
</template>

<script>

import Layout from './components/Layout';
import Settings from './components/Settings.vue';
import {Header, Body, Footer} from './components';

export default {
  name: 'App',
  components: {
    Layout, 
    Settings, 
    Header,
    Body,
    Footer,
  }
}
</script>

<style>
html {
  margin:0;
  background-color: antiquewhite;
  min-height: 100%;
}

body {
  margin:0;
  height: 100%;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin:0;
}

</style>
