<template>
  <div class="img-container">
    <img :src="src" :width="size" class="img-thumbnail" />
  </div>
</template>

<script>
export default {
  name: 'ImagenFoto',
  props: {
    size: Number,
    src: String,
  },
};
</script>

<style>
.img-container {
  display: inline-block;
  margin: 10px;
}
</style>