<template>
  <div id="app">
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-navbar-brand href="#">ZSZ-Rekrutacja</b-navbar-brand>
      <b-navbar-toggle target="nav_collapse" />

      <b-collapse id="nav_collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item to="/">Strona domowa</b-nav-item>
          <b-nav-item to="/about">O aplikacji</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>

    <b-container class="py-2" fluid>
      <router-view />
    </b-container>
  </div>
</template>
