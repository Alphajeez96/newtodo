<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <h3>Today's Agenda</h3> -->
    <todo></todo>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import todo from '@/components/todo.vue'

export default {
  name: 'home',
  components: {
   todo
  }
}
</script>
