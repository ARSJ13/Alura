<template>
  <div>
    <h1>{{title}}</h1>
    <ul >
      <li v-for="foto of fotos">
        <img :src="foto.url" :alt="foto.titulo">
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: 'Animal',
      fotos: [
        {
          titulo: 'tiger',
          url: 'C:/Users/00668695102/projects/vue-alura/src/assets/elephant.jpg'
        },
        {
          titulo: 'snake',
          url: __dirname+'/assets/tiger.jpg'
        }
      ]
    }
  },
}
</script>

<style>

</style>
