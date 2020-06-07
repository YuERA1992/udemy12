<template>
  <div id="app">
    input
    <!-- <p>
      {{message}}
    </p>
    <textarea v-model="message"></textarea>
    <input type="text" v-model="message">
    <pre>
    {{$data}}
    </pre> -->
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return{
      // message: '今日の19時にYouTubeあげるよ'
      checked:false
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
