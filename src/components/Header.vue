<template>
    <header id="masthead" class="site-header navbar-static-top navbar-light" role="banner">
      <div class="container">
        <nav class="navbar navbar-expand-xl p-0">
          <div class="navbar-brand">
            <a href="#">
              <img src="../../public/images/logo.png" alt="Roadside Rescue">
            </a>
          </div>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#main-nav" aria-controls="" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
  
          <div id="main-nav" class="collapse navbar-collapse justify-content-center">
            <ul id="menu-main-menu" class="navbar-nav">
              <li class="menu-item">
                <a href="#" class="nav-link">Home</a>
              </li>
              <li class="menu-item">
                <a href="#" class="nav-link">About us</a>
              </li>
              <li class="menu-item">
                <a href="#" class="nav-link">Services</a>
              </li>
              <li class="menu-item">
                <a href="#" class="nav-link">Book a service</a>
              </li>
            </ul>
          </div>                
          <div class="xtra_links">
            <a href="#" class="login">log in</a>
            <a href="#" class="signup">Sign up</a>
          </div>
        </nav>
      </div>
    </header>
  </template>
  
  <script>
  export default {
    name: 'Header',
  }
  </script>
  
  <style scoped>
  </style>
  