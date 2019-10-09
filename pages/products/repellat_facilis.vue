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
      return {"slug":"repellat_facilis","name":"Qui delectus ducimus consequuntur.","description":"Autem tempora ad. Soluta autem unde. Reiciendis in laborum.","price":14528.91,"header":"Fugit corporis alias eum.","footer":"Et eveniet consequatur quibusdam.","moreInfo":"Molestias eligendi voluptate ipsum."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
