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
      return {"slug":"hic_maxime","name":"Tempore tenetur temporibus quasi.","description":"Quisquam omnis voluptatem. Necessitatibus mollitia est. Fuga iure soluta.","price":30870.11,"header":"Consequatur non eveniet asperiores.","footer":"Illo fugit quo dolorem.","moreInfo":"Inventore facilis eum iusto."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
