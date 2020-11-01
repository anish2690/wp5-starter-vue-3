<template>
  <div>{{ msg }}</div>
</template>

<script>
import { ref } from "vue";
export default {
  setup() {
    const msg = ref("Hello from Vue!");
    return {
      msg,
    };
  },
};
</script>

<style lang="scss" scoped></style>
