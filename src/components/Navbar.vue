<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark px-3 d-flex justify-content-between align-items-center" style="height: 10em;">
    <div class="">
        <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">
          <div class="d-flex flex-column align-items-center">
            <img alt="logo" src="https://www.javaidaho.com/uploads/5/9/9/9/59994583/java-sun-logo.png" class="img-fluid java-logo" />
          </div>
        </router-link>
      </div>
      <div>
        <div>
          <ul class="navbar-nav me-auto">
            <li>
              <router-link :to="{ name: 'Home' }" class="btn text-success lighten-30 selectable text-uppercase">
                Home
              </router-link>
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
  border-bottom: 2px solid var(--bs-success);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

.java-logo{
  height: 7em;
  
  margin-left: 3em;
}

@media screen and (min-width: 768px) {
  nav {
    height: 64px;
  }
}
</style>
