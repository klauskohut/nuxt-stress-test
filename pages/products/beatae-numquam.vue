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
      return {"slug":"beatae-numquam","name":"Voluptate ad aut quisquam.","description":"Repellendus cumque veritatis. Nisi repudiandae tempora. Nam tempore dolores.","price":33584.46,"header":"Ipsum excepturi aliquid tempore.","footer":"Corrupti ut mollitia dolores.","moreInfo":"Suscipit voluptatem deserunt necessitatibus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
