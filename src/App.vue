<!-- eslint-disable -->
<template>
  <div id="app">
    <app-header></app-header>
    <router-view/>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Header from './components/shared/header';
import Footer from './components/shared/footer';

export default {
  name: 'App',

  data() {
    return {
      title: 'Echo-3',
    };
  },
  components: {
    'app-header': Header,
    'app-footer': Footer,
  },
};
</script>


<style lang="scss">
@import './styles/custom-bootstrap.scss';
@import '../node_modules/bootstrap/scss/bootstrap.scss';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  // margin-top: 60px;
}
</style>
