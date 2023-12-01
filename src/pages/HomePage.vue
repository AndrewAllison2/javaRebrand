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
              <button class="btn menu-btn" data-bs-toggle="modal" data-bs-target="#exampleModal">DRINK MENU</button>
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
            <div class="d-flex justify-content-center align-items-center">
              <img style="height: 4em;" src="../assets/img/BeanImg.png" alt="*">
              <h1 class="events-heading text-center">See What's Going On At Your Local Java:</h1>
              <img style="height: 4em;" src="../assets/img/BeanImg.png" alt="*">
            </div>
            
            <div class="row me-0 m-auto d-flex">
              <div class="col-4">
                <TarotCards/>
              </div>
              <div class="col-4">
                <BirthdayDeal />
              </div>
              <div class="col-4">
                <ZodiacNight />
              </div>
            </div>
          </div>
        </div>

      </div>

      <div class="row mb-5" style="background-color: #283e5e;">
        <div class="col-5 mb-5 mt-5">
          <div class="img-block">
            <div>
              <img class="tShirtMerch img-fluid" src="../assets/img/T-Shirt.png" alt="T-Shirt">
              <img class="toteMerch img-fluid" src="../assets/img/Tote.png" alt="Tote Bag">
            </div>
            <div>
              <img class="img-fluid cupMerch" src="../assets/img/TogoCup.png" alt="Cups">
              <img class="img-fluid mugsMerch" src="../assets/img/JavaMugs.png" alt="Mugs">
            </div>
          </div>
        </div>

        <div class="col-7">
          <div class="text-center">
            <button @click="sendMerchPop()" class="btn" style="font-family: 'Fjalla One', sans-serif; margin-top: 12em; font-size:xx-large; color: #283E5E; background-color: #c38e59;" >MERCH</button>
          </div>
          <div class="text-center mt-5" style="color: #c38e59; width: 70%; margin: auto;">
            <h5 style="font-family: 'Cantarell', sans-serif;">You can enjoy the rich flavors of our brews in you own kitchen, rock some gnarly Java swag , or take home your very own handmade coffe mug! </h5>
          </div>
        </div>
      </div>

              <div class="row mt-5 mb-5" style="background-color:#c38e59;">
          <div class="col-10 m-auto text-center mt-4" style="color:#283E5E;">
            <h1 style="font-family: 'Fjalla One', sans-serif;">STAY CONNECTED WITH YOUR FAVORITE COFFEE</h1>

            <div>
              <SvgIcon class="mdi mdi-facebook fs-1 me-4"></SvgIcon>
              <i class="mdi mdi-instagram fs-1 me-4"></i>
              <i class="mdi mdi-twitter fs-1"></i>
            </div>
          </div>
        </div>



  </div>

</template>

<script>
import Pop from "../utils/Pop.js";
import SvgIcon from '@jamescoyle/vue-icon';
import {mdiFacebook} from '@mdi/js'
import {mdiInstagram} from '@mdi/js'
import {mdiTwitter} from '@mdi/js'

export default {
  setup() {
    return {
      sendMerchPop() {
        Pop.toast("We're updating our mech! Please check back later!")
      }
    }
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
  height: 75vh;
  width: 100%;
  position: relative;
  bottom: -20em;
}
.events-heading{
  color: white;
  text-shadow: 2px 2px #283E5E;
  padding: 1em;
}
.tShirtMerch{
  height: 17em;
  width: 16em;
  object-position:center;
}
.toteMerch{
  height: 17em;
  width: 16em;
  margin-left: 9px;
  object-fit: cover;
}
.cupMerch{
  height: 17em;
  width: 16em;
  margin-top: 9px;
  object-fit: cover;
}
.mugsMerch{
  height: 17em;
  width: 16em;
  margin-left: 9px;
  margin-top: 9px;
  object-fit: cover;
}
.img-block{
  margin-top: 15em;
  margin-left: 5em;
}
</style>
