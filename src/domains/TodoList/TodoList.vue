<template lang="">
  <div>
    <p>{{ todos }}</p>
  </div>
</template>
<script setup>
import { reactive } from "vue";
const todos = reactive(["first", "second", "third"]);
</script>
<style lang=""></style>
