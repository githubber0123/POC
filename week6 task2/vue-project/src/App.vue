<script>
export default {
  data() {
    return {
      checkedNames: []
    }
  }
}
</script>

<template>
  <div>Checked names: {{ checkedNames }}</div>
  
  <br>

  <input type="checkbox" id="jack" value="Apple" v-model="checkedNames" />
  <label for="Apple">Apple</label>
 <br>
  <input type="checkbox" id="john" value="Banana" v-model="checkedNames" />
  <label for="Banana">Banana</label>
 <br>
  <input type="checkbox" id="mike" value="Mango" v-model="checkedNames" />
  <label for="Mango">Mango</label>
   <br>
  <input type="checkbox" id="Grapes" value="Grapes" v-model="checkedNames" />
  <label for="Grapes">Grapes</label>
  
</template>