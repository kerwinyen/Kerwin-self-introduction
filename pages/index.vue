<template>
  <div class="container">
    <b-navbar class="navbar" toggleable="md" type="dark" variant="dark" string="top">
      <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

      <b-navbar-brand href="#">
        <img class="logo" src="https://i.imgur.com/eAvQcvd.png">
      </b-navbar-brand>

      <b-collapse is-nav id="nav_collapse">
        <b-navbar-nav>
          <b-nav-item href="#">Profoilo</b-nav-item>
          <b-nav-item href="#" disabled>Connect</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
      </b-collapse>
    </b-navbar>

    <div class="container-fluid px-0">
      <div
        class="d-flex flex-column text-center justify-content-center align-items-center bg-banner"
      >
        <p class="text-white subtitle">Hi, Im</p>
        <h1 strong class="text-white title">Kerwin Yen</h1>
      </div>
    </div>
    <div class="self-introduction"></div>
  </div>
</template>

<script>
</script>

<style>
.container {
  max-width: 100%;
  height: auto;
  margin: 0px;
  padding: 0px;
  z-index: -1;
}

.navbar {
  position: absolute;
  max-width: 100％;
  height: 40px;
  margin: 0px;
  padding: 0px;
}

.background {
  max-width: 100%;
  height: 700px;
  margin: 0px;
  padding: 0px;
  z-index: -1;
}

.title {
  position: "absolute";
  top: 500px;
  left: 200px;
  z-index: 1;
}

.subtitle {
  position: "absolute";
  top: 800px;
  left: 400px;
  z-index: 1;
}

.logo {
  hight: 30px;
  width: 30px;
}

.bg-banner {
  background-image: url("https://i.imgur.com/WCwXGbD.jpg");
  min-height: 100vh;
  background-size: cover;
}
</style>



