<template>


<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true" >
  <div class="modal-dialog" style="background-color: #0E2541;">
    <div>
      
      <div class="modal-body p-0">
        <slot name="body"></slot>
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

</style>