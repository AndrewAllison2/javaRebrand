<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-12">
        <div class="card">
          <div class="">
            <img class="img-fluid deal-img" src="../assets/img/BirthdayDeal.png" alt="">
          </div>
          <h3 class="mt-2 text-center" style="color:  #c38e59;">Aquarius Season</h3>
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
.deal-img{
  height: 18em;
  object-fit: cover;
}
.card{
  width: fit-content;
  padding: 10px;
  background-color: #283E5E;
}
</style>