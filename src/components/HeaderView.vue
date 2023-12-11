<template>
  <div>
    <h1>{{ title }}</h1>
    <h2>{{ text }}</h2>
  </div>
</template>
  
<script>
export default {
  data () {
    return {
      title: 'ＸＸＸＸメニュー',
      text: 'menu作ってみました。'
    }
  }
}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1 {
  text-align: center;
}

h2 {
  text-align: center;
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #35495E;
}
</style>
  