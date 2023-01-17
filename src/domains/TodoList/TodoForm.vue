<template lang="">
  <div>
    <form @submit="submitTodoHandler">
      <input type="button" value="+" v-model="newTodo" />
    </form>
  </div>
</template>
<script setup>
import { ref } from "vue";
const newTodo = ref("");
const submitTodoHandler = () => {};
</script>
<style lang=""></style>
