<template>
<div id="nav">
  <b-navbar type="dark" variant="dark">
    <b-navbar-nav>
      <b-nav-item to="/home">Početna</b-nav-item>
      <b-nav-item to="/reservation">Moje rezervacije</b-nav-item>
      <b-nav-item to="/add">Dodaj film</b-nav-item>
    </b-navbar-nav>
  </b-navbar>
    </div>
</template>

<script>
export default {
  data () {
    return {
      role: ''
    }
  }
}
</script>
