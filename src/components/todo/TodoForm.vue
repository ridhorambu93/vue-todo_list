<script setup>
import WelcomeItem from "./TodoList.vue";
</script>

<template>
  <form>
    <input v-model="todo" type="text" />
    <button>Add</button>
  </form>
</template>

<script>
import { ref } from "vue";
export default {
  setup() {
    const todo = ref("");
    return { todo };
  },
};
</script>
