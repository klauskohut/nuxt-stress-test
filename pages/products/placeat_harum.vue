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
      return {"slug":"placeat_harum","name":"Illo repudiandae molestiae sint.","description":"Numquam velit facere. Iste rerum commodi. Aperiam quia voluptatum.","price":66621.12,"header":"Illum maiores eos cum.","footer":"Quia inventore rem rerum.","moreInfo":"Non corrupti repudiandae dicta."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
