<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>{{ $store.state.user }}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

