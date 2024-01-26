<template>
  <section>
    <h1>Científicos increíbles</h1>
    <ImagenFoto :size="100" :src="albertImage" />
    <ImagenFoto :size="50" :src="albertImage" />
    <ImagenFoto :size="200" :src="albertImage" />
    <ImagenFoto :size="150" :src="albertImage" />
    <TablaClientes/>
  </section>
</template>

<script>
import ImagenFoto from './ImagenFoto.vue';
import TablaClientes from './TablaClientes.vue';
import albertImage from '../assets/albert.jpg'; 

export default {
  name: 'GaleriaCientificos',
  components: {
    ImagenFoto,
    TablaClientes
  },
  data() {
    return {
      albertImage
    };
  }
};
</script>