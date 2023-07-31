<template>
  <div class="backdrop">
    <div class="modal">
      <p>Modal content</p>
    </div>
  </div>
</template>

<script>
export default {
  name:"ModalA"
}
</script>

<style>
  .backdrop{
    position: fixed;
    top: 0;
    background: rgb(0, 0, 0,0.5);
    width: 100%;
    height: 100%;
  }
  .modal{
    width: 400px;
    padding: 20px;
    margin: 100px auto;
    background-color: aliceblue;
    border-radius: 10px;
  }
</style>