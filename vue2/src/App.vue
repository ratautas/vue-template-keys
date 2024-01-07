<template>
  <div>
    <template v-for="item in list">
      <div></div>
      <div></div>
    </template>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  components: {
    HelloWorld,
  },
  data() {
    return {
      list: ['one', 'two', 'three'],
    }
  },
}
</script>
