<!-- html -->
<template>
  <atd-input v-model="password" type="password" showPassword placeholder="请输入密码"></atd-input>
</template>

<!-- js -->
<script setup>
  import {ref} from 'vue'
  const password = ref('')
</script>