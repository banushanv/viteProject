<template>
  <div>
  This is a vite Project
<button @click="counter++" >{{counter}}</button>
  </div>
</template>

<script>
import {ref} from 'vue';    
export default {
  setup () {
 const counter=ref(344);  

    return {
      counter
    };
  }
}
</script>

<style>

</style>