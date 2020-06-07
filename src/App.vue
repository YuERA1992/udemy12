<template>
  <div id="app">
    136
    <br>
    <input type="number" v-model.number="num">
    <p>
      {{num+10}}
    </p>
    133,134,135
    <br>
    <input type="text" v-model.trim="message">
    <br>
    <input type="text" v-model="message">
    <p>
      {{message}}
    </p>

    132
    <br>
    <select v-model="erabu" multiple>
      <option disable >1つ選んだってーな</option>
      <option >お好み焼き</option>
      <option >たこ焼き</option>
      <option >コンサバ</option>
    </select>
    <br>
    
    131
    <br>
    <select v-model="selected" name="" id="">
      <option disable >1つ選んだってーな</option>
      <option >お好み焼き</option>
      <option >たこ焼き</option>
      <option >コンサバ</option>
    </select>
    <br>

    128
    <br>
    <input type="checkbox" id="red" value="Red" v-model="colors">
    <label for="red">Red</label>
    <input type="checkbox" id="green" value="Green" v-model="colors">
    <label for="green">Green</label>
    <input type="checkbox" id="blue" value="Blue" v-model="colors">
    <label for="blue">Blue</label>
    <p>
      {{colors}}
    </p>

    129
    <br>
    <input type="radio" id="lion" value="Lion" v-model="animals">
    <label for="lion">ライオン</label>
    <input type="radio" id="dog" value="Dog" v-model="animals">
    <label for="dog">イヌ</label>
    <input type="radio" id="cat" value="Cat" v-model="animals">
    <label for="cat">ネコ</label>
    <p>
      {{animals}}
    </p>
    <!-- <input type="checkbox" v-model="checked"> -->
    <!-- <label for="checkbox" >{{checked}}</label> -->
    <!-- <p>
      {{message}}
    </p>
    <textarea v-model="message"></textarea>
    <input type="text" v-model="message"> -->
    <pre>
    {{$data}}
    </pre>
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return{
      num:"",
      message: '',
      // checked:false
      colors:[],
      animals:'',
      selected:false,
      erabu:[]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
