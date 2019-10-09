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
      return {"slug":"ullam-id","name":"Sed laborum alias accusamus.","description":"Dicta et quia. Consequuntur voluptas explicabo. Ullam explicabo tenetur.","price":48656.23,"header":"Eos ullam quia deserunt.","footer":"Omnis quia magnam perspiciatis.","moreInfo":"Tempora harum nam debitis."}
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
