<template>
  <lay-layout class="example">
    <lay-header>header</lay-header>
    <lay-body>content</lay-body>
    <lay-footer>footer</lay-footer>
  </lay-layout>
</template>

<script>
import { ref } from 'vue';

export default {
  setup() {

    return {
    }
  }
}
</script>

<style>
.example .layui-footer,
.example .layui-header {
  line-height: 60px;
  text-align: center;
  background: #87ca9a;
  color: white;
}
.example .layui-side {
  display: flex;
  background: #77c38c;
  align-items: center;
  justify-content: center;
  color: white;
}
.example .layui-body {
  display: flex;
  background: #5FB878;
  align-items: center;
  justify-content: center;
  color: white;
}
</style>
