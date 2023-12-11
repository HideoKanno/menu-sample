<template>
  <div id="dialog">
    <p>ボタンをクリックしてください</p>
    <button id="yes">はい</button>
    <button id="no">いいえ</button>
    <button id="cancel">キャンセル</button>
  </div>
  <button id="btn">ボタン</button>
</template>

<script>
  name: 'dialog'
</script>

<style scoped>
#dialog {
    width: 250px;
    margin: auto;
    margin-top: 40vh;
    padding: 30px 20px;
    display: none;
    text-align: center;
    border: 1px solid #aaa;
    box-shadow: 2px 2px 4px #888;
}
</style>