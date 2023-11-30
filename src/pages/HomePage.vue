<template>
  <div class="container-fluid" style="background-color: #283e5e;">


      <div class="row">
        <div class="col-12 px-0">
          <img class="img-fluid hero-img px-0" src="https://t4.ftcdn.net/jpg/02/34/63/07/360_F_234630793_eHKQucxaXftnWrecTJFITmD4cr3TlUgG.jpg" alt="Coffee Img">
  
          <div class="text-center hero-text">
            <h1 class="fs-2">JAVA COFFEE & CAFE</h1>
            <h1 class="mt-4">Bringing the power of the cosmos to your cup!</h1>
          </div>
        </div>
      </div>
  
      <div class="row">
        <div class="col-7">
          <div class="menu-card text-end">
            <h1 class="menu-text ps-3">Have you tired our cosmic creations?</h1>
            <div class="text-end mt-5">
              <button class="btn menu-btn">MENU</button>
            </div>
          </div>
        </div>
        <div class="col-5">
          <div >
            <img class="img-fluid coffee-img" src="https://neurosciencenews.com/files/2023/06/coffee-brain-caffeine-neuroscincces.jpg" alt="Cosmic Creations">
          </div>
        </div>
      </div>
  
      <div class="row" style="background-color: #283e5e; height: 100vh;">
        <div class="col-12 px-0">
          <div class="event-section">
            <div>
              <img src="../assets/img/BeanImg.png" alt="*">
              <h1 class="events-heading text-center">Check out our upcoming events!</h1>
              <img src="../assets/img/BeanImg.png" alt="*">
            </div>
          </div>
        </div>

      </div>



  </div>

</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
.hero-img{
  width: 100%;
  height: 20em;
  object-fit: cover;
  position: absolute;
}
.hero-text{
  position: relative;
  top: 5em;
  left: 34em;
  width: 30em;
  color: #283E5E;
  text-shadow: 2px 2px #c38e59;
  font-family: 'Fjalla One', sans-serif;
}

.menu-card{
  position: relative;
  top: 16em;
  left: 7em;
  background-color: #c38e59;
  height: 20em;
  width: 40em;
  padding: 5em;
}
.menu-text{
  color: white;
  text-shadow: 4px 4px #061930;
  font-family: 'Fjalla One', sans-serif;
}
.coffee-img{
  position: relative;
  top: 16em;
  left: -1em;
  height: 20em;
  width: 20em;
  object-fit: cover;
}
.menu-btn{
  border-radius: 1px solid #c38e59;
  background-color: white;
  color: #c38e59;
  font-family: 'Fjalla One', sans-serif;
}

.event-section{
  background-color: #E0B399;
  height: 35vh;
  width: 100%;
  position: relative;
  bottom: -20em;
}
.events-heading{
  color: white;
  text-shadow: 2px 2px #283E5E;
  padding: 1em;
}
</style>
