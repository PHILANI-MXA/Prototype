<template>
    <div>
      <nav class="navbar navbar-expand">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"
            ><img src="https://i.postimg.cc/KY6s82D6/favicon-32x32.png" alt=""
          /></a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav m-auto">
              <li class="nav-item text-white">
                <router-link class="text-decoration-none text-black" to="/"
                  >Home</router-link
                >
              </li>
              <li class="nav-item text-decoration-none">
                <router-link class="text-decoration-none text-black" to="/about"
                  >About</router-link
                >
              </li>
              <li class="nav-item">
                <router-link
                  class="text-decoration-none text-black"
                  to="/education"
                  >Education</router-link
                >
              </li>
              <li class="nav-item">
                <router-link
                  class="text-decoration-none text-black"
                  to="/experience"
                  >Experience
                </router-link>
              </li>
              <li class="nav-item">
                <router-link class="text-decoration-none text-black" to="/skills"
                  >Skills</router-link
                >
              </li>
              <li class="nav-item">
                <router-link
                  class="text-decoration-none text-black"
                  to="/testimonials22"
                  >Testimonials
                </router-link>
              </li>
              <li class="nav-item">
                <router-link class="text-decoration-none text-black" to="/contact"
                  >Contact me</router-link
                >
              </li>
              <li class="nav-item flex-end">
                <router-link
                  class="text-decoration-none text-black invisible"
                  to="/projects"
                  >Projects</router-link
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
    <router-view />
  </template>
  
  <style scoped>
  @import url("https://fonts.googleapis.com/css?family=Raleway:400,700");
  
  * {
    /* comment */
  }
  
  .nav-item {
    position: relative;
    padding: 7px;
    font-size: small;
    
  }
  
  .navbar-brand {
    font-style: italic;
  }
  
  .btn {
    color: white;
    border-color: white;
  }
  
  nav {
    position: fixed;
    width: 100%;
    top: 0;
    background-color: #e8eeef;
    z-index: 50;
  }
  </style>
  