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
      return {"slug":"minus_impedit","name":"Consequatur tempora eum inventore.","description":"Voluptatum hic incidunt. Non a iure. Iusto illo eum.","price":58309.49,"header":"Dignissimos omnis adipisci fuga.","footer":"Itaque eum aut sit.","moreInfo":"Rerum laboriosam officia vel."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
