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
      return {"slug":"et-est","name":"Laboriosam dolorem sint vitae.","description":"Earum suscipit necessitatibus. Dolorem rerum nostrum. Doloremque consequuntur repellendus.","price":81402.79,"header":"Ut qui velit sed.","footer":"Totam dolore quam omnis.","moreInfo":"Odit est aspernatur veritatis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
