<template>
  <div class="container">

    <!-- DEVISE -->

    <div class="  d-none d-sm-block ">
      <div class="fdb-navbar">
        <!-- navbar-left -->
        <div class="navbar-left">
          <nuxt-link class="" to="/luzerne">Luzerne</nuxt-link>
          <nuxt-link class="" to="/caravane">Caravane</nuxt-link>
        </div>
        <!-- Logo -->
        <nuxt-link class="" to="/"><img src="~assets/images/logo-fdb-circle-black-2.png"></nuxt-link>
        <!-- navbar-right -->
        <div class="navbar-right">
          <nuxt-link class="" to="/exploitation">Equipe</nuxt-link>
          <nuxt-link class="" to="/team">Contact</nuxt-link>
        </div>
      </div>
    </div>

    <!-- MOBIL -->

    <div class="d-block d-sm-none">
      <div class="fdb-navbar-mobil">
        <!-- navbar-left -->
        <div class="navbar-left-mobil">
          <h5>Fermedebrye</h5>
        </div>
        <!-- navbar-right -->
        <div class="navbar-right-mobil">
          <div class="dropdown">
            <i class="fa fa-bars dropdown-toggle" data-toggle="dropdown"></i>
            <ul class="dropdown-menu dropdown-menu-right navbar-wagon-dropdown-menu">
              <li><nuxt-link class="" to="/exploitation">Exploitation</nuxt-link></li>
              <li><nuxt-link class="" to="/luzerne">Luzerne</nuxt-link></li>
              <li><nuxt-link class="" to="/caravane">Caravane</nuxt-link></li>
              <li><nuxt-link class="" to="/equipe">Equipe</nuxt-link></li>
            </ul>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<style lang="scss" scope>
  .item{
    font-size: 40px;
  }
</style>
