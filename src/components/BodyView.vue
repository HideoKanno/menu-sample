<template>
  <div>
    <p><button @click="onClick1">メニュー①</button></p>
    <p><button @click="onClick2">メニュー②</button></p>
    <p><button @click="onClick3">メニュー③</button></p>
    <p><button @click="onClick4">メニュー④</button></p>
  </div>
</template>
<script>
export default {
  name: 'BodyView',
  methods: {
    onClick1 () {
      alert('Button1 Click', 'タイトル')
    },
    onClick2 () { },
    onClick3 () { },
    onClick4 () { }
  }
}
</script>

<style scoped>
div {
  text-align: center;
  border: none
}

</style>