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
      return {"slug":"non_a","name":"Qui repellendus officia ipsam.","description":"Ad magni laudantium. Cumque iusto doloribus. Et saepe qui.","price":72467.45,"header":"Voluptas nostrum repellendus non.","footer":"Fugiat ut et inventore.","moreInfo":"Est qui et dicta."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
