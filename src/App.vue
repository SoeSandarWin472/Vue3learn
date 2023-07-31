<template>
  <h1>HI</h1>
  <Modal></Modal>
</template>

<script>
import Modal from "./components/Modal.vue";
export default {
  data(){
    return{
      title:"u know js"

    }
  },
 
  components:{
    Modal
  }

}
</script>
 
<style>
h1{
  color: blue;
}
</style>