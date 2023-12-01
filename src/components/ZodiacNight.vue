<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-12 p-0">
        <div class="card selectable m-auto">
          <div class="">
            <img class="img-fluid zodiac-img" src="../assets/img/ZodiacNight.png" alt="">
          </div>
          <h3 class="mt-2 text-center" style="color:  #c38e59;">Zodiac Night</h3>
        </div>
      </div>

    </div>
  </div>
</template>


<script>
export default {
  setup(){
    return {}
  }
}
</script>


<style lang="scss" scoped>
.zodiac-img{
  height: 18em;
  width: 18em;
  object-fit: cover;
}
.card{
  width: fit-content;
  padding: 10px;
  background-color: #283E5E;
}
</style>