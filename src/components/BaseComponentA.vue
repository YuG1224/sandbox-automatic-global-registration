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

<style>
.foo {
  color: red;
}
</style>
