<template>
  <nav class="navbar navbar-expand-lg navbar-white px-3 d-flex justify-content-between align-items-center" style="height: 10em;">
    <div class="">
        <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">
          <div class="d-flex align-items-center">
            <img alt="logo" src="../assets/img/JavaLogo.png" class="img-fluid java-logo" />
            <h1 class="nav-text ms-4">Wake Up and Live.</h1>
          </div>
        </router-link>
      </div>
      <div>
        <div>
          <ul class="navbar-nav me-auto">
            <li class="nav-menu">
              <div class="btn selectable text-uppercase" style="color: #c38e59;">
                Home
              </div>
              <div class="btn selectable text-uppercase" style="color: #c38e59;">
                Hours/Locations
              </div>
              <div class="btn selectable text-uppercase" style="color: #c38e59;">
                Menus
              </div>
              <div class="btn selectable text-uppercase" style="color: #c38e59;">
                About Us
              </div>
              <!-- <router-link :to="{ name: 'About' }" class="btn text-success lighten-30 selectable text-uppercase">
                About
              </router-link> -->
            </li>
          </ul>
        </div>
      </div>

    
  </nav>
</template>

<script>

export default {
  setup() {
    return {}
  },

}
</script>

<style scoped>
a:hover {
  text-decoration: none;
}

.nav-link {
  text-transform: uppercase;
}

.navbar-nav .router-link-exact-active {
  /* border-bottom: 2px solid var(--bs-success); */
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

.java-logo{
  height: 7em;
  
  margin-left: 3em;
}
.nav-text{
  color: #da9a5b;
  text-shadow: 1px 1px #cea783;
  font-family: 'Fjalla One', sans-serif;
}

.navbar{
  background-color: #283e5e;;
}
.nav-menu{
  font-family: 'Fjalla One', sans-serif;
}

@media screen and (min-width: 768px) {
  nav {
    height: 64px;
  }
}
</style>
