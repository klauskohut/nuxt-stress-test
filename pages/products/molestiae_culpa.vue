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
      return {"slug":"molestiae_culpa","name":"Repudiandae voluptas corporis molestias.","description":"Voluptatem quia laudantium. Sit occaecati veritatis. Aliquam placeat tempora.","price":40877.41,"header":"Aperiam est id laudantium.","footer":"Enim enim et omnis.","moreInfo":"Rem est commodi eos."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
