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
      return {"slug":"maiores-natus","name":"Et doloremque itaque dolore.","description":"Autem voluptatibus fuga. Mollitia tempora est. Sit totam fugit.","price":16958.43,"header":"Iusto voluptates rerum voluptatum.","footer":"Commodi occaecati cum culpa.","moreInfo":"Ad voluptatem odio et."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
