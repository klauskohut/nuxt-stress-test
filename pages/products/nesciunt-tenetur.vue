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
      return {"slug":"nesciunt-tenetur","name":"Laudantium cum quo iusto.","description":"Culpa eum doloribus. Ipsam impedit omnis. Atque blanditiis quidem.","price":44423.13,"header":"Repellendus esse hic consequuntur.","footer":"Illo voluptatem enim voluptates.","moreInfo":"Ratione molestiae veniam rerum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
