<template>
  <div class="square"></div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>


<style scoped>
.square {
  width: 40px;
  height: 40px;
  border: 1px solid rgb(40, 28, 78);
  background: red;
}
</style>
