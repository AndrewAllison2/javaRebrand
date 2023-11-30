<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-12">
        <div class="card selectable">
          <div class="">
            <img class="img-fluid tarot-img" src="../assets/img/TarotReading.png" alt="">
          </div>
          <h3 class="mt-2 text-center" style="color: #283E5E;">Tarot Thursdays</h3>
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
.tarot-img{
  height: 18em;
  object-fit: cover;
}
.card{
  width: fit-content;
  padding: 10px;
  background-color: #c38e59;
}
</style>