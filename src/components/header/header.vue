<template>
  <div>
    <ul>
      <li v-for="custom in customs">
        {{ custom.text }}
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: 'header',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
