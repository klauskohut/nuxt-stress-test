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
      return {"slug":"assumenda_qui","name":"Sint explicabo voluptates quia.","description":"Suscipit aperiam a. Non id quia. Explicabo voluptatibus labore.","price":48006.69,"header":"Culpa laudantium enim magnam.","footer":"Explicabo est consectetur repellat.","moreInfo":"Incidunt architecto voluptatem nulla."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
