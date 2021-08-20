<template>
  <div id="app">
    <div class="hello-world">
      <div class="hello-world__message"></div>
    </div>
    <div class="ore">ore</div>
    <ShortTermTodo></ShortTermTodo>
    <LongTermTodo></LongTermTodo>
  </div>
</template>

<script>
import ShortTermTodo from "@/components/ShortTermTodo.vue"
import LongTermTodo from "@/components/LongTermTodo.vue"
export default {
  name: "App",
  components: {
    ShortTermTodo,
    LongTermTodo,
  },
  data: function () {
    return {}
  },
  methods: {},
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>

<style scoped>
.hello-world {
  margin-top: 60px;
  text-align: center;
}

.hello-world .hello-world__message {
  color: #2c3e50;
}
.ore {
  margin-left: auto;
  margin-right: auto;
}
</style>
