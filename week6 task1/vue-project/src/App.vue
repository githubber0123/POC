<script>
export default {
  data() {
    return {
      message: '',
      messages: ''
      
    }
  }
}
  
</script>



<template>
	<label>Email: </label>
	<input v-model="messages" placeholder="Email" /> <br>
    <p>Email is : {{ messages }}</p>
  
  <label>Password: </label>
	<input v-model="message" placeholder="Password" type= "password" />
    <p>Password is : {{ message }}</p>
  
</template>