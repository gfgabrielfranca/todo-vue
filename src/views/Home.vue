<template>
  <div class="home">
    <img alt="Vue logo" src="@/assets/logo.png" class="logo">
    <TodoList/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import TodoList from '@/components/TodoList.vue'

export default {
  name: 'home',
  components: {
    // HelloWorld
    TodoList
  }
}
</script>

<style lang="scss" scoped>
.logo {
  height: 75px;
  margin-bottom: 16px;
}
</style>
