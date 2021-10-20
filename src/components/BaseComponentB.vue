<template>
  <h1 class="foo">{{ msg }}</h1>
</template>

<script>
export default {
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.foo {
  color: blue;
}
</style>
