<script setup lang="ts">
//復習
const right = 3;
const left = 4;
const result = right * left;

// 初級: 
// * 右辺と左辺にランダムな1桁の数字を表示する
//// ヒント: Math.floor(Math.random()*10) を使う

// * 左辺と右辺を掛けて答えを表示する

</script>

<template>
  <main class="main">
    {{ right }} × {{ left }} = {{ result }}
  </main>
</template>

<style scoped>
/* ここでスタイルを設定します。 */
.main {
  font-size: 16vw;
  text-align: center;
}
</style>
