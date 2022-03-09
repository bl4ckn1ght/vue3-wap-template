<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
  <h1 class="demo-title">{{ msg }}</h1>
  <div class="flex">
    <div class="space">
     <div class="s"></div>
    </div>
    <div class="space"></div>
    <div class="space"></div>
    <div class="space"></div>
  </div>
</template>

<style lang="postcss" scoped>
@import url('../styles/var.css');
.demo-title {
    margin-bottom: 10px;
    font-size: 20px;
}
.space {
  box-sizing: border-box;
  vertical-align: top;
  display: inline-block;
  background: #42b983;
  width: calc(375px / 4);
  height: 100px;
  border-width: 5px;
  border-style: solid;
  border-image: svg(1px-border param(--color red)) 1 stretch;
  &:after {
      content: ''
  }
}
</style>
