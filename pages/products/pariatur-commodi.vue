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
      return {"slug":"pariatur-commodi","name":"Ratione quae voluptatem perferendis.","description":"Odit id mollitia. Similique unde quas. Cumque repellat autem.","price":72311.23,"header":"Odio ut soluta doloremque.","footer":"Ab laboriosam est est.","moreInfo":"Repellat et ducimus dolorum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
