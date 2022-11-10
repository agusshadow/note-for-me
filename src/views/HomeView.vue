<template>
  <hello-world />
  <carrito-compras />
</template>

<script>
  import HelloWorld from '../components/HelloWorld'
  import CarritoCompras from '../components/CarritoCompras'

  export default {
    name: 'Home-view',
    components: {
      HelloWorld,
      CarritoCompras
    },
  }
</script>
