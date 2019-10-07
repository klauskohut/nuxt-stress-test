<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  export default {
    layout: 'product',
    components: {
      Product,
    },
    data() {
      return {"slug":"consequatur_harum","name":"Nihil dolore quae harum.","description":"Consequatur veritatis autem. Exercitationem blanditiis temporibus. Provident omnis laborum.","price":71737.63,"header":"Modi ipsum in voluptates.","footer":"Ea possimus nemo eum.","moreInfo":"Porro ab et quia."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
