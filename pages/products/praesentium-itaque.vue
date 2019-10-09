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
      return {"slug":"praesentium-itaque","name":"Sed tempora et provident.","description":"Odio velit asperiores. Dicta enim iusto. Vel necessitatibus voluptatum.","price":82966.95,"header":"Veritatis magnam velit vel.","footer":"Dolorem doloribus ullam deserunt.","moreInfo":"Consequatur id debitis sed."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
