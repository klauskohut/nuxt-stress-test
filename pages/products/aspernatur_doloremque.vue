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
      return {"slug":"aspernatur_doloremque","name":"Tempore asperiores ut dolorem.","description":"Occaecati dolor optio. In quia dolores. Recusandae cum aut.","price":44183.32,"header":"Quod est ut molestias.","footer":"Voluptatem ipsam cumque fuga.","moreInfo":"Sed consequatur est veniam."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
