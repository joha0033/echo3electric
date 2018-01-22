<template lang="html">
  <b-navbar class="fixed-top" toggleable="md" type="dark" variant="success">
    <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
    <b-navbar-nav class="white h3 pl-4 pr-5" href="#">Echo3</b-navbar-nav>
    <b-collapse is-nav id="nav_collapse">
      <b-navbar-nav class=" h5">
        <b-nav-item href="#">Overview</b-nav-item>
        <b-nav-item href="#">Features</b-nav-item>
        <b-nav-item href="#">Specs</b-nav-item>
        <!-- <b-nav-item href="#">Contact</b-nav-item> -->
      </b-navbar-nav>
      <b-navbar-nav class="ml-auto p-2">
        <div class="container">
          <b-button size="md" class="my-2 my-sm-0" type="submit">Get a Quote</b-button>
        </div>
        <div class="container">
          <b-button size="md" class="my-2 my-sm-0" type="submit">Contact</b-button>
        </div>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {

};
</script>

<style lang="css">
.white{
  color: #fefbf7;
}
</style>
