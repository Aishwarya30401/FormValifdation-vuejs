<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  <p> {{ message }}</p>
<input v-model="message" placeholder="enter your name" />&nbsp;NAME
<p style="white-space: pre-line;">{{ message }}</p>
&nbsp;&nbsp;&nbsp;&nbsp;<textarea v-model="message" placeholder="enter your address"></textarea>&nbsp;ADDRESS
<br><br>
<input type="checkbox" id="MALE" value="MALE" v-model="checkedNames">
<label >MALE</label>
<input type="checkbox" id="FMALE" value="FEMALE" v-model="checkedNames">
<label >FEMALE</label>
<br><br>
<input v-model.number="age" />&nbsp;
<label>AGE</label>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'FORM'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  border:1px solid gray;
  width:350px;
  height:350px;
  position: relative;
  left: 499px;

}
</style>
