<template>
  <Product :slug="slug" :name="name" :description="description" :price="price" :header="header" :footer="footer">
    <Slider />
    <h3>More product info below:</h3>
    <p>{{moreInfo}}</p>
  </Product>
</template>

<script>
  import Product from '../product'
  import Slider from '../../components/Slider'

  export default {
    layout: 'product',
    components: {
      Product,
      Slider
    },
    data() {
      return {"slug":"placeat-cum","name":"Explicabo totam esse adipisci.","description":"Eum repellendus et. Eum occaecati necessitatibus. Velit autem excepturi.","price":85000.47,"header":"Ut fuga cum voluptatum.","footer":"Quia asperiores rem nihil.","moreInfo":"Qui non eaque ut."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
