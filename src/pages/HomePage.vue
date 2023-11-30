<template>
  <div class="container-fluid" style="background-color: #283e5e;">


      <div class="row">
        <div class="col-12 px-0">
          <img class="img-fluid hero-img px-0" src="https://t4.ftcdn.net/jpg/02/34/63/07/360_F_234630793_eHKQucxaXftnWrecTJFITmD4cr3TlUgG.jpg" alt="Coffee Img">
  
          <div class="text-white hero-text">
            <h1 class="fs-2">JAVA COFFEE & CAFE</h1>
            <h1 class="text-warning mt-4">Rise and Grind.</h1>
          </div>
        </div>
      </div>
  
      <div class="row">
        <div class="col-7">
          <div class="menu-card text-end">
            <h1 class="text-white ps-3">Have you tired our cosmic creations?</h1>
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
  
      <div class="row">
        <div class="col-12 px-0">
          <div class="event-section">
            <div>
              <h1 class="text-warning">Check out our upcoming events!</h1>
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
  left: 38em;
  width: 25em;
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
}

.event-section{
  background-color: #323d3f;
  height: 35vh;
  width: 100%;
  position: relative;
  bottom: -20em;
}
</style>
