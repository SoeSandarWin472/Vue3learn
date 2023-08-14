<template>
  <h1>HI</h1>
  <div v-if="showModal">
  <Modal :theme="theme" @close="showModal=false">
    <h1>Login Success</h1>
    <p>Welcome user soe lay</p>
  </Modal>
  </div>
  <button @click="showModal=true">open button</button>
   <div v-if="showModal2">
  <Modal theme="delete" @close="showModal2=false">
    <h1>Delete Success</h1>
    <p>delete user soe lay</p>
  </Modal>
  </div>
  <button @click="showModal2=true">delete</button>
</template>

<script>
import Modal from "./components/Modal.vue";
export default {
  data(){
    return{
      theme:"success",
      showModal:"false",
      showModal2:"false"
    }
  },
 
  components:{
    Modal,
    
  }

}
</script>
 
<style scoped>
h1{
  color: blue;
}
</style>