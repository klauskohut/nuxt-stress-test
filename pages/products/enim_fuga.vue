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
      return {"slug":"enim_fuga","name":"Magnam velit exercitationem quam.","description":"Cumque officia est. Possimus rerum non. Omnis facilis iste.","price":66990.58,"header":"Voluptatibus sapiente harum dignissimos.","footer":"Velit omnis qui aut.","moreInfo":"Quo iure vel ducimus."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
