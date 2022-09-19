<template>
    <div class="hello">
      <h1>{{ msg }}</h1>
      <div class="status" id="app">
        <HelloWorld msg="Your Vue.js App"/>
      </div>  
    </div>
</template>

<script>
    import HelloWorld from './HelloWorld.vue'

    export default {
      name: 'Welcome',
      components: {
        HelloWorld
      },
      props: {
        msg: String
          
      }
    }
</script>